<script>
export default {
  props: {
    headerText: String,
    subtitleText: String,
    type: String,
  },
}
</script>

<template>
  <div>
    <div
    class="flex flex-col space-y-4 w-full bg-black rounded-lg py-6"
    :class="{ 'bg-main-gold': type === 'bottom' }">
      <h2
      v-text="headerText"
      class="text-3xl text-center font-semibold"
      :class="{ 'text-main-gold text-3xl text-center font-semibold uppercase': type === 'top' }"
      >
      </h2>
      <p
      v-text="subtitleText"
      v-show="type === 'top'"
      class="text-main-gold text-lg text-center font-light"
      >
      </p>
    </div>
  </div>
</template>
