<template>
    <div class="jumbotron">
        <img src="http://samcharter.com/wp-content/uploads/2019/06/NASA.jpg" alt="Evangelion Wallpaper">
    </div>
</template>

<script>
export default {
    name: "HeroComponent",
    props: {

    }
}
</script>

<style lang="scss" scoped>
    .jumbotron {
        margin: 2rem 0;
        width: 100vw;
    }
    img {
        width: 100%;
        display: block;
    }
</style>