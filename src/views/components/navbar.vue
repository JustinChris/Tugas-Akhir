<template>
    <nav>
        <img src="../../assets/images/onetripid-logo.png" alt="">
        <ul>
            <div class="d-flex list-unstyled">
                <li>
                    <div class="dropdown">
                        <button class="btn btn-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Dropdown button
                        </button>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#">Action</a></li>
                            <li><a class="dropdown-item" href="#">Another action</a></li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </div>
                </li>
                <li><a href="#">Offer</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">Contact Us</a></li>
            </div>
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

/* ul {
    display: flex;
} */

ul > li{
    list-style: none;
    padding: 20px;
}
</style>