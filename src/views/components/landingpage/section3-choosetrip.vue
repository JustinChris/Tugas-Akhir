<template>
    <section>
        <h3>Dream Vacation Destination</h3>
        <h2>Start your Vacation Now</h2>
        <p>Are you ready to start your vacation but don't know how to begin? With the help of</p>
        <p>Onetrip.id, your journey will be easier.</p>

        <div class="travel-agent">
            <img src="../../../assets/images/company1.png" alt="blissful-escapes">
            <img src="../../../assets/images/company2.png" alt="yacht-club">
            <img src="../../../assets/images/company3.png" alt="traveling-loremipsum">
            <img src="../../../assets/images/company4.png" alt="biking tournament">
            <img src="../../../assets/images/company5.png" alt="travel-world">
        </div>
    </section>
</template>

<style scoped>
section {
    width: 100vw;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #F2F2F2;
}

section h3 {
    color: #1BBC9B;
    font-family: cursive;
    margin-top: 100px;
}

section h2 {
    font-weight: bolder;
    font-size: 2.5rem;
    margin: 20px;

}

.travel-agent {
    display: flex;
    margin: 100px;
}

.travel-agent img {
    width: 200px;
}

</style>