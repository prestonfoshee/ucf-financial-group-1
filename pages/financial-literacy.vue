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
      <div class="flex flex-col items-center space-y-6 px-4 py-14 md:flex-row md:justify-between md:px-8 lg:px-32 2xl:px-64 w-full">
        <div class="flex flex-col space-y-4">
          <div class="flex flex-col space-y-2 pb-3">
            <h2 class="text-white text-4xl font-bold">A Financial Resource for Every Student</h2>
            <div class="w-40 border-b-2 border-main-gold"></div>
          </div>
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
            <p class="text-white text-lg font-light">
              Below are some resources to help you gain control of your finances and understand how financial aid can impact your finances.
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
      <img src="~/assets/img/financial-literacy-doctors.jpg" alt="" class=" w-80">
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <building-icon />
          <div class="flex flex-col">
            <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black text-center">Understanding Loans</h2>
            <p class="text-xs lg:text-lg md:text-base font-light text-black text-center">(Interest rates and more)</p>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 pb-10 border-b-2 border-gray-400 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-1.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Private Loans</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">Private loans are made by private organizations such banks, credit unions, and state-based or state-affiliated organizations, and have terms
              and conditions that are set by the lender. Private student loans are generally more expensive than federal student loans.</p>
              <a href="https://studentaid.gov/understand-aid/types/loans" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about private loans</a>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-2.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center uppercase">FAFSA</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-main-gold text-lg text-center md:text-left">The Free Application for Federal Student Aid, or FAFSA, is the form that the federal government,
              states, colleges and other organizations use to award financial aid. Submitting it is your key to accessing grants, scholarships, work-study programs and federal student loans.
            </p>
              <a href="https://studentaid.gov/understand-aid/types/loans" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more FAFSA</a>
          </div>
        </div>
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold pt-2">
          <card-icon />
          <div class="flex flex-col">
            <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black text-center">Understanding Credit</h2>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center pb-10 px-4 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10 border-b-2 border-gray-400">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-3.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center uppercase">Credit Scores & Reports</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">A credit score is a three-digit number, typically between 300 and 850, which is designed
              to represent your credit risk, or the likelihood you will pay your bills on time.Credit scores are one of many factors used by lenders when
              determining your likelihood of paying back a loan.
            </p>
              <a href="https://www.equifax.com/personal/understanding-credit/" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about your reports</a>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 pb-10 border-b-2 border-gray-400 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-4.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center uppercase">Federal Trade Commission</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-main-gold text-lg text-center md:text-left">We hear a lot about credit — credit reports, credit scores, credit freezes, credit monitoring.
              What does it all mean for you? Your credit matters because it affects your ability to get a loan, a job, housing, insurance, and more. It's important
              to understand what your credit is and how to protect it.
            </p>
              <a href="https://www.ftc.gov/" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about your the FTC</a>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-5.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center uppercase">Types of Credot</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">A line of credit is a type of bank loan. You or your business can withdraw up to an
              agreed-upon amount as many times as you want, as long as you repay what you owe each time. We'll break down the different types of lines of credit
              that are available and tell you how each differs from debt instruments you might be more familiar with, like loans or credit cards.
            </p>
              <a href="" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about your the types of credit</a>
          </div>
        </div>
      </div>

      <!-- <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <CardIcon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Understanding Credit</h2>
        </div>
        <div class="flex flex-wrap flex-col justify-center items-center md:gap-5 md:flex-row lg:flex-nowrap space-y-4 md:space-y-0">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Credit Scores & Reports</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255 px-4" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Federal Trade Commission (FTC)</h3>
            </div>
          </a>
          <a href="https://studentaid.gov/understand-aid/types/loans" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-link.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Types of Credit</h3>
            </div>
          </a>
        </div>
      </div> -->

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 space-x-4 w-full bg-main-gold">
          <budgeting-icon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Budgeting</h2>
        </div>
        <div class="flex flex-col justify-between items-center px-4 pb-10 border-b-2 border-gray-400 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-6.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Guide to Budgeting 101</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-main-gold text-lg text-center md:text-left">What is a budget? A budget is a plan for every dollar you have. It's not magic,
              but it represents more financial freedom and a life with much less stress. Here;s how to set up and then manage your budget.
            </p>
              <a href="" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about budgeting</a>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-7.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Intuit Mini Budget Planner</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">What is a budget? A budget is a plan for every dollar you have. It's not magic,
              but it represents more financial freedom and a life with much less stress. Here;s how to set up and then manage your budget.
            </p>
              <a href="" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Try the Intuit Planner Today</a>
          </div>
        </div>
      </div>

      <div class="space-y-10">
        <div class="flex items-center justify-center px-16 w-full bg-main-gold">
          <saving-icon />
          <h2 class="text-sm lg:text-3xl md:text-xl font-bold text-black">Saving</h2>
        </div>
        <div class="flex flex-col justify-between items-center px-4 pb-10 border-b-2 border-gray-400 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-8.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Tips for Saving</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">Sometimes the hardest thing about saving money is just getting started. This step-by-step
              guide can help you develop a simple and realistic strategy, so that you can save for all your short and long-term goals.
            </p>
              <a href="" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Check out savings tips</a>
          </div>
        </div>
        <div class="flex flex-col justify-between items-center px-4 md:px-8 lg:px-32 2xl:px-64 md:gap-5 md:flex-row space-y-4 md:space-y-0 md:space-x-10">
          <a href="https://www.salliemae.com/student-loans/get-ready-to-borrow/" target="_blank">
            <div class="flex justify-center items-center bg-no-repeat bg-cover w-288 h-191 md:w-384 md:h-255" :style="{'background-image': `url(${require('@/assets/img/financial-literacy-9.jpg')})`}">
              <h3 class="text-3xl text-white font-bold text-center">Saving Whilst in College</h3>
            </div>
          </a>
          <div class="flex flex-col items-center space-y-5 md:items-start">
            <p class="text-white text-lg text-center md:text-left">The idea of saving money in college might sound impossible - but it's totally doable!
              For most college students, this is the first time really having to budget and manage money on your ownHere's some of the best ideas on how to manage
              your money and save money in college. These all come from experience.
            </p>
              <a href="" class="bg-main-gold text-center pb-2 pt-5 px-4 max-w-xs md:max-w-min md:whitespace-nowrap rounded">Learn more about saving in college</a>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
