<template>
    <section>
        <div class="w-50 m-0">
            <h1>
                Trusted Partners
            </h1>
            <div class="separator"></div>
            <p class="mt-1">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Suscipit, doloremque quaerat beatae repellat velit ex tenetur laborum, blanditiis enim accusamus magni expedita nesciunt ducimus accusantium quo, laudantium quisquam numquam ipsum.
            </p>
        </div>
        <div class="flex w-85 m-0">
            <div class="card" v-for="imgObj in partners"
                :partnersImg="imgObj">
                <img :src="imgObj.image" alt="">
            </div>
        </div>
    </section>
    <section>
        <div class="flex back">
            <div class="building w-85 m-0">
                <h1>
                    BUILDING INSPIRING SPACES
                </h1>
                <div class="separator"></div>
                <p class="mt-1">Vivamus Sed Consectetur Tellus Dolor Sit Amet, Consectetur Adipiscing Lorem Elit Sadip Ipsum Ets Ficilis Uns.</p>
            </div>
            <div class="building w-85 m-0">
                <button class="get-quote">
                    GET A FREE QUOTE
                </button>
                <h4 class="mt-1">
                    Only takes a few seconds
                </h4>
            </div>
        </div>
    </section>
    <footer>
        <div class="flex">
            <div class="w-4">
                <img src="../assets/images/footer-logo.png" alt="footer logo">
                <p class="mt-0">
                    We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.
                </p>
                <button class="get-quote mt-0">
                    LEARN MORE
                </button>
            </div>
            <div class="twitter w-4">
                <h1>
                    LATEST TWEETS
                </h1>
                <div>
                    <img src="../assets/images/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="logo avada twitter">
                </div>
            </div>
            <div class="w-4">
                <h1>
                    CONTACT US TODAY
                </h1>
                <div class="flex mt-0">
                    <i class="fa-solid fa-globe"></i>
                    <p>
                        Corporate Location <br>
                        1600 Amphitheatre Parkway <br>
                        London WC1 1BA
                    </p>
                </div>
                <div class="flex mt-0">
                    <i class="fa-solid fa-house-chimney"></i>
                    <p>
                        Residential Location <br>
                        9521 Broadsberry Avenue <br>
                        Paddington RC7 9ZA
                    </p>
                </div>
                <div class="flex mt-0">
                    <i class="fa-solid fa-phone-flip"></i>
                    <p>
                        1.800.458.556 / 1.800.532.2112
                    </p>
                </div>
                <div class="flex mt-0">
                    <i class="fa-solid fa-phone-flip"></i>
                    <p>
                        info@your-domain.com
                    </p>
                </div>
                <div class="flex mt-0">
                    <i class="fa-regular fa-clock"></i>
                    <p>
                        Monday / Friday: 9:00 AM / 6:00 PM
                    </p>
                </div>
                <div class="flex mt-0">
                    <i class="fa-regular fa-clock"></i>
                    <p>
                        Saturday / Sunday: 9:00 AM / 12:00 PM
                    </p>
                </div>
            </div>
            <div class="w-4">
                <h1>
                    OUR LOCATION
                </h1>
            </div>
        </div>
        <div class="flex around m-0 bkbl">
            <div>
                ©COPYRIGHT 2012 - 2023 | AVADA THEME BY THEMEFUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS  
            </div>
            <div class="flex">
                <i class="fa-brands fa-facebook-f"></i>
                <i class="fa-brands fa-youtube"></i>
                <i class="fa-brands fa-twitter"></i>
                <i class="fa-brands fa-instagram"></i>
            </div>
        </div>
    </footer>
</template>


<script>

export default {
    name: 'AppFooter',
    data(){
        return{
            partners: [
                {
                    image: 'home-logo1-219096700-320x202.png'
                },
                {
                    image: 'home-logo2-219096700-320x202.png'
                },
                {
                    image: 'home-logo9-219096700-320x202.png'
                },
                {
                    image: 'home-logo10-219096700-320x202.png'
                },
                {
                    image: 'home-logo11-219096700-320x202.png'
                },
            ]
        }
    }
}

</script>


<style lang="scss" scoped>
@use '../styles/general.scss';
    section{
        text-align: center;
    }
    .separator{
        margin-top: 2rem;
    }
    div.back{
        background-image: url(../assets/images/about-call-to-action-57862405.jpg);
        background-size: cover;
        background-position-y: bottom;
        color: white;
        height: 417px;
    }
    .building{
        align-self: center;
        width: 45%;
        text-align: left;
    }
    .building .separator{
        width: 40%;
        margin-left: 0;
    }
    footer{
        background-color: #1f1f1f;
        color:#8f8f8f;
    }
    footer h1{
       color: #fed03d;
    }
    .card{
        width: calc(100% / 5);
        margin: 5rem 0;
    }
    .card img{
        width: 70%;
    }
    .get-quote{
        width: 200px;
    }
    div.flex i{
        margin-right: 1rem;
    }
</style>