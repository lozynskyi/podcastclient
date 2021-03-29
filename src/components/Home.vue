<template>
  <div>
    <podcast-sample></podcast-sample>
    <podcast-sample></podcast-sample>
    <podcast-sample></podcast-sample>
  </div>
</template>

<script>
import PodcastSample from './podcast/Sample'
export default {
  name: 'home',
  components: {
    PodcastSample
  }
}
</script>
