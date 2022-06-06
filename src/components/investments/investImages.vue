<template>
   <section id="invest-images">
      <div class="container">
        <div class="text-wrapper">
            <h2>Our next steps</h2>
            <p>Over the next years we will have a further focus on food chains starting at smallholders in developing countries.
             We want to Balance the value chain towards smallholders, by shifting revenue from developed countries to developing countries. 
             Our desire will be to target natural, traceable, and sustainable products. Our portfolio will primarily consist of companies who produce fruits, coffee, 
             cocoa, tea and nuts and seeds. With all this we hope to become a strong market power on fair and ecological products.</p>
        </div>
        <div class="image-container">
           <div class="image1 image"></div>
           <div class="image2 image"></div>
           <div class="image3 image"></div>   
        </div>
      </div>
       

   </section>
</template>


<style scoped>
   #invest-images{ 
       display: flex;
       justify-content: center;
       margin: 5rem 0rem;
   }


   .container {
       width: 100%;
       max-width: 1200px;
       padding: 0 1.2rem;
       display: flex;
       flex-direction: column;
       align-self: center;
   }

   h2 {
        display: inline-block;
        font-size: 1.8rem;
        position: relative; 
        font-weight: 400;
    
   }

   

   p {
       margin: 1rem 0rem 2rem 0rem;
       font-weight: 300;
       font-size: 0.95rem;
       line-height: 1.6;

   }

   .image-container {
       display: flex;
       justify-content: space-between;
   }

   .image {   
        width: 33.2%;
        height: 300px; 
   }


   .image1 {
        background: url("@/assets/seed1.jpeg") no-repeat center / cover;
   }

   .image2{
        background: url("@/assets/seed2.jpg") no-repeat center / cover;  
       
         
   }

   .image3 {
        background: url("@/assets/seed3.jpg") no-repeat center / cover;
   }



</style>