<template>
    <nav>
        <img src="../../assets/images/onetripid-logo.png" alt="">
        <ul>
            <li><a href="#">Accommodation</a></li>
            <li><a href="#">Offer</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
</template>

<style scoped>
img {
    width: 10%;
}

nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100vw;
}

li > a {
    color: black;
}

ul {
    display: flex;
}

ul > li{
    list-style: none;
    padding: 20px;
}
</style>