
<!-- html of my project -->
<template>
    <!-- div container of all my components -->
    <div>
        <div class="container-fluid">

            <div class="row row-cols-2">
                <!-- col-left -->
                <!-- here i will use logo text and buttons -->
                <div class="col flex-grow-1">
                    <img class="logoHeader" src="../../public/images/logotype.png" alt="">
                </div>


                <!-- col-right -->
                <!-- here i will use image and nav link -->
                <div class="col">
                    <!-- image of my col right -->
                    <img class="imageHeader" src="../../public/images/portrait-of-young-architect-woman-on-meeting-KFZCE3A.jpg" alt="">

                    <!-- my nav links -->
                    <!-- i will stamp this with v-for  -->
                    <div>

                        <ul class="list-unstyled my-nav-link d-flex">

                            <li>
                                <a href="">HOME</a>
                            </li>
                            <li>
                                <a href="">ABOUT</a>
                            </li>
                            <li>
                                <a href="">PROJECTS</a>
                            </li>
                            <li>
                                <a href="">SERVICES</a>
                            </li>
                            <li>
                                <a href="">BLOG</a>
                            </li>
                            <li>
                                <a href="">CONTACT</a>
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
        }
    },
    
}
</script>

<!-- styles css/scss -->
<style scoped>
.logoHeader{
    width: 100px;
}
.imageHeader{
   width: 100%;
}
.my-nav-link{
    position: absolute;
    top: 0;
    right: 50px;
    z-index: 999;
}
</style>