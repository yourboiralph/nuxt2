<template>
    <div class="card text-center">
        <img :src="product.image" alt="product thumb">

    </div>
</template>

<script setup>
    const { product } = defineProps(['product'])

</script>

<style scoped>
 
</style>
