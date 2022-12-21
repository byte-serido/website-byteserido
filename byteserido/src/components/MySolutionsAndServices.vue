<template>
    <section class="sands-container">
        <div class="container sands">
            <p>SERVIÇOS E SOLUÇÕES INOVADORAS</p>
            <div class="option-container">
                <button class="button-services" :class="options" @click="changeState()">
                    <img v-if="toogleServices" src="../assets/img/icon_develop_activate.svg" alt="Icone de Serviços ativado">
                    <img v-else src="../assets/img/icon_develop_desativate.svg" alt="Icone de Seviços desativado">
                    <span>desenvolvimento</span>
                </button>
                <button class="button-solutions" :class="options2" @click="changeState()">
                    <img v-if="toogleSolutions" src="../assets/img/icon_marketing_activate.svg" alt="Icone de Marketing ativado">
                    <img v-else src="../assets/img/icon_marketing_desativate.svg" alt="Icone de Marketing desativado">
                    <span>marketing</span>
                </button>
                <div class="line"></div>
            </div>
            <MyService v-if="toogleServices"></MyService>
            <MySolution v-else></MySolution>
        </div>
    </section>
</template>

<script lang="js">
import MyService from "./MyService.vue"
import MySolution from "./MySolution.vue"
export default {
    components:{MyService, MySolution},
    data(){
        return{
            toogleServices: true,
            toogleSolutions: false,
        }
    },
    computed:{
        options(){
            return{
                toogleService:this.toogleServices,
                toogleDesative:!this.toogleServices,
            }
        },
        options2(){
            return{
                toogleSolutions:this.toogleSolutions,
                toogleDesative:!this.toogleSolutions,
            }
        },
    },
    methods:{
        changeState(){
            this.toogleServices = !this.toogleServices;
            this.toogleSolutions = !this.toogleSolutions;
        }
    }
}
</script>

<style scoped>
    .sands-container{
        background-color: #111010;
    }

    .sands-container .sands{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 63px 128px 126px 128px;
        gap: 80px;
    }

    .sands p {
        font-family: "Exo", sans-serif;
        font-weight: 700;
        font-size: 2.5rem;
        color: #FFFFFF;
    }

    .option-container{
        display: flex;
    }

    .option-container button{
        display: flex;
        gap: 15px;
        color:#FFFFFF;
        background-color: transparent;
        border-top: none;
        border-left: none;
        border-right: none;
        font-family: 'Raleway', sans-serif;
        font-weight: 700;
        font-size: 2rem;
        line-height: 38px;
        cursor: pointer;
        padding-bottom: 19px;
    }

    .button-solutions{
        padding-left: 20px;
        padding-right: 10px;
    }

    .button-services{
        padding-right: 20px;
    }

    .line{
        color:#FFFFFF;
        width: 36rem;
        background-color: transparent;
        border-top: none;
        border-left: none;
        border-right: none;
        line-height: 38px;
        padding-bottom: 19px;
        border-bottom: 0.5px solid #FFFFFF;
    }

    .toogleService{
        border-bottom: 3px solid #1EBB66;
    }

    .toogleDesative{
        border-bottom: 0.5px solid #FFFFFF;
    }

    .toogleSolutions{
        border-bottom: 3px solid blue;
    }

    /* @media */

    @media (max-width:1200px){
        .line{
            color:#FFFFFF;
            width: 12rem;
            background-color: transparent;
            border-top: none;
            border-left: none;
            border-right: none;
            line-height: 38px;
            padding-bottom: 19px;
            border-bottom: 0.5px solid #FFFFFF;
        }
    }

    @media (max-width:800px){
        .line{
            display: none;
        }
    }

    @media (max-width:700px){
        .sands-container .sands{
            display: flex;
            flex-direction: column;
            align-items:center;
            padding: 60px 20px 120px 20px;
            gap: 60px;
        }

        .sands p {
            font-family: "Exo", sans-serif;
            font-weight: 700;
            font-size: 2rem;
            color: #FFFFFF;
        }

        span{
            font-size: 1.5rem;
        }
    }
</style>