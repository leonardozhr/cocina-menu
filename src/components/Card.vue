SFC

<template>
<grid>
    <img v-bind:src="url" alt="Vue.js">
    <h2>{{nombre}}</h2>
    <h3>{{descripcion}}</h3>
    <h3>{{costo}}</h3>
    
    
</grid>
</template>
<script>
import Grid from "./Grid.vue";
    export default{
    props: {
        url: { String,
        },
        nombre: { String,
        },
        descripcion: { String
        },
        costo: { String

        },
    },
    components: { Grid }

};
</script>

<style scoped>
    
    img{
        width: 8rem;
        height: 8rem;
        padding: 0.5rem;
        background-color: snow;
    }

    a{
        text-decoration: none;
        color: snow;
        background-color: darkgray;
        padding: 0.3rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }

</style>