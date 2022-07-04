<template>
    <div>
        <div class="container margin-top">
            <!-- div of subtitle and line -->
            <div class="d-flex align-items-baseline my-4">
                <div class="line me-3"></div>
                <span>BLOG</span>
            </div>

            <div class="d-flex justify-content-between">
                <h2>THE RECENT NEWS YOU MUST READ IT</h2>
                <button class="button-blog">VIEW ALL</button>
            </div>

            <!-- here i will stamp 2 col with image -->
            <div class="row my-5">
                <div class="col">
                    <div class="position-relative">
                       <img class="w-100" src="../../public/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg" alt="">
                        <div class="container-review-blog bg-white">
                            <div class="row">
                                <div class="col square-blog">
                                    <!-- date and name in red  -->
                                    <span class="date-and-name">
                                        july 4,2019
                                    </span>
                                    <span class="date-and-name">
                                        by paul
                                    </span>
                                    
                                    <!-- title  -->
                                    <h4 class="mt-3 mb-3 title-blog">
                                        Canadian Consulting Firm acquired by UK Giant
                                    </h4>

                                    <!-- text of the blog -->
                                    <p class="mb-3 review-blog">
                                        When,while lovely valley teems with vapour 
                                        around meand eridian sun strikes the upper 
                                        impenetrable foliage of my trees,and but a..
                                    </p>

                                </div>
                            </div>
                        </div> 
                    </div>
                    
                </div>

                <div class="col">
                    <div class="position-relative">
                        <img class="w-100" src="../../public/images/business-people-working-together-on-project-and-5FHSKBL-1390.jpg" alt="">
                        <div class="container-review-blog bg-white">
                            <div class="row">
                                <div class="col square-blog">
                                    <!-- date and name in red  -->
                                    <span class="date-and-name">
                                        july 4,2019
                                    </span>
                                    <span class="date-and-name">
                                        by paul
                                    </span>
                                    
                                    <!-- title  -->
                                    <h4 class="mt-3 mb-3 title-blog">
                                        Canadian Consulting Firm acquired by UK Giant
                                    </h4>

                                    <!-- text of the blog -->
                                    <p class="mb-3 review-blog">
                                        When,while lovely valley teems with vapour 
                                        around meand eridian sun strikes the upper 
                                        impenetrable foliage of my trees,and but a..
                                    </p>

                                </div>
                            </div>
                        </div> 
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
            name:"The Blog"
        }
    },
}
</script>

<style lang="scss" scoped>
.margin-top{
    margin-top: 10rem;
}
.line{
    border-bottom: 5px solid #39FFBF;
    width: 50px;
}
.button-blog{
    background-color: #39FFBF;
    border: none;
    padding: .8rem 3rem;
    font-size: 15px;
}
.container-review-blog{
    position: absolute;
    top: 300px;
    right: 0;

    .square-blog{
        padding: 1rem;
        max-width: 500px;
        min-width: 300px;
        padding-left: 5rem;
        padding-right: 5rem;
        
    }
    .date-and-name{
        color:#f81d39;
        font-size: 15px;
    }
    .title-blog{
        color: black;
        font-size: 22px;
    }
    .review-blog{
        color: rgb(155,155,155);
        font-size: 15px;
    }
}
</style>