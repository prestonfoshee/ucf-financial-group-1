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

      this.total = strTotal

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
  <div class="flex flex-col items-center">
    <div class="flex flex-col items-center space-y-6 px-16 py-4 border-2 border-black max-w-3xl">
      <div class="max-w-lg">
        <h1 class="text-3xl text-black text-center font-bold">Follow the 50/30/20 rule when it comes to your budget needs</h1>
      </div>
      <p class="text-lg text-black font-light text-justify">
        <span class="font-bold">50% of your income: Needs.</span> Necessities are the expenses you can’t avoid. This portion of your budget should cover required costs such as:
        <span class="font-bold">Housing, Food, Transportation, Basic utilities, Insurance, Minimum loan payments</span>.
      </p>

        <form action="" class="flex flex-wrap justify-center items-center gap-3">
            <div>
              <label for="housing" class="block uppercase font-bold text-black text-sm text-center">
                Housing/Rent
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.housing" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="food" class="block uppercase font-bold text-black text-sm text-center">
                Food
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.food" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="transportation" class="block uppercase font-bold text-black text-sm text-center">
                Transportation
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.transportation" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="utilities" class="block uppercase font-bold text-black text-sm text-center">
                Utilities
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.utilities" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="insurance" class="block uppercase font-bold text-black text-sm text-center">
                Insurance
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.insurance" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="loans" class="block uppercase font-bold text-black text-sm text-center">
                Minimum loan payments
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.loans" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="misc" class="block uppercase font-bold text-black text-sm text-center">
                Miscellaneous expenses
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.misc" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>


        <p class="text-lg text-black font-light text-justify">
          <span class="font-bold">30% of your income: Wants.</span> Distinguishing between needs and wants isn't always easy and can vary from one budget to another.
          Generally, though, wants are the extras that aren't essential to living and working. They're often for fun and may include:
          Monthly subscriptions, Travel, Entertainment, Meals out.
        </p>


            <div>
              <label for="subscriptions" class="block uppercase font-bold text-black text-sm text-center">
                Monthly subscriptions
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.subscriptions" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="travel" class="block uppercase font-bold text-black text-sm text-center">
                Travel
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.travel" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="entertainment" class="block uppercase font-bold text-black text-sm text-center">
                Entertainment
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.entertainment" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="meals" class="block uppercase font-bold text-black text-sm text-center">
                Meals out
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.meals" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>


        <p class="text-lg text-black font-light text-justify">
          20% of your income: Savings and Debt. Savings is the amount you sock away to prepare for the future.
          Devote this chunk of your income to paying down existing debt and creating a financial cushion.
          How, exactly, to use this part of your budget depends on your situation, but it will likely include:
          <span class="font-bold">Starting and growing an emergency fund, Saving for retirement through a 401(k) and perhaps an individual
          retirement account, Paying off debt, beginning with high-interest accounts like credit cards.</span>
        </p>


            <div>
              <label for="emergency" class="block uppercase font-bold text-black text-sm text-center">
                Emergency fund
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.emergency" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="retirement" class="block uppercase font-bold text-black text-sm text-center">
                Retirement
              </label>

              <input @keypress="isNumber($event)" v-model="form.inputs.retirement" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>

            <div>
              <label for="debt" class="block uppercase font-bold text-black text-sm text-center">
                Money towards debt
              </label>

              <input @keypress="isNumber($event)"  v-model="form.inputs.debt" type="number" class="border border-gray-400 p-2 w-full outline-none [appearance:textfield]">
            </div>
        </form>

        <div class="flex justify-between items-center mr-auto w-full">
          <div class="flex space-x-3">
            <button @click="calculate" class="px-5 py-3 bg-main-gold rounded-lg">Calculate</button>
            <button @click="reset" class="mr-auto px-5 py-3 bg-gray-300 rounded-lg">Reset</button>
          </div>
          <div>
            <span v-show="calculated">Total monthly budget: ${{ total }}</span>
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
