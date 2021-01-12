<template>
    <div class="home-second-section" id="whatwedo">
        <b-container>
            <b-row class="mb-5">
                <b-col cols="12" class="text-center">
                <h2>WHAT WE DO</h2> 
                <div class="divider"></div>
                <p>Our Mission is to help Southeast Asia’s most promising startups build world-class organisations that scale.</p>
                <p>Our approach is to strengthen the four foundations of a great organisation.</p>
                </b-col>
            </b-row>

            <b-row class="mb-4">
                <b-card class="card py-2 w-100">
                   <b-row align-v="center">
                        <b-col lg="4">
                            <b-img src="../assets/our_team_icon_1.png"></b-img>
                        </b-col>
                        <b-col lg="4">
                            <span>Leadership</span>
                        </b-col>
                        <b-col lg="4">
                            <ul>
                                <li>High Performance Leadership Team</li>
                                <li>CEO Coaching</li>
                                <li>Mission & Vision</li>
                            </ul>
                        </b-col>
                    </b-row>
                </b-card>
            </b-row>
            
            <b-row class="mb-4">
                <b-card class="card py-2 w-100">
                   <b-row align-v="center">
                        <b-col lg="4">
                            <b-img src="../assets/our_team_icon_2.png"></b-img>
                        </b-col>
                        <b-col lg="4">
                            <span>Execution</span>
                        </b-col>
                        <b-col lg="4">
                            <ul>
                                <li>Organisation Design</li>
                                <li>High Performance Execution Teams</li>
                            </ul>
                        </b-col>
                    </b-row>
                </b-card>
            </b-row>

            <b-row class="mb-4">
                <b-card class="card py-2 w-100">
                   <b-row align-v="center">
                        <b-col lg="4">
                            <b-img src="../assets/our_team_icon_3.png"></b-img>
                        </b-col>
                        <b-col lg="4">
                            <span>People</span>
                        </b-col>
                        <b-col lg="4">
                            <ul>
                                <li>Talent Development</li>
                                <li>Manager Training</li>
                            </ul>
                        </b-col>
                    </b-row>
                </b-card>
            </b-row>

            <b-row class="mb-4">
                <b-card class="card py-2 w-100">
                   <b-row align-v="center">
                        <b-col lg="4">
                            <b-img src="../assets/our_team_icon_4.png"></b-img>
                        </b-col>
                        <b-col lg="4">
                            <span>Culture</span>
                        </b-col>
                        <b-col lg="4">
                            <ul>
                                <li>Company Values</li>
                                <li>High Performance Communications</li>
                            </ul>
                        </b-col>
                    </b-row>
                </b-card>
            </b-row>
            
        </b-container>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .home-second-section {
        padding-top: 100px;
        padding-bottom: 100px;
        background-color: #EFF1EC;
    }

    h2 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-size: 50px;
        line-height: 75px;
        color: #ef3922;
        font-weight: 400;
    }

    .divider {
        height: 5px;
        width: 70px;
        display: block;
        margin-left: auto;
        margin-right: auto;
        margin-top: 30px;
        margin-bottom: 30px;
        background-color: #F8BE23;
    }

    p {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-weight: 500;
        font-size: 20px;
        color: #666666
    }

    span {
        color: #ef3922;
        font-size: 22px;
        font-weight: 700;
    }

    .card {
        border-bottom: 5px solid #F8BE23;
        padding-left: 100px;
        padding-right: 100px;
    }

    @media only screen and (max-width: 991px) {
        .card {
            text-align: center;
        }
    }
</style>