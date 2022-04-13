<script>

</script>

<template>
  <div class="grid gap-6 grid-cols-2 grid-rows-4 md:grid-cols-3 md:grid-rows-3 lg:grid-cols-4 lg:grid-rows-2 mb-20" style="text-shadow: -3px 3px 3px #000000;">

    <NuxtLink to="/budget-calculator">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/budget-calculator.jpg" class="w-full h-full object-cover absolute">
          <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Budget Calculator</h3>
      </div>
    </NuxtLink>

    <NuxtLink to="/calendar">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/calendar.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Calendar</h3>
      </div>
    </NuxtLink>

    <NuxtLink to="/financial-aid">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/financial-aid.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Financial Aid</h3>
      </div>
    </NuxtLink>

    <NuxtLink to="/scholarships">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/scholarships.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Scholarships</h3>
      </div>
    </NuxtLink>

    <NuxtLink to="/coupons-and-discounts">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/coupons-and-discounts.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Coupons & Discounts</h3>
      </div>
    </NuxtLink>

    <NuxtLink to="/financial-literacy">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/financial-literacy.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Financial Literacy</h3>
      </div>
    </NuxtLink>

    <!-- <NuxtLink to="/financial-events">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/financial-events.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Financial Events</h3>
      </div>
    </NuxtLink> -->

    <NuxtLink to="/contact">
      <div class="flex flex-col justify-center items-center relative h-72 transition hover:scale-110 duration-150 hover:cursor-pointer">
        <img src="~/assets/img/contact-us.jpg" class="w-full h-full object-cover absolute">
        <h3 class="text-3xl text-white font-bold text-center absolute left-0 right-0">Contact Us</h3>
      </div>
    </NuxtLink>

  </div>
</template>
