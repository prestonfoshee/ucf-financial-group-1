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
      <h1 class="text-black text-3xl text-center font-bold">Popular Scholarships at UCF</h1>
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
    <div class="flex flex-col items-center space-y-5 mb-8">
      <h1 class="text-black text-4xl text-center font-bold">UCF College & Departmental Scholarships</h1>
      <div class="max-w-3xl">
        <p class="text-black text-lg text-center font-light">Click any of the links below to access their databases and to find out more information on these different types of scholarships avaliable for UCF students.</p>
      </div>
    </div>
    <div class="flex flex-col space-y-8">
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
