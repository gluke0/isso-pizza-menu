<script>

import Pizza from './views/mpizza.vue'
import Extra from './views/mextra.vue'

export default {
  name: "Main",
  data() {
    return {
    }
  },
  components: {
    Pizza,
    Extra,
  },
}
</script>

<template>

  <Pizza></Pizza>
  <Extra></Extra>

</template>

<style lang="scss">
@import '../../style/main.scss';
</style>