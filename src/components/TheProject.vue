<template>
    <div>
        <div class="container margin-top mb-5">
            <div class="container-subtitle d-flex mb-3">
                <!-- this is the little green line -->
                <div class="line me-3"></div>
                <!-- this is the subtitle -->
                <span>PROJECT</span>
            </div>

            <!-- this is div container my title -->
            <div class="mb-3 d-flex justify-content-between">

                <div class="title-project">
                    <h2 class="align-text">
                        OUR EXPERT TRUST CONSULTANTS
                        HELP CLIENTS
                    </h2>
                </div>

                <div>
                    <!-- left arrow -->
                    <span class="me-2 bg-arrows">
                        <i class="fa-solid fa-left-long"></i>
                    </span>

                    <!-- right arrow -->
                    <span class="ms-2 bg-arrows">
                        <i class="fa-solid fa-right-long"></i>
                    </span>
                    
                </div>
            </div>

            <!-- this is my div row with 3 cols img -->
            <div class="row mb-5">
                <!-- image 1 -->
                <div class="col">
                    <img class="w-100" src="../../public/images/DRY-1-790x592.jpg" alt="">
                </div>
                <!-- image 2 -->
                <div class="col">
                    <img class="w-100" src="../../public/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg" alt="">
                </div>
                <!-- image 3 -->
                <div class="col">
                    <img class="w-100" src="../../public/images/z1el4c4p-790x592.jpg" alt="">
                </div>
            </div>

        </div>
    </div>
</template>


<script>
export default{
    data(){
        return{
            name:"The Project"
        }
    }
}
</script>

<style scoped>
.title-project{
    width: 650px;
}
.align-text{
    text-align: left;
}
.line{
    border-bottom: 5px solid #39FFBF;
    width: 50px;
}
.container-subtitle{
    align-content: stretch;
    align-items: baseline;
}
.margin-top{
    margin-top: 7rem;
}
.bg-arrows{
    background-color: #888888 ;
    padding: .8rem;
    font-size: 12px;
    opacity: .7;
}
</style>