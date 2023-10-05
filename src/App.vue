<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <p class="h3 text-success fw-bold">App component</p>
        <p class="fst-italic">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt necessitatibus eligendi, quae ea adipisci qui in nostrum? Quo velit nostrum similique maiores pariatur, culpa dolores! Ab minima ipsa quasi pariatur.</p>
      </div>
    </div>

    <Counter/>
    <Greetings/>

  </div>
</template>

<script>

import Counter from './components/Counter.vue';
import Greetings from './components/Greetings.vue';

export default {
  name: 'App',
  components: {
    Counter,
    Greetings,
},
  data: function(){

    }
}

</script>

<style scoped>

</style>