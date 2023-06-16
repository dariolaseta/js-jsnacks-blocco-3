<template>
    <header>
        <nav>
            <NavLink />
        </nav>
    </header>
</template>

<script>
import NavLink from "./NavLink.vue"

export default {
    name: "AppHeader",
    components:{
        NavLink
    }
}
</script>

<style lang="scss" scoped>
    @import "../styles/general.scss";
</style>