<script>
import UcfLogo from '../components/UcfLogo.vue'
export default {
  components: {
    UcfLogo
  },
}
</script>

<template>
<main class="min-h-screen bg-black">
  <section class="flex justify-between items-center px-4 md:px-16 py-3">
    <div class="flex items-center">
      <ucf-logo />
      <div class="flex items-center space-x-8">
        <div class="px-6 pt-3">
          <h1 class="text-lg text-center md:text-left md:text-2xl text-main-gold font-medium uppercase">University of Central Florida</h1>
        </div>
      </div>
    </div>
    <div class="flex flex-col items-center space-y-5 md:flex-row md:space-x-4 md:space-y-0">
      <div class="flex h-10 justify-center items-center bg-main-gold border-yellow-500 text-yellow-700 rounded font-bold pb-1 pt-3 px-4">
          Logout
      </div>
      <NuxtLink to="/account">
        <img src="~assets/img/profile-pic.jpeg" alt="" class="rounded-full">
      </NuxtLink>
    </div>
  </section>
  <section class="">
    <div class="max-w-screen-3xl mx-auto">
      <Nuxt />
    </div>
  </section>
</main>
</template>
