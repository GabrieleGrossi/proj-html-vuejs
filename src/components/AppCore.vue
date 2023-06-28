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
    <section class="img-bk">
        <div class="carousel">
            <h1>
                QUI ANDRà IL CAROSELLO MALEDETTO
            </h1>
            <AppCoreCarousel v-for="imgObj in imageList"
                :userElement="imgObj"/>
        </div>
    </section>
    <section>
        <div class="w-85">
            <h1>
                Latest News
            </h1>
            <div class="separator"></div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora iusto dolorem veritatis aut, nostrum minima asperiores veniam id voluptas obcaecati provident necessitatibus commodi perferendis. Recusandae cumque ratione provident aspernatur officia?</p>
        </div>
        <div class="w-90 flex">
            <div class="card">
                <img src="../assets/images/blog-post-134132600-400x241.jpg" alt="">
                <h2>
                    Redeveloping Florida's Remote Southern Coast
                </h2>
                <h5>
                    December 7th, 2015
                </h5>
                <div class="separator"></div>
                <p>
                    Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed
                </p>
            </div>
            <div class="card">
                <img src="../assets/images/blog-post-92486644-400x241.jpg" alt="">
                <h2>
                    How We Manage Large Construction Projects
                </h2>
                <h5>
                    December 7th, 2015
                </h5>
                <div class="separator"></div>
                <p>
                    Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed
                </p>
            </div>
            <div class="card">
                <img src="../assets/images/blog-post-332773904-400x241.jpg" alt="">
                <h2>
                    Future proofing a modern home
                </h2>
                <h5>
                    December 6th, 2015
                </h5>
                <div class="separator"></div>
                <p>
                    Technology is Here to Stay Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus purus nisl, elementum vitae consequat at, tristique ut enim. Sed ut dignissim leo. Nullam sed metus id sapien faucibus rhoncus sed
                </p>
            </div>
        </div>
        <div class="flex m-4">
            <div class="separator"></div>
            <button>
                VIEW ALL PROJECTS
            </button>
            <div class="separator"></div>
        </div>
    </section>
</template>
<script>
import AppCoreCarousel from './AppCoreCarousel.vue';
export default {
    name: 'AppCore',
    components:{
        AppCoreCarousel
    },
    data(){
        return{
            imageList: [
                {
                    image: "home-testimonial-113165296.jpg",
                    text: "No man but feels more of a man in the world if he have but a bit of ground that he can call his own. However small it is on the surface, it is four thousand miles deep; and that is a very handsome property",
                    user: "HARRY SMITH • NEW HOME OWNER"
                },
                {
                    image: 'home-testimonial-84268399.jpg',
                    text: "Many novice real estate investors soon quit the profession and invest. When you invest in real estate, you often see a side of humanity that stocks, bonds, mutual funds, and saving money shelter you from.",
                    user: "JOHN DOE • PROPERTY INVESTOR"
                }
            ],
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
    .img-bk{
        background-image: url(../assets/images/home-parallax-144609983.jpg);
        height: 80vh;
        background-size: cover;
        background-position-y: center;
        color: white;
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
        width: 90%;
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
    .card{
        width: calc((100% / 3) - 6.5rem);
        text-align: left;
        background-color: white;
        margin: 0 2rem 0 5rem;
        
    }
    .card img{
        width: 100%;
    }
    .card h2,
    h5,
    p{
        padding: 1rem 2rem;
    }
    .m-4{
        padding: 4rem 0;
    }
    .m-4 .separator{
        border-color: white;
    }
    button{
        background-color: transparent;
        border: 1px solid transparent;
        padding: 1rem 5rem;
        &:hover{
            background-color: #fed03d;
            transition: all 0.5s ease;
        }
    }
</style>