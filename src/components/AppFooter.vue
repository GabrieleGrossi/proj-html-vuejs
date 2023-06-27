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
        <h1>
            ALTRO CAROSELLO BRUTTISSIMO
        </h1>
    </section>
    <section>
        <div class="flex back">
            <div class="building m-0">
                <h1>
                    BUILDING INSPIRING SPACES
                </h1>
                <div class="separator"></div>
                <p>Vivamus Sed Consectetur Tellus Dolor Sit Amet, Consectetur Adipiscing Lorem Elit Sadip Ipsum Ets Ficilis Uns.</p>
            </div>
            <div class="building m-0">
                <button class="get-quote">
                    GET A FREE QUOTE
                </button>
                <h4>
                    Only takes a few seconds
                </h4>
            </div>
        </div>
    </section>
    <footer>
        <div class="flex">
            <div>
                <img src="../assets/images/footer-logo.png" alt="footer logo">
                <p>
                    We are specialists in the construction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.
                </p>
                <button class="get-quote">
                    LEARN MORE
                </button>
            </div>
            <div class="twitter">
                <h1>
                    LATEST TWEETS
                </h1>
                <div>
                    <img src="../assets/images/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="logo avada twitter">
                </div>
            </div>
            <div>
                <h1>
                    CONTACT US TODAY
                </h1>
            </div>
            <div>
                <h1>
                    OUR LOCATION
                </h1>
            </div>
        </div>
        <div class="flex spaced m-0 bkbl">
            <div>
                ©COPYRIGHT 2012 - 2023 | AVADA THEME BY THEMEFUSION | ALL RIGHTS RESERVED | POWERED BY WORDPRESS  
            </div>
            <a>

            </a>
        </div>
    </footer>
</template>
<script>
export default {
    name: 'AppFooter'
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
        background-color: #333333;
    }
    footer h1{
       color: #fed03d;
    }
</style>