<script>
import HamburgerIcon from './HamburgerIcon.vue'

export default {
  components: {
    HamburgerIcon
  },
  data() {
    return {
      toggled: false
    }
  },
  methods: {
    toggle() {
      this.toggled = !this.toggled
    },
  },
}
</script>

<template>
  <div>
    <nav class="hidden lg:block">
        <ul class="flex text-white whitespace-nowrap tracking-wider lg:gap-y-10 lg:flex-wrap lg:justify-center xl:flex-nowrap xl:justify-start xl:gap-y-0" >
            <li>
                <NuxtLink to="/"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300">Home
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/financial-aid"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'financial-aid' }">
                    Financial Aid
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/scholarships"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'scholarships' }">
                    Scholarships
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/coupons-and-discounts"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'coupons-and-discounts' }">
                    Coupons & Discounts
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/financial-literacy"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'financial-literacy' }">
                    Financial Literacy
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/budget-calculator"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'budget-calculator' }">
                    Budget Calculator
                </NuxtLink>
            </li>
            <li>
                <NuxtLink to="/contact"
                class="font-bold hover:bg-black/90 px-6 pb-4 pt-7 transition duration-300"
                :class="{ 'bg-gray-400/80 px-6 pb-4 pt-7': $route.name === 'contact' }">
                    Contact Us
                </NuxtLink>
            </li>
        </ul>
    </nav>

    <nav class="block lg:hidden">
      <hamburger-icon @clicked="toggle" class="absolute right-0" />
      <ul v-show="toggled" class="flex flex-col items-center space-y-6 md:space-y-10 text-white bg-zinc-700/90 w-screen py-4">
        <li>
          <NuxtLink to="/"
          class="font-bold p-4 transition duration-300">
              Home
          </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/financial-aid"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 py-4 px-24': $route.name === 'financial-aid' }">
                Financial Aid
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/scholarships"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4 px-24': $route.name === 'scholarships' }">
                Scholarships
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/coupons-and-discounts"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4 px-24': $route.name === 'coupons-and-discounts' }">
                Coupons & Discounts
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/financial-literacy"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4 px-24': $route.name === 'financial-literacy' }">
                Financial Literacy
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/budget-calculator"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4 px-24': $route.name === 'budget-calculator' }">
                Budget Calculator
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/contact"
            class="font-bold hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4 px-24': $route.name === 'contact' }">
                Contact Us
            </NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>
