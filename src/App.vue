<template>
  <div id="app">
    <site-nav></site-nav>
    <router-view/>
    <site-footer></site-footer> 
  </div>
</template>

<script>
import siteNav from '@/components/global/siteNav';
import siteFooter from '@/components/global/siteFooter';

  export default {
    components: {
      siteNav,
      siteFooter,
    }
  }
</script>


<style>
  @import url('https://unpkg.com/flickity@2/dist/flickity.min.css');
  @import url('https://fonts.googleapis.com/css?family=Poppins:200,300,400,500,600,700,800,900&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap');
*
{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  overflow-x: hidden;
}

body{
  font-family: 'Poppins', sans-serif;
  overflow-x: hidden;
}

a {
    text-decoration: none;
    color: #FFF;
    transition: 0.3s;
}

button {
  cursor: pointer
}

ul {
    list-style: none;
}

.mobile * {
 z-index:100;
}



</style>
