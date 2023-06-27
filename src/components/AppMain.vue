<template>
    <div>
        <AppJumbo/>
        <AppBody/>
        <AppMainSection/>
    </div>
</template>
<script>
import AppJumbo from './AppJumbo.vue';
import AppBody from './AppBody.vue';
import AppMainSection from './AppMainSection.vue';
export default {
    name: 'AppMain',
    components:{
        AppJumbo,
        AppBody,
        AppMainSection
    },
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>