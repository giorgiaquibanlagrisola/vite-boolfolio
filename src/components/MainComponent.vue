<script>
export default {
    data() {
        return {
            message: 'MAIN'
        }
    }
};
</script>

<template>
    <main>
        {{ message }}
    </main>
</template>

<style scoped>
main {
    color: blue;
}
</style>