<template>
    <div>
        <Navbar/>
        <router-view/>
    </div>
</template>

<style lang="scss">

* {
    padding: 0;
    margin: 0;
}
#app {
    a {
        &.router-link-exact-active {}
    }
}
</style>
