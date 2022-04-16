<script>
export default {
  layout: 'contact',
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-24">
      <div class="flex flex-col items-center space-y-6 px-4 py-16 lg:flex-row lg:justify-between md:px-8 lg:px-32 2xl:px-64 bg-main-gold">
          <div class="flex flex-col space-y-14 pb-3">
            <div>
              <h2 class="text-black text-4xl font-bold">Make An Appointment</h2>
              <div class="w-40 border-b-2 border-white"></div>
            </div>
          <div class="lg:max-w-5xl space-y-5">
            <p class="text-black text-sm md:text-lg font-base">The University of Central Florida has several departments that can offer support
              to students. Below is information on how students can get in touch with a financial advisor or an academic advisor.
            </p>
            <p class="text-black text-sm md:text-lg font-base">Financial Assistance counselors can only address questions pertaining to
              Financial Assistance and briefly address any general questions regarding tuition payments.
            </p>
            <div class="lg:max-w-5xl">
              <p class="text-black text-sm md:text-lg font-base">Specific Advising Offices</p>
              <p class="text-black text-sm md:text-lg font-base">https://academicsuccess.ucf.edu/ssa/advising-offices/#college-advising</p>
            </div>
          </div>
        </div>
        <div class="flex flex-col items-center justify-center w-full space-y-8 md:flex-row md:space-y-0 md:space-x-10 lg:space-x-0 lg:relative">
          <img src="~/assets/img/contact-circle-1.jpg" alt="" class="lg:absolute lg:-bottom-14 lg:right-0 rounded-full w-52 h-52 border-2 border-white">
          <img src="~/assets/img/contact-circle-2.jpg" alt="" class="lg:absolute lg:-bottom-48 lg:-right-20 rounded-full w-52 h-52 border-2 border-white">
        </div>
      </div>

      <div class="flex flex-col space-y-16 px-4 md:px-8 lg:px-32 2xl:px-64">
        <div class="px-10 pb-5 pt-12 uppercase border-4 border-black text-4xl text-center font-bold tracking-wider">How to schedule a meeting with financial assistance</div>
        <div class="flex flex-col md:items-center md:justify-between md:flex-row">
          <div class="md:max-w-lg xl:max-w-4xl">
            <p class="text-black text-xl">Schedule an appointment with a Financial Assistance counselor to discuss the UCF Financial Aid application process or your financial aid status.
              Due to the limited number of appointments available, appointments should be reserved to gather information not accessible through myUCF or available
              on the UCF student Financial Assistance website. Appointments are available for booking up to 2 weeks in advance.</p>
          </div>
          <div class="bg-black flex flex-col items-center space-y-4 py-8 px-12">
            <div class="max-w-min border-b border-main-gold">
              <h3 class="text-white text-2xl text-center">Schedule Today!</h3>
            </div>
            <!-- <div class="border-b border-main-gold w-14"></div> -->
            <a href="" class="bg-main-gold px-4 pb-2 pt-5 border-2 border-gray-300">Book Now</a>
          </div>
        </div>
        <div class="px-10 pb-3 pt-8 text-lg bg-teal-100">NOTE: If you do not see the confirmation email in your inbox, <span class="font-bold">please be
          sure to check your junk and/or spam folder.</span> Confirmation emails will be sent to the email address provided.
        </div>
      </div>

      <div class="ml-auto text-2xl whitespace-nowrap w-3/4 2xl:w-1/2 bg-main-gold rounded-l-lg px-5 pb-3 pt-7 lg:px-10 lg:pb-3 uppercase font-bold tracking-wide">
        Advising Offices
      </div>

      <div class="flex flex-col space-y-16 px-4 md:px-8 lg:px-32 2xl:px-64">
        <h2 class="text-zinc-400 font-bold tracking-wide text-4xl">Financial Assistance</h2>
        <div class="flex flex-col space-y-8 bg-zinc-400 p-12">
        <div class="flex justify-between">

          <div class="">
            <p class="text-black text-xl"><span class="font-bold">Email:</span> finaid@ucf.edu</p>
            <p class="text-black text-xl"><span class="font-bold">Phone:</span> (844) 376-9160</p>
            <p class="text-black text-xl"><span class="font-bold">Fax:</span> (407) 823-5241</p>
          </div>
          <div>
            <h4 class="text-black font-bold uppercase text-2xl">Office Hours</h4>
            <p class="text-black text-xl">Monday to Friday</p>
            <p class="text-black text-xl">9 a.m. - 5p.m.</p>
          </div>
        </div>

          <div class="flex justify-between">
            <div>
              <h4 class="text-black font-bold uppercase text-2xl">Office Address</h4>
              <p class="text-black text-xl">Office of Student Financial Assistance</p>
              <p class="text-black text-xl">4000 Central Florida Blvd.</p>
              <p class="text-black text-xl">Millican Hall, Room 107</p>
              <p class="text-black text-xl">Orlando, FL 32816-0113</p>
            </div>
            <div class="text-right">
              <h4 class="text-black font-bold uppercase text-2xl">Mailing Address</h4>
              <p class="text-black text-xl">Office of Student Financial Assistance</p>
              <p class="text-black text-xl">P.O. Box 160113</p>
              <p class="text-black text-xl">Orlando, FL 32816-0113</p>
            </div>
          </div>
        </div>

        <h2 class="text-zinc-400 font-bold tracking-wide text-4xl ml-auto text-right">Student Success and Advising</h2>
        <div class="flex flex-col space-y-8 bg-zinc-400 p-12">
        <div class="flex justify-between">
            <div>
              <h4 class="text-black font-bold uppercase text-2xl">Contact Us</h4>
              <p class="text-black text-xl">407-823-6250</p>
              <p class="text-black text-xl">ssa@ucf.edu</p>
            </div>
            <div class="text-right">
              <h4 class="text-black font-bold uppercase text-2xl">Hours of Operation</h4>
              <p class="text-black text-xl">Monday to Friday:</p>
              <p class="text-black text-xl">8 a.m. - 4 p.m.</p>
            </div>
          </div>

          <div class="flex justify-between">
          <div class="">
            <h4 class="text-black font-bold uppercase text-2xl">Office Hours</h4>
            <p class="text-black text-xl">Trevor Colbourn Hall, Suite 215</p>
            <p class="text-black text-xl">12796 Aquarius Agora Dr.</p>
            <p class="text-black text-xl">Orlando, FL 32816-0160</p>
          </div>
          <div class="text-right">
            <h4 class="text-black font-bold uppercase text-2xl">Online Advising</h4>
            <p class="text-black text-xl">
              https://academicsuccess.ucf.edu/ssa/remote-advising/
            </p>
          </div>
        </div>

        </div>

        <h2 class="text-zinc-400 font-bold tracking-wide text-4xl">Collections</h2>
        <div class="flex flex-col space-y-8 bg-zinc-400 p-12">
        <div class="flex justify-between">

          <div class="">
            <p class="text-black text-xl"><span class="font-bold">Email:</span> finaid@ucf.edu</p>
            <p class="text-black text-xl"><span class="font-bold">Phone:</span> (844) 376-9160</p>
            <p class="text-black text-xl"><span class="font-bold">Fax:</span> (407) 823-5241</p>
          </div>
          <div>
            <h4 class="text-black font-bold uppercase text-2xl">Office Hours</h4>
            <p class="text-black text-xl">Monday to Friday</p>
            <p class="text-black text-xl">9 a.m. - 5p.m.</p>
          </div>
        </div>

          <div class="flex justify-between">
            <div>
              <h4 class="text-black font-bold uppercase text-2xl">Office Address</h4>
              <p class="text-black text-xl">Research Pavilion</p>
            </div>
            <div class="text-right">
              <h4 class="text-black font-bold uppercase text-2xl">Mailing Address</h4>
              <p class="text-black text-xl">Office of Student Financial Assistance</p>
              <p class="text-black text-xl">P.O. Box 160115</p>
              <p class="text-black text-xl">Orlando, FL 32816-0115</p>
            </div>
          </div>
        </div>

      </div>

    </div>
  </div>
</template>
