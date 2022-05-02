<template>
    <div class="wrapper">
        <img src="https://wompampsupport.azureedge.net/fetchimage?siteId=7575&v=2&jpgQuality=100&width=700&url=https%3A%2F%2Fi.kym-cdn.com%2Fentries%2Ficons%2Fmobile%2F000%2F028%2F367%2Fcover1.jpg" alt="">
    </div>
</template>

<script>
export default {
    name: 'AwesomeJumbotron'
}
</script>

<style scoped>

    .wrapper {
        margin: 2rem auto;
        width: 70%;
        max-width: 700px;
        border-radius: 40px;
        border: 3px solid #2c3e50;
        overflow: hidden;
    }

    .wrapper > img {
        display: block;
        max-width: 100%;
    }

</style>