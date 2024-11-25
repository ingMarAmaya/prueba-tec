<script setup>

</script>
<template>
    <div>
        <section class="tarjetas">
            <article class="tarjeta">
                <h2>Producto: </h2>
                <p>Precio: </p>
                <p>Descripción: </p>
            </article>
        </section>
    </div>
</template>
<style scoped>
    .tarjetas{
        margin: 0px auto;
        width: 70%;
    }
    .tarjeta{
        display: block;
        float: left;
        margin: 0px auto;
        width: 25%;
        height: 200px;
        border: 1px solid #ccc;
        border-radius: 5px;
        margin: 5px;
        padding: 15px;
    }
    .tarjeta h2{
        color: white;
        text-align: center;
        padding: 10px;
    }
</style>