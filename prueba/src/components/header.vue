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
        background-color: transparent;
        border: 1px solid #ccc;
        border-radius: 5px;
        backdrop-filter: blur(20px);
        box-shadow: 0 0 10px rgba(0,0,0,.2);
    }
    .encabezado h1{
        display: block;
        float: left;
        height: 100px;
        line-height: 100px;
        width: 200px;
        color: white;
        padding: 15px;
        font-family: Arial, Helvetica, sans-serif
    }
    ul li{
        width: 100px;
        display: block;
        float: left;
        /* border-right: 1px solid #ccc; */
        /* margin: 10px 10px 0px 10px; */
        min-height: 100px;
        line-height: 100px;
        margin-right: 10px
    }

    ul li a{
        color: white;
        /* padding: 10px 20px; */
        font-size: 17px;
        width: 50px;
        height: 100px;
        line-height: 100px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
        font-weight: 500;
        text-align: center;
    }
    ul li:hover{
        background-color: white;
    }
    ul li a:hover{
        color: navy
    }
    .clearFix{
        float: none;
        clear: both;
    }
</style>