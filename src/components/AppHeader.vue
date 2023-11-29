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
        <img src="public\img\favicon.ico" alt="logo dc">
        <div id="linkcontainer">
            <a v-for="links in headerlinks" href="{{ links.link }}">{{ links.name }}</a>
            <!--<span v-for="bars in headerlinks"></span>-->
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: rgb(255, 255, 255);
    width: 100%;
    height: 10vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

header a {
    margin: 1%;
    color: rgb(54, 156, 245);
    text-decoration: none;
}

header span {
    width: 15%;
    height: 25%;
    background-color: rgb(0, 162, 255);
}

header img {
    width: 3%;
}
</style>
