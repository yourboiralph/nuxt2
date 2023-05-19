<template>
    <div>
        <h1>FAKE STORE API</h1>
    </div>
</template>

<script setup>

    //fetch products
    const {data: products } = await useFetch('https://fakestoreapi.com/products/')


</script>

<style scoped>
    li{
        text-decoration: none;
        list-style: none;
    }
</style>
