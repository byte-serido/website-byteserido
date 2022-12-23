<template>
    <section class="contact-container">
        <div class="container contact">
            <p class="title">Fale com um de nossos consultores e descubra mais sobre nossos serviços.</p>
            <button>AGENDE UMA REUNIÃO CONOSCO</button>
            <hr>
            <p class="options-socias">Siga nossas redes sociais:</p>
            <div class="list-social">
                <a class="item" rel="stylesheet" href="https://www.facebook.com/profile.php?id=100072218402852" target="_blank">
                    <img src="../assets/social/icon_facebook.svg" alt="Icone do Facebook">
                </a>

                <a class="item" rel="stylesheet" href="https://www.instagram.com/byteseridojr/" target="_blank">
                    <img src="../assets/social/icon_instagram.svg" alt="Icone do Instagram">
                </a>

                <a class="item" rel="stylesheet" href="https://twitter.com/ByteSerido" target="_blank" >
                    <img src="../assets/social/icon_twitter.svg" alt="Icone do Twitter">
                </a>

                <a class="item" rel="stylesheet" href="https://www.linkedin.com/company/byte-serid%C3%B3-jr/" target="_blank">
                    <img src="../assets/social/icon_linkdin.svg" alt="Icone do Linkedin">
                </a>

                <a class="item" rel="stylesheet" href="https://github.com/byte-serido" target="_blank">
                    <img src="../assets/social/icon_github.svg" alt="Icone do GitHub">
                </a>

                <a class="item" title="(83)9-9801-0847" rel="stylesheet" href="https://wa.me/558398010847" target="_blank">
                    <img src="../assets/social/icon_whatsaap.svg" alt="Icone do Whatsaap">
                </a>

                <a class="item" rel="stylesheet" title="byteseridoceres@gmail.com" target="_blank" href="mailto:byteseridoceres@gmail.com?subject=Hello%20again">
                    <img src="../assets/social/icon_email.svg" alt="Icone do E-mail">
                </a>

            </div>
        </div>
    </section>
</template>

<script lang="js">
export default {
    
}
</script>

<style scoped>
    .contact-container{
        background-color:#111010;
    }

    .contact{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 84px;
        padding: 70px 126px 126px 126px;
    }

    .contact .title{
        font-family: "Exo", sans-serif;
        font-size: 2rem;
        line-height: 42.53px;
        font-weight: 700;
        text-align: center;
        max-width: 597px;
    }

    .contact button{
        font-family: "Exo",sans-serif;
        border-radius: 10px;
        font-weight: 700;
        font-size: 1.5rem;
        padding: 20px 20px;
        background-color: #005EFF;
        color: #FFFFFF;
        border: solid 1px #005EFF;
        cursor: pointer;
        position: relative;
        transition: all 400ms ease;
    }

    .contact button:hover{
        background: transparent;
        color: #005EFF;
    }

    .contact hr{
        min-width: 100%;
        background-color: transparent;
        border-top: none;
        border-left: none;
        border-right: none;
        border-bottom: 0.5px solid #FFFFFF;
    }

    .contact .options-socias{
        font-family: "Exo", sans-serif;
        font-size: 2rem;
        font-weight: 700;
        text-align: center;
    }

    .contact .list-social{
        display: flex;
        gap: 40px;
        align-items: center;
    }

    a{
        text-decoration: none;
    }

    /* @media */

    @media (max-width:700px){


        .contact .list-social{
            display: grid;
            grid-template-areas:"item item item";
            gap: 26px;
        }

        .contact button{
            font-size: 1.2rem;
            padding: 20px 20px;
        }
    }

    @media (max-width:460px){
        .contact{
            gap: 60px;
            padding: 70px 40px 100px 40px;
        }

        .contact .title{
            font-family: "Exo", sans-serif;
            font-size: 1.6rem;
            line-height: 30px;
            font-weight: 700;
            text-align: center;
            max-width: 597px;
        }

        .contact button{
            font-size: 1rem;
            padding: 18px 18px;
        }

        .contact .options-socias{
            font-size: 1.6rem;
        }
    }

</style>