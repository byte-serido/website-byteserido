<template>
    <section class="sands-container">
        <div class="container sands">
            <p>SERVIÇOS E SOLUÇÕES INOVADORAS</p>
        </div>
    </section>
</template>

<script>
export default {
    data(){
        return{
            toggleServices: false,
            toggleSolutions: false,
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
        padding: 30px 128px 126px 128px;
        gap: 77px;
    }

    .sands p {
        font-family: "Exo", sans-serif;
        font-weight: 700;
        font-size: 2.5 rem;
        color: #FFFFFF;
    }
</style>