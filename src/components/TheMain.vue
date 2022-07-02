
<!-- html of my project -->
<template>

    <div>
        <!-- div container of all my components -->
        <div class="section no-padding-right">
            <div class="container-fluid no-padding-right padding-top-info-container">
                <h5 class="d-flex">
                    OUR CONSULTANTS CAN HELP YOU
                    <div class="line-first-section ms-2"></div>
                </h5>
                

                <!-- container info -->
                <div class="container mt-5">
                    <div class="row row-cols-2">
                        <div class="col-6">
                            <div class="d-flex mb-5">
                                <div class="col-2">
                                    <span class="logo-info">
                                        <i class="size-logo fa-solid fa-chart-line"></i>
                                    </span>
                                </div>

                                <div class="col-10">
                                    <h6 class="title-info">
                                        STATISTICAL CONSULTING
                                    </h6>

                                    <p class="overview-info">
                                        When, while lovelly valley teems with vapour
                                        around meand eridian sun strikes the upper
                                        impenetrable foliage of my trees, and but a
                                    </p>
                                </div>
                            </div>    
                        </div>
                        
                        <div class="col-6">
                            <div class="d-flex mb-5">
                                <div class="col-2">
                                    <span class="logo-info">
                                        <i class="size-logo fa-solid fa-bullhorn"></i>
                                    </span>
                                </div>

                                <div class="col-10">
                                    <h6 class="title-info">
                                        DIGITAL CONSULTING
                                    </h6>

                                    <p class="overview-info">
                                        When, while lovelly valley teems with vapour
                                        around meand eridian sun strikes the upper
                                        impenetrable foliage of my trees, and but a
                                    </p>
                                </div>
                            </div>    
                        </div>
                        <div class="col-6">
                            <div class="d-flex mb-5">
                                <div class="col-2">
                                    <span class="logo-info">
                                        <i class="size-logo fa-solid fa-wallet"></i>
                                    </span>
                                </div>

                                <div class="col-10">
                                    <h6 class="title-info">
                                        BANKING CONSULTING
                                    </h6>

                                    <p class="overview-info">
                                        When, while lovelly valley teems with vapour
                                        around meand eridian sun strikes the upper
                                        impenetrable foliage of my trees, and but a
                                    </p>
                                </div>
                            </div>    
                        </div>

                        <div class="col-6">
                            <div class="d-flex mb-5">
                                <div class="col-2">
                                    <span class="logo-info">
                                        <i class="size-logo fa-solid fa-bullseye"></i>
                                    </span>
                                </div>

                                <div class="col-10">
                                    <h6 class="title-info">
                                        ENTERPRISE CONSULTING
                                    </h6>

                                    <p class="overview-info">
                                        When, while lovelly valley teems with vapour
                                        around meand eridian sun strikes the upper
                                        impenetrable foliage of my trees, and but a
                                    </p>
                                </div>
                            </div>    
                        </div>


                    </div>

                </div>
            </div>
            
        </div>
        <!-- component about us -->
            <AboutUs></AboutUs>
    </div>

</template>

<!-- vuejs -->
<script>
import AboutUs from './AboutUs.vue'
export default{
    data() {
        return {
            name: "The Main",
        };
    },
    components: { AboutUs }
}
</script>

<!-- styles css/scss -->
<style lang="scss" scoped>
.section{
    background-color: white;
    color: black;
    padding: 3rem;
    height: 95vh;
}
.padding-top-info-container{
    padding-top: 6rem;
}
.no-padding-right{
    padding-right: 0;
}
.line-first-section{
    margin-bottom: 15px;
    border-bottom: 5px solid #39FFBF;
    width: 67%;
    vertical-align: middle;
}
.logo-info{
    text-align: center;
    border: 1px solid black;
    border-radius: 100%;
    background-color: #F81D39;
    padding: 1rem;
    color: white;
}
.size-logo{
    font-size: 30px;
    vertical-align: text-top;
}
.title-info{
    margin-left: 6rem;
    color: #242340;
}
.overview-info{
    padding-left: 6rem;
    padding-right: 6rem;
    font-size: 15px;
    color: rgb(155, 155, 155);
}

</style>