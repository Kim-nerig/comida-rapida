<template>
    <gridlogo>
        <div><img v-bind:src="url" :alt="nombre" align="left" ><h2>{{nombre}}</h2></div>
        
    </gridlogo>
</template>

<script>
import Gridlogo from "./Gridlogo.vue";
    export default{
    props: {
        url: {
            String
        },
        nombre: {
            String
        },
    },
    components: { Gridlogo }
}
</script>

<style scoped>
    img{
        width: 7rem;
        height: 7rem;
        padding: 0.5rem;
        background-color: snow;
    }
    a{
        text-align: center;
    }
</style>