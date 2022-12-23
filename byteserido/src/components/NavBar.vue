<template>
    <section class="navbar-container">
        <div class="container navbar">
            <img src="../assets/img/navbar-logo.svg" alt="Logo da ByteSeridó Jr">
            <div class="menu-bar">
                <a class="menu-button" href="#hero">início</a>
                <a class="menu-button" href="#about">quem somos</a>
                <a class="menu-button" href="#sands">serviços</a>
                <a class="menu-button" href="#contact">fale conosco</a>
            </div>
        </div>
    </section>
</template>

<script>
export default {

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
        border: none;
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

    a{
        text-decoration: none;
    }

    /* @media */
    @media (max-width:900px){
        .menu-bar{
            display: none;
        }
        .navbar{
            justify-content: center;
        }
    }
</style>