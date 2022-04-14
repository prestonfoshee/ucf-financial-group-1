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
        <h1 class="text-2xl text-main-gold text-center font-semibold uppercase">University of Central Florida</h1>
      </div>
      <div class="flex space-x-4 w-64">
        <facebook-icon />
        <twitter-icon />
        <ucf-social />
        <youtube-icon />
        <instagram-icon />
      </div>
    </div>
      <ul class="flex flex-wrap text-xs md:flex-nowrap justify-center space-x-3 md:text-sm text-white font-light">
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">About UCF</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Contact US</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Faculty</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Online Degrees</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Policies</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Privacy Notice</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Public Records</a></li>
        <li class="border-r border-white pr-3 m-1"><a href="" target="_blank">Regulations</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Report a Concern</a></li>
        <li class=""><a href="" target="_blank">UCF News</a></li>
      </ul>
    <div class=" space-y-2">
      <p class="text-white text-sm text-center font-light">4000 Central Florida Blvd. Orlando, Florida, 32816</p>
      <p class="text-white text-sm text-center font-light underline">407.823.2000</p>
      <p class="text-white text-sm text-center font-light">&copy; University of Central Florida</p>
    </div>
  </div>
</template>
