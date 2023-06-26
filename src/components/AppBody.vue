<template>
    <section>
        <div class="w-85">
            <h2>
                Specialist In Modern Construction
            </h2>
            <div class="separator">

            </div>
            <p>
                Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corporis nobis ipsa pariatur fuga iure quam, ut numquam tenetur, reprehenderit nihil dolorum quod velit ipsam soluta, assumenda quasi officiis magnam. Quis.
            </p>
        </div>
        <div class="flex card-section">
            <div class="card">
                <div class="circle">
                    <i class="fa-regular fa-building"></i>
                </div>
                <h2>
                    Buildings
                </h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quas, laborum perspiciatis. 
                </p>
            </div>

            <div class="card">
                <div class="circle">
                    <i class="fa-solid fa-arrows-rotate"></i>
                </div>
                <h2>
                    Renovate
                </h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quas, laborum perspiciatis. 
                </p>
            </div>

            <div class="card">
                <div class="circle">
                    <i class="fa-solid fa-house"></i>
                </div>
                <h2>
                    Construct
                </h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quas, laborum perspiciatis. 
                </p>
            </div>

            <div class="card">
                <div class="circle">
                    <i class="fa-solid fa-truck"></i>
                </div>
                <h2>
                    Exclusive
                </h2>
                <p>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quas, laborum perspiciatis. 
                </p>
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
   div.w-85 h2{
    margin-bottom: 2rem;
   }
   .separator{
    width: 35%;
    border: 1px solid #fed03d;
    margin: 0 auto;
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
    padding: 0 1rem;
    margin: 0 auto;
    border-radius: 15px;
    text-align: center;
   }
   .circle{
    width: 75px;
    height: 75px;
    border-radius: 50%;
    border: 1px solid black;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 2rem auto;
   }
   div.circle i{
    font-size: xx-large;
   }
   div.card p{
    padding-top: 1rem;
   }
</style>