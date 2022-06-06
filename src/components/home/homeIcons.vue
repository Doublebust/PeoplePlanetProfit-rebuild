<template>
   <section id="icons">
     <div id="icons-container">
        <div class="investment-text">
          <h2>Tripple bottom line</h2>
          <p>Odio aliquet, fringilla odio eget, tincidunt nunc duis aliquet pulvinar <br> ante employees and organizations to support.</p>
        </div>
          <div class="icons-wrapper">
            <div class="left"><i class="fa-solid fa-chart-line"></i>
            <h5>Economic </h5>
            <p>Odio aliquet, fringilla odio eget, tincidunt nunc duis aliquet pulvinar ante employees.</p>
            </div>
            <div class="center"><i class="fa-solid fa-earth-europe"></i>
            <h5>Environmental </h5>
            <p>Odio aliquet, fringilla odio eget, tincidunt nunc duis aliquet pulvinar ante employees.</p>
            </div>
            <div class="right"><i class="fa-solid fa-people-arrows-left-right"></i>
            <h5>Social equity </h5>
            <p>Odio aliquet, fringilla odio eget, tincidunt nunc duis aliquet pulvinar ante employees.</p>
          </div>
          </div>
        </div>
    </section>
</template>

<style scoped>

#icons {
  background: #fff;
  position: relative;
}

#icons-container {
  width: 100%;
  max-width: 1200px;
  line-height: 1.4;
  margin: 0px auto;
  padding: 120px 1.2rem;
}

.icons-wrapper  i {
  background-color: #59b555;
  font-size: 2rem;
  padding: 2rem;
  border-radius: 50%;
  margin-bottom: 35px;
  color: #fff;
  transition: 0.2s;

}


.investment-text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 70px;
  text-align: center;
}



.investment-text h2 {
  font-family: 'Lora', serif;
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
}

.investment-text p {
  color: #6a6063;
}

.icons-wrapper {
  display: flex;

}

.icons-wrapper h5 {
  font-size: 1.5rem;
  font-family: 'Lora', serif;
  margin-bottom: 20px;
  color: #59b555;
}

.icons-wrapper p {
  font-weight: 300;
  margin: 1.2rem 0rem;
  color: #6a6063;
}


.icons-wrapper div {
  display: flex;
  flex-direction: column;
  justify-content: center;  
  align-items: center;
  text-align: center;
}

.left, .center, .right {
  padding: 0rem 3rem;
}
</style>