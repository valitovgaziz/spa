<template>
    <div>
        <h1>{{ isUppercase ? title.toUpperCase() : title }}</h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'Component without uppercase',
            isUppercase: false,
        }
    },
}
</script>

<style>
h1 {
    font-family: 'Avenir', Arial, Helvetica, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>