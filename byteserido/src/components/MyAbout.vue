<template>
    <section class="about-container">
        <div class="container about">
            <img src="../assets/img/logo-azul.svg" alt="Logo da ByteSeridoJunior azul">
            <div class="about-title">
                <p>DO SERIDÓ PARA O MUNDO</p>
                <hr>
            </div>
            <div class="history">
                <article>
                    <p>A Byte Seridó JR é a primeira Empresa Junior do Seridó a ser federada. Foi fundada e iniciou as suas atividades no ano de 2019 e atualmente é composta por 20 membros, que tem a missão de oferecer serviços competentes e soluções inovadoras para a região.</p>
                    <p>A EJ (ou marca?) representa o Curso de Bacharelado em Sistemas de Informação da UFRN, campus CERES Caicó e tem “Seridó” na sua marca para referenciar a sua localidade.</p>
                </article>
                <div>
                    <img src="../assets/img/vista_aérea_caico.svg" alt="Imagem aérea de Caicó"/>
                    <span>Vista aérea de Caicó.</span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .about-container{
        background-color: #111010;
    }

    .about{
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 54px 64px 120px 64px;
        gap: 60px;
    }

    .about-title{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        min-width: 100%;
        gap: 44px;
    }

    .about-title p{
        font-family: "Exo", sans-serif;
        font-size: 2.5rem;
        font-weight: 700;
        padding-left: 20px;
    }
    
    hr{
        min-width: 100%;
        background-color: transparent;
        border-top: none;
        border-left: none;
        border-right: none;
        border-bottom: 0.5px solid #FFFFFF;
    }

    .history{
        display: flex;
        gap: 92px;
    }

    .history article{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;
        max-width: 511px;
        font-size: 1.5rem;
        line-height: 28.18px;
        font-family: "Raleway", sans-serif;
        gap:40px;
        color: #FFFFFF;
    }

    span{
        display: flex;
        justify-content: flex-end;
        color: #FFFFFF;
        font-weight: 400;
    }

    /* @media */
    @media (max-width:1200px){
        .history article{
            max-width: none;
            gap: 20px;
        }

        span{
            justify-content: flex-start;
        }

        .history{  
            display: flex;
            flex-direction: column;
            gap: 60px;
        }
        
    }

    @media (max-width:700px){

        .about-title{
            gap: 26px;
        }

        .about-title p{
            font-family: "Exo", sans-serif;
            font-size: 2rem;
            font-weight: 700;
            padding-left: 20px;
        }

        .history{
            display: flex;
            flex-direction: column;
        }

        .history article{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            max-width: 511px;
            font-size: 1.5rem;
            line-height: 28.18px;
            font-family: "Raleway", sans-serif;
            gap:30px;
            color: #FFFFFF;
        }

        .history div{
            display: none;
        }
    }

    @media (max-width:400px){

        .about{
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 40px 40px 100px 40px;
            gap: 50px;
        }
        .about-title{
            gap: 20px;
        }

        .about-title p{
            font-size: 1.5rem;
            padding-left: 0px;
        }

        .history{
            display: flex;
            flex-direction: column;
        }

        .history article{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: flex-start;
            max-width: 520px;
            font-size: 1.2rem;
            line-height: 24.18px;
            font-family: "Raleway", sans-serif;
            gap:24px;
            color: #FFFFFF;
        }

        .history div{
            display: none;
        }
    }

</style>