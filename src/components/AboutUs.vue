<template>
<div class="">
    <!-- this is component about us of my page -->
    <div class="container-fluid position-relative">
        <div class="row bg-section-aboutUs">
            <div class="col-8 no-padding-left">
                <img class="w-100" src="../../public/images/business-people-working-together-on-project-and-5FHSKBL.jpg" alt="">
                
            </div>

            <div class="col-4">

                <div class="col-right-text">

                    <div class="d-flex mb-3">
                        <div class="green-line"></div>
                        <span>ABOUT US</span>
                    </div>

                    <h2 class="mb-3">
                        WE MAKE YOUR STRATEGY WORK
                    </h2>
                    
                    <p class="overview-aboutUs">
                        When, while lovelly valley teems with vapour
                        around meand eridian sun strikes the upper
                        impenetrable foliage of my trees, and but a thousand unknown plants
                        are noticed when i hear the buzz of the little world among the stalks, and grow
                        familiar indescribable forms of the insects and flies, then i feel the 
                        presence of the Almighty.
                    </p>
                </div>

                
            </div>
        </div>

        
            <div class="container bg-container-aboutUs no-padding-left">
                <!-- container no left margin -->
                <div class="row">

                    <div class="col-6">
                        <h3 class="p-5 m-5">
                            WE HELP TO DELIVER
                            THE BUSINESS CASE
                        </h3>
                    </div>

                    <div class="col-6">
                        <p class="p-5 m-2 mt-5">
                            When, while lovelly valley teems with vapour around
                            meand meridian sun strikes the upper impenetrable
                            foliage of my trees, and but a thousand unknown
                        </p>
                    </div>
                </div>
                
                <button class="myBtn">
                    GET STARTED
                </button>
            </div>
        
    </div>
</div>
</template>


<script>
export default{
    data(){
        return{
            name:"About Us"
        }
    }
}
</script>


<style lang="scss" scoped>
.bg-section-aboutUs{
    background-color: #242340;
}
.no-padding-left{
    padding-left: 0;
}
.bg-container-aboutUs{
    background-color:  #39ffbf;
    position: relative;
    left: -40px;
}
.myBtn{
    position: absolute;
    bottom: 0;
    right: 0;
    background-color: #f81d39;
    border-style: none;
    padding: .5rem 2rem;
    color: white;

}
.green-line{
    border-bottom: 5px solid #39FFBF;
    width: 50px;
    margin-right: 10px;
}
.col-right-text{
    margin-top: 9rem;
}
.overview-aboutUs{
    font-size: 15px;
    color: rgb(155, 155, 155);
}
</style>