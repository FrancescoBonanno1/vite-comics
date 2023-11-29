<script>
export default {
    name: "Appcomics",
    props: ["fumetti"]
}

</script>

<template>
    <nav id="contentcontainer">
        <div v-for="fumetto in fumetti" id="comicbox">
            <img :src="fumetto.thumb" alt="immfumetto">
            <p>{{ fumetto.price }}</p>
        </div>
    </nav>
</template>

<style scoped>
nav {
    background-color: black;
    width: 100%;
    height: 10vh;
}

#comicbox {
    width: 15%;
    height: 10%;
}

p {
    font-weight: bold;
    color: aliceblue;
}
</style>
