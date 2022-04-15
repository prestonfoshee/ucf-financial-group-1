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
    <div class="flex flex-col space-y-4 w-full border-2 border-gray-300 rounded-lg py-6">
      <h2
      v-text="headerText"
      class="text-lg lg:text-3xl text-center font-semibold"
      :class="{ 'text-3xl text-center font-semibold uppercase': type === 'top' }"
      >
      </h2>
      <p
      v-text="subtitleText"
      v-show="type === 'top'"
      class="text-sm lg:text-lg text-center font-extralight"
      >
      </p>
    </div>
  </div>
</template>
