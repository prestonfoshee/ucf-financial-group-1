<script>
import NavGrid from '../components/home/NavGrid.vue'
export default {
    layout: 'home',
    components: { NavGrid },
}
</script>

<template>
<div>
    <div class="flex flex-col items-center space-y-3 mb-12">
      <h1 class="text-white text-3xl text-center font-bold">UCF Financial</h1>
      <div class="max-w-md">
        <p class="text-white text-xl text-center font-light">Manage all your UCF-related finances to get yourself ahead of the game.</p>
      </div>
    </div>
    <NavGrid />
</div>
</template>
