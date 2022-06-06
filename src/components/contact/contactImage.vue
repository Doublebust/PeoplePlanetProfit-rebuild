<template>

  <section id="container">
    <div class="overlay">
        <div class="text-wrapper">
          <h5>Join People Planet Profit</h5>
          <h2>Become a committed partner</h2>
        </div>
    </div>
  </section>

</template>


<style scoped>
 #container {
     background: url("@/assets/field4.jpg") no-repeat center / cover;
     height: 45vh;
     margin: 7rem 0rem 5rem 0rem;
     position: relative;
     display: flex;
     align-items: center;
     justify-content: center;
   
 }


.overlay:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #fa802f;
    opacity: 0.8;
    z-index: 0;
}

.text-wrapper * {
   z-index: 10;
}

 .text-wrapper {
     font-family: 'Lora', serif;
     width: 100%;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     max-width: 1200px;
     height: 100%;
     margin: 0px auto;
     text-align: center;
     color: #fff;
     padding:  1.2rem;
 }

 .text-wrapper h5 {
   
     font-size: 0.95rem;
     letter-spacing: 3px;
     margin-bottom: 1.1rem;
     text-transform: uppercase;

 }

 .text-wrapper h2 {
     font-size: 3rem;
     font-weight: 600;
     text-transform: capitalize;
   
 }


</style>