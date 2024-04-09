<script>
export default {
    data(){
        return {
            title:'La mia prima app con Vite'
        }
    },
    mounted(){
        console.log('mounted')
    },
}
</script>

<template>
    <div class="contenitore">
        <h1>{{title}}</h1>
    </div>
</template>

<style>
body{
    font-family: sans-serif;
    height: 100vh;
    position: relative;
}

.contenitore{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>