<script>

export default {
  name: "Footer",
  data() {
    return {
    }
  },
  components: {
    
  },
}
</script>

<template>

  <div class="justify-content-center d-flex py-5">
    <div class="credits">
      <div>
        <b><i>Made in 2024 with <i class="fa-solid fa-laptop-code"></i> by: </i></b>
      </div>
      <div class="d-flex justify-content-center">
        <i><a href="https://www.github.com/gluke0" target=”_blank” class="text-black text-decoration-none"> <i class="fa-brands fa-square-github"></i> gluke</a></i>
      </div>
      <br>
    </div>
  </div>

</template>

<style lang="scss">
@import '../../style/main.scss';

.footerino{
  font-size: smaller
}

.credits{
  font-size: smaller;
}

#cci{
  font: black!important;
}
</style>