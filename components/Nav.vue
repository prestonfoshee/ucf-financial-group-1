<script setup>


</script>

<template>
  <nav>
      <ul class="flex space-x-10">
          <li>
              <NuxtLink to="/"
              class="text-main-gold font-medium uppercase hover:underline"
              :class="$route.name === 'index' ? 'underline'  : null">
                  Home
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/about"
              class="text-main-gold font-medium uppercase hover:underline"
              :class="$route.name === 'about' ? 'underline'  : null">
                  About
              </NuxtLink>
          </li>
          <li>
              <NuxtLink to="/posts"
              class="text-main-gold font-medium uppercase hover:underline"
              :class="$route.name === 'posts' ? 'underline'  : null">
                  Posts
              </NuxtLink>
          </li>
      </ul>
  </nav>
</template>
