<template>
    <div class="container-fluid">
    <transition name="home"></transition>
        <Header />
        <div class="body">This will be forums</div>
    </div>
    
</template>

<script>
export default {
    transition: 'home'
}
</script>

<style scoped>
    .home-enter-active, .home-leave-active { transition: opacity .5s; }
    .home-enter, .home-leave-active { opacity: 0; }
</style>