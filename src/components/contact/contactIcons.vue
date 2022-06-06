<template>
<section id="card-section">
        <div class="card-container">
            <div class="left phone">
                <div class="top-card">
                  <i class="fa-solid fa-envelope"></i>
                    <h4><span>Mail</span> us</h4>   
                </div>
                <div class="bottom-card">
                    <a href="#">Peter@Peopleplanetprofit.com</a>
                </div> 
            </div>
            <div class="center mail">
                <div class="top-card">
                    <i class="fa-solid fa-phone"></i>
                    <h4><span>Call</span> us </h4>
                </div>
                <div class="bottom-card">
                    <a href="#">+31-6532-608-50</a>
                </div>
            </div>
            <div class=" right address">
                <div class="top-card">
                    <i class="fa-solid fa-compass"></i>
                    <h4><span>Find</span> us at</h4>
                </div>
                <div class="bottom-card">
                    <ul>
                        <li>Benoordenhoutseweg 43</li>
                        <li>2596 BC Den Haag</li>
                        <li>Zuid-Holland</li>
                    </ul> 
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
  .card-container {
    width:100%;
    max-width: 1200px;
    margin: 0px auto;
    display: flex;
    padding: 0 1.2rem;
    justify-content: space-between;   
    position: relative;
    bottom: 50px;
}

span {
 
}

.phone, .mail, .address {
    background: #fff;
    border-radius: 5px;
    color: #262626;
    width: 32%;
    padding: 3rem 2rem !important;
    box-shadow: rgb(0 0 0 / 8%) 0px 0px 30px 0px;
    transition: background-color 0.2s;
}

.top-card {
    display: flex;
    align-items: center;
    margin-bottom: 2rem;
}


.top-card h4 {
    color: #262626;
    font-weight: 500;
    font-size: 1.05rem;
}

.top-card i {
    background: #59b555;
    color: #fff;
    padding: 1rem;
    font-size: 1.2rem;
    border-radius: 50%;
    margin-right: 1rem;
}

.bottom-card {
    display: flex;
    justify-content: flex-start;
}

.bottom-card a{
    color: #262626;
    font-size: 0.9rem;
    font-weight: 300;
}

.bottom-card ul {
    color: #262626;
    font-weight: 300;
    font-size: 0.9rem;
}

.bottom-card a:hover {
    color: #ff4800;
}

</style>