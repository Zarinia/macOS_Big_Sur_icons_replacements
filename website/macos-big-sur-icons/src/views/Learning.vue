<template>
  <div>
    <main class="content-wrapper-compact">

      <H3-Description
        :text="introText"
        class="m-b-50 p-b-10 p-t-50"
      />

      <div class="resources-grid card-grid" id="how-to-install">

        <ResourcesCard
          v-for="resource in resourcesData"
          :key="resource.name"
          :link="'/learning/'+resource.slug"
          :step='resource'
        />

        <!-- <div
          class="card-hover relative coral-card resources-card-ad"
          @click="adClick({position: 'Icon Grid Bottom', type: 'Carbon'})"
        >
            <script
              async="async"
              type="application/javascript" src="//cdn.carbonads.com/carbon.js?serve=CEBIK27J&amp;placement=macosiconscom"
              id="_carbonads_js">
            </script>
          <a
              class="card-no-ad relative"
              href="https://www.paypal.com/donate/?hosted_button_id=5PMNX4DPW83KN"
              rel="noopener"
              target="_blank"
              style="width: 100%; left: 0;"
              @click="logDonation('support-message')"
            >
              <div class="support-page">
                <h3 class="coral-Heading--S m-0">
                  Support this page
                </h3>
                <p class="coral-Body--S m-0">
                  Please consider disabling your ad blocker or making a
                  <a  
                    rel="noopener"
                    class="coral-Link"
                    target="_blank"
                    href="https://www.paypal.com/donate/?hosted_button_id=5PMNX4DPW83KN"
                  >
                    donation 
                  </a>
                 to support this project.
                </p>
              </div>
            </a>
        </div> -->

      </div>

    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import { mapActions } from 'vuex'
import Header from '@/components/Header.vue'
import ResourcesCard from '@/components/ResourcesCard.vue'
import Footer from '@/components/Footer.vue'
import H3Description from '@/components/H3_Description.vue'

import pages from '@/api/pages.json';


export default {
  name: 'Learning',
  
  components: {
    Header,
    ResourcesCard,
    Footer,
    H3Description
  },

  metaInfo: {
      // if no subcomponents specify a metaInfo.title, this title will be used
      title: 'Free icon templates resources for macOS Monterey, Big Sur.',
      description:"Resources and templates to help you design and showcase icons for macOS.",
      // all titles will be injected into this template
      titleTemplate: '%s | macOSicons',
      meta:[
        // Facebook
        {
          property: 'og:url',
          content:  'https://macosicons.com/resources'
        },
        {
          property: 'og:title',
          content:  'Free icon templates resources and over 5000+ icons for macOS Monterey, Big Sur.',
        },
        {
          property: 'og:description',
          content:  'Resources and templates to help you design and showcase icons for macOS. Over 5000+ free icons ready for Big Sur.',
        },
        {
          property: 'og:image',
          content:  'https://raw.githubusercontent.com/elrumo/macOS_Big_Sur_icons_replacements/master/icons/Social/low-res/Resources-thumbnail.jpg'
        },

        // Twitter
        {
          property: 'twitter:url',
          content:  'https://macosicons.com/resources'
        },
        {
          property: 'twitter:description',
          content:  'Resources and templates to help you design and showcase icons for macOS. Over 5000+ free icons ready for Big Sur.',
        },
        {
          property: 'twitter:title',
          content:  'Free icon templates resources and over 5000+ icons for macOS Monterey, Big Sur.',
        },
        {
          property: 'twitter:image',
          content:  'https://raw.githubusercontent.com/elrumo/macOS_Big_Sur_icons_replacements/master/icons/Social/low-res/Resources-thumbnail.jpg'
        },
      ]
  },

  data(){
    return {
      isMobile: this.$isMobile(),
      introText:{
        h3: "Tutorials",
        description: "More tutorials on everything macOS icons coming soon. If you’d like to contribute or make suggestions, let us know on our [Discord](https://discord.gg/f4mTRyyTkT) channel or [Twitter](https://twitter.com/elrumo).",
        isAd: false,
        isCenter: true,
      },

      resourcesData: [
        {
          feature_image: "https://i.imgur.com/gKriWTY.jpg",
          title: "Introduction to macOS icon design",
          description: "Learn how to designicons for macOS in Photoshop",
        },
        {
          feature_image: "https://i.imgur.com/ScAgHYI.jpg",
          title: "More coming soon",
          description: "If you’d like to contribute or make suggestions, let us know on our Discord channel or Twitter.",
        }
      ]
      // resourcesData: pages
    }
  },
  
  mounted: async function(){
    const parent = this;
    // let storeResourcesData = parent.$store.state.resourcesData
    // parent.getPages()
    // parent.getPageData
    // parent.resourcesData = await storeResourcesData;
  },

  methods: {
    ...mapActions([
      'getPageData',
      'adClick'
    ]),

    async getPages(){
      console.log(this.getPageData);
    }
  }

}
</script>

