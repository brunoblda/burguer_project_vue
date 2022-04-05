<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>

</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>

    #main-banner {
        background-image: url('/home/brunoblda/area_de_trabalho/estudo/vue/youtube/burguer_project/public/img/burger.jpg');
        background-position: 0 -350px;    
        background-size: cover;
        height: 820px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    #main-banner h1{
        color: #FFF;
        text-align: center;
        font-size: 70px;
        background-color: #222;
        padding: 20px 100px;
    }

</style>

