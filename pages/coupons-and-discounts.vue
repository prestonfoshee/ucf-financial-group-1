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
      <div class="flex flex-col items-center space-y-6 px-4 py-14 md:flex-row md:justify-between md:px-8 lg:px-32 2xl:px-64 bg-main-gold">
        <div class="flex flex-col space-y-14 pb-3">
            <div>
              <h2 class="text-black text-4xl font-bold">Find Student Discounts & Offers</h2>
              <div class="w-40 border-b-2 border-white"></div>
            </div>
          <div class="lg:max-w-3xl">
            <p class="text-black text-sm md:text-lg font-base">As a part of UCF's community, you have access to a multitude of discounts and savings. In addition to online
              retailers, there are multiple businesses in and around UCF that will offer discounts to UCF students so long
              as you have a valid UCF ID, don't forget to ask if there is a promotion available and show your ID. Below is
              information for some popular student discounts.
            </p>
          </div>
        </div>
          <img src="~assets/img/coupons-circular.jpg" alt="" class="rounded-full w-60 h-60 border-2 border-white">
      </div>
      <div class="px-4 md:px-16 space-y-12 text-center md:text-left">
        <div class="flex flex-col space-y-8">
          <div class="pb-3 pt-6 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Technology & Media</h2>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">Adobe</p>
              <p class="text-black text-lg font-light">UCF students can get the Adobe creative suite of products for <span class="font-bold underline">$19.99 a month</span>, down from the usual price of $52.99 a month.</p>
            </div>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">Adobe Signup</a>
            </div>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">Amazon Prime</p>
              <p class="text-black text-lg font-light">Amazon offers students a free 6 month trial of Amazon Prime, with the service being half off at $49 after the initial 6 months are over.</p>
            </div>
              <div class="flex justify-center">
                <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">Prime Student</a>
              </div>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2 pb-6">
              <p class="text-black text-xl font-semibold">Apple</p>
              <p class="text-black text-lg font-light">Apple offers educational pricing on certain products including iPads, MacBooks and iPhones.</p>
            </div>
              <div class="flex justify-center">
                <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">Apple EDU Store</a>
              </div>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">Microsoft Office</p>
              <p class="text-black text-lg font-light">Microsoft Office is free for students!</p>
            </div>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">MS Office</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Clothing & Furniture</h2>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">UNiDAYS</p>
              <div class="max-w-5xl">
                <p class="text-black text-lg font-light">UNiDAYS is a one stop shop for hundreds of discounts from very notable retailers.
                By making a UNiDAYS account you will gain access to all these student discounts. Levis, Adidas, and Tillys are just some of the
                retailers you can find with UNiDAYS.</p>
              </div>
            </div>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">UNiDAYS signup</a>
            </div>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">SheerID</p>
              <div class="max-w-5xl">
                <p class="text-black text-lg font-light">SheerID is similar to UNiDAYS as with one account you can unlock hundreds of discounts
                from retailers like Nike and Peloton. Just create an account using your Knights email account.</p>
              </div>
            </div>
              <div class="flex justify-center">
                <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">Sheer student deals</a>
              </div>
          </div>
          <div class="flex justify-between items-center pb-6 pt-2">
            <div class="flex flex-col space-y-2 pt-1">
              <p class="text-black text-xl font-semibold">UCF Gear</p>
              <div class="max-w-5xl">
                <p class="text-black text-lg font-light">Sign up at shops.ucfknights.com to receive 10% off your purchase. There you can find all
                your official UCF Gear needs and deck yourself out head to toe in UCF pride!</p>
              </div>
            </div>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">UCF shop</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Events</h2>
          </div>
          <div class="flex justify-between items-center pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">SGA Ticket Center</p>
              <div class="max-w-5xl">
                <p class="text-black text-lg font-light">The SGA Ticket Center is open Monday thru Saturday and offers discounts to popular attractions
                around central Florida. Check their website for ticket availability as experiences sell out quickly!</p>
              </div>
            </div>
            <div class="flex justify-center">
              <a href="" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">SGA Tickets</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-8">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">Local Discounts</h2>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">Enzian Theater</p>
              <p class="text-black text-lg font-light">An arthouse cinema that offers student discounted tickets for $9. Enzian.org</p>
            </div>
            <div class="flex justify-center">
              <a href="https://www.burgerfi.com/" class="flex items-center justify-center max-w-min px-3 pt-6 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">Enzian FAQ</a>
            </div>
          </div>
          <div class="flex justify-between items-center border-b border-gray-300 pb-6">
            <div class="flex flex-col space-y-2">
              <p class="text-black text-xl font-semibold">BuegerFi</p>
              <p class="text-black text-lg font-light">Discounted burgers and shakes for students who bring their ID's.</p>
            </div>
            <div class="flex justify-center">
              <a href="https://www.burgerfi.com/" class="flex items-center justify-center max-w-min px-3 pt-5 pb-2 text-black text-md whitespace-nowrap bg-main-gold rounded">burgerfi.com</a>
            </div>
          </div>
        </div>
        <div class="flex flex-col space-y-12 pb-12">
          <div class="pb-3 border-b border-main-gold">
            <h2 class="text-black text-2xl font-bold">UCF On-Campus Aid</h2>
          </div>

          <div class="flex justify-center">
            <div class="flex flex-wrap justify-center gap-24 max-w-6xl">

              <div class="flex flex-col items-center space-y-5 max-w-xl">
                <div class="border-2 border-main-gold p-12 rounded-full">
                  <img src="~/assets/img/drumstick.jpg" alt="Knights Pantry Icon" class="w-44 h-44">
                </div>
                <div class="bg-main-gold px-6 pb-3 pt-6 text-center rounded-md">Knights Pantry</div>
                <div class="max-w-xs">
                  <p class="text-black text-center">The Knights Helping Knights Pantry is committed to serving UCF students by providing basic needs including food, clothing,
                    and personal hygiene items to foster continued academic success and increase retention for students in need.
                  </p>
                </div>
              </div>

              <div class="flex flex-col items-center space-y-5 max-w-xl">
                <div class="border-2 border-main-gold p-14 rounded-full">
                  <img src="~/assets/img/ramen.jpg" alt="Dining Services Icon" class="w-40 h-40">
                </div>
                <div class="bg-main-gold px-6 pb-3 pt-6 text-center rounded-md">Dining Services</div>
                <div class="max-w-xs">
                  <p class="text-black text-center">Our meal plans are convenient, flexible and loaded with options. Members gain access to dining locations
                    all across campus with a range of menus and offerings.
                  </p>
                </div>
              </div>

              <div class="flex flex-col items-center space-y-5 max-w-xl">
                <div class="border-2 border-main-gold p-12 rounded-full">
                  <img src="~/assets/img/bus.jpg" alt="Bus Icon" class="w-44 h-44">
                </div>
                <div class="bg-main-gold px-6 pb-3 pt-6 text-center rounded-md">Knights Pantry</div>
                <div class="max-w-xs">
                  <p class="text-black text-center">The Knights Helping Knights Pantry is committed to serving UCF students by providing basic needs including food, clothing,
                    and personal hygiene items to foster continued academic success and increase retention for students in need.
                  </p>
                </div>
              </div>

              <div class="flex flex-col items-center space-y-5 max-w-xl">
                <div class="border-2 border-main-gold p-12 rounded-full">
                  <img src="~/assets/img/train.jpg" alt="Sunrail Icon" class="w-44 h-44">
                </div>
                <div class="bg-main-gold px-6 pb-3 pt-6 text-center rounded-md">Knights Pantry</div>
                <div class="max-w-xs">
                  <p class="text-black text-center">The Knights Helping Knights Pantry is committed to serving UCF students by providing basic needs including food, clothing,
                    and personal hygiene items to foster continued academic success and increase retention for students in need.
                  </p>
                </div>
              </div>

              <div class="flex flex-col items-center space-y-5 max-w-xl">
                <div class="border-2 border-main-gold p-12 rounded-full">
                  <img src="~/assets/img/sedan.jpg" alt="Lyft Icon" class="w-44 h-44">
                </div>
                <div class="bg-main-gold px-6 pb-3 pt-6 text-center rounded-md">Knights Pantry</div>
                <div class="max-w-xs">
                  <p class="text-black text-center">The Knights Helping Knights Pantry is committed to serving UCF students by providing basic needs including food, clothing,
                    and personal hygiene items to foster continued academic success and increase retention for students in need.
                  </p>
                </div>
              </div>
            </div>
          </div>


        </div>
      </div>

    </div>
  </div>
</template>
