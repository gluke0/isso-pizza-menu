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
    <Contacts></Contacts>
    <Logo></Logo>
  </div>

</template>

<style lang="scss">

@import '../../style/main.scss';

</style>