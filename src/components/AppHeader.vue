<script>
export default {
    name: "AppHeader",
    data() {
        return {
            headerlinks: [{
                name: "CHARACTERS",
                link: "#CHARACTERS",
            },
            {
                name: "COMICS",
                link: "#COMICS",
            },
            {
                name: "MOVIES",
                link: "#MOVIES",
            },
            {
                name: "TV",
                link: "#TV",
            },
            {
                name: "GAMES",
                link: "#GAMES",
            },
            {
                name: "COLLECTIBLES",
                link: "#COLLECTIBLES",
            },
            {
                name: "VIDEOS",
                link: "#VIDEOS",
            },
            {
                name: "FANS",
                link: "#FANS",
            },
            {
                name: "NEWS",
                link: "#NEWS",
            },
            {
                name: "SHOP",
                link: "#SHOP",
            }]
        }
    }
}
</script>

<template>
    <header>
        <img src="" alt="logo dc">
        <div id="link container">
            <a v-for="links in headerlinks" href="{{ links.link }}">{{ links.name }}</a>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: rgb(124, 107, 107);
    width: 100%;
    height: 20vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

header a {
    margin: 1%;
}
</style>
