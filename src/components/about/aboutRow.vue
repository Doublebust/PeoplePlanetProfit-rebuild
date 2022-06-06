<template>

  <section id="about-rows">
       <div class="row">
          <div class="left-row"></div>
           <div class="right-row">
              <div class="right-text">
                 <h3>Our work</h3>
                 <p>We have a strong commitment towards the People Planet Profit concept and want to help organizations implementing this concept by providing capital, knowledge, 
                   our network and entrepreneurial drive. Studies show a clear need for sustainable, natural products that are also traceable in their origin. 
                   The social theme of equal prosperity in the chain is also more relevant than ever. To be able to make a difference here too, 
                   growth of our portfolio is desirable and therefore also the need for new capital.</p>
              </div>
          </div>
       </div>  
       <div class="row-reverse">
          <div class="left-row2"></div>
           <div class="right-row">
              <div class="right-text">
                 <h3>Our cause</h3>
                 <p> People Planet Profit has got over 14 years of experience in sustainable food and sustainable energy.
                   Because making the global energy supply more sustainable has now been successfully deployed, we have said goodbye to the participations in this sector. The goal has been achieved!
                   Now full focus is on companies that are sustainably active in international food chains and where the origins are "smallholders" in developing countries.</p>           
              </div>
          </div>
       </div>  
       <div class="row">
          <div class="left-row3">
       </div>
           <div class="right-row">
              <div class="right-text">
                 <h3>Our principles</h3>
                 <p> People Planet Profit has got over 14 years of experience in sustainable food and sustainable energy.
                   Because making the global energy supply more sustainable has now been successfully deployed, we have said goodbye to the participations in this sector. The goal has been achieved!
                   Now full focus is on companies that are sustainably active in international food chains and where the origins are "smallholders" in developing countries.</p>
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
    background: url("@/assets/coffee1.png") no-repeat center / cover;
    width: 50%;
    height: 450px;
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
    margin-bottom: 0.6rem;
    display: inline-block;
    font-size: 1.45rem;
    font-weight: 400;
  
 }

 p {
   font-weight: 300;
   font-size:0.95rem;
   line-height: 1.7;
 
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
   background: url("@/assets/sample5.jpg") no-repeat center / cover;
    width: 50%;
    height: 450px;
 }


 .left-row3 {
   background: url("@/assets/field2.jpg") no-repeat center / cover;
    width: 50%;
    height: 450px;
 }

</style>