<template>
  <div class="home">
      <Navbar/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Navbar from '@/components/Navbar.vue' // @ is an alias to /src

export default Vue.extend({
  name: 'Home',
  components: {
    Navbar
  }
})
</script>
