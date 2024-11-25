<script setup>
    
</script>
<template>
    <nav>
        <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
    </nav>
</template>
<style scoped>
    .form-inline{
        margin: 0px auto;
        background-color: transparent;
        width: 70%;
        height: 100px;
        line-height: 100px;
    }
    .form-control{
        display: block;
        float: left;
        width: 250px;
        height: 30px;
        border-radius: 5px;
        border: 1px solid #ccc;
        margin: 15px;
        padding: 10px;
    }
    .btn{
        display: block;
        float: left;
        width: 50px;
        height: 30px;
        border-radius: 5px;
        border: 1px solid #ccc;
        margin: 15px;
        background: transparent;
        color: white;
        cursor: pointer
    }
    .clearFix{
        float: none;
        clear: both;
    }
    
</style>