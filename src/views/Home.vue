<template>
  <div class="home">
  <slider/>
  </div>
</template>

<script>
// @ is an alias to /src
import slider from '@/components/HomeComp.vue'

export default {
  name: 'Home',
  components: {
    slider
  }
}
</script>
