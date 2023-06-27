<template>
    <div>
        <AppJumbo/>
        <AppBody/>
        <AppMainSection/>
        <AppCore/>
    </div>
</template>
<script>
import AppJumbo from './AppJumbo.vue';
import AppBody from './AppBody.vue';
import AppMainSection from './AppMainSection.vue';
import AppCore from './AppCore.vue';
export default {
    name: 'AppMain',
    components:{
        AppJumbo,
        AppBody,
        AppMainSection,
        AppCore,
    },
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>