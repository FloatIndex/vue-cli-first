<template>
    <header>
        <h1>La mia prima app con Vue CLI!</h1>
    </header>
</template>


<script>
    export default {
        name: 'TitleComponent'
    }
</script>


<style scoped>
    header {
        height: 90px;
        line-height: 90px;
    }

    h1 {
        text-align: center;
        color: #FEDCF4;
        text-shadow: 1px 1px #e80299;
        text-transform: uppercase;
    }
</style>