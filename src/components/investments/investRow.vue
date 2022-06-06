<template>

  <section id="about-rows">
       <div class="row">
          <div class="left-row"></div>
           <div class="right-row">
              <div class="right-text">
                 <h3>Moyee Ethiopia</h3>
                 <h5>Leading coffee company in Ethiopia</h5>
                 <p>We have a strong commitment towards the People Planet Profit concept and want to help organizations implementing this concept by providing capital, knowledge, 
                   our network and entrepreneurial drive. Studies show a clear need for sustainable, natural products that are also traceable in their origin. 
                   The social theme of equal prosperity in the chain is also more relevant than ever. To be able to make a difference here too, 
                   growth of our portfolio is desirable and therefore also the need for new capital.</p>
                 <a class="btn" href="#">Visit site</a>
              </div>
          </div>
       </div>  
       <div class="row-reverse">
          <div class="left-row2"></div>
           <div class="right-row">
              <div class="right-text">
                 <h3>AgroFair</h3>
                 <h5>Fairtrade organic fruit</h5>
                 <p> People Planet Profit has got over 14 years of experience in sustainable food and sustainable energy.
                   Because making the global energy supply more sustainable has now been successfully deployed, we have said goodbye to the participations in this sector. The goal has been achieved!
                   Now full focus is on companies that are sustainably active in international food chains and where the origins are "smallholders" in developing countries.</p> 
                 <a class="btn" href="#">Visit site</a>          
              </div>
          </div>
       </div>  
       
  </section>
  
</template>

<style scoped>
  .row{
    width: 100%;
    max-width: 1200px;
    margin: 3rem auto 6.5rem auto;
    padding: 0rem 1.2rem;
    display: flex;
    align-items: center;
  }

  .left-row {
    background: url("@/assets/Moyee.webp") no-repeat center / cover;
    width: 50%;
    height: 600px;
  }

  .right-row {
    width: 50%;
    background: #fff;
    padding: 2rem 3rem;
    box-shadow: rgb(0 0 0 / 8%) 0px 0px 30px 0px;
    display: flex;
    margin-left: -100px;
  }


 h3{
   display: inline-block;
   font-size: 1.65rem;
   font-family: 'Lora', serif;
 }

 h5 {
    margin: 0.55rem 0rem;
    font-size: 1.15rem;
    font-weight: 500;
     font-family: 'Lora', serif;
 }

 p {
   font-weight: 300;
   font-size:0.95rem;
   line-height: 1.7;
 }

 a {
  display: inline-block;
  font-size: 0.9rem;
  padding: 10px 30px;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 500;
  margin-top: 1.5rem;
  background-color: #262626;
  color: #fff;
  border-radius: 20px;
  letter-spacing: 2px;
  transition: 0.3s;
}
a:hover {
  background-color: #dc3d04
}


 .row-reverse {
    width: 100%;
    max-width: 1200px;
    margin: 6.5rem auto;
    padding: 0rem 1.2rem;
    display: flex;
    align-items: center;
    flex-direction: row-reverse;
 }

 .row-reverse .right-row {
   margin-right: -100px;
 }

 .left-row2 {
   background: url("@/assets/Agrosample.jpg") no-repeat center / cover;
   width: 50%;
   height: 500px;
 }


 .left-row3 {
   background: url("@/assets/field2.jpg") no-repeat center / cover;
    width: 50%;
    height: 450px;
 }

</style>