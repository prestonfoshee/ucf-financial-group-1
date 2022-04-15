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
      <div class="flex justify-center items-center whitespace-nowrap max-w-min bg-main-gold rounded-r-lg px-10 py-6">
        <h1 class="text-black text-3xl text-center font-bold">How do I find a scholarship?</h1>
      </div>
      <div class="flex justify-between px-16 xl:px-48">
        <div class="flex flex-col space-y-10">
          <div class="w-1/2">
            <p class="text-black text-xl font-light">
              Use Access 2 Opportunities (A2O), UCF's scholarship application system to search for scholarships.
              By completing a one-time application, you will be considered for more than 200 scholarships offered
              by the university and gain access to hundreds of external scholarships, too.
            </p>
          </div>
            <a href="" class="max-w-min p-5 bg-main-gold whitespace-nowrap text-black text-xl rounded-sm">
              Tips on Scholarships
            </a>
        </div>
        <div class="flex flex-col items-center space-y-4 bg-cover w-340 h-340 py-10 -mt-24" :style="{'background-image': `url(${require('@/assets/img/search-for-scholarships.jpg')})`}">
          <div class="mx-20">
            <h3 class="text-white text-3xl font-semibold text-center">Access 2 Opportunities (A20)</h3>
          </div>
          <div class="mx-10">
            <p class="text-white font-extralight text-lg text-center">Be Considered for over 200 scholarships by completing a one-time application.</p>
          </div>
          <a href="" class="bg-main-gold max-w-min p-3 font-medium text-black text-lg whitespace-nowrap rounded">Search for Scholarships</a>

        </div>
      </div>

      <div class="flex flex-col space-y-8 py-12 px-64 mt-16">
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

    </div>


    <div class="bg-main-gold flex flex-col space-y-10 px-64 py-10">
      <h1 class="text-black text-4xl text-center font-bold uppercase tracking-wide">UCF College & Departmental Scholarships</h1>
      <div class="flex justify-between text-lg">
        <ul class=" text-teal-800 space-y-2">
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
        <ul class=" text-teal-800 space-y-2">
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
