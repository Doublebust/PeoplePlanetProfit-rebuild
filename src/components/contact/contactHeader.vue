<template>

    <header id="contact-hero">
        <div class="contact-banner">
            <div class="contact-banner-text">
                <H2>Contact us</H2>
                <p>We would love to hear from you</p>
            </div>
        </div>
    </header>

</template>


<style scoped>
  #contact-hero {
    background: url("@/assets/beans.jpg");
    background-repeat: no-repeat;
    background-position: center;
    background-attachment: fixed;
    background-size: cover;
    height: 60vh;
    color: #fff;
    position: relative;
}

#contact-hero:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.5);
} 

#contact-hero * {
    z-index:10;
}

.contact-banner-text {
    margin-top:15rem;
   
}

.contact-banner {
    width: 100%;
    max-width: 1200px;
    margin: 0px auto;
    height: 100%;
    display: flex;
    align-items: center;
    padding: 0rem 1.2rem;
}

.contact-banner h2 {
    font-size: 3rem;
}

.contact-banner p {
    font-size: 0.95rem;
    font-weight: 300;
}

</style>

