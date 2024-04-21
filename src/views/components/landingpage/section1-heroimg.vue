
<template>
    <section>
        <p>ONE TRIP ID TRAVEL AGENCY</p>
        <h2><a href="#">GO Explore</a> &</h2>
        <h2>Experience</h2>
        <h2>Your Trip!</h2>
    </section>
</template>

<style scoped>
section{
    margin-top: 10px;
    margin-bottom: 100px;
    height: 100vh;
    width: 100vw;
    background-position: center;
    background-size: cover;
    background-image: linear-gradient(rgba(255, 255, 255, 0.8),rgba(255, 255, 255, 0.8)),url(../../../assets/images/section1-heroimg.png);
}

section > p {
    color: rgb(150, 150, 150);
    margin-left: 15vw;
    padding-top: 10vw;
    font-size: 0.8rem;
}

section > h2 {

    margin-left: 15vw;
    color: black;
    font-weight: 700;
    font-size: 2rem;
}

section > h2 > a {
    color: black;
    font-weight: 700;
    font-size: 2rem;
    text-decoration: underline;
    text-decoration-color: rgb(255, 174, 0);
    text-decoration-thickness: 5px;
}

section > h2 > a:hover {
    text-decoration-color: rgb(255, 4, 163);
}
</style>