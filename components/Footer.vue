<script>
import FacebookIcon from './FacebookIcon.vue'
import InstagramIcon from './InstagramIcon.vue'
import TwitterIcon from './TwitterIcon.vue'
import YoutubeIcon from './YoutubeIcon.vue'
export default {
  components: {
    FacebookIcon,
    TwitterIcon,
    YoutubeIcon,
    InstagramIcon,
  },
}
</script>

<template>
  <div class="flex flex-col items-center space-y-8 py-8 bg-zinc-700">
    <div class="flex flex-col items-center space-y-4">
      <div>
        <h1 class="text-2xl text-main-gold text-center uppercase tracking-widest">University of Central Florida</h1>
      </div>
      <div class="flex space-x-4 w-64">
        <facebook-icon />
        <twitter-icon />
        <ucf-social />
        <youtube-icon />
        <instagram-icon />
      </div>
    </div>
      <ul class="flex flex-wrap px-4 text-xs gap-3 justify-center text-white font-light md:flex-nowrap md:text-sm md:px-0">
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/about-ucf/" target="_blank">About UCF</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/contact-ucf/" target="_blank">Contact US</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/faculty/" target="_blank">Faculty</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/online/" target="_blank">Online Degrees</a></li>
        <li class="border-r border-white pr-4"><a href="https://policies.ucf.edu/" target="_blank">Policies</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/internet-privacy-policy/" target="_blank">Privacy Notice</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/public-records-requests/" target="_blank">Public Records</a></li>
        <li class="border-r border-white pr-4"><a href="https://regulations.ucf.edu/" target="_blank">Regulations</a></li>
        <li class="border-r border-white pr-4"><a href="https://www.ucf.edu/contact-ucf/reporting/" target="_blank">Report a Concern</a></li>
        <li class=""><a href="https://www.ucf.edu/news/" target="_blank">UCF News</a></li>
      </ul>
    <div class=" space-y-2">
      <p class="text-white text-sm text-center font-light">4000 Central Florida Blvd. Orlando, Florida, 32816</p>
      <p class="text-white text-sm text-center font-light underline">407.823.2000</p>
      <p class="text-white text-sm text-center font-light">&copy; University of Central Florida</p>
    </div>
  </div>
</template>
