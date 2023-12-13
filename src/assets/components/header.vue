<script>

import Logo from './views/hlogo.vue'
import Contacts from './views/hcontacts.vue'

export default {
  name: "Header",
  data() {
    return {
    }
  },
  components:{
    Logo,
    Contacts,
  },
}
</script> 

<template>

  <Logo></Logo>
  <Contacts></Contacts>

</template>

<style lang="scss">

@import '../../style/main.scss';

</style>