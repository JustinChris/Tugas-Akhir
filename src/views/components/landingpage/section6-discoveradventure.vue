

<template>
    <section>
        <div class="section1">
            <div class="section1-headline">
                <h3>Wandering Souls</h3>
                <h2>Discover Your Next<br>Adventure</h2>
                <p>Are you planning a vacation with your partner or with your family? We<br>can meet your needs. So, start choosing the vacation package that suits<br> your dreams.</p>
                <p>Organized Group Tour</p>
                <div class="progress-bar">
                    <div class="bar" style="height:10px;width:90%"></div>
                </div>
                <p>Single Customized Trip</p>
                <div class="progress-bar">
                    <div class="bar" style="height:10px;width:75%"></div>
                </div>
            </div>
    
            <div class="section1-images">
                <img src="../../../assets/images/section6-images.jpg" alt="">
            </div>
        </div>
    </section>
</template>

<style scoped>
section {
    width: 100vw;
    margin: 10% 5%;
    padding: 0px 20px;
}

section h3 {
    color: #1BBC9B;
    font-family: cursive;
}

section h2 {
    font-weight: 700;
    font-size: 2.5rem;
    
    margin-top: 20px;
}

section p {
    padding: 5px 0;
}

.section1 {
    display: flex;
    justify-content: space-between;
    
    width: 85vw;
}

.progress-bar {
    width: 100%;
    height: 10px;
    background-color: #F1F1F1;
    border-radius: 20px;
}

.bar {
    background-color: #434A54;
}

.section1-images img {
    max-width: 45vw;
    border-radius: 200px 0 0 200px;
}

</style>