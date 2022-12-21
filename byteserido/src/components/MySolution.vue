<template>
    <div class="solutions">
        <div class="consultoria">
            <img src="../assets/img/icon_instagram.svg"  alt="Imagem decorativa de Consultoria de Marketing">
            <p>Consultoria de Marketing Digital</p>
        </div>
        <div class="midias-sociais">
            <img src="../assets/img/icon_compartilhar.svg"  alt="Imagem decorativa de Gestão de redes Socias">
            <p>Gerenciamento de Mídias Sociais</p>
        </div>
    </div>
</template>

<script lang="js">
export default {
    
}
</script>

<style>
    .solutions{
        display: flex;
        gap: 100px;
        align-items: center;
        color: #FFFFFF;
    }

    .consultoria{
        height: 250px;
        width: 350px;
        font-size: 1.5rem;
        font-weight: 700;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 37px 36px;
        border: 3px solid blue;
        justify-content: center;
        line-height: 28.18px;
        text-align: center;
        gap: 34px;
        border-radius: 10px;
    }

    .midias-sociais{
        height: 250px;
        width: 350px;
        font-size: 1.5rem;
        font-weight: 700;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 37px 36px;
        border: 3px solid blue;
        gap: 34px;
        border-radius: 10px;
        text-align: center;
        justify-content: center;
    }

    /* @media */
    @media (max-width:1200px){

        .solutions{
            display: flex;
            gap: 50px;
            align-items: center;
            color: #FFFFFF;
        }
        .consultoria{
            height: 200px;
            width: 240px;
            font-size: 1.5rem;
            font-weight: 700;
            padding: 20px;
            gap: 22px;
        }

        .midias-sociais{
            height: 200px;
            width: 240px;
            font-size: 1.5rem;
            font-weight: 700;
            padding: 20px;
            gap: 22px;
        }
    }

    @media (max-width:700px){
        .solutions{
            display: flex;
            flex-direction: column;
            gap: 40px;
            align-items: center;
            color: #FFFFFF;
        }
    }

</style>