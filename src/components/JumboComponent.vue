<template>
    <div id="jumbo">
        <img src="../assets/thailand.jpg">
        <div class="border">
            <span>have fun in thailand</span>
        </div>
    </div>
</template>


<script>
    export default {
        name: 'JumboComponent'
    }
</script>


<style scoped>
    #jumbo {
        height: 700px;
        position: relative;
    }

    img {
        height: 100%;
        width: 100%;
        object-fit: cover;
        object-position: top;
    }

    span {
        color: #FEDCF4;
        text-transform: uppercase;
        font-size: 0.6rem;
    }

    .border {
        width: 98%;
        height: 95%;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        border: 1px solid #FEDCF4;
        display: flex;
        justify-content: flex-end;
        align-items: flex-end;
        padding: 2px 3px;
    }
</style>

