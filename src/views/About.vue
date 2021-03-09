<template>
    <div class="about">
        <Navbar />
        <h1>This is the About page</h1>
    </div>
</template>

<script lang="ts">
import Vue from "vue";
import Navbar from "@/components/Navbar.vue"; // @ is an alias to /src

export default Vue.extend({
    name: "Home",
    components: {
        Navbar
    }
});
</script>
