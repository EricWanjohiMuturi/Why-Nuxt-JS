<template>
    <div>
        <h1>ID: {{ id }}</h1>
        <h1>Name: {{ name }}</h1>
    </div>
</template>

<script setup>
    const route = useRoute()
    const name = route.params.name
    const id = route.params.id
</script>

<style scoped>
   

</style>