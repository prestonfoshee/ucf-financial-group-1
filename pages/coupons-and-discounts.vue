<script>
import TextBox from '../components/coupons-and-discounts/TextBox.vue'
export default {
  components: {
    TextBox
  },
}
</script>

<template>
  <div class="flex flex-col space-y-12">
    <h1 class="text-black text-3xl text-center font-bold">Find Student Discounts & Offers</h1>
    <div class="flex flex-col space-y-8">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">Technology & Media</h2>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">Adobe</p>
        <p class="text-black text-lg font-light">UCF students can get the Adobe creative suite of products for <span class="font-bold underline">$19.99 a month</span>, down from the usual price of $52.99 a month.</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Adobe signup</a>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">Amazon Prime</p>
        <p class="text-black text-lg font-light">Amazon offers students a free 6 month trial of Amazon Prime, with the service being half off at $49 after the initial 6 months are over.</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Prime Student</a>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">Apple</p>
        <p class="text-black text-lg font-light">Apple offers educational pricing on certain products including iPads, MacBooks and iPhones.</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Apple EDU store</a>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">Microsoft Office</p>
        <p class="text-black text-lg font-light">Microsoft Office is free for students!</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">MS Office download page</a>
      </div>
    </div>
    <div class="flex flex-col space-y-8">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">Clothing & Furniture</h2>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">UNiDAYS</p>
        <p class="text-black text-lg font-light">UNiDAYS is a one stop shop for hundreds of discounts from very notable retailers.
        By making a UNiDAYS account you will gain access to all these student discounts. Levis, Adidas, and Tillys are just some of the
        retailers you can find with UNiDAYS.</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">UNiDAYS signup</a>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">SheerID</p>
        <p class="text-black text-lg font-light">SheerID is similar to UNiDAYS as with one account you can unlock hundreds of discounts
        from retailers like Nike and Peloton. Just create an account using your Knights email account.</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">Sheer student deals</a>
      </div>
      <div class="flex flex-col space-y-2">
        <p class="text-black text-xl font-semibold">UCF Gear</p>
        <p class="text-black text-lg font-light">Sign up at shops.ucfknights.com to receive 10% off your purchase. There you can find all
        your official UCF Gear needs and deck yourself out head to toe in UCF pride!</p>
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">UCF shop</a>
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
        <a href="" class="flex items-center justify-center max-w-min p-3 text-black text-md whitespace-nowrap font-semibold bg-main-gold rounded">SGA Tickets</a>
      </div>
    </div>
    <div class="flex flex-col space-y-4">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">Local Discounts</h2>
      </div>
      <p class="text-black text-xl font-semibold">Enzian Theater</p>
      <p class="text-black text-lg font-light">An arthouse cinema that offers student discounted tickets for $9. Enzian.org</p>
      <div>
        <p class="text-black text-xl font-semibold">Bulk Nation</p>
        <p class="text-black text-lg font-light">Students recieve 10% off their purchases at Bulk Nation on Tuesdays.</p>
        <a href="https://www.bulknationusa.com" class="text-main-gold text-lg font-light underline">bulknationusa.com</a>
      </div>
      <div>
        <p class="text-black text-xl font-semibold">BuegerFi</p>
        <p class="text-black text-lg font-light">Discounted burgers and shakes for students who bring their ID's.</p>
        <a href="https://www.burgerfi.com/" class="text-main-gold text-lg font-light underline">burgerfi.com</a>
      </div>
    </div>
    <div class="flex flex-col space-y-4">
      <div class="pb-3 border-b border-main-gold">
        <h2 class="text-black text-2xl font-bold">UCF On-Campus Aid</h2>
      </div>
      <div class="flex justify-center space-x-8">
        <text-box :text="'Knights Pantry'" />
        <text-box :text="'Knights Pantry'" />
        <text-box :text="'Knights Pantry'" />
      </div>
    </div>
  </div>
</template>
