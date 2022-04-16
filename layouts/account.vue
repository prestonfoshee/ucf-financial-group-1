<script>
import UcfLogo from '../components/UcfLogo.vue'
  export default {
    components: {
      UcfLogo
    },
  }
</script>

<template>
  <main class="min-h-screen bg-white">
    <div class="flex flex-col space-y-4 bg-black px-16 py-6">
      <section class="flex justify-between items-center">
        <div class="flex items-center">
            <ucf-logo />
            <div class="flex items-center space-x-8">
                <div class="px-6">
                    <h1 class="text-2xl text-main-gold font-medium uppercase">University of Central Florida</h1>
                </div>
            </div>
        </div>
        <div class="flex items-center justify-center space-x-10 text-main-gold">
          <svg width="60" height="60" viewBox="0 0 60 60" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="30" cy="30" r="30" fill="#C4C4C4"/>
          </svg>
        </div>
      </section>
    </div>
        <div class="bg-black lg:flex lg:justify-center lg:pb-8">
          <div class="relative lg:w-auto">
            <Nav class="absolute -top-10 right-0 md: lg:static lg:mx-auto" />
          </div>
        </div>

    <section class="">
      <div class="mx-auto">
        <Nuxt />
        <Footer />
      </div>
    </section>
  </main>
</template>
