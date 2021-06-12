<template>
    <footer>
        <p>Copyright &copy; 2021</p>
        <router-link to="/about">About</router-link>
    </footer>
</template>

<script>
    export default {
        name: "Footer"
    }
</script>

<style scoped>
    a {
        color: #ccc;
        text-decoration: none;
    }
    footer {
        margin-top: 30px;
        text-align: center;
    }
</style>
