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
          headerText: 'Ask an advisor to guide you',
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
  <main class="min-h-screen bg-main-white">
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
        <!-- <div class="flex justify-between relative">
          <input type="text" class="px-4 py-2 rounded-md text-black text-sm">
          <button type="submit" class="absolute right-0 w-1/6 h-full bg-main-gold rounded-md">
            <svg fill="#000000" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 30 30" width="20px" height="20px" class="absolute right-2 bottom-2">
             <path d="M 13 3 C 7.4889971 3 3 7.4889971 3 13 C 3 18.511003 7.4889971 23 13 23 C 15.396508 23 17.597385 22.148986 19.322266 20.736328 L 25.292969 26.707031 A 1.0001 1.0001 0 1 0 26.707031 25.292969 L 20.736328 19.322266 C 22.148986 17.597385 23 15.396508 23 13 C 23 7.4889971 18.511003 3 13 3 z M 13 5 C 17.430123 5 21 8.5698774 21 13 C 21 17.430123 17.430123 21 13 21 C 8.5698774 21 5 17.430123 5 13 C 5 8.5698774 8.5698774 5 13 5 z"/>
            </svg>
          </button>
        </div> -->
      </div>
    </section>

    <div class="flex justify-center bg-right bg-no-repeat w-full lg:bg-cover lg:h-550" :style="{'background-image': `url(${require('@/assets/img/contact-header.jpg')})`}">
      <div class="flex flex-col space-y-24 py-10 px-16">
        <Nav />
        <div class="flex flex-col justify-center space-y-8">
          <div class="flex justify-center items-center bg-main-gold/50 max-w-md p-4">
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
      <div class="max-w-screen-3xl mx-auto space-y-32">
        <Nuxt />
        <Footer />
      </div>
    </section>
  </main>
</template>
