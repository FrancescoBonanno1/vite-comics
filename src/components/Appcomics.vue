<script>

</script>

<template>
    <div v-for="comic in comics">
        <img :src="comic.thumb" alt="fumetto">
        <p>{{ comic.series }}</p>
    </div>
</template>

<style scoped></style>