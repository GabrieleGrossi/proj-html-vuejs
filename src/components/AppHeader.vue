<template>
    <header>
        <section class="flex spaced">
            <img src="../assets/images/construction_logo.png" alt="Avada Construction Logo">
            <AppNavbar/>
        </section>
    </header>
</template>
<script>
import AppNavbar from './AppNavbar.vue';
export default {
    name: 'AppHeader',
    components: {
        AppNavbar
    },
    data(){
        return{
            
        }
    }
}
</script>
<style lang="scss" scoped>
   
</style>