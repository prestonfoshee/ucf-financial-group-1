<script>
import UcfLogo from '../components/UcfLogo.vue'
  export default {
    data() {
      return {
        budget: {
          headerText: 'Manage your budget',
          subtitleText: 'Use real figures from your current records to plan out your semester.',
        },
        calendar: {
          headerText: 'Events & Important Dates',
          subtitleText: 'Keep track of events & important milestones to stay ahead of the game.',
        },
        aid: {
          headerText: 'One-stop for financial aid',
          subtitleText: 'Keep track of events & important milestones to stay ahead of the game.',
        },
        scholarships: {
          headerText: 'An endless list of possibilities',
          subtitleText: 'Use real figures from your current records to plan out your semester.',
        },
        coupons: {
          headerText: 'Discounts at your convenience',
          subtitleText: 'Use real figures from your current records to plan out your semester.',
        },
        literacy: {
          headerText: 'Finance information at your fingertips',
          subtitleText: 'Use real figures from your current records to plan out your semester.',
        },
        contact: {
          headerText: 'Contact an advisor',
          subtitleText: 'Use real figures from your current records to plan out your semester.',
        },
      }
    },
    components: {
      UcfLogo
    }
  }
</script>

<template>
  <main class="min-h-screen bg-white">
    <section class="flex justify-between items-center px-16 py-3 bg-black">
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

    <div class="flex lg:justify-center bg-center bg-no-repeat w-full lg:bg-cover lg:h-550" :style="{'background-image': `url(${require('@/assets/img/scholarships-header.jpg')})`}">
      <div class="lg:static py-6 lg:flex lg:flex-col lg:space-y-24 lg:py-10 lg:px-16">
        <div class="relative w-screen lg:w-auto">
          <Nav class="absolute right-0 lg:static" />
        </div>
        <div class="flex flex-col justify-center items-center lg:items-start space-y-8 mt-16 lg:mt-0">
          <div class="flex justify-center items-center bg-main-gold/50 max-w-sm p-4">
            <h1 v-if="$route.name === 'budget-calculator'" class="text-white text-5xl  font-bold uppercase">{{ budget.headerText }}</h1>
            <h1 v-else-if="$route.name === 'calendar'" class="text-white text-5xl  font-bold uppercase">{{ calendar.headerText }}</h1>
            <h1 v-else-if="$route.name === 'financial-aid'" class="text-white text-5xl  font-bold uppercase">{{ aid.headerText }}</h1>
            <h1 v-else-if="$route.name === 'scholarships'" class="text-white text-5xl  font-bold uppercase">{{ scholarships.headerText }}</h1>
            <h1 v-else-if="$route.name === 'coupons-and-discounts'" class="text-white text-5xl  font-bold uppercase">{{ coupons.headerText }}</h1>
            <h1 v-else-if="$route.name === 'financial-literacy'" class="text-white text-5xl  font-bold uppercase">{{ literacy.headerText }}</h1>
            <h1 v-else-if="$route.name === 'contact'" class="text-white text-5xl  font-bold uppercase">{{ contact.headerText }}</h1>
          </div>
          <div class="max-w-sm">
            <p v-if="$route.name === 'budget-calculator'" class="text-white text-3xl font-extralight">{{ budget.subtitleText }}</p>
            <p v-else-if="$route.name === 'calendar'" class="text-white text-3xl font-extralight">{{ calendar.subtitleText }}</p>
            <p v-else-if="$route.name === 'financial-aid'" class="text-white text-3xl font-extralight">{{ aid.subtitleText }}</p>
            <p v-else-if="$route.name === 'scholarships'" class="text-white text-3xl font-extralight">{{ scholarships.subtitleText }}</p>
            <p v-else-if="$route.name === 'coupons-and-discounts'" class="text-white text-3xl font-extralight">{{ coupons.subtitleText }}</p>
            <p v-else-if="$route.name === 'financial-literacy'" class="text-white text-3xl font-extralight">{{ literacy.subtitleText }}</p>
            <p v-else-if="$route.name === 'contact'" class="text-white text-3xl font-extralight">{{ contact.subtitleText }}</p>
          </div>
        </div>
      </div>
    </div>

    <section class="pt-12">
      <div class="mx-auto">
        <Nuxt />
        <Footer />
      </div>
    </section>
  </main>
</template>
