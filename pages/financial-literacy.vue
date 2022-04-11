<script>
import FinancialLiteracyBanner from '../components/FinancialLiteracyBanner.vue'
export default {
  components: { FinancialLiteracyBanner },
    layout: 'financial-literacy'
  }
</script>

<template>
  <div>
    <div class="flex flex-col space-y-6 p-10 w-full">
      <div class="flex flex-col space-y-5 pb-3">
        <h2 class="text-white text-4xl font-bold">A Financial Resource for Every Student</h2>
        <div class="w-40 border-b-2 border-main-gold"></div>
      </div>
      <div class="flex justify-between">
        <div class="flex flex-col space-y-4">
          <div class="max-w-3xl">
            <p class="text-white text-lg font-light">Financial Literacy means confidently understanding and
              utilizing financial concepts like saving, budgeting, credit,
              etc. At UCF we believe in setting students up for success,
              this means guiding students towards financial literacy.
              Below are some resources to help you gain control of your
              finances and understand how financial aid can impact your
              finances.
            </p>
          </div>
          <div class="max-w-3xl">
            <p class="text-white text-lg font-light">In addition to the resources listed below, UCF has partnered with Gradready
              to offer students free courses for financial learning. They cover everything that is listed above and more! This is a
              benefit offered to students to help make better money habits that apply to the real world and amplify their success.
              To learn more about Gradready please visit: <a href="https://gradready.com/sponsor/ucf" target="_blank" class="text-main-gold underline">UCF.gradready.com</a>
            </p>
          </div>
      </div>
      <div class="w-64 h-64 bg-gray-400"></div>
      </div>
      <div class="relative">
        <financial-literacy-banner />
        <h2 class="absolute top-10 left-20 text-sm lg:top-5 lg:left-48 lg:text-3xl md:left-40 md:top-8 md:text-xl font-bold text-black">Understanding Loans</h2>
        <p class="absolute top-14 left-20 text-xs lg:top-14 lg:left-48 lg:text-lg md:left-40 md:text-base font-light text-black">(Interest rates and more)</p>
      </div>
    </div>
  </div>
</template>
