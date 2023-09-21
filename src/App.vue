<!--
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.✔️
Modificate il componente App.vue, che deve usare l'option api, e poi nel template stampate in pagina un titolo hello Vite ✔️
Bonus:
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" ✔️
Creare un secondo componente AppHero, che visualizza un jumbotron.-->

<script>
import AppTitle from './components/AppTitle.vue';


export default {
  data() {
    return {
      message: 'Hello Vite!'
    };
  },
  components: { AppTitle }
}
</script>

<template>
  <AppTitle />
  <h1>{{ message }}</h1>
</template>

<style>
h1 {
  color: white;
}
</style>
