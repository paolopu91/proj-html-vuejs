
<!-- html of my project -->
<template>
    <!-- div container of all my components -->
    <div class="header-section">
        <div class="container-fluid">

            <div class="row d-flex">
                <!-- col-left -->
                <!-- here i will use logo text and buttons -->
                <div class="col-4 my-left-col">
                    <div class="mt-3">
                        <img class="logoHeader" src="../../public/images/logotype.png" alt="">
                    </div>
                    <div class="d-flex flex-column position-absolute my-title-header">

                        
                        <h6 class="d-flex">
                            <div class="line me-3"></div>
                            ALWAYS THE BEST WAY YOU NEED IT
                        </h6>

                        <h1>
                            THE BEST BUSINESS CONSULTING
                        </h1>

                        <!-- container button header -->
                        <div class="mt-5">
                            <button class="header-button px-4 py-2">
                                READ MORE
                            </button>

                            <span class="mx-5 header-button-play">
                                <i class="change-color fa-solid fa-play"></i>
                            </span>

                        </div>
                    </div>
                </div>


                <!-- col-right -->
                <!-- here i will use image and nav link -->
                <div class="col-8 my-right-col">
                    
                    <!-- image of my col right -->
                    <img class="imageHeader" src="../../public/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg" alt="">

                    <!-- my nav links -->
                    <!-- i will stamp this with v-for  -->
                    <div>
                        <ul class="list-unstyled my-nav-links d-flex mt-4">
                            <li class="px-2 " v-for="(link,i) in getNavLink" :key="i">
                                <a class="color-text-nav-link nav-link" href="#">{{link.name}}</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>    
        </div>
    </div>
   
    
</template>

<!-- vuejs -->
<script>
import {state} from "../store";

export default{
    data(){
        return{
            name:"The Header",
            // navLinks:[
            //     {
            //         name:"HOME"
            //     },
            //     {
            //         name:"ABOUT"
            //     },
            //     {
            //         name:"PROJECT"
            //     },
            //     {
            //         name:"SERVICES"
            //     },
            //     {
            //         name:"BLOG"
            //     },
            //     {
            //         name:"CONTACT"
            //     },
            // ]
        }
    },
    computed:{
        getNavLink(){
            return state.navLink
        }
    }
    
}
</script>



<!-- styles css/scss -->
<style lang="scss" scoped>
.header-section{
    background-color: #242340;
    height: 100vh;
}
.logoHeader{
    width: 150px;
}
.my-left-col{
    height: 100vh;
}
.my-right-col{
    padding-right: 0;
    height: 100vh;
}
.imageHeader{
   width: 100%;
   height: 100%;
}
.my-nav-links{
    position: absolute;
    top: 0;
    right: 50px;
    z-index: 999;
    font-size: 15px;
}
.line{
    border-bottom: 5px solid #39FFBF;
    width: 50px;
}
.my-title-header{
    margin-top: 10rem;
}
h1{
    font-size: 5.5rem;
    padding-right: 20rem;
}
.header-button{
    background-color: #39FFBF;
    font-size: 20px;
    border-style: none;

    &:hover{
        background-color: #21e9a9;
    }
}
.color-text-nav-link{
        color: white;

        &:hover{
            color: black;
        }
    }
.change-color{
    color: #39FFBF;
}
.header-button-play{
    border: 1px solid white;
    padding: .5rem .7rem;
    border-radius: 100%;
}
</style>