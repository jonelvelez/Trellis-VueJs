<template>
    <div class="banner">
        <div class="banner-content">
            <h1>We Build <span>Organisation</span> That Scale</h1>
            <b-button>LEARN MORE</b-button>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .banner {
        background-image: url("../assets/BannerImage.png"),linear-gradient(1deg,#282660 50%,#140d41 100%)!important;
        background-size: contain;
        background-repeat: no-repeat;
        background-position: bottom center;
        height: 47vw;
    }

    .banner-content {
        padding: 8vw 20vw;
    }

    button {
        font-family: Oswald, Helvetica, Arial, Lucida, sans-serif;
        background-color: #FABD27;
        border-radius: 0;
        border: none;
        font-weight: 400;
        font-size: 18px;
        padding-left: 45px;
        padding-right: 45px;
        padding-top: 8px;
        padding-bottom: 8px;
        margin-top: 20px;
    }

    h1 {
        font-family: Oswald, Helvetica, Arial, Lucida, sans-serif;
        color: #fff;
        font-size: 55px;
        font-weight: 400;
        line-height: 70px;
        letter-spacing: 2px;
    }

    span {
        color: #fabd27;
        display: block;
        font-weight: 700;
    }

    @media only screen and (max-width: 1024px) {
        h1 {
           font-size: 30px;
           line-height: 2.5rem;
        }
    }

    @media only screen and (max-width: 720px) {
        .banner {
            height: 50vh;
            background-size: cover;
            background-position: 20% 110%;
        }
    }

    @media only screen and (max-width: 560px) {
        .banner-content {
            padding: 10vw 11vw;
        }
    }
</style>