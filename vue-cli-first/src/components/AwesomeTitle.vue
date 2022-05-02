<template>

    <div class="wrapper">
        <h1>La mia prima app con Vue CLI!</h1>
    </div>
    
</template>

<script>
export default {
    name: 'AwesomeTitle'
}
</script>



<style scoped>
    .wrapper {
        margin: 3rem auto;
        padding: 1rem 0;
        background-color: rgb(209, 223, 234);
        width: 60%;
        max-width: 700px;
        border-radius: 40px;
        border: 3px solid #2c3e50;
    }

    .wrapper > h1 {
        text-align: center;
        font-family: Arial, Helvetica, sans-serif;
    }
</style>
