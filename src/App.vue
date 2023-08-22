<script>
import HelloWorld from './components/HelloWorld.vue'
//importo il nome del componente
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
import Banner from './components/Banner.vue';


// specifico che voglio usarli nel export default aggiungendo la chiave components con i nomi del componente
export default {
  components: {
    TheHeader,
    TheFooter,
  }

}
</script>

<template>
  
  <TheHeader></TheHeader>
  <main> 
    <div class="container">
      <p>Content goes here </p>

    </div>
    
  </main>
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
</style>
