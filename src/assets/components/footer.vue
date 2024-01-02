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

  <div class="justify-content-around d-flex">
    <div class="footerino">
      <div> <b><i>L'Angolo Della Pizza di Mapy </i></b> </div> 
      
      <div>  <i> Via Cascina Secchi, 516 </i> </div>
      
      <div> <i> 24058 Isso BG </i> </div>
      
      <div> P. IVA 04604600165 </div>

    </div>
    <div class="credits">
      <div>
        <b><i>Made with <i class="fa-solid fa-laptop-code"></i> by: </i></b>
      </div>
      <div>
        <i><a href="https://www.github.com/gluke0" target=”_blank” class="text-black text-decoration-none ms-4"> <i class="fa-brands fa-square-github"></i> gluke</a></i>
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