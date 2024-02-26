<template>
    <div id="main" :style="{backgroundColor: cor}">
        <button @click="mudarCor"><img id="mode-button" src="../imgs/mode.svg"></button>
        <div id="container-img">
            <div v-for="dado in dados" :key="dado.url">
                <div id="img">
                    <img id="fotos" :src="dado.url" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            dados: [],
            cor: "rgb(236, 236, 236)",
            isNight: true // Renomeei para 'clicks'
        };
    },
    methods: {
        mudarCor() {
                if (this.isNight) {
                    this.cor = "rgb(44, 50, 56)";
                    this.isNight = false;
                } else {
                    this.cor = "rgb(236, 236, 236)";
                    this.isNight = true;
                }
        
        },
    },
    async fetch(){
        let api = 'https://api.thecatapi.com/v1/images/search?limit=50';
        this.dados = await this.$axios.$get(api)
        console.log(this.$axios)
        console.log(this.dados);
    }
};
</script>


<style>
    #main{
        background-color: rgb(236, 236, 236);
        padding: 25px;
    }
    #container-img{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 25px;
    }
    #fotos{
        max-height: 240px;
        min-height: 240px;
        max-width: 250px;
        min-width: 250px;
    }
    #mode-button{
        width: 30px;
    }
    #img{
        background-color: white;
        padding: 25px;
        height: 300px;
        box-shadow: 1px 1px 1px 1px rgb(194, 194, 194);
    }
</style>
