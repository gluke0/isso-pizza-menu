<script>

export default {
  name: "contacts",
  data() {
    return {
    }
  },
  components: {
    
  },
}
</script>

<template>
    
    <div class="">
      <div>
        <a target="_blank" href="https://maps.app.goo.gl/GWR7UsDnFQ4gR2rbA">
          <div class="namep"> <h1>L'Angolo Della Pizza di Mapy </h1> </div> 
      
          <div>  <i> Via Cascina Secchi, 516 </i> </div>
      
          <div> <i> 24058 Isso BG </i> </div> 
        </a>
      </div>                

      <br>
      <div class="calling"> <a target="_blank" class="text-black text-decoration-none" href="tel:+393895468163"><i> <b> <i class="fa-solid fa-phone"></i> +39 389 5468163 </b> </i> </a> </div>
    </div>

</template>

<style lang="scss">
.calling{
  font-size: x-large;
  cursor: pointer;
}

.calling:hover{
  transform: scale(1.03);
}

a{
  text-decoration: none!important;
  color: black!important;
}

</style>