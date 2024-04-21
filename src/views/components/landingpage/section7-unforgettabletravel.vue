
<template>
    <section>
        <div class="section1-headline">
            <div class="section1-headline-text">
                <h2>Unforgettable Travel <br>Experiences</h2>
                <p>Customer feedback is crucial for us in building trust and customer <br> satisfaction. By listening to the feedback and needs of our customers, we <br>will strive to provide an unforgettable experience for our customers.</p>
            </div>
            <div class="section1-headline-image">
                <img src="../../../assets/images/section7-profileimage1.jpg" alt="">
            </div>
        </div>

        <div class="section2-testimony">
            <div class="section2-card">
                <p>I have used the services of the travel agent Onetrip.id before, and they provide excellent trip planning.</p>
                <div class="section2-card-profile">
                    <img src="../../../assets/images/section7-profileimage2.jpg" alt="">
                    <div>
                        <p class="bold">Dharmajati</p>
                        <p>Indonesia</p>
                    </div>
                </div>
            </div>

            <div class="section2-card">
                <p>This travel agency made my dream trip to Bali come true. They worked with me every step of the way to the plan the itinerary.</p>
                <div class="section2-card-profile">
                    <img src="../../../assets/images/section7-profileimage3.jpg" alt="">
                    <div>
                        <p class="bold">Dylan and Emily</p>
                        <p>Miami</p>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>

<style scoped>
section {
    width: 100vw;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    background-image: linear-gradient(rgba(0, 0, 0, 0.5),rgba(0, 0, 0, 0.5)),url(../../../assets/images/section7-background.jpg);
    margin-bottom: 100px;
}

.section1-headline {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 100px 15vw;
}

.section1-headline-text {
    color: white;
}

.section1-headline-text h2{
    font-weight: 700;
    font-size: 2.5rem;
}

.section1-headline-image img {
    min-width: 150px;
    border-radius: 100px;
}

.section2-testimony {
    display: flex;
    justify-content: center;

    align-items: stretch;
    padding: 0 15vw 100px 15vw;
}

.section2-card {
    border-radius: 15px;
    width: 30vw;
    background-color: #1BBC9B;
    margin: 0 30px;
    padding: 20px 25px;
    color: white;
}

.section2-card-profile {
    display: flex;
    padding: 10px 10px;
}

.section2-card-profile div {
    padding-left: 2vw;
}

.section2-card-profile img {
    border-radius: 30px;
}

img {
    width: 50px;
}

.bold {
    font-weight: 700;
}

</style>