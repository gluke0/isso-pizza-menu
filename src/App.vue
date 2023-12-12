<script >

import Header from '../src/assets/components/header.vue';
import Main from '../src/assets/components/main.vue';
import Footer from '../src/assets/components/footer.vue';

export default {
  name: "App",
  data() {
    return {
    }
  },
  components: {
    Header,
    Main,
    Footer,
  },
}

</script>



<template>
  <Header></Header>
  <Main></Main>
  <Footer></Footer>
</template>

<style lang="scss">

</style>
