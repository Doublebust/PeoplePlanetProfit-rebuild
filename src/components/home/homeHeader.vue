<template>
  <header id="showcase">
     <video src="../../assets/banana.mp4" muted loop autoplay></video>
     <div class="overlay"></div>
     <div class="text">
          <h2>Work towards a better world</h2>
          <p>Building a sustainable future for workers</p>
          <button @click="scrollDown" id="btn">Learn more</button>
     </div> 


   </header>


</template>

<script>
   export default {
     methods: {
       scrollDown() {
         const height = document.querySelector('#nav').offsetHeight;
         this.gsap.to(window, {duration: 0.8, scrollTo: {y: "#main-container", offsetY: height}});
       }
     }
   }
</script>

<style scoped>

  #showcase
{
  position: relative;
  right: 0;
  width: 100%;
  min-height: 100vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #111;
  transition: 0.5s;
  z-index: 0;
}


#showcase.active
{
  right: 300px;
}

#showcase video
{
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.8;
  z-index: 0;
}

.overlay
{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #00000059;
  /* background: #ff48002d; */
  mix-blend-mode: overlay;
}


 
.text
{
 
  max-width: 1200px;
  padding: 1.2rem;
  width: 100%;
  margin: 3rem auto 0rem auto;
  z-index: 10;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  text-align: left;
}

.text h2
{
  font-size: 3.8rem;
  font-weight: 800;
  color: #fff;
  text-align: left;
  line-height: 1em;
  text-transform: uppercase;
}


.text p
{
  font-size: 1.1em;
  color: #fff;
  margin: 20px 0;
  font-weight: 400;
}

.text button
{
  border: none;
  display: inline-block;
  font-size: 1em;
  background: #fff;
  padding: 10px 30px;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 500;
  margin-top: 10px;
  color: #111;
  border-radius: 20px;
  letter-spacing: 2px;
  transition: 0.3s;
}
.text button:hover
{
  background: #dc3d04;
  color: #fff;
}

@media (max-width: 991px)
{
  .showcase,
  .showcase header
  {
    padding: 40px;
  }
  .text h2
  {
    font-size: 3em;
  }
  .text h3
  {
    font-size: 2em;
  }
}

</style>


