<template>
    <nav class="flex spaced">
        <img src="../assets/images/construction_logo.png" alt="Avada Construction Logo">
        <ul>
            <li v-for="link in navbar" :class="link.active ? 'active':''">
                <a :href="link.link">
                    {{ link.text }}
                </a>
            </li>
            <button class="get-quote">
                GET QUOTE
            </button>
        </ul>
    </nav>
</template>
<script>
export default {
    name: 'AppNavbar',
    data(){
        return{
            navbar:[
                {
                    link: '#',
                    text: 'HOME',
                    active: true
                },
                {
                    link: '#',
                    text: 'ABOUT',
                    active: false
                },
                {
                    link: '#',
                    text: 'SERVICES',
                    active: false
                },
                {
                    link: '#',
                    text: 'WORK',
                    active: false
                },
                {
                    link: '#',
                    text: 'ARTICLES',
                    active: false
                },
            ]
        }
    }
}
</script>
<style lang="scss" scoped>
     @use '../styles/general';
nav{
    margin: 2rem 5rem;
}
nav ul{
    display: flex;
    flex-direction: row;
}
.active{
    color: #fed03d;
}
a{
    padding: 3.5rem 1.5rem;
    &.active,
    &:hover{
        color: #fed03d;
        transition:all 0.5s ease-in-out;
    }
}
.get-quote{
    background-color: #fed03d;
    border: 1px solid #fed03d;
    padding: 1rem;
    height: 45px;
    width: 160px;
    align-self: center;
    &:hover{
        background-color: black;
        color: white;
        transition: all 0.5s ease-in-out;
    }
}
</style>