<script>

</script>

<template>
  <div>
    <nav class="block md:hidden">
      <hamburger-icon />
      <ul>
        <li>
          <NuxtLink to="/"
          class="font-medium hover:bg-black/90 p-4 transition duration-300">
              Home
          </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/financial-aid"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'financial-aid' }">
                Financial Aid
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/scholarships"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'scholarships' }">
                Scholarships
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/coupons-and-discounts"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'coupons-and-discounts' }">
                Coupons & Discounts
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/financial-literacy"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'financial-literacy' }">
                Financial Literacy
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/budget-calculator"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'budget-calculator' }">
                Budget Calculator
            </NuxtLink>
        </li>
        <li>
            <NuxtLink to="/contact"
            class="font-medium hover:bg-black/90 p-4 transition duration-300"
            :class="{ 'bg-gray-400/80 p-4': $route.name === 'contact' }">
                Contact Us
            </NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>
