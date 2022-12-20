<template>
    <section class="footer-container">
        <div class="container footer">
            <img src="../assets/img/logo-preto-branco.svg" alt="Logo da Byte Seridó Junior no footer">
            <div class="navigation-and-social">
                <div class="navigation">
                    <p>MAPA DO SITE</p>
                    <div class="menu">
                        <a class="item">início</a>
                        <a class="item">serviços</a>
                        <a class="item">quem somos</a>
                        <a class="item">fale conosco</a>
                    </div>
                </div>
                <div class="social">
                    <p>ACOMPANHE NOSSAS REDES SOCIAIS</p>
                    <div class="icons">
                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_facebook.svg" alt="Icone do Facebook">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_instagram.svg" alt="Icone do Instagram">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_twitter.svg" alt="Icone do Twitter">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_linkdin.svg" alt="Icone do Linkedin">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_github.svg" alt="Icone do GitHub">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_whatsaap.svg" alt="Icone do Whatsaap">
                        </a>

                        <a rel="stylesheet" href="" target="_blank">
                            <img src="../assets/social/icon_email.svg" alt="Icone do E-mail">
                        </a>
                    </div>
                </div>
            </div>
            <hr>
            <p class="rights-business">2022 Byte Seridó Júnior. Todos os direitos reservados.</p>
        </div>
    </section>
</template>

<script lang="js">
export default {
    
}
</script>

<style scoped>
    .footer-container{
        font-family: "Exo",sans-serif;
    }

    .footer{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 50px;
        padding: 50px 132px 132px 74px;
    }

    .navigation-and-social{
        display: flex;
        justify-content: space-between;
        align-items: center;
        min-width: 100%;
    }

    .navigation{
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        gap: 30px;
    }

    .social{
        display: flex;
        align-items: flex-end;
        flex-direction: column;
        gap: 30px;
    }

    .footer hr{
        min-width: 100%;
        background-color: transparent;
        border-top: none;
        border-left: none;
        border-right: none;
        border-bottom: 0.5px solid #C4C4C4;
    }

    .footer .rights-business{
        font-size: 1.5rem;
        text-align: center;
        font-weight: 500;
    }

    .navigation p{
        font-weight: 700;
        font-size: 1.75rem;
    }

    .navigation .menu{
        display: grid;
        grid-template-areas:"item item"
                            "item item";
        gap: 26px;
    }

    .social p{
        font-weight: 700;
        font-size: 1.75rem;
    }

    .social .icons{
        display: flex;
        gap: 40px;
        align-items: center;
    }

    .navigation a{
        font-size: 1.75rem;
        color: #C4C4C4;
        font-weight: 700;
        text-decoration: none;
        cursor: pointer;
    }
</style>