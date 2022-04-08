<script>
export default {
  props: {
    text: String,
  },
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-4 bg-black rounded-lg px-4 py-6">
      <h2 v-text="text" class="text-main-gold text-xl text-center font-semibold uppercase"></h2>
    </div>
  </div>
</template>
