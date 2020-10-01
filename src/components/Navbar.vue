<template>
    <nav>
        <div class="navbar">
            <div class="">
                <router-link to="/">Home</router-link>
                <router-link to="/dnd">D&D</router-link>
            </div>
        </div>
    </nav>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'Navbar'
})
</script>

<style scoped lang="scss">

</style>
