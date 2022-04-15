<script>
import TextBox from '../components/scholarships/TextBox.vue'
export default {
  components: {
    TextBox,
  },
  layout: 'scholarships'
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-8 mb-16">
      <div class="flex justify-center items-center whitespace-nowrap max-w-min bg-main-gold rounded-r-lg px-5 lg:px-10 py-6">
        <h1 class="text-black lg:text-3xl text-center font-bold">How do I find a scholarship?</h1>
      </div>
      <div class="flex flex-col items-center lg:items-start lg:flex-row lg:justify-between lg:space-x-16 md:px-16 2xl:px-48">
        <div class="flex flex-col items-center space-y-10 lg:items-start ">
          <div class="2xl:w-3/4">
            <p class="text-black text-xl text-center lg:text-left font-light">
              Use Access 2 Opportunities (A2O), UCF's scholarship application system to search for scholarships.
              By completing a one-time application, you will be considered for more than 200 scholarships offered
              by the university and gain access to hundreds of external scholarships, too.
            </p>
          </div>
            <a href="" class="max-w-min px-5 pb-2 pt-5 bg-main-gold whitespace-nowrap text-black text-xl rounded-sm border-2 border-gray-300">
              Tips on Scholarships
            </a>
        </div>
        <div class="flex flex-col items-center space-y-4 bg-cover w-340 h-340 py-10 mt-12 lg:-mt-24" :style="{'background-image': `url(${require('@/assets/img/search-for-scholarships.jpg')})`}">
          <div class="mx-20">
            <h3 class="text-white text-3xl font-semibold text-center">Access 2 Opportunities (A20)</h3>
          </div>
          <div class="mx-10">
            <p class="text-white font-extralight text-lg text-center">Be Considered for over 200 scholarships by completing a one-time application.</p>
          </div>
          <a href="" class="bg-main-gold max-w-min px-3 pb-1 pt-4 text-black text-lg whitespace-nowrap rounded border-2 border-white">Search for Scholarships</a>
        </div>
      </div>
      <div class="border-b-2 border-black pb-16 mx-16 2xl:mx-48"></div>
      <div class="flex flex-col space-y-8 py-12 px-4 md:flex-row md:px-16 md:space-x-8 md:space-y-0 2xl:px-48 mt-16">
        <text-box
        :header-text="'Florida bright futures'"
        :subtitle-text="'Learn about the state funded program and the awards based on high school academic achievement'"
        :type="'top'"
        />
        <text-box
        :header-text="'Pegasus scholarships'"
        :subtitle-text="'Information about the undergraduate scholarships awarded to students upon admission to UCF'"
        :type="'top'"
        />
        <text-box
        :header-text="'Private scholarships'"
        :subtitle-text="'Information about how to notify the financial aid office of a private or outside award.'"
        :type="'top'"
        />
      </div>

      <div class="flex justify-center items-center">
        <div class="bg-main-gold text-black px-8 pb-4 pt-8 text-xl text-center max-w-min lg:whitespace-nowrap border-2 border-gray-300">List of External Scholarship Resource Links</div>
      </div>

      <div class="flex flex-col space-y-16">
        <div class="flex flex-col space-y-10 px-16 2xl:px-48">
          <div class="space-y-4">
            <h2 class="text-zinc-700 text-4xl font-bold tracking-wider">Scholarship Appeals</h2>
            <div class="border-b-2 border-yellow-700 w-32"></div>
          </div>
          <p class="text-black text-xl">
            Initial scholarship eligibility may be appealed if a student has experienced relevant extenuating circumstances they
            feel caused them to not receive an award. Learn more about appeals.
          </p>
        </div>
        <div class="flex flex-col px-16 2xl:px-48">
          <div class="space-y-4">
            <h2 class="text-zinc-700 text-4xl font-bold tracking-wider">Winning Tips</h2>
            <div class="border-b-2 border-yellow-700 w-32"></div>
          </div>
        </div>

        <div class="flex flex-col space-y-12">
          <div class="text-center max-w-xs px-16 pb-3 pt-6 bg-black border-2 border-l-0 text-main-gold text-lg border-main-gold rounded-r-lg md:max-w-min md:whitespace-nowrap">Maximize Scholarship Opportunities</div>
          <div class="px-4 md:px-48">
            <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Apply early.</span> The peak time to apply for scholarships is January through May for the upcoming school year. Remember the early bird gets the worm!</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Check for scholarships frequently.</span> Check your department, college, and the UCF Scholarship Listing Page for updates to scholarships.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Get Involved.</span> While some scholarships do not require involvement, it does help showcase who you are as a person. Also, being involved helps identify your involvement within your community i.e. campus, local, church, sports.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Complete Your FAFSA.</span> Some scholarships do not require the FAFSA, however, it is recommended for consideration of scholarships that require completing the FAFSA.</p>
            </div>
          </div>
        </div>

        <div class="flex flex-col space-y-12">
          <div class="text-center max-w-xs px-16 pb-3 pt-6 bg-black border-2 border-l-0 text-main-gold text-lg border-main-gold rounded-r-lg md:max-w-min md:whitespace-nowrap">Write an Award-Winning Scholarship Essay</div>
          <div class="px-4 md:px-32">
            <p class="text-xl text-gray-400">**Students many times do not apply for scholarships that involve writing essays. However, scholarships that require essays do not usually
              have many applicants which may increase your chances of earning a scholarship.
            </p>
          </div>
          <div class="px-4 md:px-48">
            <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Tailor your essay for your intended audience.</span> While writing your essay, it is important to stay focused on the topic and specifically address the essay question.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Target your audience by using keywords.</span> Identify the goals of the donor as well as identifying why you should be selected for the scholarship.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Stand out.</span> Make the committee interested in who you are by grabbing their attention. Give the committee something different, so brainstorming will be very important before you begin writing your essay.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Introduce yourself.</span> Explain who you are, what your goals are, and how receiving the scholarship will help you accomplish your educational objectives.  Examples include campus and community involvement, and hobbies.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Avoid negative messages.</span> When writing your essay, avoid negative messages such as tear-jerker. Many use this method in hopes of being selected for a scholarship. However, it may have the opposite impact and not accomplish the intended message.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Write positive messages.</span> In keeping with the theme of tailoring and targeting your audience, it is important to do so with positive messages. Positive messages are important when discussing negative situations. It gives great insight to you as a person, i.e., how you have overcome difficult situations.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Proofread.</span> Essays should be proofread several times over to ensure that there are no typing or grammatical errors. Utilize your resources such as the UCF Writing Center or having a financial aid advisor review your essay.</p>
            </div>
          </div>
        </div>

        <div class="flex flex-col space-y-12">
          <div class="text-center max-w-xs px-16 pb-3 pt-6 bg-black border-2 border-l-0 text-main-gold text-lg border-main-gold rounded-r-lg md:max-w-min md:whitespace-nowrap">Manage Your Scholarship Award</div>
          <div class="px-4 md:px-48">
            <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
              <p class="text-black text-xl">Most students entering college encounter their first real-world situations with large amounts of money. We've compiled information on budgeting your money, as well as other financial literacy tips.</p>
            </div>
          </div>
        </div>

        <div class="flex flex-col space-y-12">
          <div class="text-center max-w-xs px-16 pb-3 pt-6 bg-black border-2 border-l-0 text-main-gold text-lg border-main-gold rounded-r-lg md:max-w-min md:whitespace-nowrap">Avoid Scholarship Scams</div>
          <div class="px-4 md:px-32">
            <p class="text-xl text-gray-400">**If you believe you have encountered a fraudulent scholarship, visit the Federal Trade Commission website for help.
            </p>
          </div>
          <div class="px-4 md:px-48">
            <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Do not pay for scholarship searches.</span> You have many options for free scholarship search engines as well as campus resources.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Avoid Scholarship Guarantees.</span> Be wary of scholarship organizations that guarantee you will receive a scholarship based upon a small application fee. No one can guarantee you will receive a scholarship by paying an application fee.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Avoid Giving Personal Information.</span> Do not provide personal information such as bank account numbers, and credit card numbers.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Money-Back Guarantee.</span> Avoid scholarships that promise your money is guaranteed to be refunded if you do not receive a scholarship.</p>
            </div>
          </div>
        </div>

<!-- Make sure your letter is legible. If your handwriting is hard to read, you should type the letter instead.

Be sure to address the donor of the scholarship and not the scholarship committee.

Letters should be proofread and you should have someone else proofread it as well.

You should let the donor(s) know something about yourself and the impact their generosity has had on your education and life. You should also indicate what your future goals may be. -->

        <div class="flex flex-col space-y-12">
          <div class="text-center max-w-xs px-16 pb-3 pt-6 bg-black border-2 border-l-0 text-main-gold text-lg border-main-gold rounded-r-lg md:max-w-min md:whitespace-nowrap">Write a Thank You Letter</div>
          <div class="px-4 space-y-4 md:px-32">
            <p class="text-xl text-gray-400">**Letters of appreciation from scholars encourage our donors to continue funding deserving students like you. We ask that you prepare a brief letter describing how their contribution will help you reach your educational and personal goals.
            </p>
            <p class="text-xl text-gray-400">***Feel free to come into the Office of Student Financial Assistance if you have trouble writing your thank you letter and a staff member will assist you. You can also visit the Writing Center for assistance.
            </p>
          </div>
          <div class="px-4 md:px-48">
            <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Make sure your letter is legible.</span> If your handwriting is hard to read, you should type the letter instead.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Be sure to address the donor of the scholarship</span> and not the scholarship committee.</p>
              <p class="text-black text-xl"><span class="text-red-500 font-bold">Letters should be proofread</span> and you should have someone else proofread it as well.</p>
              <p class="text-black text-xl">You should let the donor(s) know something about yourself and the impact their generosity has had on your education and life. You should also indicate what your future goals may be.</p>
            </div>
          </div>
        </div>

      </div>
    </div>

<!-- Do not pay for scholarship searches. You have many options for free scholarship search engines as well as campus resources.

Avoid Scholarship Guarantees. Be wary of scholarship organizations that guarantee you will receive a scholarship based upon a small application fee. No one can guarantee you will receive a scholarship by paying an application fee.

Avoid Giving Personal Information. Do not provide personal information such as bank account numbers, and credit card numbers.

Money-Back Guarantee. Avoid scholarships that promise your money is guaranteed to be refunded if you do not receive a scholarship. -->

    <div class="bg-main-gold flex flex-col space-y-10 py-10 px-4 lg:px-64">
      <h1 class="text-black text-2xl text-center font-bold uppercase tracking-wide lg:text-4xl">UCF College & Departmental Scholarships</h1>
      <div class="flex flex-col items-center text-center space-y-5 text-lg md:space-y-0 md:flex-row md:justify-between md:items-start md:text-left">
        <ul class="flex flex-col text-teal-800 text-sm space-y-5 lg:text-base lg:space-y-2">
          <li class="hover:underline"><a href="https://ucfalumni.com/scholarships" target="_blank">Alumni Association</a></li>
          <li class="hover:underline"><a href="https://honors.ucf.edu/students/honors-scholarships/" target="_blank">The Burnett Honors College</a> </li>
          <li class="hover:underline"><a href="https://www.cah.ucf.edu/academics/scholarships/" target="_blank">College of Arts and Humanities</a></li>
          <li class="hover:underline"><a href="https://business.ucf.edu/scholarships/" target="_blank">College of Business</a></li>
          <li class="hover:underline"><a href="https://ccie.ucf.edu/scholarships/" target="_blank">College of Community Innovation and Education</a></li>
          <li class="hover:underline"><a href="https://www.cecs.ucf.edu/current-students/scholarships/" target="_blank">College of Engineering and Computer Science</a></li>
          <li class="hover:underline"><a href="https://graduate.ucf.edu/funding/" target="_blank">College of Graduate Studies</a></li>
          <li class="hover:underline"><a href="https://healthprofessions.ucf.edu/scholarships/" target="_blank">College of Health Professions and Sciences</a></li>
          <li class="hover:underline"><a href="https://nursing.ucf.edu/academics/scholarships-aid/" target="_blank">College of Nursing</a></li>
          <li class="hover:underline"><a href="https://www.creol.ucf.edu/academics/undergrad/scholarships/" target="_blank">College of Optics and Photonics | CREOL</a></li>
        </ul>
        <ul class="flex flex-col text-teal-800 text-sm space-y-5 lg:text-base lg:space-y-2">
          <li class="hover:underline"><a href="https://sciences.ucf.edu/scholarships/" target="_blank">College of Sciences</a></li>
          <li class="hover:underline"><a href="https://undergrad.ucf.edu/academics/scholarships/" target="_blank">College of Undergraduate Studies</a></li>
          <li class="hover:underline"><a href="https://ucfglobalperspectives.org/internship-program/fellowship-opportunities/" target="_blank">Global Perspectives</a></li>
          <li class="hover:underline"><a href="https://graduate.ucf.edu/funding/" target="_blank">Graduate Fellowships and Assistantships</a></li>
          <li class="hover:underline"><a href="https://mass.sdes.ucf.edu/resources/" target="_blank">Multicultural Academic and Support Services</a></li>
          <li class="hover:underline"><a href="https://hospitality.ucf.edu/students/current-students/financial-aid/#inside-graysection" target="_blank">Rosen College of Hospitality Management</a></li>
          <li class="hover:underline"><a href="https://sas.sdes.ucf.edu/" target="_blank">Student Accessibility Services</a></li>
          <li class="hover:underline"><a href="https://studyabroad.ucf.edu/index.cfm?FuseAction=Abroad.ViewLink&Parent_ID=0&Link_ID=22908872-DB40-1771-8A2CD16883E03E28" target="_blank">Study Abroad</a></li>
          <li class="hover:underline"><a href="https://transfer.sdes.ucf.edu/?page=scholarships" target="_blank">Transfer and Transition Services</a></li>
        </ul>
      </div>
    </div>
  </div>
  <!-- College of Sciences
College of Undergraduate Studies
Global Perspectives
Graduate Fellowships and Assistantships
Multicultural Academic and Support Services
Rosen College of Hospitality Management
Student Accessibility Services
Study Abroad
Transfer and Transition Services -->
</template>
