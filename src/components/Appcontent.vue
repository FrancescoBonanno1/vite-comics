<script>
export default {
    name: "Appcomics",
    props: ["dati"]
}

</script>

<template>
    <div id="comicsdisplay">
        <div id="comicbox">
            <img :src="dati.thumb" alt="immfumetto">
            <p>{{ dati.series }}</p>
        </div>
    </div>
</template>

<style scoped>
#comicsdisplay {
    background-color: rgb(165, 161, 161);
    width: 100%;
    height: 30vh;
    display: flex;
}

#comicbox {
    width: 20%;
    height: 10%;
}

#comicbox img {
    width: 10%;
}

p {
    font-weight: bold;
    color: rgb(13, 13, 14);
}
</style>
