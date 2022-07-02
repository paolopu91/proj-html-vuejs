<template>
<div class="">
    <!-- this is component about us of my page -->
    <div class="container-fluid">
        <div class="row bg-section-aboutUs">
            <div class="col-8 no-padding-left">
                <img class="w-100" src="../../public/images/business-people-working-together-on-project-and-5FHSKBL.jpg" alt="">
                
            </div>

            <div class="col-4">
                ciao universo
            </div>
        </div>


        
    </div>

    <div class="container-fluid">
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
            <button>
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


<style scoped>
.bg-section-aboutUs{
    background-color: #242340;
}
.no-padding-left{
    padding-left: 0;
}
.bg-container-aboutUs{
    background-color:  #39ffbf;
    position: absolute;
    left: 0;
}
</style>