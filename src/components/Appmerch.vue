
<script>
export default {
    name: "AppHeader",
    data() {
        return {
            logos: [{
                image: "public/img/buy-comics-digital-comics.png",
                link: "#DIGITALCOMICS",
                name: "DIGITAL COMICS"
            },
            {
                image: "public/img/buy-comics-merchandise.png",
                link: "#DCMERCH",
                name: "DC MERCHANDISE"
            },
            {
                image: "public/img/buy-comics-subscriptions.png",
                link: "#SUBSCRIPTION",
                name: "SUBSCRIPTION"
            },
            {
                image: "public/img/buy-comics-shop-locator.png",
                link: "#COMICSHOPLOCATOR",
                name: "COMIC SHOP LOCATOR"
            },
            {
                image: "public/img/buy-dc-power-visa.svg",
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
        <div v-for="logo in logos">
            <img :src="logo.image" alt="merchimage">
            <a href="{{ logo.link }}">{{ logo.name }}</a>
        </div>
    </div>
</template>

<style scoped>
#Merchbluecontainer {
    background-color: rgb(10, 129, 209);
    width: 100%;
    height: 25vh;
    display: flex;
    justify-content: space-around;
    align-items: center;

}

#Merchbluecontainer img {
    width: 25%;
}

#Merchbluecontainer {}


span {
    font-weight: bold;
    color: aliceblue;
    font-size: 2rem;
    text-align: center;
}
</style>
