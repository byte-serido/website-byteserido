<template>
    <section class="navbar-container">
        <div class="container navbar">
            <img src="../assets/img/navbar-logo.svg" alt="Logo da ByteSeridó Jr">
            <div class="menu-bar">
                <li v-for="menu in menu" :key="menu">
                    <button class="menu-button">{{menu}}</button>
                </li>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    data(){
        return{
            menu:["início","quem somos","serviços", "fale conosco"]
        }
    }
}
</script>
<style scoped>
    .navbar-container {
        padding: 10px 96px;
        background-color: #000000;
        font-family: 'Raleway', sans-serif;
    }
    .navbar{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .menu-bar{
        display: flex;
        gap: 50px;
    }
    li{
        list-style: none;
    }
    .menu-button{
        background-color: transparent;
        color: #FFFFFF;
        font-size: 1.25rem;
        font-weight: 700;
        font-family: 'Raleway', sans-serif;
        line-height: 23.48px;
        cursor: pointer;
        position: relative;
        transition: all 400ms ease;
    }
    .menu-button:hover{
        color: #005EFF;
    }
</style>