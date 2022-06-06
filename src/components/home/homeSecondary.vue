<template>
    <section id="secondary-banner">
        <div class="secondary-text">
          <div class="wrapper">
          <h2>Emphasis on People and Planet</h2>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
            Aliquid odit perferendis. accusamus assumenda et quasi beatae sunt totam atque vel!</p>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. 
          Aliquid odit perferendis. accusamus assumenda et quasi beatae sunt totam atque vel!</p>
          <div><a href="">Read more</a></div>
          </div>   
        </div>
    </section>
</template>

<style scoped>
  #secondary-banner {
  background-image: url('@/assets/88322.webp');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  background-size: cover;
  position: relative;
  padding: 5rem 0rem;
}


.secondary-text {
  width: 100%;
  max-width: 1200px;
  height: 100%;
  margin: 0px auto;
  padding: 0px 1.2rem;
}

.secondary-text .wrapper {
 background: #fff;
 width: 48%;
 padding: 65px;
 border-radius: 5px;
}

.secondary-text h2 {
  font-size: 2.5rem;
  font-family: 'Lora', serif;
  margin-bottom: 20px;
}

.secondary-text p {
  margin: 10px 0px;
  font-size: 0.938rem;
  font-weight: 300;
}


.secondary-text a {
  display: inline-block;
  font-size: 0.938rem;
  background: fff;
  padding: 10px 30px;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 500;
  margin-top: 30px;
  background-color: #262626;
  color: #fff;
  border-radius: 20px;
  letter-spacing: 2px;
}

.secondary-text a:hover {
  background: #dc3d04;
  color: #fff;
}


</style>