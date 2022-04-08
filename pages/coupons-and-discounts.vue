<script>
import TextBox from '../components/coupons-and-discounts/TextBox.vue'
export default {
  components: {
    TextBox
  },
}
</script>

<template>
  <div class="flex flex-col space-y-12">
    <h1 class="text-black text-3xl text-center font-bold">Find Student Discounts & Offers</h1>
    <div class="flex flex-col space-y-4">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">Technology & Media</h2>
      </div>
      <p class="text-black text-xl font-semibold">Adobe</p>
      <p class="text-black text-lg font-light">Adobe products are currently <span class="underline">almost 70% off</span> with current Black Friday deals</p>
      <p class="text-black text-xl font-semibold">Amazon Prime</p>
      <p class="text-black text-lg font-light">Amazon offers students a free 6 month trial of Amazon Prime, with the service being half off at $49 after the initial 6 months are over.</p>
      <p class="text-black text-xl font-semibold">Microsoft Office</p>
      <p class="text-black text-lg font-light">Microsoft Office is free for students!</p>
    </div>
    <div class="flex flex-col space-y-4">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">Local Discounts</h2>
      </div>
      <p class="text-black text-xl font-semibold">Enzian Theater</p>
      <p class="text-black text-lg font-light">An arthouse cinema that offers student discounted tickets for $9. Enzian.org</p>
      <div>
        <p class="text-black text-xl font-semibold">Bulk Nation</p>
        <p class="text-black text-lg font-light">Students recieve 10% off their purchases at Bulk Nation on Tuesdays.</p>
        <a href="https://www.bulknationusa.com" class="text-main-gold text-lg font-light underline">bulknationusa.com</a>
      </div>
      <div>
        <p class="text-black text-xl font-semibold">BuegerFi</p>
        <p class="text-black text-lg font-light">Discounted burgers and shakes for students who bring their ID's.</p>
        <a href="https://www.burgerfi.com/" class="text-main-gold text-lg font-light underline">burgerfi.com</a>
      </div>
    </div>
    <div class="flex flex-col space-y-4">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">UCF On-Campus Aid</h2>
      </div>
      <div class="flex justify-center space-x-8">
        <text-box :text="'Knights Pantry'" />
        <text-box :text="'Knights Pantry'" />
        <text-box :text="'Knights Pantry'" />
      </div>
    </div>
  </div>
</template>
