<template>
    <div>
        <AppJumbo/>
        <AppBody/>
    </div>
</template>
<script>
import AppJumbo from './AppJumbo.vue';
import AppBody from './AppBody.vue';
export default {
    name: 'AppMain',
    components:{
        AppJumbo,
        AppBody
    },
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>