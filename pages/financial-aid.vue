<script>
export default {
  layout: 'financial-aid',
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-36 px-4 md:px-32 xl:px-48">
      <div class="flex flex-col md:flex-row md:justify-between">
        <div class="flex flex-col space-y-8">
          <div class="border-2 border-main-gold md:max-w-min md:whitespace-nowrap p-4">
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
            <a href="https://studentaid.gov/h/apply-for-aid/fafsa" target="_blank" class="max-w-min py-4 px-6 rounded text-xl whitespace-nowrap text-black bg-main-gold">Studentaid.gov</a>
          </div>
        </div>
        <div class="flex flex-col justify-center space-y-6 text-black text-center">
          <div class="bg-white p-8 space-y-10">
            <p class="uppercase font-light text-2xl">UCF School Code:</p>
            <p class="font-bold text-2xl">003954</p>
          </div>
          <div class="bg-white p-8 space-y-10">
            <p class="uppercase font-light text-2xl">UCF's <span class="underline">Priority Date</span> for FAFSA:</p>
            <p class="font-bold text-2xl">December 1, 2022</p>
          </div>
        </div>
      </div>
      <div class="flex flex-col space-y-8">
        <div class="space-y-5">
          <h2 class="text-white text-4xl font-bold">Types of Financial Aid</h2>
          <div class="w-28 border-b-2 border-main-gold"></div>
        </div>
        <div class="flex justify-between items-center">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Scholarships</h3>
            <p class="text-white text-xl font-light">Scholarships are awarded for a variety of reasons including academic achievement,
              financial need, campus and community involvement, and leadership experience, and in general they do not need to be repaid.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="" class=" bg-main-gold max-w-min rounded p-3 text-black whitespace-nowrap">Scholarships</a>
          </div>
        </div>
        <div class="flex flex-col space-y-5">
          <h3 class="text-main-gold text-3xl">Grants</h3>
          <p class="text-white text-xl font-light">Grants are awarded on the basis of need and do not have to be repaid. The Federal Pell Grant
            is the the largest grant program offered. UCF offers several one-time and renewable grants to students who demonstrate financial need.
          </p>
          <a href="" class="ml-auto bg-main-gold max-w-min rounded p-3 text-black whitespace-nowrap">Learn More About Grants</a>
        </div>
        <div class="flex flex-col space-y-5">
          <h3 class="text-main-gold text-3xl">Loans</h3>
          <p class="text-white text-xl font-light">Loans are a type of financial aid where students or parents of dependent students borrow money
            to pay for college. UCF participates in the Federal Direct Loan Program, which offers low-interest educational loans administered through
            the U.S. Department of Education and includes the Federal Stafford, PLUS and Grad PLUS Loans. Loans are required to be repaid, usually with interest.
          </p>
          <a href="" class="ml-auto bg-main-gold max-w-min rounded p-3 text-black whitespace-nowrap">Learn More About Loans</a>
        </div>
        <div class="flex flex-col space-y-5">
          <h3 class="text-main-gold text-3xl">Waivers</h3>
          <p class="text-white text-xl font-light">Loans are a type of financial aid where students or parents of dependent students borrow money
            to pay for college. UCF participates in the Federal Direct Loan Program, which offers low-interest educational loans administered through
            the U.S. Department of Education and includes the Federal Stafford, PLUS and Grad PLUS Loans. Loans are required to be repaid, usually with interest.
          </p>
          <a href="" class="ml-auto bg-main-gold max-w-min rounded p-3 text-black whitespace-nowrap">Learn More About Waivers</a>
        </div>
        <div class="flex flex-col space-y-5">
          <h3 class="text-main-gold text-3xl">Federal Work Study</h3>
          <p class="text-white text-xl font-light">Federal Work Study is an employment program designed to provide college students a chance to earn money
            while pursuing their degrees. FWS provides part-time jobs for undergraduate and graduate students on and off campus. JobX (formerly UCF Federal Work Study
            Job Connection) can help you find a job that fits your schedule and is just minutes from your classes.
          </p>
          <a href="" class="ml-auto bg-main-gold max-w-min rounded p-3 text-black whitespace-nowrap">Learn More About FWS</a>
        </div>
      </div>
      <div class="flex flex-col">
        <h2 class="text-white text-4xl font-bold text-center">Learn More About How to Prepare</h2>
        <div class="flex flex-col justify-center -space-y-20 md:flex-row md:space-y-0">
          <div class="flex flex-col items-center relative">
            <img src="~/assets/img/financial-aid-person-2.jpg" alt="" class="rounded-full scale-50">
            <a href="" class="flex justify-center items-center bg-main-gold w-64 md:py-6 lg:w-80 rounded py-4 text-black whitespace-nowrap absolute bottom-24">Applying for Financial Aid</a>
          </div>
          <div class="flex flex-col items-center justify-center relative">
            <img src="~/assets/img/financial-aid-person-3.jpg" alt="" class="rounded-full scale-50">
            <a href="" class="flex justify-center items-center bg-main-gold w-64 md:py-6 lg:w-80 rounded py-4 text-black whitespace-nowrap absolute bottom-24">Filling Out the FAFSA</a>
          </div>
          <div class="flex flex-col items-center justify-center relative">
            <img src="~/assets/img/financial-aid-person-4.jpg" alt="" class="rounded-full scale-50">
            <a href="" class="flex justify-center items-center bg-main-gold w-64 md:py-6 lg:w-80 rounded py-4 text-black whitespace-nowrap absolute bottom-24">Financial Aid To-Do List </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
