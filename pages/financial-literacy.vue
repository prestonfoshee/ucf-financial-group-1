<script>
import FinancialLiteracyBanner from '../components/FinancialLiteracyBanner.vue'
import BuildingIcon from '../components/BuildingIcon.vue'
import CardIcon from '../components/CardIcon.vue'
import BudgetingIcon from '../components/BudgetingIcon.vue'
import SavingIcon from '../components/SavingIcon.vue'
export default {
  components: {
    FinancialLiteracyBanner,
    BuildingIcon,
    CardIcon,
    BudgetingIcon,
    SavingIcon,
   },
  layout: 'financial-literacy'
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-16 w-full">
      <div class="flex flex-col space-y-5 pb-3 px-16">
        <h2 class="text-white text-4xl font-bold">A Financial Resource for Every Student</h2>
        <div class="w-40 border-b-2 border-main-gold"></div>
      </div>
      <div class="flex justify-between px-16">
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

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <building-icon />
          <div class="flex flex-col">
            <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black text-center">Understanding Loans</h2>
            <p class="text-xs lg:text-lg md:text-base font-light text-black text-center">(Interest rates and more)</p>
          </div>
        </div>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-10 md:space-y-0 md:space-x-16">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Private Loans</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">FAFSA</h3>
            </div>
          </a>
        </div>
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <CardIcon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Understanding Credit</h2>
        </div>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-10 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Credit Scores & Reports</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255 px-4" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Federal Trade Commission (FTC)</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Types of Credit</h3>
            </div>
          </a>
        </div>
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 space-x-4 w-full bg-main-gold">
          <BudgetingIcon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Budgeting</h2>
        </div>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-10 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Guide to Budgeting 101</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255 px-4" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Intuit Mini Budget Planner</h3>
            </div>
          </a>
        </div>
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <SavingIcon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Saving</h2>
        </div>
        <div class="flex flex-col md:flex-row justify-center items-center space-y-10 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Tips for Saving</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255 px-4" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center" style="text-shadow: -3px 3px 3px #000000;">Saving in College</h3>
            </div>
          </a>
        </div>
      </div>

    </div>
  </div>
</template>
