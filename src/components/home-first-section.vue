<template>
    <div class="home-first-section">
        <b-container>
            <b-row>
                <b-col cols="12" class="text-center">
                    <h2>SCALING IS HARD</h2>
                    <div class="divider"></div>
                    <p>When you’re a 10-person startup, it’s all hands on deck to get stuff done. Alignment, communication, collaboration and culture emerge naturally and almost invisibly. As your team grows from 10 to 100, you need more processes and controls – OKRs, budgets, org charts, meetings – but these are fairly straightforward. But as you grow from 100 to 1000, maintaining effective leadership, communication, collaboration and the culture you want gets much harder.</p>
                </b-col>
            </b-row>

            <b-row class="pt-5">
                <b-col cols="12 text-center">
                <h3>Six Key Challenges of Scaling</h3>
                    <!-- <p v-for="user in users" :key="user.id">{{user.text}}</p>
                    <b-img v-for="user in users" :key="user.id" :src="user.img"></b-img> -->
                     <!-- <b-img src="../assets/our_team_icon_1.png"></b-img> -->
                </b-col>
            </b-row>

            <b-row class="pt-5">
                <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_1.png"></b-img>
                    <p>Hiring & Intergrating <span class="d-block">Experienced</span> Leader</p>
                </b-col>

                <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_2.png"></b-img>
                    <p>Developing <span class="d-block">a Culture of</span> Accountability</p>
                </b-col>

                <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_3.png"></b-img>
                    <p>Building <span class="d-block">High-Performing</span> Teams</p>
                </b-col>

                 <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_4.png"></b-img>
                    <p><span class="d-block">Helping Founders</span> become Leaders</p>
                </b-col>
                <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_5.png"></b-img>
                    <p>Collaborating <span class="d-block">Across Teams &</span> Departments</p>
                </b-col>
                <b-col col lg="4" md="6" sm="12" class="text-center">
                    <b-img src="../assets/icon_redesign_6.png"></b-img>
                    <p>Scaling the <span class="d-block">Culture</span></p>
                </b-col>
            </b-row>
        </b-container>
    </div>
</template>

<script>

// import json from '@/components/home-first-section.json'

// // import json from '@/components/home-first-section.json';
// export default {

//    data(){
//        return{
//            users: json,
//        };
//    },
// };
 
</script>

<style scoped>
    .home-first-section {
        padding-top: 100px;
        padding-bottom: 100px;
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

    h2 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-size: 50px;
        line-height: 75px;
        color: #ef3922;
        font-weight: 400;
    }

    h3 {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-size: 22px;
        line-height: 75px;
        color: #ef3922;
        font-weight: 700;
    }

    p {
        font-family: 'Oswald',Helvetica,Arial,Lucida,sans-serif;
        font-weight: 500;
        font-size: 20px;
        color: #666666
    }
    
    img {
        padding-bottom: 25px;
        padding-top: 30px;
    }
</style>