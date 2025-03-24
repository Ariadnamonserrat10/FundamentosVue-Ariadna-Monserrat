<script setup>
//importacion del primer card
import Card from './Card.vue';
//importacion del card principal
import CardPrincipal from './CardPrincipal.vue';
//metodos
</script>

<template>
 <!--estructura html-->
<div class="container">
    <h1 class="text-center">NATURALEZA</h1>
    <!--Inicio del Primer row-->
    <CardPrincipal/>
    <!--Fin del Primer row-->
    <!--Inicio del Segundo row-->
    <Card/>
    <!--Fin del Segundo row-->

    <!--Inicio del Tercer row-->
    <Card/>
    <!--Fin del Tercer row-->
</div>
</template>

<style scoped>
/*Estilos css*/
h1{
    color: #4CAF50;
    font-family: cursive;
    text-shadow: 2px 2px 4px #0b5317;
    font-size: 80px;
}

.flora{
    color: #4CAF50;
    font-family: fantasy;
    text-align: center;
}

.fauna{
    color: #ee843e;
    font-family: fantasy;
    text-align: center;
}

p{
    font-family:Arial, Helvetica, sans-serif;
    text-align: justify;
    font-size: 18px;
}
</style>
