<template>
    <section class="jumbo">
        <div class="flex">
            <div class="counter-box-container">
                <div>
                    <i class="fa-solid fa-suitcase fa-2xl"></i>
                    <h2>
                        3534
                    </h2>
                </div>
                <div class="counter-box-content">
                    <h3>
                        PLANNING APPLICATIONS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div>
                    <i class="fa-regular fa-building fa-2xl"></i>
                    <h2>
                        896
                    </h2>
                </div>
                <div class="counter-box-content">
                    <h3>
                        COMPLETED PROJECTS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div>
                    <i class="fa-solid fa-users fa-2xl"></i>
                    <h2>
                        172
                    </h2>
                </div>
                <div class="counter-box-content">
                    <h3>
                        TRAINED PROFESSIONALS
                    </h3>
                </div>
            </div>
            <div class="counter-box-container">
                <div>
                    <i class="fa-solid fa-globe fa-2xl"></i>
                    <h2>
                        19
                    </h2>
                </div>
                <div class="counter-box-content">
                    <h3>
                        INTERNATIONAL OFFICES
                    </h3>
                </div>
            </div>
        </div>
    </section>
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
    .counter-box-content{
        color: white;
        margin-top: 1.5rem;
    }
    
</style>