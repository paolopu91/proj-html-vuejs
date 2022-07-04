
<!-- html of my project -->
<template>
    <!-- div container of all my components -->
    <div>
        <!-- qui andrà il mio footer della pagina -->
        <div class="container d-flex justify-content-between mb-5 mt-5">
            <div>
                <!-- logo -->
                <img src="../../public/images/logotype-2-139x23.png" alt="">
            </div>
            <div>
                <!-- link -->
                <a class="link-footer" href="#">HOME</a>
                <a class="link-footer" href="#">ABOUT</a>
                <a class="link-footer" href="#">PROJECTS</a>
                <a class="link-footer" href="#">SERVICES</a>
                <a class="link-footer" href="#">BLOG</a>
                <a class="link-footer" href="#">CONTACT</a>
            </div>
            <div class="d-flex">
                <!-- socials -->
                <div class="mx-2">
                    <!-- instagram -->
                    <i class="fa-brands fa-instagram"></i>
                </div>
                <div class="mx-2">
                    <!-- linkedin -->
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
                <div class="mx-2">
                    <!-- facebook -->
                    <i class="fa-brands fa-facebook-f"></i>
                </div>
                <div class="mx-2">
                    <!-- twitter -->
                    <i class="fa-brands fa-twitter"></i>
                </div>
            </div>
        </div>

        <div class="container footer-line"></div>

        <div class="container d-flex justify-content-between mt-5">
            <div>
                <span>Terme of use</span>
                <span>Privacy Environmental Policy</span>
            </div>
            <div>

                <span>
                    Copyright <span><i class="fa-solid fa-copyright"></i></span> 2020 Phlox Consulting. All Rights Reserved. <span class=""><i class="fa-solid fa-arrow-up"></i></span> <span class=""><i class="fa-solid fa-comment"></i></span> 
                </span>

            </div>
        </div>
    </div>
</template>

<!-- vuejs -->
<script>
export default{
    data(){
        return{
            name:"The Footer",
        }
    },
    
}
</script>

<!-- styles css/scss -->
<style scoped>
.footer-line{
    text-align: center;
    border-bottom: 3px solid rgb(155,155,155);
    width: 100%;
}
.link-footer{
    text-decoration: none;
    color: rgb(155,155,155);
    font-size: 15px;
    margin: 0 1rem;
}
</style>