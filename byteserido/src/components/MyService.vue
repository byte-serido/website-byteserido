<template>
    <div class="services">
        <div class="landing-page">
            <img src="../assets/img/icon_system_web.svg"  alt="Imagem decorativa de landingpage">
            <p>Criação de websites e landing pages</p>
        </div>
        <div class="system-web">
            <img src="../assets/img/icon_laning_page.svg"  alt="Imagem decorativa de Sistema web">
            <p>Sistemas Web</p>
        </div>
    </div>
</template>

<script lang="js">
export default {
    
}
</script>

<style scoped>
    .services{
        display: flex;
        gap: 100px;
        align-items: center;
        color: #FFFFFF;
    }

    .landing-page{
        height: 250px;
        width: 350px;
        font-size: 1.5rem;
        font-weight: 700;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 37px 36px;
        border: 3px solid #1EBB66;
        justify-content: center;
        line-height: 28.18px;
        text-align: center;
        gap: 34px;
        border-radius: 10px;
    }

    .system-web{
        height: 250px;
        width: 350px;
        font-size: 1.5rem;
        font-weight: 700;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 37px 36px;
        border: 3px solid #1EBB66;
        gap: 34px;
        border-radius: 10px;
        justify-content: center;
    }

    /* @media */
    @media (max-width:1200px){

        .services{
            display: flex;
            gap: 50px;
            align-items: center;
            color: #FFFFFF;
        }
        .landing-page{
            height: 200px;
            width: 240px;
            font-size: 1.5rem;
            font-weight: 700;
            padding: 20px;
            gap: 22px;
        }

        .system-web{
            height: 200px;
            width: 240px;
            font-size: 1.5rem;
            font-weight: 700;
            padding: 20px;
            gap: 22px;
        }
    }
    
    @media (max-width:700px){
        .services{
            display: flex;
            flex-direction: column;
            gap: 40px;
            align-items: center;
            color: #FFFFFF;
        }
    }

</style>