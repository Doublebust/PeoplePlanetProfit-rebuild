<template>
  <div>
    <home-header></home-header>
    <home-about></home-about>
    <home-secondary></home-secondary>
    <home-icons></home-icons>
  </div>
</template>

<script>
  import homeHeader from '@/components/home/homeHeader';
  import homeAbout from '@/components/home/homeAbout';
  import homeSecondary from '@/components/home/homeSecondary';
  import homeIcons from '@/components/home/homeIcons';
  export default {
    components: {
      homeHeader,
      homeAbout,
      homeSecondary,
      homeIcons,
    }
  }
</script>
