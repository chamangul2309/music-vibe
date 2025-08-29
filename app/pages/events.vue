<script setup lang="ts">

</script>

<template>

  <section class="relative h-screen flex flex-col items-center justify-center text-center text-white ">
    <div class="video-docker absolute top-0 left-0 w-full h-full overflow-hidden">
      <video class="min-w-full min-h-full absolute object-cover"
             src="/video.mp4"
             type="video/mp4" autoplay muted loop></video>
    </div>
    <div class="video-content space-y-2 z-10">
      <h1 class="font-light text-6xl">Vibe</h1>
      <h3 class="font-light text-3xl">Atmosphere in my club!</h3>
    </div>
  </section>
  <div class="bg-white dark:bg-gray-800 ">
    <div class="mx-auto max-w-screen-2xl px-4 md:px-8">
      <div class="mb-4 flex items-center justify-between gap-8 sm:mb-8 md:mb-12">
        <div class="flex items-center gap-12">
          <h2 class="text-2xl font-bold text-gray-800 lg:text-3xl dark:text-white">Gallery</h2>

          <p class="hidden max-w-screen-sm text-gray-500 dark:text-gray-300 md:block">
            "One good thing about music, when it hits you, you feel no pain"
          </p>
        </div>

        <a href="#"
           class="inline-block rounded-lg border bg-white dark:bg-gray-700 dark:border-none px-4 py-2 text-center text-sm font-semibold text-gray-500 dark:text-gray-200 outline-none ring-indigo-300 transition duration-100 hover:bg-gray-100 focus-visible:ring active:bg-gray-200 md:px-8 md:py-3 md:text-base">
          More
        </a>
      </div>

      <div class="grid grid-cols-2 gap-4 sm:grid-cols-3 md:gap-6 xl:gap-8">
        <!-- image - start -->
        <a href="#"
           class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:h-80">
          <img src="https://st.depositphotos.com/3917667/60291/i/450/depositphotos_602911680-stock-photo-hip-hop-dance-street-style.jpg" loading="lazy" alt="Photo by Minh Pham" class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

          <div
              class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
          </div>

          <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">HipHop day</span>
        </a>
        <!-- image - end -->

        <!-- image - start -->
        <a href="#"
           class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:col-span-2 md:h-80">
          <img src="https://ourkids.social/wp-content/uploads/2020/01/confetti-parties-1240.jpg" loading="lazy" alt="Photo by Magicle" class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

          <div
              class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
          </div>

          <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Party</span>
        </a>
        <!-- image - end -->

        <!-- image - start -->
        <a href="#"
           class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:col-span-2 md:h-80">
          <img src="https://www.vedantu.com/seo/content-images/0a6de36b-c0e9-42c7-8769-943759328a1f_10_Fun_Activities_for_Summer_Music_and_Dance_Parties.png" loading="lazy" alt="Photo by Martin Sanchez" class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

          <div
              class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
          </div>

          <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Halloween</span>
        </a>
        <!-- image - end -->

        <!-- image - start -->
        <a href="#"
           class="group relative flex h-48 items-end overflow-hidden rounded-lg bg-gray-100 shadow-lg md:h-80">
          <img src="https://static.mywebsites360.com/fb56d5f3bf75434fb0f27f03ade1bd1b/i/cdba11174b9f4fc58a5dc64e2a9f72b6/1/4SoifmQp45JMgBnHp7ed2/Why%20You%20Should%20Enroll%20Your%20Child%20in%20a%20Summer%20Dance%20Camp%20-%20Image%202.jpg" loading="lazy" alt="Photo by Lorenzo Herrera" class="absolute inset-0 h-full w-full object-cover object-center transition duration-200 group-hover:scale-110" />

          <div
              class="pointer-events-none absolute inset-0 bg-gradient-to-t from-gray-800 via-transparent to-transparent opacity-50">
          </div>

          <span class="relative ml-4 mb-3 inline-block text-sm text-white md:ml-5 md:text-lg">Dance</span>
        </a>
        <!-- image - end -->
      </div>
    </div>
  </div>
  <div class="bg-indigo-700] p-4">
    <h2 class="text-3xl text-white font-bold mb-12">Chronology</h2>
    <div class="flex flex-col grid-cols-9 p-2 mx-auto md:grid">
      <div class="flex md:contents flex-row-reverse">
        <div
            class="relative p-4 my-6 text-gray-800 bg-white rounded-xl col-start-1 col-end-5 mr-auto md:mr-0 md:ml-auto">
          <h3 class="text-lg font-semibold lg:text-xl">Pamirian dance</h3>

          <span class="absolute text-sm text-black -top-5 left-2 whitespace-nowrap">Date 1</span>
        </div>
        <div class="relative col-start-5 col-end-6 mr-7 md:mx-auto">
          <div class="flex items-center justify-center w-6 h-full">
            <div class="w-1 h-full bg-indigo-300 rounded-t-full bg-gradient-to-b from-indigo-400 to-indigo-300">
            </div>
          </div>
          <div class="absolute w-6 h-6 -mt-3 bg-white border-4 border-indigo-400 rounded-full top-1/2"></div>
        </div>
      </div>

      <div class="flex md:contents">
        <div class="relative col-start-5 col-end-6 mr-7 md:mx-auto">
          <div class="flex items-center justify-center w-6 h-full">
            <div class="w-1 h-full bg-indigo-300"></div>
          </div>
          <div class="absolute w-6 h-6 -mt-3 bg-white border-4 border-indigo-400 rounded-full top-1/2"></div>
        </div>
        <div class="relative p-4 my-6 text-gray-800 bg-white rounded-xl col-start-6 col-end-10 mr-auto">
          <h3 class="text-lg font-semibold lg:text-xl">Information about music</h3>

          <span class="absolute text-sm text-black-100/75 -top-5 left-2 whitespace-nowrap">Date 2</span>
        </div>
      </div>

      <div class="flex md:contents flex-row-reverse">
        <div
            class="relative p-4 my-6 text-gray-800 bg-white rounded-xl col-start-1 col-end-5 mr-auto md:mr-0 md:ml-auto">
          <h3 class="text-lg font-semibold lg:text-xl">TikTok dance</h3>

          <span class="absolute text-sm text-black-100/75 -top-5 left-2 whitespace-nowrap">Date 3</span>
        </div>
        <div class="relative col-start-5 col-end-6 mr-7 md:mx-auto">
          <div class="flex items-center justify-center w-6 h-full">
            <div class="w-1 h-full bg-indigo-300 rounded-t-full bg-gradient-to-b from-indigo-400 to-indigo-300">
            </div>
          </div>
          <div class="absolute w-6 h-6 -mt-3 bg-white border-4 border-indigo-400 rounded-full top-1/2"></div>
        </div>
      </div>

      <div class="flex md:contents">
        <div class="relative col-start-5 col-end-6 mr-7 md:mx-auto">
          <div class="flex items-center justify-center w-6 h-full">
            <div class="w-1 h-full bg-indigo-300"></div>
          </div>
          <div class="absolute w-6 h-6 -mt-3 bg-white border-4 border-indigo-400 rounded-full top-1/2"></div>
        </div>
        <div class="relative p-4 my-6 text-gray-800 bg-white rounded-xl col-start-6 col-end-10 mr-auto">
          <h3 class="text-lg font-semibold lg:text-xl">Free lesson</h3>

          <span class="absolute text-sm text-black-100/75 -top-5 left-2 whitespace-nowrap">Date 4</span>
        </div>
      </div>

    </div>
  </div>

 
</template>

<style scoped>
.video-docker video {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.video-docker::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: rgba(0, 0, 0, 0.6);
  z-index: 1;
}
</style>