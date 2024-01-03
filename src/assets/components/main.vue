<script>

import Pizza from './views/mpizza.vue'
import Focaccia from './views/mfocaccia.vue'
import Extra from './views/mextra.vue'


export default {
  name: "Main",
  data() {
    return {
    }
  },
  components: {
    Pizza,
    Focaccia,
    Extra,
  },
}
</script>

<template>

  <Pizza></Pizza>
  <Focaccia></Focaccia>
  <Extra></Extra>

</template>

<style lang="scss">
@import '../../style/main.scss';
</style>