<template>
    <section class="jumbo">
        <div class="flex">
            <div class="counter-box-container">
                <div class="counter-box-info">
                    <i class="fa-solid fa-suitcase fa-2xl"></i>
                    <h1>
                        3534
                    </h1>
                </div>
                <div class="counter-box-content">
                    <h3>
                        PLANNING APPLICATIONS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div class="counter-box-info">
                    <i class="fa-regular fa-building fa-2xl"></i>
                    <h1>
                        896
                    </h1>
                </div>
                <div class="counter-box-content">
                    <h3>
                        COMPLETED PROJECTS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div class="counter-box-info">
                    <i class="fa-solid fa-users fa-2xl"></i>
                    <h1>
                        172
                    </h1>
                </div>
                <div class="counter-box-content">
                    <h3>
                        TRAINED PROFESSIONALS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div class="counter-box-info">
                    <i class="fa-solid fa-globe fa-2xl"></i>
                    <h1>
                        19
                    </h1>
                </div>
                <div class="counter-box-content">
                    <h3>
                        INTERNATIONAL OFFICES
                    </h3>
                </div>
            </div>
        </div>
    </section>
    <div class="w-85 mt-1">
        <h2>
            Explore Recent Work
        </h2>
        <div class="separator">
        </div>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem commodi placeat dolor, nobis aspernatur, cupiditate quasi repellat dolores, ipsam vero temporibus quaerat fugit atque labore perspiciatis? Labore, nostrum fugiat! A.
        </p>
    </div>
    <div class="flex">
        <div class="img-card">
            <img src="../assets/images/project2-featured-15013609-400x400.jpg" alt="">
        </div>
        <div class="img-card">
            <img src="../assets/images/project1-featured-294276386-400x400.jpg" alt="">
        </div>
        <div class="img-card">
            <img src="../assets/images/project3-featured-189023420-400x400.jpg" alt="">
        </div>
    </div>
    <div class="flex m-4">
        <div class="separator"></div>
        <button>
            VIEW ALL PROJECTS
        </button>
        <div class="separator"></div>
    </div>
</template>
<script>
export default {
    name: 'AppMainSection',
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
@use '../styles/general.scss';
    section{
        background-image: url(../assets/images/home-244125289.jpg);
        height: 650px;        
    }
    .jumbo{
        display: flex;
    }
    .flex{
        display: flex;
        text-align: center;
        align-items: center;
        width: 80%;
        margin: 0 auto;
    }
    .counter-box-container{
        width: calc(100%/4);
        margin-top: 1.5rem;
        color: #fed03d;
    }
    .counter-box-info i{
        font-size: 120px;
        margin-bottom: 4.5rem;
    }
    .counter-box-content{
        color: white;
        margin-top: 1.5rem;
    }
    .w-85 h1,
    p{
        margin: 2.5rem 0;
    }
    h1{
        font-size: 50px;
    }
    .img-card{
        height: 100%;
        margin: 0 1rem;
        
    }
    button{
        background-color: white;
        border: 1px solid white;
        padding: 1rem 5rem;
        &:hover{
            background-color: #fed03d;
            transition: all 0.5s ease;
        }
    }
    .separator{
        border: 1px solid lightgray;
        width: 25%;
    }
    .m-4{
        margin-top: 4rem;
        margin-bottom: 4rem;
    }
</style>