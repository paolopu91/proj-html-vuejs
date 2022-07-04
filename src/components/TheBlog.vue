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
                        <div class="position-absolute text-primary bg-danger">
                            <div>
                                
                            </div>
                        </div> 
                    </div>
                    
                </div>
                <div class="col">
                    <img class="w-100" src="../../public/images/startup-business-people-and-strategy-board-PAJ3P9K-1390x1042.jpg" alt="">
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

<style scoped>
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
</style>