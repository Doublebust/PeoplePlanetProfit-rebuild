<template>

    <header id="investment-hero">
       
        <div class="invest-banner">
            <div class="invest-banner-text">
                <H2>Investments</H2>
                <p>Developing portfolio companies</p>
            </div>
        </div>
    
    </header>

</template>
 
 <style scoped>


 #investment-hero {
    background: url("@/assets/ethc.jpg");
    background-repeat: no-repeat; 
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    height: 60vh;
    color: #fff;
    position: relative;
}

#investment-hero:before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.5);
} 

#investment-hero * {
    z-index:10;
}

.invest-banner-text {
    margin-top:10rem;
   
}

.invest-banner {
    width: 100%;
    max-width: 1200px;
    margin: 0px auto;
    height: 100%;
    display: flex;
    align-items: center;
    padding: 0rem 1.2rem;
}

.invest-banner h2 {
    font-size: 3rem;
}

.invest-banner p {
    font-size: 0.95rem;
    font-weight: 400;
}


@media (max-width: 576px){
 .invest-banner h2 {
   font-size: 8.3vw;
}

 .invest-banner p {
   font-size: 3.2vw;
    
}

.invest-banner-text {
    margin-top:5rem;
   
}

#investment-hero {
    height: 70vh;
}

}
 </style>