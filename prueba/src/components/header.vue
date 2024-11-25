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
    }
    h1{
        display: block;
        float: left;
        height: 100px;
        line-height: 100px;
        width: 200px;
    }
    ul li{
        width: 150px;
        display: block;
        float: left;
        height: 100px;
        line-height: 100px;
    }
    .clearFix{
        float: none;
        clear: both;
    }
</style>