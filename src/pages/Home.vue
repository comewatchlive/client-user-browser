<template>
  <div class="home-lists">
    <broadcaster-grid tags="Trending"></broadcaster-grid>
    <broadcaster-grid tags="Top"></broadcaster-grid>
    <broadcaster-grid tags="z1"></broadcaster-grid>
    <broadcaster-grid></broadcaster-grid>
  </div>
</template>
<script>
  import BroadcasterGrid from '../components/BroadcasterGrid.vue'

  export default {
    components: {
      BroadcasterGrid
    }
  }
</script>
