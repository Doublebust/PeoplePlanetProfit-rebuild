<template>
  <div>
    <contact-header></contact-header>
    <contact-icons></contact-icons>
    <contact-map></contact-map>
    <contact-image></contact-image>
  </div>
</template>

<script>
  import contactHeader from '@/components/contact/contactHeader';
  import contactIcons from '@/components/contact/contactIcons';
  import contactImage from '@/components/contact/contactImage';
  import contactMap from '@/components/contact/contactMap';
  export default {
    components: {
      contactHeader,
      contactIcons,
      contactImage,
      contactMap
    }
  }
</script>