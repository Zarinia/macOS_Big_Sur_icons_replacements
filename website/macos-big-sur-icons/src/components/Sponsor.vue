<template>
  <main>
    <article class="Box p-3">
      <div class="d-flex">

        <div class="mr-3">
            <img
              class="rounded-1 avatar-user"
              :src="gitHub.profile"
              width="48"
              height="48"
              alt="@elrumo"
            />
        </div>

        <div class="d-sm-flex flex-auto">
          <a
            aria-label="Support the project on PayPal"
            target="_blank"
            href="https://github.com/sponsors/elrumo?o=esc"
            style="color: black"
          >
          <div class="flex-sm-auto mr-sm-3">
            <div class="h3 mb-2 f-w-900">
              Support the project
            </div>

            <div class="mb-2 f-w-400">
              👋 I'm Elias, the creator of macOSicons. The website has been more successful than I expected thanks to people like you, but maintaining it, building new features and curating the icons takes a lot of time. So any donation is much appreciated.
            </div>
          </div>
          </a>

          <div class="sponsor-buttons">
            <a
              class="btn"
              aria-label="Sponsor @elrumo"
              target="_blank"
              href="https://github.com/sponsors/elrumo?o=esc"
            >
              <svg
                class="octicon octicon-heart icon-sponsor text-pink mr-2"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M4.25 2.5c-1.336 0-2.75 1.164-2.75 3 0 2.15 1.58 4.144 3.365 5.682A20.565 20.565 0 008 13.393a20.561 20.561 0 003.135-2.211C12.92 9.644 14.5 7.65 14.5 5.5c0-1.836-1.414-3-2.75-3-1.373 0-2.609.986-3.029 2.456a.75.75 0 01-1.442 0C6.859 3.486 5.623 2.5 4.25 2.5zM8 14.25l-.345.666-.002-.001-.006-.003-.018-.01a7.643 7.643 0 01-.31-.17 22.075 22.075 0 01-3.434-2.414C2.045 10.731 0 8.35 0 5.5 0 2.836 2.086 1 4.25 1 5.797 1 7.153 1.802 8 3.02 8.847 1.802 10.203 1 11.75 1 13.914 1 16 2.836 16 5.5c0 2.85-2.045 5.231-3.885 6.818a22.08 22.08 0 01-3.744 2.584l-.018.01-.006.003h-.002L8 14.25zm0 0l.345.666a.752.752 0 01-.69 0L8 14.25z"
                ></path>
              </svg>
              <span style="
                top: 11%;
                position: relative;
              ">GitHub</span>
            </a>
            
            <a
              class="btn m-t-15 p-r-20"
              aria-label="Donate to using PayPal"
              target="_blank"
              href="https://www.paypal.com/donate?hosted_button_id=5PMNX4DPW83KN"
            >
              <svg
                class="octicon octicon-heart icon-sponsor text-pink mr-2"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                aria-hidden="true"
              >
                <svg viewBox="0 0 1965.25 2307.48" xmlns="http://www.w3.org/2000/svg"><path d="m1196.89 2.3c107.12 1.32 211.33 18.62 311.29 58 54.08 21.32 104.07 50.17 145.58 91.11 62.6 61.74 105.32 134.93 122.42 222.26 8.92 45.55 8.39 91.42 7.22 137.3-.59 22.86-3.58 45.75-7.32 68.43-.65 3.93-1 8-4 11.1a4.55 4.55 0 0 1 -3.24 1c-10.82-2.6-20.07-8.8-30.12-13.16-64.79-28.09-132.85-42.84-202.68-50.81-59.61-6.81-119.41-8-179.33-7.93q-261.2.45-522.39.06c-9.73 0-19.31.68-28.64 3.47-35.7 10.7-57.05 34.64-63.29 71.16-8.29 48.57-15.51 97.32-23.22 146q-40.73 257-81.26 514c-4.77 29.91-9.07 59.9-14.38 89.73a34.77 34.77 0 0 0 .15 9.93c-15.42 76.37-25.43 153.64-37.71 230.54q-30.71 192.32-60.73 384.74c-4.32 27.62-8.72 55.24-13.41 82.81-.82 4.85-1 10.13-6.22 13-4.46 1.82-9.16 1.5-13.8 1.5q-214.08 0-428.17 0c-30.05 0-54.25-17.3-62-43.88-1.22-4.31-2.56-19.79-.71-39.32 1.9-20 290.13-1847.2 297-1891.94 5.43-35.17 23.69-61.58 54.34-79.5a74.08 74.08 0 0 1 30.14-9.58c49.59-5.23 808.89-.02 814.48-.02z" fill="#223a7f"/><path d="m1965.25 928.43c-.56 11.35-.53 22.7 0 34-1.67 77-15.69 152-36.47 225.84-22.15 78.68-54.33 152.88-101 220.34q-79.92 115.44-204 181.28c-62.24 32.94-128.34 54.6-197.27 68.12a989.11 989.11 0 0 1 -126.49 16.2c-45.21 3-90.44 3.35-135.7 3-19.28-.15-36.88 4.55-52.73 15.44-23.38 16-35.44 38.83-39.73 66.48-9.29 59.77-71.53 452.3-77.27 484.37l-.15.81a77.19 77.19 0 0 1 -76 62.9c-128.47 0-327.75.16-398.36.25-26.55 0-47.17-23.42-43.4-49.7l.09-.59c6.6-43.57 120.56-763.56 125.42-794.7 4.72-30.15 9.35-60.31 14.34-90.42 1-6.17 3.47-12.1 5.26-18.14-.81-5.28 1.34-9.76 4.06-14 21.75-33.69 51.74-52.64 92.76-52.55 74.23.17 148.46.64 222.68-.1 95.42-1 189.88-10.63 282.48-35 101.75-26.72 195.24-70.23 276.79-137.46 62.51-51.52 113.57-112.82 154-183.09 58.34-101.49 91.92-211.38 111.66-326 .9-5.2 1-10.66 4.4-15.13a1.15 1.15 0 0 1 1.14.4c30.56 16.53 59.18 35.84 84.15 60.11 48 46.65 78.61 103.29 95.09 167.88a471.21 471.21 0 0 1 14.25 109.46z" fill="#0699d6"/><path d="m1770.62 590.62c-.17 13.37-3.48 26.3-6 39.29-12.36 64.77-29.41 128.25-53.5 189.72-29.58 75.48-68.26 145.69-120 208.44a649 649 0 0 1 -195.58 160.34c-69.35 37.27-143.11 62-220 78a1094.64 1094.64 0 0 1 -135.13 19.19c-37.13 3-74.38 4.55-111.67 4.48-68.9-.12-137.8.17-206.7-.1-47.35-.18-80.34 21.51-100.28 64-2.62-2.88-1.72-6.34-1.2-9.51 4.8-29.7 115-743.66 123.31-767.59 11.18-32.37 34.79-50.68 67.7-58.17 7.26-1.65 419.24-2 618-1.45 19.1 0 77.33 4.27 87.23 5.52 14.11 1.78 85.55 11.21 106.85 16 26.86 6.07 53.37 13.18 79.3 22.66 23.18 8.43 45.89 17.67 67.67 29.18z" fill="#272f64"/></svg>
              </svg>
              <span style="
                top: 11%;
                position: relative;
              ">
              PayPal</span>
            </a>
            
            <a
              class="btn m-t-15 p-r-20"
              aria-label="Donate using KoFi"
              target="_blank"
              href="https://ko-fi.com/elrumo"
            >
              <svg
                class="octicon octicon-heart icon-sponsor text-pink mr-2"
                height="16"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                aria-hidden="true"
              >
               <svg viewBox="0 0 600 600" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="m600 300c0-165.686-134.314-300-300-300s-300 134.314-300 300 134.314 300 300 300 300-134.314 300-300" fill="#35a1cd"/><path d="m548.427 254.133c-6.319-33.374-24.284-54.164-42.697-67.019-19.041-13.295-41.848-20.126-65.072-20.126h-329.585c-11.466 0-15.857 11.194-15.901 16.801-.006.731.021 3.657.021 3.657s-.541 145.813.483 223.693c3.111 45.978 49.177 45.963 49.177 45.963s150.404-.441 222.535-.889c3.383-.022 6.761-.386 10.044-1.207 41.068-10.275 45.317-48.428 44.878-69.696 82.548 4.586 140.792-53.664 126.117-131.177m-92.731 75.675c-17.605 2.2-31.908.548-31.908.548v-107.795h21.662c14.317 0 28.127 5.961 37.469 16.81 6.576 7.638 11.837 18.388 11.837 33.237 0 36.299-18.704 50.6-39.06 57.2" fill="#fffffe"/><path d="m256.614 396.633c3.585 1.805 5.875-.438 5.875-.438s52.457-47.878 76.089-75.451c21.02-24.666 22.39-66.234-13.707-81.766-36.097-15.531-65.795 18.272-65.795 18.272-25.755-28.326-64.734-26.892-82.763-7.722-18.028 19.17-11.732 52.073 1.717 70.384 12.625 17.19 68.118 66.65 76.529 75.015 0 0 .613.64 2.055 1.706" fill="#e05958"/></g></svg>
              </svg>
              <span style="
                top: 11%;
                position: relative;
              ">
              Ko-fi
              </span>
            </a>

            <!-- <a
              class="btn m-t-15 p-r-20"
              aria-label="Donate to using PayPal"
              target="_blank"
              @click="showDialog('bitcoin')"
            >
              <svg
                class="octicon octicon-heart icon-sponsor mr-2"
                height="16"
                style="color: #F5932F"
                viewBox="0 0 16 16"
                version="1.1"
                width="16"
                aria-hidden="true"
              >
               <svg viewBox="0 0 980 980" xmlns="http://www.w3.org/2000/svg"><path d="m977.13 437.75c-9.15-85.41-38.38-163.38-88.8-232.86-74.33-102.39-173.56-167.46-297.33-194.22-23.61-5.12-48-6.59-72.13-9.75l-6.87-.92h-44c-10.25 1-20.52 1.82-30.76 2.91-64.53 6.84-125.43 25.6-182.13 57.09q-153.91 85.51-220.43 248.84a469.54 469.54 0 0 0 -32.8 138.89c-.56 6.76-1.25 13.51-1.88 20.27v44c1 10.24 1.82 20.49 2.91 30.71 7.33 69.19 28.32 134 63.72 193.87q89.37 151.1 253.81 213.18a470.14 470.14 0 0 0 141.7 29.38c2 .11 3.91.57 5.86.86h44c10.09-1 20.18-1.8 30.25-2.87 77.17-8.17 148.62-33 213.45-75.56q159.08-104.49 208.65-288.66a458.49 458.49 0 0 0 14.77-94.55c.11-2.13.58-4.24.88-6.36v-44c-.95-10.08-1.79-20.18-2.87-30.25zm-190.56 235.39c-17.16 42.61-49 69.55-91.59 84.8-34.18 12.24-69.73 15.46-105.7 15.8-5.31 0-10.63 0-16.52 0v125.95h-77.69v-125.69h-51.33v125.7h-77.69v-126h-149.41c.85-27.15 1.69-53.72 2.54-80.85 2.14-.12 4-.32 6-.32h49.49c21.36 0 32.22-10.43 33.32-31.85.16-3 .16-6 .16-9q0-168 0-336c0-2.66.07-5.35-.18-8-1-10-5.85-17.44-15.57-20.58a60.82 60.82 0 0 0 -17.08-3.1c-19.16-.43-38.33-.25-57.49-.31h-5.83v-79.75h154v-123.81h77.57v123.47h51.43v-123.27h77.4v124.61c8.37 1.05 16.24 1.9 24.07 3.05 35.49 5.2 69.79 14.28 101.18 32.24 24.89 14.23 45.53 32.84 56.22 60.15 17.4 44.48 9.85 104.55-34.87 143.62-6.62 5.78-13.89 10.8-21.17 16.41 3.39 1.18 6.89 2.31 10.32 3.62 31.39 11.92 57.59 30.45 75.27 59.65a119.89 119.89 0 0 1 17.12 57.32c1.46 31.58-2.06 62.58-13.97 92.14z"/><path d="m618.12 537.2c-22-12-45.93-16.77-70.63-17.19-33.47-.57-67-.22-100.44-.24-1 0-1.91.18-3.11.3v164.61c1.74.08 3 .19 4.34.19 27.82 0 55.64.14 83.45-.09 21.06-.18 41.85-2.48 61.87-9.65 46-16.47 60.1-53.72 57-92.92-1.6-21.06-14.6-35.21-32.48-45.01z"/><path d="m537.63 440.44a72.15 72.15 0 0 0 37.55-10.17c24.39-14.06 35.81-36 38.33-63.44 2.62-28.49-8.83-50.07-34.31-63-17.05-8.68-35.47-12.78-54.32-13.59-26.27-1.14-52.6-.91-78.9-1.25a14 14 0 0 0 -2.2.33v151.01h6.41c29.15 0 58.3-.24 87.44.11z"/></svg>
              </svg>
              <span>Bitcoin</span>
            </a> -->

          </div>
        </div>
      </div>
    </article>
  </main>
</template>

<script>
export default {
  name: "Sponsor",
  data() {
    return {
      gitHub: {
        profile: require("../assets/profilePic.jpg"),
      },
    };
  },

  methods:{
    showDialog(dialogId, icon){
      let parent = this

      document.getElementById(dialogId).show()
    },
  }
};
</script>

<style>
@import url("../assets/sponsors-embed-b6c9390efcf556f7abc24c7291e23a35.css");
</style>
