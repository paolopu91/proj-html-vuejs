<template>

    <div>
        <!-- container for my title and subtitle -->
        <div class="container margin-top">

            <div class="text-center">

                <span class="text-center">TESTIMONIALS</span>

            </div>
            
            <div class="d-flex justify-content-end mb-4">
                <div class="line"></div>
            </div>
            <!-- in this div I put the title moved to the right with d-flex -->
            <div class="d-flex justify-content-end">

                <div class="title-testimonials">
                    <h2>
                    WHAT'S THE CUSTOMER SAY
                    <span class="align-text">ABOUT OUR WORK</span> 
                    </h2>
                </div>
                
            </div>

        </div>
        
        <!-- container for testimonials -->
        <div class="container bg-white ">

                <div class="row">

                    <!-- testimonal 1 -->
                    <div class="col">
                        <div class="py-5 px-3 ">
                            <p class="testimonial-review">
                                When,while lovely valley teems with vapour
                                around meand eridian sun strikes the upper impenetrable foliage of my trees,
                                and but a thousand unknown plants are noticed by when i hear the buzz of the little.
                            </p>

                            <h5 class="name-testimonial">
                                Vera Duncan
                            </h5>

                            <span class="company">
                                Amazon Inc.
                            </span>
                        </div>
                    </div>

                    <!-- testimonial 2 -->
                    <div class="col">
                        <div class="py-5 px-3 ">
                            <p class="testimonial-review">
                                When,while lovely valley teems with vapour
                                around meand eridian sun strikes the upper impenetrable foliage of my trees,
                                and but a thousand unknown plants are noticed by when i hear the buzz of the little.
                            </p>

                            <h5 class="name-testimonial">
                                Vera Duncan
                            </h5>

                            <span class="company">
                                Amazon Inc.
                            </span>
                        </div>
                    </div>

                    <!-- testimonal 3 -->
                    <div class="col">
                        <div class="py-5 px-3 ">
                            <p class="testimonial-review">
                                When,while lovely valley teems with vapour
                                around meand eridian sun strikes the upper impenetrable foliage of my trees,
                                and but a thousand unknown plants are noticed by when i hear the buzz of the little.
                            </p>

                            <h5 class="name-testimonial">
                                Vera Duncan
                            </h5>

                            <span class="company">
                                Amazon Inc.
                            </span>
                        </div>
                    </div>

                </div>
        </div>
    </div>  

</template>



<script>
export default{
    data(){
        return{
            name:"The Testimonials"
        }
    },
}
</script>

<style lang="scss" scoped>
.margin-top{
    margin-top:7rem;
}
.line{
    border-bottom: 5px solid #39FFBF;
    width: 50px;
}
.title-testimonials{
    width:530px;
    text-align: right;
}
.bg-white{
    background-color: white;
}
.testimonial-review{
    color: rgb(155,155,155);
    font-size: 15px;
}
.name-testimonial{
    color: black;
}
.company{
    color:rgb(155,155,155);
    font-size: 15px;
}
</style>