<script>
export default {
  layout: 'financial-aid',
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-36 px-4 md:px-8 xl:px-48">
      <div class="flex flex-col space-y-8 border-b-2 border-main-gold pb-16 md:space-x-8 md:flex-row md:justify-between md:space-y-0">
        <div class="flex flex-col space-y-8">
          <div class="border-2 border-main-gold md:max-w-min md:whitespace-nowrap pb-0 px-4 pt-6">
            <h2 class="text-main-gold text-4xl text-center font-bold tracking-wider">Applying for Aid?</h2>
          </div>
          <div class="flex flex-col items-center space-y-12 max-w-3xl md:items-start">
            <p class="text-white text-xl text-center md:text-left">
              Completing the Free Application for Federal Student Aid (FAFSA) automatically allows you to be considered for federal, state and
              university financial aid programs. Filling out the FAFSA is free.
            </p>
            <p class="text-white text-xl text-center font md:text-left">
              All students <span class="text-main-gold underline">must apply or reapply</span> for financial aid every year.
            </p>
            <a href="https://studentaid.gov/h/apply-for-aid/fafsa" target="_blank" class="max-w-min pb-2 pt-6 px-6 rounded text-xl whitespace-nowrap text-black bg-main-gold border-2 border-white">Studentaid.gov</a>
          </div>
        </div>
        <div class="flex flex-col justify-center space-y-6 text-black text-center">
          <div class="bg-white px-4 py-8 space-y-10">
            <p class="uppercase font-light text-2xl">UCF School Code:</p>
            <p class="font-bold text-2xl">003954</p>
          </div>
          <div class="bg-white px-4 py-8 space-y-10">
            <p class="uppercase font-light text-2xl">UCF's <span class="underline">Priority Date</span> for FAFSA:</p>
            <p class="font-bold text-2xl">December 1, 2022</p>
          </div>
        </div>
      </div>
      <div class="flex flex-col space-y-8">
        <div class="space-y-5">
          <h2 class="text-white text-4xl font-bold tracking-wider">Types of Financial Aid</h2>
          <div class="w-28 border-b-2 border-main-gold"></div>
        </div>
        <div class="flex flex-col space-y-5 text-center md:space-x-5 md:max-w-5xl lg:max-w-full md:space-y-0 md:text-left md:flex-row md:justify-between items-center pb-8 border-b-2 border-zinc-800">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Scholarships</h3>
            <p class="text-white text-xl font-light">Scholarships are awarded for a variety of reasons including academic achievement,
              financial need, campus and community involvement, and leadership experience, and in general they do not need to be repaid.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="https://www.ucf.edu/financial-aid/types/scholarships/" target="_blank" class=" bg-main-gold max-w-min rounded pb-2 pt-5 px-3 text-black whitespace-nowrap border-2 borderwhite">Scholarships</a>
          </div>
        </div>
        <div class="flex flex-col space-y-5 text-center md:space-x-5 md:max-w-5xl lg:max-w-full md:space-y-0 md:text-left md:flex-row md:justify-between items-center pb-8 border-b-2 border-zinc-800">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Grants</h3>
            <p class="text-white text-xl font-light">Grants are awarded on the basis of need and do not have to be repaid. The Federal Pell Grant
              is the the largest grant program offered. UCF offers several one-time and renewable grants to students who demonstrate financial need.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="https://www.ucf.edu/financial-aid/types/grants/" class=" bg-main-gold max-w-min rounded px-6 pb-2 pt-5 text-black whitespace-nowrap border-2 borderwhite">Grants</a>
          </div>
        </div>
        <div class="flex flex-col space-y-5 text-center md:space-x-5 md:max-w-5xl lg:max-w-full md:space-y-0 md:text-left md:flex-row md:justify-between items-center pb-8 border-b-2 border-zinc-800">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Loans</h3>
            <p class="text-white text-xl font-light">Loans are a type of financial aid where students or parents of dependent students borrow money
              to pay for college. UCF participates in the Federal Direct Loan Program, which offers low-interest educational loans administered through
              the U.S. Department of Education and includes the Federal Stafford, PLUS and Grad PLUS Loans. Loans are required to be repaid, usually with interest.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="https://www.ucf.edu/financial-aid/types/loans/" class=" bg-main-gold max-w-min rounded px-6 pb-2 pt-5 text-black whitespace-nowrap border-2 borderwhite">Loans</a>
          </div>
        </div>
        <div class="flex flex-col space-y-5 text-center md:space-x-5 md:max-w-5xl lg:max-w-full md:space-y-0 md:text-left md:flex-row md:justify-between items-center pb-8 border-b-2 border-zinc-800">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Waivers</h3>
            <p class="text-white text-xl font-light">Need-based, non-resident waivers are awarded to first-time-in-college students, transfer students
              and continuing UCF students who are non-Florida residents. The awards are based on academic performance, as well as financial need, and act
              as a waiver for non-resident tuition fees. There is no separate application to receive this award. Students who apply for financial aid and
              have been admitted to UCF are automatically considered for this award, which does need to be repaid.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="https://www.ucf.edu/financial-aid/types/waivers/" class=" bg-main-gold max-w-min rounded px-6 pb-2 pt-5 text-black whitespace-nowrap border-2 borderwhite">Waivers</a>
          </div>
        </div>
        <div class="flex flex-col space-y-5 text-center md:space-x-5 md:max-w-5xl lg:max-w-full md:space-y-0 md:text-left md:flex-row md:justify-between items-center">
          <div class="flex flex-col space-y-5">
            <h3 class="text-main-gold text-3xl">Federal Work Study</h3>
            <p class="text-white text-xl font-light">Federal Work Study is an employment program designed to provide college students a chance to earn
              money while pursuing their degrees. FWS provides part-time jobs for undergraduate and graduate students on and off campus. JobX
              (formerly UCF Federal Work Study Job Connection) can help you find a job that fits your schedule and is just minutes from your classes.
            </p>
          </div>
          <div class="flex flex-col items-center space-y-3">
            <p class="text-white text-lg font-thin whitespace-nowrap">Learn more about:</p>
            <a href="https://www.ucf.edu/financial-aid/types/federal-work-study/" class="w-32 bg-main-gold rounded px-2 pb-2 pt-5 text-black text-center border-2 borderwhite">Federal Work Study (FWS)</a>
          </div>
        </div>
      </div>
      <div class="flex flex-col space-y-10">
        <h2 class="text-white text-4xl font-bold text-center">Learn More About How to Prepare</h2>
        <div class="flex flex-col justify-center -space-y-20 lg:flex-row lg:space-y-0 lg:space-x-48">
          <div class="flex flex-col items-center relative">
            <img src="~/assets/img/financial-aid-person-2.jpg" alt="" class="rounded-full scale-50 xl:scale-90 2xl:scale-75">
            <a href="https://studentaid.gov/h/apply-for-aid/fafsa" target="_blank" class="flex justify-center items-center bg-main-gold w-64 lg:w-48 xl:w-64 2xl:w-80 rounded pt-6 pb-3 text-black whitespace-nowrap absolute bottom-24 border-2 border-white xl:bottom-0 2xl:bottom-8">Applying for Financial Aid</a>
          </div>
          <div class="flex flex-col items-center justify-center relative">
            <img src="~/assets/img/financial-aid-person-3.jpg" alt="" class="rounded-full scale-50 xl:scale-90 2xl:scale-75">
            <a href="https://www.ucf.edu/financial-aid/apply/fafsa/" target="_blank" class="flex justify-center items-center bg-main-gold w-64 lg:w-48 xl:w-64 2xl:w-80 rounded pt-6 pb-3 text-black whitespace-nowrap absolute bottom-24 border-2 border-white xl:bottom-0 2xl:bottom-8">Filling Out the FAFSA</a>
          </div>
          <div class="flex flex-col items-center justify-center relative">
            <img src="~/assets/img/financial-aid-person-4.jpg" alt="" class="rounded-full scale-50 xl:scale-90 2xl:scale-75">
            <a href="https://www.ucf.edu/financial-aid/resources/understanding-to-do-list/" target="_blank" class="flex justify-center items-center bg-main-gold w-64 lg:w-48 xl:w-64 2xl:w-80 rounded pt-6 pb-3 text-black whitespace-nowrap absolute bottom-24 border-2 border-white xl:bottom-0 2xl:bottom-8">Financial Aid To-Do List </a>
          </div>
        </div>
      </div>
      <div class="flex flex-col space-y-12 md:items-start">
        <div class="flex flex-col items-center space-y-10 px-4 md:px-0 lg:items-start">
          <div class="border-2 border-white md:max-w-min md:whitespace-nowrap px-2 pb-2 pt-9">
            <h1 class="text-main-gold text-4xl text-center">Receiving Financial Aid</h1>
          </div>
          <p class="text-white text-xl text-center font-light md:text-left">In order to receive financial aid, you must satisfy a <span class="text-main-gold underline">specific set of conditions</span> determined
            by the Office of Student Financial Assistance. You must also maintain UCF's Standards for <span class="text-main-gold underline">Satisfactory Academic Progress.</span> The full
            Satisfactory Academic Progress Policy is outlined online.</p>
        </div>
        <div class="flex flex-col items-center space-y-10 lg:items-start">
          <div class="border-2 border-white md:max-w-min whitespace-nowrap px-2 pb-2 pt-8">
            <h1 class="text-main-gold text-4xl text-center">Dollars & Sense</h1>
          </div>
          <p class="text-white text-xl text-center font-light md:text-left"><span class="text-main-gold underline">Centsible Knights</span> is UCF's free financial literacy program. Through information and resources,
            the program prepares students to make sound financial decisions during college and after graduation. As a UCF Online student, you can access
            this and many other helpful programs.</p>
        </div>
        <div class="flex flex-col items-center space-y-10 lg:items-start">
          <div class="border-2 border-white md:max-w-min md:whitespace-nowrap px-2 pb-2 pt-8">
            <h1 class="text-main-gold text-4xl text-center">Financial Aid Help Videos</h1>
          </div>
          <p class="text-white text-xl text-center font-light md:text-left">These short videos will assist in understanding the financial aid process at UCF and give an
            overview of the Free Application for Federal Student Aid (FAFSA). Learn helpful tips and tricks to file your FAFSA faster and more accurately!
            <a href="https://www.ucf.edu/financial-aid/video/" target="_blank" class="text-main-gold underline">www.finaid.ucf.edu/video</a></p>
        </div>
      </div>
    </div>
  </div>
  <!-- Centsible Knights is UCF’s free financial literacy program. Through information and resources, the program prepares students to make sound financial decisions during college and after graduation. As a UCF Online student, you can access this and many other helpful programs. -->
</template>
