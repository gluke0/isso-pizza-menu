<script>

export default {
  name: "extra",
  data() {
    return {
    }
  },
  components: {
    
  },
}
</script>

<template>
    
    <div>
      <h3 class="text-uppercase">piccola gastronomia d'asporto</h3>
      <h5>Dal martedì al venerdì solo a pranzo</h5>

      <div class="list d-flex justify-content-between">
        <div>
          <ul class="ps-0">
            <li class="oddy">Panzerotti assortiti <span class="det">cad.</span></li>
            <li>Patatine <span class="det">por.</span></li>
            <li class="oddy">Olive ascolane <span class="det">pz 8</span></li>
            <li>Mozzarelline <span class="det">pz 8</span></li>
            <li class="oddy">Stik di pollo <span class="det">pz 8</span></li>
            <li>Crocchette di patate <span class="det">pz 8</span></li>
          </ul>
        </div>
        <div>
          <ul class="">
            <li class="oddy">€ 4,50</li>
            <li>€ 2,50</li>
            <li class="oddy">€ 4,00</li>
            <li>€ 3,50</li>
            <li class="oddy">€ 4,00</li>
            <li>€ 3,50</li>
          </ul>
        </div>
      </div>
    </div>

</template>

<style lang="scss">

li{
  list-style: none;
}

h5{
  color: rgb(40, 85, 89)!important;
  font-style: italic;
}

</style>