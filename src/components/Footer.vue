<template>
    <footer>
        <p>{{ currentYear }} Copyright by Max Mustermann. Create with Vue.</p>
    </footer>
</template>

<script>

export default {
    data() {
        return {
            currentYear: new Date().getFullYear()
        }
    }
}

</script>

<style lang="scss" scoped>

footer {
    display: flex;
    justify-content: center;
    margin: 5rem 0 0 0;
    p {
        font-size: 1.2rem;
        font-family: $roboto;
        color: $ciGrey;
    }
}

</style>