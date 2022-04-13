<script>
import SocialIcon from './SocialIcon.vue'
export default {
  components: {
    SocialIcon,
  },
}
</script>

<template>
  <div class="flex flex-col space-y-6">
    <h1 class="text-2xl text-main-gold text-center font-semibold uppercase">University of Central Florida</h1>
    <div class="flex justify-center space-x-5">
      <SocialIcon />
      <SocialIcon />
      <SocialIcon />
      <SocialIcon />
      <SocialIcon />
    </div>
    <div>
      <ul class="flex justify-center space-x-3 text-sm text-white font-light">
        <li class="border-r border-white pr-3"><a href="" target="_blank">About UCF</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Contact US</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Faculty</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Online Degrees</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Policies</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Privacy Notice</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Public Records</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Regulations</a></li>
        <li class="border-r border-white pr-3"><a href="" target="_blank">Report a Concern</a></li>
        <li class=""><a href="" target="_blank">UCF News</a></li>
      </ul>
    </div>
    <div>
      <p class="text-white text-sm text-center font-light">4000 Central Florida Blvd. Orlando, Florida, 32816</p>
      <p class="text-white text-sm text-center font-light underline">407.823.2000</p>
      <p class="text-white text-sm text-center font-light">&copy; University of Central Florida</p>
    </div>
  </div>
</template>
