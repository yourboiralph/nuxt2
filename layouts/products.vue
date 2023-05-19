<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav>
            <NuxtLink to="/products">FAKE STORE API</NuxtLink>
        </nav>
        </header>

    </div>
    <div class="container mx-auto p-4">
        <slot />
    </div>
    <footer class="container mx-auto p-4 flex justify-between">
        <ul class="flex gap-4">
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style scoped>
    .router-link-exact-active{
        color: #12b488;
    }
    li{
        text-decoration: none;
        list-style: none;
    }
</style>

