<template>
    <grid>
        <img v-bind:src="url" alt="hamburguesa.js">
        <h3>{{ nombre }}</h3>
        <h3>{{ precio }}</h3>
        <h10>{{descripcion}}</h10>
        <br>
        <br>
        <a href="texto" target="_blank" >Comprar</a>
    </grid>

</template>

<script>
    import Grid from "./Grid.vue";
    export default {
    props: {
        url: {
            String,
        },
        nombre: {
            String,
        },
        precio: {
            String,
        },
        descripcion: {
            String,
        },
    },
    components: { Grid }
};
</script>

<style scoped>
    img {
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background-color: snow;
    }
    a {
        text-decoration: none;
        color: snow;
        background-color: grey;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>