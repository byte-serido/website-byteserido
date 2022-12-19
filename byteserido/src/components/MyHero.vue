<template>
    <section class="hero-container">
        <div class="container hero">
            <article>
                <p class="text">
                    A primeira Empresa Júnior de Tecnologia e Inovação do Seridó chegou para ficar!
                </p>
                <p class="subtext">
                    Descubra como nossos serviços podem fazer você se destacar no mercado.
                </p>
            </article>
            <button>
                <p>CONHEÇA A BYTE SERIDÓ JÚNIOR</p>
                <img src="../assets/icon-next.svg" alt="Icone de avanço">
            </button>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>

<style scoped>
    .hero-container{
        font-family: 'Exo', sans-serif;
    }
    .hero{
        padding: 144px 0px 302px 0px;
        background-size: cover;
        background-image: url("../assets/background-hero.svg");
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-items: center;
        gap: 43px;
    }

    .hero article{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-items: center;
        gap: 34px;
    }

    .text{
        max-width: 778px;
        font-weight: 700;
        font-size: 3rem;
        line-height: 63.79px;
        text-align: center;

    }
    
    .subtext{
        max-width: 584px;
        font-weight: 400;
        font-size: 1.25rem;
        line-height: 26.58px;
        text-align: center;
    }

    .hero button{
        font-family: "Exo",sans-serif;
        display: flex;
        gap: 15px;
        border-radius: 10px;
        justify-content: center;
        align-items: center;
        padding: 14px 20px;
        background-color: #005EFF;
        color: #FFFFFF;
        border: solid 1px #005EFF;
        cursor: pointer;
        position: relative;
        transition: all 400ms ease;
    }

    .hero button:hover{
        background: transparent;
        color: #005EFF;
    }

    .hero button p{
        font-size: 1.25rem;
        line-height: 26.58px;
        font-weight: 700;
    }
    
    /* @media */
    @media (max-width:700px){
        .text{
            max-width: 778px;
            font-weight: 700;
            font-size: 3rem;
            line-height: 63.79px;
            text-align: start;
        }
        
        .subtext{
            max-width: 584px;
            font-weight: 400;
            font-size: 1.25rem;
            line-height: 26.58px;
            text-align: start;
        }
        .hero article{
            display: flex;
            flex-direction: column;
            align-items: start;
            gap: 34px;
        }
        .hero{
            display: flex;
            flex-direction: column;
            align-items: start;
            gap: 43px;
        }
    }
</style>