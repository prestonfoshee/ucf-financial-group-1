<script>
export default {
  layout: 'account',

}
</script>

<template>
  <div>
    <div class="flex flex-col items-center space-y-24  px-4 md:px-8 lg:px-32 2xl:px-64 py-24">
      <div class="flex flex-col items-center space-y-12">
        <img src="~/assets/img/horse.jpg" alt="Photo of UCF Horse" class="w-3/4 md:w-5/12">
        <div class="flex flex-col items-center space-y-2">
          <h2 class="text-black text-4xl text-center font-bold tracking-wide">Welcome fellow Knight, Erin!</h2>
          <div class="border-b-2 border-main-gold w-48"></div>
        </div>
      </div>
      <div class="flex flex-col w-full border-b-2 border-dotted border-gray-400 pb-24">
        <h3 class="text-zinc-400 text-4xl text-center font-bold tracking-wide">Student Details</h3>
        <div class="flex flex-col gap-y-8">
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Name</p>
            </div>
            <div>
              <p>Erin K. Schumer</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Birthdate</p>
            </div>
            <div>
              <p>10/08/2002</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Major</p>
            </div>
            <div>
              <p>Electrical Engineering (B.S.)</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Minor (if applicable)</p>
            </div>
            <div>
              <p>N/A</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Address</p>
            </div>
            <div>
              <p>3608 Orlando Ave. Suite 203, Orlando, FL 32766</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>Academic Standing</p>
            </div>
            <div>
              <p>Freshman (1-year)</p>
            </div>
          </div>
          <div class="flex justify-between border-b-2 border-gray-400">
            <div>
              <p>GPA (Weighted/Unweighted)</p>
            </div>
            <div>
              <p>3.78/3.45</p>
            </div>
          </div>
        </div>
      </div>

      <div class="flex flex-col space-y-6 px-8 text-xs md:text-base">
        <h3 class="text-zinc-400 text-4xl text-center font-bold tracking-wide">Financial Aid Summary</h3>
        <div class="flex flex-col px-4">
          <h4 class="text-2xl font-bold text-black">2020-21</h4>
          <div class="flex flex-col md:flex-row border-2 border-main-gold ">
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Award Description</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">Discover Optional - 320 - Fall</p>
              </div>
            </div>
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Category</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">Loan</p>
              </div>
            </div>
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Offered</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">$6,000.00</p>
              </div>
            </div>
            <div class="flex flex-col">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Accepted</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center font-bold">$6,000.00</p>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="flex flex-col space-y-6 px-8 text-xs md:text-base md:px-16">
        <h3 class="text-zinc-400 text-4xl text-center font-bold tracking-wide">Financial Aid Award Packages</h3>
        <div class="flex flex-col px-4">
          <h4 class="text-2xl font-bold text-black">Fall 2020</h4>
          <div class="flex flex-col md:flex-row border-2 border-main-gold ">
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Award Description</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">Discover Optional - 320 - Fall</p>
              </div>
            </div>
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Category</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">Loan</p>
              </div>
            </div>
            <div class="flex flex-col border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Career</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">Undergraduate</p>
              </div>
            </div>
            <div class="flex flex-col border-r-2 border-yellow-500">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Offered</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center">$6,000.00</p>
              </div>
            </div>
            <div class="flex flex-col">
              <div class=" pb-2 pt-4 px-2 md:px-8">
                <p class="text-center">Accepted</p>
              </div>
              <div class="bg-main-gold pb-2 pt-6 px-2 md:px-8">
                <p class="text-center font-bold">$6,000.00</p>
              </div>
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
