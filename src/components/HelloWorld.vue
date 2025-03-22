<script setup>
//metodos
</script>

<template>
 <!--estructura html-->
<div class="container">
    <h1 class="text-center">NATURALEZA</h1>
    <!--Inicio del Primer row-->
    <div class="row">
        <div class="col-md-6">
            <div class="card">
                <div class="card-header">
                    <h2 class="flora">FLORA</h2>
                    <img width="100px" height="100px" style="display: block; margin: auto; border-radius: 15%;"  src="https://i.pinimg.com/736x/1a/69/4a/1a694a7c4e8a0cff078c9a6fda6ec309.jpg" alt="">
                </div>
                <div class="card-body">
                    <p class="card-text">La flora se refiere al conjunto de plantas que habitan
                         en una región geográfica específica, un período de tiempo 
                         geológico determinado o un ecosistema en particular. 
                         Es, en esencia, el mundo vegetal de un área, incluyendo todas 
                         sus especies, desde los árboles más grandes hasta las hierbas más pequeñas.</p>
                </div>
            </div>
        </div>
        <div class="col-md-6">
            <div class="card">
                <div class="card-header">
                    <h2 class="fauna">FAUNA</h2>
                    <img width="100px" height="100px" style="display: block; margin: auto; border-radius: 15%;" src="https://i.pinimg.com/736x/06/0e/5a/060e5aa0c24dde7243af81f726298dfd.jpg" alt="">
                </div>
                <div class="card-body">
                    <p class="card-text">La fauna es el conjunto de especies animales que 
                        habitan en una región geográfica, 
                        que son propias de un período geológico o que se pueden encontrar en 
                        un ecosistema determinado. 
                        Es el conjunto de animales que viven en un área geográfica o en 
                        un período de tiempo determinado.</p>
                </div>
            </div>
        </div>
    </div>
    <!--Fin del Primer row-->
    <!--Inicio del Segundo row-->
    <div class="row mt-4">
    <div class="col-md-4">
        <div class="card" style="width: 18rem;">
            <img src="https://i.pinimg.com/736x/c8/a9/3c/c8a93c1fb3e6e6e3400b3046314588e4.jpg" class="card-img-top" alt="Lirio">
            <div class="card-body text-center">
                <p class="card-text">El lirio es una planta herbácea, conocido por sus 
                    flores grandes y vistosas, que vienen en una variedad de 
                    colores, incluyendo blanco, amarillo, morado, azul y rosa.</p>
                <button class="btn btn-success">Acerca</button>
            </div>
        </div>
    </div>
    <div class="col-md-4">
        <div class="card" style="width: 18rem;">
            <img src="https://i.pinimg.com/736x/bc/42/45/bc4245b564c4460c46af3d52cddd4a35.jpg" class="card-img-top" alt="Lirio">
            <div class="card-body text-center">
                <p class="card-text">El pavo real destaca por el despliegue de su cola multicolor 
                    durante el cortejo, un espectáculo visual para atraer a las hembras, 
                    su plumaje iridiscente y ocelos lo convierten en un símbolo de belleza y elegancia.</p>
                <button class="btn btn-success">Acerca</button>
            </div>
        </div>
    </div>
    <div class="col-md-4">
        <div class="card" style="width: 18rem;">
            <img src="https://i.pinimg.com/736x/14/d1/76/14d17629f56b6b858f7d4e54206d75c3.jpg" class="card-img-top" alt="Lirio">
            <div class="card-body text-center">
                <p class="card-text">El jazmín es una planta trepadora o arbusto 
                    conocido por sus flores muy fragantes, generalmente blancas, aunque 
                    también existen variedades amarillas y rosadas.
                     Se cultiva ampliamente por su aroma dulce, utilizado 
                     en perfumería.</p>
                <button class="btn btn-success">Acerca</button>
            </div>
        </div>
    </div>
</div>


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
