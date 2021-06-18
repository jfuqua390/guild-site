<template>
    <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="/">Home</b-navbar-brand>
        
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
                <b-nav-item>
                    <nuxt-link to="/about">About</nuxt-link>
                </b-nav-item>
                <b-nav-item>
                    <nuxt-link to="/forum">Fourms</nuxt-link>
                </b-nav-item>
                <b-nav-item>
                    <nuxt-link to="/recruitment">Recruitment</nuxt-link>
                </b-nav-item>
            </b-navbar-nav>
            <b-navbar-nav class="ml-auto">
                <b-nav-item-dropdown text="User">
                    <b-dropdown-item>Profile</b-dropdown-item>
                    <b-dropdown-item>SignOut</b-dropdown-item>
                </b-nav-item-dropdown>
            </b-navbar-nav>
        </b-collapse>
    </b-navbar>
</template>

<script>
export default {}
</script>

<style scoped>

</style>
