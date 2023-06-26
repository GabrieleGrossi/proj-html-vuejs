<template>
    <div class="jumbo flex">
        <div class="jumbo-info">
            <h1>
                BUILDING INSPIRING SPACED
            </h1>
            <h3>
                We Build Inspiring Residential & Commercial Spaces
            </h3>
            <button class="black-btn">
                EXPLORE RECENT WORK
            </button>
            <button class="yellow-btn">
                GET A QUOTE TODAY
            </button>
        </div>
    </div>
    <div class="helper flex column">
        <h2>
            Do You Have A Construction Project We Can Help Whit?
        </h2>
        <button class="btn-help">
                GET A FREE QUOTE
        </button>
    </div>
</template>

<script>
export default {
    name: 'AppJumbo',
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    div.jumbo{
        background-image: url(../assets/images/home-slider-62528242.jpg);
        height: 710px;
        padding-top: 130px;
    }
    .jumbo-info{
        margin: 0 auto;
        align-self: center;
        text-align: center;
    }
    div.jumbo-info h1{
        color: white;
        font-size: 70px;
        font-weight: bold;
    }
    div.jumbo-info h3{
        color: #fed03d;
        font-size: 30px;
        margin: 2rem;
    }
    button{
        padding: 1rem 2rem;
        margin: 1rem;
    }
    .black-btn{
        border: 1px solid #333333;
        background-color: #333333;
        color: white;
        &:hover{
            border: 1px solid #fed03d;
            background-color: #fed03d;
            color: #333333;            
            transition:all 0.5s;
        }
    }
    .yellow-btn{
        border: 1px solid #fed03d;
        background-color: #fed03d;
        color:#333333;
        &:hover{
            border: 1px solid #333333;
            background-color: #333333;
            color: white;
            transition:all 0.5s;
        }
    }
    .helper{
        position: relative;
        background-color: #fed03d;
        color: #333333;
        height: 150px;
        justify-content: center;
        align-items: center;
    }
    .btn-help{
        position: absolute;
        top: 125px;
        margin: 0 auto;
        background-color: #333333;
        border: 1px solid white;
        color: white;
        padding: 1rem 2rem;
        &:hover{
            background-color: white;
            color: #333333;
            border: 1.5px solid #333333;
            transition: all 0.5s;
        }
    }
</style>