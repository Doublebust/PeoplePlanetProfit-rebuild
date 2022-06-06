<template>
  <div>
    <invest-header></invest-header>
    <invest-intro></invest-intro>
    <invest-row></invest-row>
    <invest-images></invest-images>
  </div>
</template>

<script>
  import investHeader from '@/components/investments/investHeader';
  import investIntro from '@/components/investments/investIntro';
  import investRow from '@/components/investments/investRow';
  import investImages from '@/components/investments/investImages';
  export default {
    components: {
      investHeader,
      investIntro,
      investRow,
      investImages
    }
  }
</script>