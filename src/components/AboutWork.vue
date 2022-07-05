<template>
    <div>
        <div class="margin-top my-container text-center">

            <img class="w-100" src="../../public/images/business-people-working-together-on-project-and-B3MZ4TX.jpg" alt="">

            <div class="container-text-about-work">

                    
                    <h2>
                        LET'S TALK ABOUT WORK
                    </h2>

                    <div class="px-4">
                        <p>
                        A wonderfull serenity has taken possession far far 
                        away, behind the word mountains
                        </p>
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
    date(){
        return{
            name:"About Work"
        }
    }
}
</script>

<style lang="scss" scoped>
.margin-top{
    margin-top:15rem;
}
.my-container{
    position: relative;
    right: 0;
    left: 0;
    margin-bottom: 4rem;
    .container-text-about-work{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        margin-top: 1rem;
        padding-left: 5rem;
        padding-right: 5rem;
    }
    button{
        background-color: #242340;
        border: none;
        padding: .7rem 2rem;
        color:white;
        font-size: 20px;

        &:hover{
            background-color: #1d1c30;
        }
    }
}
</style>