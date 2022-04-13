<script>
export default {
  layout: 'financial-aid',
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-24">
      <div class="flex justify-between px-16">
        <div class="flex flex-col space-y-12 lg">
          <div class="border-2 border-main-gold max-w-min whitespace-nowrap p-4">
            <h2 class="text-main-gold text-4xl text-center font-medium">Applying for Financial Aid?</h2>
          </div>
          <div class="flex flex-col space-y-12 max-w-3xl">
            <p class="text-white text-xl font-medium">
              Completing the Free Application for Federal Student Aid (FAFSA) automatically allows you to be considered for federal, state and
              university financial aid programs. Filling out the FAFSA is free.
            </p>
            <p class="text-white text-xl font-medium">
              All students <span class="text-main-gold underline">must apply or reapply</span> for financial aid every year.
            </p>
          </div>
        </div>
        <div class="flex flex-col space-y-6 text-black text-center">
          <div class="bg-white p-8">
            <p class="uppercase font-light text-2xl">UCF School Code:</p>
            <p class="font-bold text-2xl">003954</p>
          </div>
        </div>
        <!-- <img src="~/assets/img/financial-aid-person-1.jpg" alt="" class=" rounded-xl"> -->
      </div>
      <div class="flex justify-center space-x-4">
        <img src="~/assets/img/financial-aid-person-2.jpg" alt="" class="rounded-full">
        <img src="~/assets/img/financial-aid-person-3.jpg" alt="" class="rounded-full">
        <img src="~/assets/img/financial-aid-person-4.jpg" alt="" class="rounded-full">
      </div>
    </div>
  </div>
</template>
