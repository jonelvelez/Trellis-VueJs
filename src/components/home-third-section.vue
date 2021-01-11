<template>
    <div class="home-third-section">
        <b-container>
            <b-row class="mb-5">
                <b-col cols="12" class="text-center">
                    <h2>OUR TEAM</h2>
                    <div class="title-divider my-5"></div>
                    <h3>who we are</h3>
                </b-col>
            </b-row>

            <b-row>
                <b-col lg="6" md="12" sm="12">
                    <b-card>
                        <b-img class="center" src="../assets/Rob.png"></b-img>
                        <h4 class="text-center">Rob Bier</h4>
                        <div class="name-divider"></div>
                        <p>Rob heads up the Leadership practice area for Trellis bringing his expertise in coaching entrepreneurs & CEOs, developing high-performing teams and designing scalable organizations. Prior to coaching, he was founder & CEO of a FinTech company acquired by Citigroup. He is also the Chairman of MoneySmart in Singapore.</p>
                        <div class="cardbox">
                            <p>rob@trellis.asia <span>in</span> Rob Bier</p>
                        </div>
                    </b-card>
                </b-col>

                <b-col lg="6" md="12" sm="12">
                    <b-card>
                        <b-img class="center" src="../assets/Tania.png"></b-img>
                        <h4 class="text-center">Tania Tulen</h4>
                        <div class="name-divider"></div>
                        <p>As Business Manager, Tania brings calm, charm and efficiency to the team. From organising meetings and workshops to keeping all of our projects on track, her ability to keep all the plates spinning at the right speed is unparalleled. Tania’s career has taken her across the globe, with dynamic roles that supported high profile entrepreneurs in a variety of industries.</p>
                        <div class="cardbox">
                            <p>Tania@trellis.asia <span>in</span> Tania Tulen</p>
                        </div>
                    </b-card>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .home-third-section {
        background-image: url(../assets/bg-image.jpg);
        padding-top: 100px;
        padding-bottom: 100px;
    }

    p {
        font-family: 'Open Sans', sans-serif;
        font-size: 16px;
        color: #666666
    }

    h2 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        color: #fff;
        font-size: 50px;
        font-weight: 400;
    }

    h3 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        color: #fff;
        font-size: 21px;
        font-weight: 500;
    }

    h4 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-size: 20px;
        font-weight: 400;
        color: #333333;
    }

    img {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .title-divider {
        height: 5px;
        width: 70px;
        background-color: #fff;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .card {
        padding-left: 30px;
        padding-right: 30px;
        margin-top: 100px;
    }

    .name-divider {
        background-color: #ef3922;
        width: 40px;
        height: 3px;
        display: block;
        margin-left: auto;
        margin-right: auto;
        margin-top: 15px;
        margin-bottom: 30px;
    }

    .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }

    .cardbox {
        position: relative;
        display: block;
        margin-left: auto;
        margin-right: auto;
        margin-top: 100px;
        margin-bottom: -55px;
        width: 200px;
        background-color: #E0A328;
        padding-top: 10px;
        padding-bottom: 1px;
        padding-left: 38px;
        padding-right: 38px;
    }

    .cardbox p {
        color: #fff;
        font-size: 15px;
        text-align: center;
    }

    .cardbox span {
        font-weight: 900;
    }

    @media only screen and (min-width: 1200px) {
        img {
            position: absolute;
            top: -5vw;
            left: 40%;
            transform: translate(-40px, 0);
        }

        h4 {
            padding-top: 6rem;
        }
    }
</style>