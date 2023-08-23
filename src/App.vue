<script>
import HelloWorld from './components/HelloWorld.vue'
//importo il nome del componente
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import Banner from './components/Banner.vue';
import productsList from './db/products.js';



// specifico che voglio usarli nel export default aggiungendo la chiave components con i nomi del componente
export default {
  components: {
    TheHeader,
    TheFooter,
    Banner,
  }
  
  // devo passale productsList in data cosi sono accessibili in html 
  data() {
    return {
      productsList
    }
  },
};

</script>

<template>
  <!-- header -->
  <TheHeader></TheHeader>


  <!--  main -->
  <main> 
    <!-- jumbo -->
    <div class="jumbotron">
      <img class="jumbo-img" src="." alt="">
    </div>

    <!-- contenuto pagina -->
    <div class="container">
      <p>Content goes here </p>
      <div class="row row-cols-6">
        <div class="col" v-for="(product, i) in productsList" :key="`product_${i}`">

          <div class="card border-0 rounded-0">
            <img :src="product.thumb" alt="">

            <div class="card-body">
              {{ product.series }}
            </div>
            

          </div>

        </div>

      </div>
    </div>

    <!-- banner -->
    <Banner></Banner>
  </main>


  <!-- footer -->
  <TheFooter></TheFooter>

  
</template>

<style >
main{
  min-height: 100px;
  background-color: black;
}
p{
  color: white;
  font-size: 20px;
  padding-top: 2rem;
}

.jumbotron{
  height: 400px;
  background-color: aquamarine;
  background-image: url(assets/img/jumbotron.jpg);

}

</style>
