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
                <div class="col position-relative ">
                    <img class="w-100 hoverEffects" src="../../public/images/DRY-1-790x592.jpg" alt="">

                    <!-- div hover -->
                    <div class="dryHover">
                        <img class="w-100 hoverEffects" src="../../public/images/DRY-1-790x592.jpg" alt="">

                        <div class="d-flex justify-content-between align-items-start">
                            <div class="text-project-hover">
                                <h4 class="text-white">
                                Purinky Products
                                </h4>
                                <span class="">
                                    Uncategorized
                                </span>
                                
                            </div>
                            
                            <span class="plus-project-hover">
                                <i class="fa-solid fa-plus"></i>
                            </span>
                        </div>
                    </div>
                </div>
                <!-- image 2 -->
                <div class="col position-relative">
                    <img class="w-100" src="../../public/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg" alt="">

                    <!-- div hover -->
                    <div class="dryHover">
                        <img class="w-100 hoverEffects" src="../../public/images/221bf0b7-8134-43bb-936a-5acbe42db64a-790x592.jpg" alt="">

                        <div class="d-flex justify-content-between align-items-start">
                            <div class="text-project-hover w-100">
                                <h4 class="text-white">
                                Purinky Products
                                </h4>
                                <span class="">
                                    Uncategorized
                                </span>
                            </div>
                            
                            <span class="plus-project-hover">
                                <i class="fa-solid fa-plus"></i>
                            </span>
                        </div>
                    </div>
                </div>
                <!-- image 3 -->
                <div class="col position-relative">
                    <img class="w-100" src="../../public/images/z1el4c4p-790x592.jpg" alt="">
                    
                    <!-- div hover -->
                    <div class="dryHover">
                        <img class="w-100 hoverEffects" src="../../public/images/z1el4c4p-790x592.jpg" alt="">
                        <div class="d-flex justify-content-between">
                            <div class="text-project-hover">
                                <h4 class="text-white">
                                Purinky Products
                                </h4>
                                <span class="">
                                    Uncategorized
                                </span>
                            </div>
                            
                            <span class="plus-project-hover">
                                <i class="fa-solid fa-plus"></i>
                            </span>
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
            name:"The Project"
        }
    }
}
</script>

<style lang="scss" scoped>
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
.hoverEffects:hover{
filter: grayscale(100%) brightness(40%) sepia(100%) hue-rotate(-50deg) saturate(600%) contrast(0.8); 
}
.dryHover{
    position: absolute;
    top:0;
    right: 0;
    bottom:0;
    left: 0;
    opacity: 0;
    
        &:hover{
            opacity: 1;
        }
    }
.text-project-hover{
    position: absolute;
    top: 200px;
}
.plus-project-hover{
    background-color: #888888;
    padding: 0.8rem;
    font-size: 12px;
    opacity: 0.7;
    position: absolute;
    top: 200px;
    right: 0;
}
</style>