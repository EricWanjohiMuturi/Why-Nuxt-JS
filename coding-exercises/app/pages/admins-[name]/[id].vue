<script setup>
    const route = useRoute()
    const adminName = route.params.name
    const adminId = route.params.id
</script>

<template>
    <div>
        <h1>ID: {{ adminId }}</h1>
        <h1>Name: {{ adminName }}</h1>
    </div>
</template>