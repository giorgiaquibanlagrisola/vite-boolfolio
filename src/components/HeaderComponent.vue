<script>
export default {
    data() {
        return {
            message: 'HEADER'
        }
    }
};
</script>

<template>
    <header>
        {{ message }}
    </header>
</template>

<style scoped>
header {
    color: red;
}
</style>