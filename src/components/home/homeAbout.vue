<template>
  <main id="fill">
    <section id="main-container"> 
        <flickity class="carousel" ref="flickity" :options="flickityOptions">
          <img v-for="(image, index) in images" :key="index" class="carousel-cell" :src="image">
        </flickity>
        <div class="text-container">
        <h2>Who we are</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid odit perferendis, accusamus assumenda et quasi beatae sunt totam atque vel!
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam nisi reiciendis iste porro est. In exercitationem possimus aliquam quas quisquam.
        </p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid odit perferendis, accusamus assumenda et quasi beatae sunt totam atque vel!
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam nisi reiciendis iste porro est. In exercitationem possimus aliquam quas quisquam.
        </p>
        <div><a href="">About us</a></div>
        </div>  
    </section> 
 </main>
</template>

<script>
import Flickity from 'vue-flickity'

  export default {
    components: {
       Flickity
    },
    data() {
      return {
        images: [
          require("@/assets/worker2.jpg"),
          require("@/assets/delight.jpg"),
          require("@/assets/sample5.jpg")
        ],
        flickityOptions: {
          draggable: true,
          autoPlay: 4000,
          fade: true,
          loop: true,
          pauseAutoPlayOnHover: false,
          wrapAround: true,
          imagesLoaded: true,
          showPrevNextButtons: false
        }
      }
    },
  }
</script>


<style scoped>

#fill {
  background: #fff !important;
  position: relative;
}

  #main-container {
  display: flex;
  justify-content: space-between;
  width: 100%;
  max-width: 1200px;
  margin: 0px auto;
  padding: 6.5rem 1.2rem;
}

.text-container {
  z-index: 10;
  background: #fff;
  width: 48%;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}

.text-container h2 {
  
  font-size: 2.5rem;
  font-family: 'Lora', serif;
}

.text-container p {
  margin: 10px 0px;
  font-size: 0.938rem;
}

.text-container a {
  display: inline-block;
  font-size: 0.938rem;
  background: #fff;
  padding: 10px 30px;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 500;
  margin-top: 10px;
  background-color: #262626;
  color: #fff;
  border-radius: 20px;
  letter-spacing: 2px;
  transition: 0.3s;
}

.text-container a:hover {
  background-color: #dc3d04
}

.carousel {
  width: 48%;
}

.carousel-cell {
  width: 100%;
  height: 400px;
  counter-increment: carousel-cell;
  object-fit: cover;
}
 
 >>> .flickity-page-dots {
 bottom: 5% !important;
 color: #dc3d04 !important;
}

>>> .flickity-page-dots .dot {
  width: 12px;
  height: 12px;
  background: #dc3d04 !important;
}

>>> .flickity-prev-next-button.next, >>> .flickity-prev-next-button.previous {
  background: transparent 
}

>>> .flickity-prev-next-button .flickity-button-icon {
  fill: #fff;
} 
</style>


