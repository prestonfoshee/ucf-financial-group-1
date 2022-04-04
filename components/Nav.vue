<script setup>


</script>

<template>
  <nav>
      <ul class="flex space-x-10 text-white">
          <li>
              <NuxtLink to="/"
              class="font-medium hover:underline"
              :class="$route.name === 'index' ? 'underline'  : null">
                  Home
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/budget-calculator"
              class="font-medium hover:underline"
              :class="$route.name === 'budget-calculator' ? 'underline'  : null">
                  Budget Calculator
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/calendar"
              class="font-medium hover:underline"
              :class="$route.name === 'calendar' ? 'underline'  : null">
                  Calendar
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/financial-aid"
              class="font-medium hover:underline"
              :class="$route.name === 'financial-aid' ? 'underline'  : null">
                  Financial Aid
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/scholarships"
              class="font-medium hover:underline"
              :class="$route.name === 'scholarships' ? 'underline'  : null">
                  Scholarships
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/coupons-and-discounts"
              class="font-medium hover:underline"
              :class="$route.name === 'coupons-and-discounts' ? 'underline'  : null">
                  Coupons & Discounts
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/financial-literacy"
              class="font-medium hover:underline"
              :class="$route.name === 'financial-literacy' ? 'underline'  : null">
                  Financial Literacy
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/financial-events"
              class="font-medium hover:underline"
              :class="$route.name === 'financial-events' ? 'underline'  : null">
                  Financial Events
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/contact"
              class="font-medium hover:underline"
              :class="$route.name === 'contact' ? 'underline'  : null">
                  Contact Us
              </NuxtLink>
          </li>
      </ul>
  </nav>
</template>
