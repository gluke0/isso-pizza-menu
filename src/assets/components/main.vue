<script>

import Pizza from './views/mpizza.vue'
import Focaccia from './views/mfocaccia.vue'
import Extra from './views/mextra.vue'
import Bevande from './views/mbevanda.vue'


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
    Bevande,
  },
}
</script>

<template>

  <Pizza></Pizza>
  <Focaccia></Focaccia>
  <Extra></Extra>
  <Bevande></Bevande>

</template>

<style lang="scss">
@import '../../style/main.scss';
</style>