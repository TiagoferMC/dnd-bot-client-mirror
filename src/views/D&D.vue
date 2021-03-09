<template>
    <div class="dnd">
        <Navbar />
        <h1>This is the D&D page</h1>
    </div>
</template>

<script lang="ts">
import Vue from "vue";
import Navbar from "@/components/Navbar.vue"; // @ is an alias to /src

export default Vue.extend({
    name: "D&D",
    components: {
        Navbar
    }
});
</script>
