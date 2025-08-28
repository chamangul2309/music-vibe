<script setup lang="ts">

</script>

<template>

  <section class="bg-gray-100">
    <div class="container mx-auto py-16 px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 md:grid-cols-2 items-center gap-8">
        <div class="max-w-lg">
          <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">🎶 About Us</h2>
          <p class="mt-4 text-gray-600 text-lg">Music Club is the place where passion meets sound.
            We bring together music lovers, performers, and creators to share vibes, play live, and celebrate every note.

             Join us — discover talent, make friends, and feel the rhythm!</p>
          <div class="mt-8">
            <a href="#" class="text-blue-500 hover:text-blue-600 font-medium">Learn more about us
              <span class="ml-2">&#8594;</span></a>
          </div>
        </div>
        <div class="mt-12 md:mt-0">
          <img src="https://3.files.edl.io/579f/21/09/16/200042-7b7d1afb-fda5-4131-bf95-1b6e6cda5da8.jpg" alt="About Us Image" class="object-cover rounded-lg shadow-md">
        </div>
      </div>
    </div>
  </section>
  <section class="relative bg-gray-900 text-white py-16 px-8 overflow-hidden">
    <!-- SVG Pattern Background -->
    <div class="absolute inset-0 -z-10">
      <svg class="w-full h-full" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" viewBox="0 0 1440 320">
        <defs>
          <pattern id="dots" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
            <circle cx="2" cy="2" r="2" class="text-gray-700" fill="currentColor"/>
          </pattern>
        </defs>
        <rect width="100%" height="100%" fill="url(#dots)" opacity="0.2"/>
      </svg>
    </div>

    <!-- Container Content -->
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center md:items-center md:space-x-12">
      <!-- Image -->
      <div class="w-full md:w-1/2 mb-8 md:mb-0">
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?ixlib=rb-4.0.4&auto=format&fit=crop&w=800&q=80" alt="Our Team" class="rounded-lg shadow-lg object-cover w-full h-full" />
      </div>

      <!-- Text Content -->
      <div class="w-full md:w-1/2">
        <h2 class="text-4xl font-bold mb-4 border-b-4 border-blue-500 inline-block">About our student</h2>
        <p class="mb-4 text-gray-300 leading-relaxed">
          We are committed to delivering innovative solutions with a focus on quality and customer satisfaction. Our team of experts works tirelessly to bring your ideas to life and help your business grow.
        </p>
        <p class="mb-4 text-gray-300 leading-relaxed">
          Join us on our journey to make a difference in the industry through creativity, dedication, and excellence.
        </p>
        <a href="#contact" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-300">
          Contact Us
        </a>
      </div>
    </div>
  </section>
  <div class="mx-auto max-w-7xl sm:px-6 lg:px-8 mt-20">

    <div
        class="relative isolate overflow-hidden bg-white px-6 py-20 text-center sm:rounded-3xl sm:border sm:border-gray-100 sm:px-16 sm:shadow-sm">

      <h2 class="mx-auto max-w-2xl text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
        More about our club
      </h2>

      <h3 class="mx-auto mt-6 max-w-xl text-lg leading-8 text-gray-500">
        Sign up for exclusive access to events, resources, and more
      </h3>

      <div class="mt-8 flex items-center justify-center gap-x-6">
        <a class="inline-flex items-center justify-center gap-2 rounded-xl bg-blue-600 px-4 py-3 text-sm font-semibold text-white shadow-sm transition-all duration-150 hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-blue-600"
           href="#">
          MORE
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd"
                  d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"></path>
          </svg>
        </a>
      </div>

      <!-- gradient svg -->
      <svg viewBox="0 0 1024 1024"
           class="absolute left-1/2 top-1/2 -z-10 h-[64rem] w-[64rem] -translate-x-1/2 [mask-image:radial-gradient(closest-side,white,transparent)]"
           aria-hidden="true">
        <circle cx="512" cy="512" r="512" fill="url(#827591b1-ce8c-4110-b064-7cb85a0b1217)" fill-opacity="0.7">
        </circle>
        <defs>
          <radialGradient id="827591b1-ce8c-4110-b064-7cb85a0b1217">
            <stop stop-color="#3b82f6"></stop>
            <stop offset="1" stop-color="#1d4ed8"></stop>
          </radialGradient>
        </defs>
      </svg>

    </div>

  </div>
</template>

<style scoped>

</style>