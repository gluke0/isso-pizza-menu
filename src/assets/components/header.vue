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

  <div class="d-flex justify-content-center pt-3">
    <Logo></Logo>
    <Contacts></Contacts>
  </div>

</template>

<style lang="scss">

@import '../../style/main.scss';

</style>