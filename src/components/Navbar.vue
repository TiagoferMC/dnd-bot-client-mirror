<template>
    <nav>
        <div class="nav-wrapper">
            <a href="#" class="brand-logo">Logo</a>
            <ul id="nav-mobile" class="right hide-on-med-and-down">
                <li><router-link to="/">Home</router-link></li>
                <li><router-link to="/dnd">D&D</router-link></li>
            </ul>
        </div>
    </nav>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
    name: "Navbar"
});
</script>

<style scoped lang="scss"></style>
