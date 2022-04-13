<script>
import TextBox from '../components/coupons-and-discounts/TextBox.vue'
export default {
  components: {
    TextBox
  },
  layout: 'coupons-and-discounts',
}
</script>

<template>
  <div>
    <div class="flex flex-col space-y-12">
      <div class="flex justify-between space-y-6 px-16 py-8 bg-main-gold">
        <div class="flex flex-col space-y-5 pb-3">
            <h2 class="text-black text-4xl font-bold">Find Student Discounts & Offers</h2>
            <div class="w-40 border-b-2 border-white"></div>
          <div class="max-w-3xl">
            <p class="text-black text-lg font-base">As a part of UCF's community, you have access to a multitude of discounts and savings. In addition to online
              retailers, there are multiple businesses in and around UCF that will offer discounts to UCF students so long
              as you have a valid UCF ID, don't forget to ask if there is a promotion available and show your ID. Below is
              information for some popular student discounts.
            </p>
          </div>
        </div>
          <img src="~/assets/img/coupons-circular-header.jpg" alt="" class="rounded-full w-52 h-52 border-2 border-white">
      </div>
      <div class="px-16 space-y-12">
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Technology & Media</h2>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">Adobe</p>
            <p class="text-black text-lg font-light">UCF students can get the Adobe creative suite of products for <span class="font-bold underline">$19.99 a month</span>, down from the usual price of $52.99 a month.</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Adobe signup</a>
            </div>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">Amazon Prime</p>
            <p class="text-black text-lg font-light">Amazon offers students a free 6 month trial of Amazon Prime, with the service being half off at $49 after the initial 6 months are over.</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Prime Student</a>
            </div>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">Apple</p>
            <p class="text-black text-lg font-light">Apple offers educational pricing on certain products including iPads, MacBooks and iPhones.</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Apple EDU store</a>
            </div>
          </div>
          <div class="flex flex-col space-y-2">
            <p class="text-black text-xl font-semibold">Microsoft Office</p>
            <p class="text-black text-lg font-light">Microsoft Office is free for students!</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">MS Office download page</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Clothing & Furniture</h2>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">UNiDAYS</p>
            <p class="text-black text-lg font-light">UNiDAYS is a one stop shop for hundreds of discounts from very notable retailers.
            By making a UNiDAYS account you will gain access to all these student discounts. Levis, Adidas, and Tillys are just some of the
            retailers you can find with UNiDAYS.</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">UNiDAYS signup</a>
            </div>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">SheerID</p>
            <p class="text-black text-lg font-light">SheerID is similar to UNiDAYS as with one account you can unlock hundreds of discounts
            from retailers like Nike and Peloton. Just create an account using your Knights email account.</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Sheer student deals</a>
            </div>
          </div>
          <div class="flex flex-col space-y-2">
            <p class="text-black text-xl font-semibold">UCF Gear</p>
            <p class="text-black text-lg font-light">Sign up at shops.ucfknights.com to receive 10% off your purchase. There you can find all
            your official UCF Gear needs and deck yourself out head to toe in UCF pride!</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">UCF shop</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Events</h2>
          </div>
          <div class="flex flex-col space-y-2">
            <p class="text-black text-xl font-semibold">SGA Ticket Center</p>
            <p class="text-black text-lg font-light">The SGA Ticket Center is open Monday thru Saturday and offers discounts to popular attractions
            around central Florida. Check their website for ticket availability as experiences sell out quickly!</p>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">SGA Tickets</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-4">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Local Discounts</h2>
          </div>
          <div class="flex flex-col space-y-2 pb-6 border-b border-gray-300">
            <p class="text-black text-xl font-semibold">Enzian Theater</p>
            <p class="text-black text-lg font-light">An arthouse cinema that offers student discounted tickets for $9. Enzian.org</p>
            <div class="flex justify-center">
              <a href="https://www.burgerfi.com/" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Enzian FAQ</a>
            </div>
          </div>
          <div>
            <p class="text-black text-xl font-semibold">BuegerFi</p>
            <p class="text-black text-lg font-light">Discounted burgers and shakes for students who bring their ID's.</p>
            <div class="flex justify-center">
              <a href="https://www.burgerfi.com/" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">burgerfi.com</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-4">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">UCF On-Campus Aid</h2>
          </div>
          <div class="flex flex-wrap justify-center items-center w-3/4 mx-auto">
            <text-box :text="'Knights Pantry'" />
            <text-box :text="'Dining Services'" />
            <text-box :text="'Lynx/Bus Info'" />
            <text-box :text="'Sunrail Info'" />
            <text-box :text="'CoachUSA'" />
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
