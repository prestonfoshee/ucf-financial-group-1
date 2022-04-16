<script>
export default {
  layout: 'budget-calculator',

  data() {
    return {
      form: {
        inputs: {
          housing: '',
          food: '',
          transportation: '',
          utilities: '',
          insurance: '',
          loans: '',
          misc: '',
          subscriptions: '',
          travel: '',
          entertainment: '',
          meals: '',
          emergency: '',
          retirement: '',
          debt: '',
        }
      },
      total: '',
      calculated: false,
    }
  },

  computed: {
    housing() {
      return Number(this.form.inputs.housing)
    },
    food() {
      return Number(this.form.inputs.food)
    },
    transportation() {
      return Number(this.form.inputs.transportation)
    },
    utilities() {
      return Number(this.form.inputs.utilities)
    },
    insurance() {
      return Number(this.form.inputs.insurance)
    },
    loans() {
      return Number(this.form.inputs.loans)
    },
    misc() {
      return Number(this.form.inputs.misc)
    },
    subscriptions() {
      return Number(this.form.inputs.subscriptions)
    },
    travel() {
      return Number(this.form.inputs.travel)
    },
    entertainment() {
      return Number(this.form.inputs.entertainment)
    },
    meals() {
      return Number(this.form.inputs.meals)
    },
    emergency() {
      return Number(this.form.inputs.emergency)
    },
    retirement() {
      return Number(this.form.inputs.retirement)
    },
    debt() {
      return Number(this.form.inputs.debt)
    },
  },

  methods: {
    calculate() {
      const numTotal =
        this.housing +
        this.food +
        this.transportation +
        this.utilities +
        this.insurance +
        this.loans +
        this.misc +
        this.subscriptions +
        this.travel +
        this.entertainment +
        this.meals +
        this.emergency +
        this.retirement +
        this.debt

      const strTotal = numTotal.toString()

      this.total = '$' + strTotal

      this.calculated = true
    },

    reset() {
      this.form.inputs.housing = ''
      this.form.inputs.food = ''
      this.form.inputs.transportation = ''
      this.form.inputs.utilities = ''
      this.form.inputs.insurance = ''
      this.form.inputs.loans = ''
      this.form.inputs.misc = ''
      this.form.inputs.subscriptions = ''
      this.form.inputs.travel = ''
      this.form.inputs.entertainment = ''
      this.form.inputs.meals = ''
      this.form.inputs.emergency = ''
      this.form.inputs.retirement = ''
      this.form.inputs.debt = ''

      this.total = ''

      this.calculated = false
    },

    isNumber ($event) {
      let keyCode = ($event.keyCode ? $event.keyCode : $event.which);
      if ((keyCode < 48 || keyCode > 57) && keyCode !== 46) {
        $event.preventDefault();
      }
    }
  },

}
</script>

