<template>
    <section>
        <div class="w-85">
            <h2>
                Specialists In Modern Construction
            </h2>
            <div class="separator">

            </div>
            <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corporis nobis ipsa pariatur fuga iure quam, ut numquam tenetur, reprehenderit nihil dolorum quod velit ipsam soluta, assumenda quasi officiis magnam. Quis.
            </p>
        </div>
        <div class="flex card-section">
            <div class="card">
                <div class="card-inner">
                    <div class="card-front">
                        <div class="circle">
                            <i class="fa-regular fa-building"></i>
                        </div>
                        <h2>
                            Buildings
                        </h2>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum. 
                        </p>
                    </div>
                    <div class="card-back">
                        <h3>
                            Artfully Crafted
                        </h3>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum.
                        </p>
                        <button class="get-quote">GET A QUOTE</button>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-inner">
                    <div class="card-front">
                        <div class="circle">
                            <i class="fa-solid fa-arrows-rotate"></i>
                        </div>
                        <h2>
                            Renovate
                        </h2>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum. 
                        </p>
                    </div>
                    <div class="card-back">
                        <h3>
                            Freshly New
                        </h3>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum.
                        </p>
                        <button class="get-quote"> GET A QUOTE</button>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-inner">
                    <div class="card-front">
                        <div class="circle">
                            <i class="fa-solid fa-house"></i>
                        </div>
                        <h2>
                            Construct
                        </h2>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum. 
                        </p>
                    </div>
                    <div class="card-back">
                        <h3>
                            Perfect Lines
                        </h3>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum.
                        </p>
                        <button class="get-quote">GET A QUOTE</button>
                    </div>
                </div>
            </div>

            <div class="card">
                <div class="card-inner">
                    <div class="card-front">
                        <div class="circle">
                            <i class="fa-solid fa-truck"></i>
                        </div>
                        <h2>
                            Exclusive
                        </h2>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum.
                        </p>
                    </div>
                    <div class="card-back">
                        <h3>
                            Planning
                        </h3>
                        <p>
                            Quis autem vel eum iure reprederit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum.
                        </p>
                        <button class="get-quote">GET A QUOTE</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
        
</template>
<script>
export default {
    name: 'AppBody',
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
@use '../styles/general.scss';
   div.w-85 h2{
    margin-bottom: 2rem;
   }
   div.w-85 p{
    margin-top: 2rem;
   }
   .card-section{
    width: 90%;
    margin: 5rem auto;
   }
   .card{
    height: 300px;
    width: calc((100% / 4) - 2rem);
    background-color: #f5f5f5;
    margin: 0 auto;
    border-radius: 15px;
    text-align: center;
    perspective: 1000px;
   }
   .card-inner{
    position: relative;
    width: 100%;
    height: 100%;
    margin: 0 auto;
    border-radius: 15px;
    text-align: center;
    transition: transform 0.2s;
    transform-style: preserve-3d;
   }
   .card:hover .card-inner{
    transform: rotateY(180deg);
    background-color: #fed03d;
   }
   .card-front, .card-back {
    position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden;
    }

    .card-back{
    transform: rotateY(180deg);
    }
    .card-back h3, button{
        margin-top: 4rem;
    }
    .card-back button{
        background-color: white;
    }
    div.circle i{
    font-size: xx-large;
   }
   div.card p{
    padding-top: 1rem;
   }
</style>