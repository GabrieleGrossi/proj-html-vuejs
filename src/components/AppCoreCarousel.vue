<template>
    <div>
        <img :src="userElement.image" alt="">
    </div>
    <p>
        {{ userElement.text }}
    </p>
    <h3>
        {{ userElement.user }}
    </h3>
</template>
<script>
export default {
    name:'AppCoreCarousel',
    props:{
        userElement: Object
    },
    data(){
        return{

        }
    }
}
</script>
<style lang="scss" scoped>
    
</style>