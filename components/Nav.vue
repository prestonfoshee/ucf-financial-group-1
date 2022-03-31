<script setup>


</script>

<template>
  <nav>
      <ul class="flex space-x-10">
          <li>
              <NuxtLink to="/"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'index' ? 'underline'  : null">
                  Home
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/about"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'about' ? 'underline'  : null">
                  Budget Calculator
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Calendar
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Financial Aid
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Scholarships
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Coupons & Discounts
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Financial Literacy
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Financial Events
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Contact Us
              </NuxtLink>
          </li>
      </ul>
  </nav>
</template>