<template>
  <div>
    <div class="flex flex-col items-center space-y-6 px-4 py-14 md:flex-row md:justify-between md:px-8 lg:px-32 2xl:px-64 bg-main-gold w-full">
      <div class="flex flex-col space-y-16 pb-3">
        <div>
          <h2 class="text-black text-4xl font-bold">Before You Budget —</h2>
          <h2 class="text-black text-4xl font-bold">Understand What You Pay For Your <span class="text-red-500">Tuition.</span></h2>
        </div>
        <div class="max-w-3xl">
          <p class="text-xl text-black">Many students pay their dues yet don't know how much of their dollars are put towards creating a better community, campus, and university.
            Let us help clarify a few things.</p>
        </div>
      </div>
      <img src="~/assets/img/budget-header-square.jpg" alt="" class="w-80 rounded-xl">
    </div>

    <div class="flex flex-col space-y-3 md:px-8 2xl:px-64 pt-12">
      <h4 class="text-black text-2xl font-bold uppercase">Tuition & Fees</h4>
      <p class="text-gray-400 text-xl">These fees are assessed per credit hour based on the level of the course:</p>
      <h4 class="text-black text-2xl font-bold uppercase">Definition</h4>
      <div class="flex flex-col space-y-12 pb-6">
        <div class="px-4 md:px-16 lg:px-48">
          <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Apply early.</span> The peak time to apply for scholarships is January through May for the upcoming school year. Remember the early bird gets the worm!</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Check for scholarships frequently.</span> Check your department, college, and the UCF Scholarship Listing Page for updates to scholarships.</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Get Involved.</span> While some scholarships do not require involvement, it does help showcase who you are as a person. Also, being involved helps identify your involvement within your community i.e. campus, local, church, sports.</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Complete Your FAFSA.</span> Some scholarships do not require the FAFSA, however, it is recommended for consideration of scholarships that require completing the FAFSA.</p>
          </div>
        </div>
      </div>
    </div>

    <div class="flex flex-col space-y-3 md:px-8 2xl:px-64 pb-12">
      <p class="text-gray-400 text-xl">The following fees are assessed on a basis other than credit hours:</p>
      <div class="flex flex-col space-y-12">
        <div class="px-4 md:px-16 lg:px-48">
          <div class="flex pl-12 flex-col border-l-2 border-main-gold space-y-8">
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Apply early.</span> The peak time to apply for scholarships is January through May for the upcoming school year. Remember the early bird gets the worm!</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Check for scholarships frequently.</span> Check your department, college, and the UCF Scholarship Listing Page for updates to scholarships.</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Get Involved.</span> While some scholarships do not require involvement, it does help showcase who you are as a person. Also, being involved helps identify your involvement within your community i.e. campus, local, church, sports.</p>
            <p class="text-black text-xl"><span class="text-red-500 font-bold">Complete Your FAFSA.</span> Some scholarships do not require the FAFSA, however, it is recommended for consideration of scholarships that require completing the FAFSA.</p>
          </div>
        </div>
      </div>
    </div>

    <div class="flex flex-col space-y-10 md:px-8 2xl:px-64">
      <div>
        <h3 class="text-black text-3xl font-bold">These links will help you get a clear idea about what to expect for the rest of your academic jounery
          here at UCF.</h3>
      </div>
      <div class="flex flex-col flex-wrap items-center justify-center max-w-full gap-4 text-center font-bold md:flex-row md:items-start">
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Tuition Rates (by program)</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Net Price Calculator</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Forms</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">FAQs</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Excess Credit Hours</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Historical Rates</a>
        <a href="" class="flex items-center justify-center w-1/5 h-24 border-2 border-black pb-6 pt-10 px-10">Parent Info</a>
      </div>
    </div>

    <div class="flex flex-col items-center bg-main-gold w-full pb-12">
      <div class="flex flex-col items-center space-y-6 px-16 py-16 max-w-5xl">
      <div class="max-w-lg">
        <h1 class="text-3xl text-black text-center font-bold">Follow the 50/30/20 rule when it comes to your budget needs</h1>
      </div>
      <div class="bg-gray-300 p-4">
        <p class="text-lg text-black font-light text-center">
          <span class="font-bold">50% of your income: Needs.</span> Necessities are the expenses you can't avoid. This portion of your budget should cover required costs such as:
          <span class="font-bold">Housing, Food, Transportation, Basic utilities, Insurance, Minimum loan payments</span>.
        </p>
      </div>

        <form action="" class="flex flex-col justify-center items-center gap-3 pb-6">
            <div class="mt-8">
              <label for="housing" class="block font-bold text-black text-sm">
                Housing/Rent
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.housing" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="food" class="block font-bold text-black text-sm">
                Food
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.food" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="transportation" class="block font-bold text-black text-sm">
                Transportation
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.transportation" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="utilities" class="block font-bold text-black text-sm">
                Utilities
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.utilities" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="insurance" class="block font-bold text-black text-sm">
                Insurance
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.insurance" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="loans" class="block font-bold text-black text-sm">
                Minimum loan payments
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.loans" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div class="mb-5">
              <label for="misc" class="block font-bold text-black text-sm">
                Miscellaneous expenses
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.misc" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

        <div class="bg-gray-300 p-4 mb-8">
          <p class="text-lg text-black font-light text-center">
            <span class="font-bold">30% of your income: Wants.</span> Distinguishing between needs and wants isn't always easy and can vary from one budget to another.
            Generally, though, wants are the extras that aren't essential to living and working. They're often for fun and may include:
            Monthly subscriptions, Travel, Entertainment, Meals out.
          </p>
        </div>


            <div>
              <label for="subscriptions" class="block font-bold text-black text-sm">
                Monthly subscriptions
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.subscriptions" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="travel" class="block font-bold text-black text-sm">
                Travel
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.travel" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="entertainment" class="block font-bold text-black text-sm">
                Entertainment
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.entertainment" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div class="mb-5">
              <label for="meals" class="block font-bold text-black text-sm">
                Meals out
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.meals" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

        <div class="bg-gray-300 p-4 mb-8">
          <p class="text-lg text-black font-light text-center">
            20% of your income: Savings and Debt. Savings is the amount you sock away to prepare for the future.
            Devote this chunk of your income to paying down existing debt and creating a financial cushion.
            How, exactly, to use this part of your budget depends on your situation, but it will likely include:
            <span class="font-bold">Starting and growing an emergency fund, Saving for retirement through a 401(k) and perhaps an individual
            retirement account, Paying off debt, beginning with high-interest accounts like credit cards.</span>
          </p>
        </div>


            <div>
              <label for="emergency" class="block font-bold text-black text-sm">
                Emergency fund
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.emergency" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="retirement" class="block font-bold text-black text-sm">
                Retirement
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.retirement" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="debt" class="block font-bold text-black text-sm">
                Money towards debt
              </label>

              <input @keypress="isNumber($event)"  v-model="form.inputs.debt" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>
        </form>

    </div>

        <div class="flex flex-col w-full space-y-6">
          <div class="w-full border-b border-yellow-700"></div>

          <div class="flex flex-col justify-center items-center space-y-6">
            <span class="flex space-x-3">
              <span class="text-black text-xl font-semibold">Total:</span>
              <div class="bg-white max-w-min px-16">
                {{ total }}
              </div>
            </span>
            <div class="flex flex-col justify-center items-center space-y-5">
              <button @click="calculate" class="w-32 px-5 py-3 bg-yellow-600 rounded font-semibold">Calculate</button>
              <div class="flex justify-center space-x-4">
                <button @click="reset" class="w-32 px-5 py-3 bg-red-500 text-white rounded font-semibold">Reset</button>
                <button class="w-32 px-5 py-3 bg-black text-white rounded font-semibold">Print</button>
              </div>
            </div>
            <div>
            </div>
          </div>
        </div>
    </div>




  </div>
</template>

<style>
  input[type=number]::-webkit-inner-spin-button,
  input[type=number]::-webkit-outer-spin-button {
    -webkit-appearance: none;
    margin: 0;
}
</style>
