<template>
    <div>
        <h1>Home</h1>
        <button @click="toUsers">Usersのページにいく</button>
    </div>
</template>

<script>
export default {
    methods: {
        toUsers() {
            this.$router.push({ path: "users" });
        }
    }
}
</script>