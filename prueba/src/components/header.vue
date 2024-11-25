<script setup>

</script>
<template>
    <div class="encabezado">
        <h1>Products</h1>
        <div class="navbar">
            <ul>
                <li>
                    <a href="#">Home</a>
                </li>
                <li>
                    <a href="#">Products</a>
                </li>
                <li>
                    <a href="#">Contact us</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="clearFix"></div>
</template>
<style scoped>
    .encabezado{
        margin: 0px auto;
        width: 70%;
        height: 100px;
        line-height: 100px;
        font-size: 18px;
        background-color: #ccc;
    }
    .encabezado h1{
        display: block;
        float: left;
        height: 100px;
        line-height: 100px;
        width: 200px;
        color: white;
        padding: 15px;
    }
    ul li{
        width: 100px;
        display: block;
        float: left;
        height: 100px;
        line-height: 100px;
    }

    ul li a{
        color: white;
        padding: 15px;
    }
    .clearFix{
        float: none;
        clear: both;
    }
</style>