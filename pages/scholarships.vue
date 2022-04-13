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
    <div class="flex flex-col space-y-8 mb-8">
      <div class="flex justify-between">
        <div class="flex flex-col space-y-10">
          <div class="flex justify-center items-center whitespace-nowrap max-w-min bg-main-gold rounded-r-lg px-10 py-6">
            <h1 class="text-black text-3xl text-center font-bold">How do I find a scholarship?</h1>
          </div>
          <div class="w-1/2 pl-16">
            <p class="text-black text-xl font-light">
              Use Access 2 Opportunities (A2O), UCF's scholarship application system to search for scholarships.
              By completing a one-time application, you will be considered for more than 200 scholarships offered
              by the university and gain access to hundreds of external scholarships, too.
            </p>
          </div>


            <a href="" class="max-w-min ml-16 p-5 bg-main-gold whitespace-nowrap text-black text-xl rounded-sm">
              Tips on Scholarships
            </a>


        </div>
      </div>

      <div class="flex flex-col ">
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
    <div class="flex flex-col items-center space-y-5 mb-8">
      <h1 class="text-black text-4xl text-center font-bold">UCF College & Departmental Scholarships</h1>
      <div class="max-w-3xl">
        <p class="text-black text-lg text-center font-light">Click any of the links below to access their databases and to find out more information on these different types of scholarships avaliable for UCF students.</p>
      </div>
    </div>
    <div class="flex flex-col space-y-10">
      <text-box
      :header-text="'Office of Student Financial Aid Scholarships'"
      :type="'bottom'"
      />
      <text-box
      :header-text="'College / Department Scholarships'"
      :type="'bottom'"
      />
      <text-box
      :header-text="'University-Wide Scholarships '"
      :type="'bottom'"
      />
      <text-box
      :header-text="'Privately Funded Scholarships'"
      :type="'bottom'"
      />
    </div>
  </div>
</template>
