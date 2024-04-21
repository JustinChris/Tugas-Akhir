
<template>
    <section>
        <div class="section1-headline">
            <h3>Roaming Tales</h3>
            <h2>Travel Blog</h2>
            <p>We share travel experiences and tips to inspire your travels. From lesser-known places to highly <br>popular tourist destinations in Bali and Yogyakarta. We will endeavor to continuously update <br>information for you.</p>
        </div>
        
        <div class="section2-blogs">
            <div class="section2-blogs-bigcard">
                <a href="#">
                    <div class="bigcard">
                        <img src="../../../assets/images/section8-place1.png" alt="">
                        <div class="timecard bg-gray">July 10, 2023</div>
                        <h4>Plan the Perfect Vacation</h4>
                        <p>Planning a vacation can indeed be very confusing for some inexperienced individuals who have never planned a detailed vacation before. We will try to assist you with our posts so that you can be helped in planning the vacation of your dreams. Strating from choosing tourist destination, booking accommodations, planning activites and other interesting activities.</p>
                    </div>
                </a>
            </div>

            <div class="section2-blogs-smallcards">
                <a href="#">
                    <div class="smallcard">
                        <img src="../../../assets/images/section8-place3.png" alt="">
                        <div>
                            <div class="timecard bg-green">April 7, 2023</div>
                            <h4>Discover the Hidden Gems</h4>
                            <p>Benefits of traveling alone, from the freeom to discover new places with new friends.</p>
                        </div>
                    </div>
                </a>
                <a href="#">
                    <div class="smallcard">
                        <img src="../../../assets/images/section8-place2.png" alt="" class="stretchimg">
                        <div>
                            <div class="timecard bg-green">April 7, 2023</div>
                            <h4>Must-See Landmarks</h4>
                            <p>Iconic landmarks that make Bali and Yogyakarta one of the world's most popular travel destinations.</p>
                        </div>
                    </div>
                </a>
                <a href="#">
                    <div class="smallcard">
                        <img src="../../../assets/images/section8-place5.png" alt="">
                        <div>
                            <div class="timecard bg-green">April 7, 2023</div>
                            <h4>Traveling on a Budget</h4>
                            <p>Practical advice for travelers who want to see the world without breaking the bank.</p>
                        </div>
                    </div>
                </a>
                <a href="#">
                    <div class="smallcard">
                        <img src="../../../assets/images/section8-place4.png" alt="">
                        <div>
                            <div class="timecard bg-green">April 7, 2023</div>
                            <h4>Explore the Wonders</h4>
                            <p>Must-see destinations and experiences, including wildlife and cultural experiences.</p>
                        </div>
                    </div>
                </a>
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    width: 100vw;
}

.section1-headline {
    text-align: center;
}

.section1-headline h3 {
    color: #1BBC9B;
    font-family: cursive;
}

.section1-headline h2 {
    font-weight: 700;
    font-size: 2.5rem;
}

.section2-blogs {
    display: flex;
    margin: 5vw 15vw;
}

.timecard {
    font-weight: 700;
    text-align: center;
    border-radius: 4px;
    color: white;
    max-width: 10vw;
    margin: 10px 0;
}

.bg-gray {
    background-color: rgb(55, 55, 55)
}

.bg-green {
    background-color: #1BBC9B;
}

.bigcard {
    width: 30vw;
}

.bigcard img {
    width: 100%;
}

.bigcard h4 {
    font-weight: 700;
    font-size: 1.2rem;
}

.bigcard p {
    text-align: justify;
}

.smallcard {
    display: flex;
    padding: 0 30px;
}

.smallcard div>h4 {
    font-weight: 700;
    font-size: 1.2rem;
}

.smallcard > div {
    margin: 0 20px;
}

.smallcard img {
    height: 20vh;
    border-radius: 10px;
}

.stretchimg {
    width: 23vw;
}


</style>