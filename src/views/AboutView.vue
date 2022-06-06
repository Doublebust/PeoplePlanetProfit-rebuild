<template>
  <div>
    <about-header></about-header>
    <about-intro></about-intro> 
    <about-row></about-row>  
  
  </div>
</template>

<script>
  import aboutHeader from '@/components/about/aboutHeader';
  import aboutIntro from '@/components/about/aboutIntro';
  import aboutRow from '@/components/about/aboutRow';
 

  export default {
    components: {
      aboutHeader,
      aboutIntro,
      aboutRow 
    }
  }
</script>