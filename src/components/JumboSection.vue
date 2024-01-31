<script>
export default {
    name: 'JumboSection'
}
</script>

<template>
    <section>
        <h2>SEZIONE JUMBOTRON</h2>
        <figure>
            <img src="../assets/jumbo.png" alt="jumbo">
        </figure>
    </section>
</template>

<style scoped>
section {
    border: 2px dotted brown;
    border-radius: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    box-shadow: 2px 2px 2px white;
}
</style>