<template>
    <section>
        <h1>
            Our Core Values
        </h1>
        <div class="separator"></div>
        <p class="w-85">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tempora quia similique facilis, soluta quisquam reprehenderit autem ad nam dolore. Accusamus odio non alias necessitatibus odit totam, laboriosam voluptatibus obcaecati saepe.
        </p>
        <div class="flex w-90">
            <div class="box-info">
                <div class="circle water-green">
                    <i class="fa-solid fa-house"></i>
                </div>
                <h4>Great Services</h4>
                <div class="separator"></div>
                <p>
                    Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia
                </p>
            </div>
            <div class="box-info">
                <div class="circle blue">
                    <i class="fa-solid fa-gear"></i>
                </div>
                <h4>Great Services</h4>
                <div class="separator"></div>
                <p>
                    Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia
                </p>
            </div>
            <div class="box-info">
                <div class="circle red">
                    <i class="fa-solid fa-users"></i>
                </div>
                <h4>Great Services</h4>
                <div class="separator"></div>
                <p>
                    Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia
                </p>
            </div>
            <div class="box-info">
                <div class="circle green">
                    <i class="fa-solid fa-lightbulb"></i>
                </div>
                <h4>Great Services</h4>
                <div class="separator"></div>
                <p>
                    Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia
                </p>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'AppCore',
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    @use "../styles/general.scss";
    section{
        background-color: #f5f5f5;
        margin: 0 auto;
        text-align: center;
        padding-top: 5rem;
    }
    h1{
        font-size: 2rem;
    }
    .box-info{
        width: calc(100% / 4);
        margin: 0 2.5rem;
    }
    .separator{
        margin-top: 2rem;
        margin-bottom: 2rem;
    }
    div.w-90 div.separator{
        width: 13%;
        border-color: lightgrey;
    }
    .circle{
        width: 120px;
        height: 120px;
        border: 1px solid transparent;
        color: white;
        padding: 1rem;
        &:hover{
            background-color: #fed03d;
            transition: 0.8s all ease-in-out;
        }
        & i{
            font-size: 55px;
        }
    }
    .w-85{
        width: 60%;
    }
    .w-90{
        width: 80%;
        margin: 0 auto;
        margin-top: 3rem;
    }
    .water-green{
        background-color: #21a6b5;
    }
    .blue{
        background-color: #517ad2;
    }
    .red{
        background-color: #fe813e;
    }
    .green{
        background-color: #84cb01;
    }
</style>