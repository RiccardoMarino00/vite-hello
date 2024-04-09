<script >
import AppTitle from './components/AppTitle.vue'
export default {
    data(){
        return {
            message:'Ciao mondo'
        }
    },
    mounted(){
        console.log('mounted')
    },   
    components: {
        AppTitle
    },
}
</script>

<template>
    <div>{{ message }}</div>

  <AppTitle />
</template>

<style scoped>

</style>
