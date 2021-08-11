<template>
    <div>
        <input type="email" placeholder="email">
        <input type="password" placeholder="password">
        <input type="submit" value="Log In">
    </div>
</template>

<script>
    export default {
        name : 'VueBody'
    }
</script>

<style scoped>
    div {
        display: grid;
        grid-template-rows: repeat(3, 1fr);
        row-gap: 5px;
    }
</style>