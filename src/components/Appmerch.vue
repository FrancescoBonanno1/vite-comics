
<script>
export default {
    name: "AppHeader",
    data() {
        return {
            logos: [{
                image: "",
                link: "#DIGITALCOMICS",
                name: "DIGITAL COMICS"
            },
            {
                image: "",
                link: "#DCMERCH",
                name: "DC MERCHANDISE"
            },
            {
                image: "",
                link: "#SUBSCRIPTION",
                name: "SUBSCRIPTION"
            },
            {
                image: "",
                link: "#COMICSHOPLOCATOR",
                name: "COMIC SHOP LOCATOR"
            },
            {
                image: "",
                link: "#DCPOWERVISA",
                name: "DC POWER VISA"
            },
            ]
        }
    }
}
</script>

<template>
    <div id="Merchbluecontainer">
        <img v-for="logo in logos" src="{{ logo.image }}" alt="merchimage">
        <a v-for="logo in logos" href="{{ logo.link }}">{{ logo.name }}</a>
    </div>
</template>

<style scoped>
#Merchbluecontainer {
    background-color: rgb(10, 129, 209);
    width: 100%;
    height: 25vh;
}

span {
    font-weight: bold;
    color: aliceblue;
    font-size: 2rem;
    text-align: center;
}
</style>
