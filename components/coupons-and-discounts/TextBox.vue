<script>
export default {
  props: {
    text: String,
  },
}
</script>

<template>
  <div>
    <div class="flex justify-center items-center w-72 m-4 bg-main-gold rounded-xl px-4 py-6">
      <h2 v-text="text" class="text-black text-xl text-center font-semibold whitespace-nowrap"></h2>
    </div>
  </div>
</template>
