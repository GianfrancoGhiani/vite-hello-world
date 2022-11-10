<template>
    <div class="wrapper">
        <img src="../assets/it-takes-two-hero-banner-desktop.jpg" alt="it takes two">
        <h2>it takes two</h2>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                title: '',
            }
        },
    }
</script>

<style lang="css" scoped>
.wrapper{
    position: relative;
}
img{
    max-width: 100%;
    position: absolute;
    top: 0;
    left: 0;
}
h2{
    position: absolute;
    top: 0;
    left: 15%;
    color: white;
    text-transform: capitalize;
}

</style>