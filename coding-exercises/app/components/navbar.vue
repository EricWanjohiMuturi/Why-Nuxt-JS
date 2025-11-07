<template>
    <div>
        <nav class="navbar">
            <div class="nav-brand">
                <NuxtLink class="nav-item" to="/">
                    My Nuxt App
                </NuxtLink>
            </div>
            <div class="navbar-menu">
                <div class="navbar-start">
                    <NuxtLink class="nav-item" to="/">Home</NuxtLink>
                    <NuxtLink class="nav-item" to="/about">About</NuxtLink>
                    <NuxtLink class="nav-item" to="/bill">Billing</NuxtLink>
                    <NuxtLink class="nav-item" to="/deals">Deals</NuxtLink>
                </div>
            </div>
        </nav>
    </div>
</template>

<script setup>

</script>

<style scoped>
.navbar {
    display: flex;
    background-color: #2c3e50;
    padding: 1rem;
    justify-content: space-between;
}
.nav-item {
    color: #ecf0f1;
    margin-right: 1rem;
    text-decoration: none;
}
.nav-item:hover {
    text-decoration: underline;
}


</style>