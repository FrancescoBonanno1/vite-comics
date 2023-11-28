<script>
</script>

<template>
    <main>
        <div id="optionscontainer">
            <div>
                <h2>DC COMICS</h2>
                <a href="#HEHE">CHARACTERS</a>
                <a href="#HEHE">COMICS</a>
                <a href="#HEHE">MOVIES</a>
                <a href="#HEHE">TV</a>
                <a href="#HEHE">GAMES</a>
                <a href="#HEHE">VIDEOS</a>
                <a href="#HEHE">NEWS</a>
            </div>
            <div>
                <h2>SHOP</h2>
                <a href="#HEHE">SHOP DC</a>
                <a href="#HEHE">SHOP DC COLLECTIBLES</a>
            </div>
            <div>
                <h2>DC</h2>
                <a href="#HEHE">CHARACTERS</a>
                <a href="#HEHE">COMICS</a>
                <a href="#HEHE">MOVIES</a>
                <a href="#HEHE">TV</a>
                <a href="#HEHE">GAMES</a>
                <a href="#HEHE">VIDEOS</a>
                <a href="#HEHE">NEWS</a>
                <a href="#HEHE">MOVIES</a>
                <a href="#HEHE">TV</a>
                <a href="#HEHE">GAMES</a>
                <a href="#HEHE">VIDEOS</a>
                <a href="#HEHE">NEWS</a>
            </div>
            <div>
                <h2>SITES</h2>
                <a href="#HEHE">CHARACTERS</a>
                <a href="#HEHE">COMICS</a>
                <a href="#HEHE">MOVIES</a>
                <a href="#HEHE">TV</a>
                <a href="#HEHE">GAMES</a>
            </div>
        </div>
        <img src="public\img\dc-logo-bg.png" alt="dc-logo">
    </main>

    <footer>
        <button>SIGN-UP NOW!</button>
        <div>
            <h2>FOLLOW US</h2>
            <img src="public\img\footer-facebook.png" alt="facebook">
            <img src="public\img\footer-twitter.png" alt="twitter">
            <img src="public\img\footer-youtube.png" alt="yout">
            <img src="public\img\footer-pinterest.png" alt="pint">
            <img src="public\img\footer-periscope.png" alt="periscope">
        </div>
    </footer>
</template>

<style scoped>
main {
    width: 100%;
    height: 50vh;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-image: url(/boolean/vite-comics/public/img/footer-bg.jpg);
    object-fit: contain;
}

#optionscontainer {
    width: 25%;
    height: 50vh;
    display: flex;
    flex-wrap: wrap;
}

main img {
    width: 25%;
    opacity: 50%;
}

footer {
    width: 100%;
    height: 10vh;
    background-color: rgb(58, 58, 58);
    display: flex;
    justify-content: space-around;
    align-items: center;

}

footer img {
    margin: 0.5rem
}

footer h2 {
    color: rgb(5, 117, 223))
}

footer div {
    display: flex;
    width: 23%;
    justify-content: space-between;
    align-items: center;
}

footer button {
    width: 10%;
    height: 50%;
    background-color: rgb(58, 58, 58);
    color: aliceblue;
    font-weight: bold;
    border: 2px solid rgb(5, 157, 245);
}
</style>