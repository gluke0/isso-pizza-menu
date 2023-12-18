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
  <div class="container">
    <Header></Header>
    <Main></Main>
    <Footer></Footer>
  </div>
</template>

<style lang="scss">

</style>
