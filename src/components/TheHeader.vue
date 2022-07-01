
<!-- html of my project -->
<template>
    <!-- div container of all my components -->
    <div>
        <div class="container-fluid">

            <div class="row d-flex">
                <!-- col-left -->
                <!-- here i will use logo text and buttons -->
                <div class="my-left-col">
                    <div>
                        <img class="logoHeader" src="../../public/images/logotype.png" alt="">
                    </div>
                    <div class="d-flex flex-column position-absolute my-title-header">

                        
                        <h6 class="d-flex">
                            <div class="line mx-2"></div>
                            ALWAYS THE BEST WAY YOU NEED IT
                        </h6>

                        <h1>
                            THE BEST BUSINESS CONSULTING
                        </h1>

                        <!-- container button header -->
                        <div>
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
                <div class="my-right-col">
                    
                    <!-- image of my col right -->
                    <img class="imageHeader" src="../../public/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg" alt="">

                    <!-- my nav links -->
                    <!-- i will stamp this with v-for  -->
                    <div>

                        <ul class="list-unstyled my-nav-links d-flex">

                            <li class="px-2 " v-for="(link,i) in navLinks" :key="i">
                                <a class="text-white nav-link" href="#">{{link.name}}</a>
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
export default{
    data(){
        return{
            name:"The Header",
            navLinks:[
                {
                    name:"HOME"
                },
                {
                    name:"ABOUT"
                },
                {
                    name:"PROJECT"
                },
                {
                    name:"SERVICES"
                },
                {
                    name:"BLOG"
                },
                {
                    name:"CONTACT"
                },
            ]
        }
    },
    
}
</script>



<!-- styles css/scss -->
<style lang="scss" scoped>
.logoHeader{
    width: 150px;
}
.my-left-col{
    width: 30%;
}
.my-right-col{
    width:70%;
    padding-right: 0;
}
.imageHeader{
   width: 100%;
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
    color: black;
    font-size: 20px;
    border-style: none;
}
.change-color{
    color: #39FFBF;
}
.header-button-play{
    border: 1px solid white;
    padding: 1rem;
    border-radius: 50%;
}
</style>