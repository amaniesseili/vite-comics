<script>
import HelloWorld from './components/HelloWorld.vue'
//importo il nome del componente
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';

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
  <main></main>
  <TheFooter></TheFooter>

  
</template>

<style >

</style>
