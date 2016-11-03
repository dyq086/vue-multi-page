<template>
    <div class="home-carousel-container">
        <div class="jumbotron jumbotron-fluid">
            <div class="container">
                <h1 class="display-3">{{ msg }}</h1>
            </div>
        </div>
    </div>

</template>

<script>
    export default {
        data () {
            return {
                msg: 'home-banner.vue'
            }
        }
    }
</script>

<style lang="scss" scoped>
    .home-carousel-container {
        margin: 30px auto;
    }
</style>