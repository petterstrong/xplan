<template>
  <audio :src="audioSrc" style="display:none" autoplay loop></audio>
</template>

<script>
import { MEDIA_URLS } from '@/assets/js/constants'

export default {
  data () {
    return {
      audioSrc: MEDIA_URLS.backgroundAudio
    }
  }
}
</script>
