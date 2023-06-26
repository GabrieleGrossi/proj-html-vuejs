<template>
    <nav>
        <ul>
            <li v-for="link in navbar" :class="link.active ? 'active':''">
                <a :href="link.link">
                    {{ link.text }}
                </a>
            </li>
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
     @use '../styles/general.scss';

nav ul{
    display: flex;
    flex-direction: row;
}
a{
    padding: 1rem;
    &.active,
    &:hover{
        color: #fed03d;
        transition:all 0.5s ease-in-out;
    }
}
</style>