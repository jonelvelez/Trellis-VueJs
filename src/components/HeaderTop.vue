<template>
    <b-navbar toggleable="lg" type="dark" variant="info">
        <b-container>
            <b-navbar-brand href="#">
                <b-img class="trellis-logo" src="../assets/trellis-logo.jpg"></b-img>
            </b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
            <!-- <b-navbar-nav>
                <b-nav-item href="#">Link</b-nav-item>
                <b-nav-item href="#" disabled>Disabled</b-nav-item>
            </b-navbar-nav> -->

            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto" v-b-scrollspy:nav-scroller>
                <b-nav-item id="1" @click="scrollIntoView" class="menu-item" href="#banner">Home</b-nav-item>
                <b-nav-item id="2" @click="scrollIntoView"  class="menu-item" href="#whatwedo">What we do</b-nav-item>
                <b-nav-item id="3" @click="scrollIntoView"  class="menu-item" href="#ourteam">Our team</b-nav-item>
                <b-nav-item id="4" @click="scrollIntoView" class="menu-item" href="#contactus">Contact</b-nav-item>
            </b-navbar-nav>
            </b-collapse>
        </b-container>
    </b-navbar>
   
</template>

<script >
// import func from '../../vue-temp/vue-editor-bridge';
export default {
    
      //* Scroll Navigation Animation *//
    created () {
        window.addEventListener('scroll', this.handlescroll);
    },
    // computed: {
    //     menuClasses() {
    //         return document.querySelectorAll('.menu-item')
    //     }
    // },
    methods: {
         handlescroll() {
          let TrellisLogo = document.querySelector(".trellis-logo");
            if (window.scrollY > 0){
                TrellisLogo.classList.add("addClassLogo")
            } else {
                TrellisLogo.classList.remove("addClassLogo")
            }
        },
        //   menuClick(){
        //    let menus = this.menuClasses
        //     Array.from(menus).forEach((menu) => {
        //         menu.addEventListener('click', () => {
        //             // let id = menu.getAttribute("id");
        //             let screenHeight = screen.height;
        //             // console.log(id)
        //             // console.log(screenHight)
        //             window.scrollBy(0, screenHeight);
        //             // console.log(id * screenHeight)
        //         });
        //     });
        // }
    },
}
</script>



<style scoped>
    .navbar {
        background-color: #fff !important;
        position: fixed;
        width: 100%;
        z-index: 999999;
    }

    .trellis-logo {
        width: 190px;
        height: auto;
        transition: 0.5s all;
    }

    .navbar-nav li a {
         font-family: Oswald, Helvetica, Arial, Lucida, sans-serif;
         font-size: 18px;
         font-weight: 400;
         color: rgba(0, 0, 0, 0.6) !important;
    }

    .addClassLogo {
        width: 100px;
    }
</style>