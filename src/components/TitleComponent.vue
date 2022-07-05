<template>
    <h1>{{test}}</h1>
</template>

<script>
export default {
    name: "TitleComponent",
    props: {
        test: String,
    }
}
</script>

<style lang="scss" scoped>
    h1 {
        font-size: 4rem;
    }
</style>