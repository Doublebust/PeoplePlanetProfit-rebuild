<template>

    <header id="about-hero">
        <div class="about-banner">
            <div class="about-banner-text">
                <H2>About us</H2>
                <p>Learn more about our cause</p>
            </div>
        </div>
    </header>

</template>
 

 <style scoped>

#about-hero {
    background: url("@/assets/field5.jpg");
    background-repeat: no-repeat; 
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    height: 60vh;
    color: #fff;
    position: relative;
}

#about-hero:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
} 

#about-hero * {
    z-index:10;
}

.about-banner-text {
    margin-top:15rem;
   
}

.about-banner {
    width: 100%;
    max-width: 1200px;
    margin: 0px auto;
    height: 100%;
    display: flex;
    align-items: center;
    padding: 0rem 1.2rem;
}

.about-banner h2 {
    font-size: 3rem;
}

.about-banner p {
    font-size: 0.9rem;
    font-weight: 400;
}
 
 </style>