<template>
 <div id="app">
  <h3>What is your favorite kind of taco?</h3>
  <p v-html="tacos"></p>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  data() {
    return {
      tacos: `I like <a href="http://www.epicurious.com/recipes/food/views/tacos-al-pastor-242132" target="_blank">Al Pastor</a> tacos`
    }
  }
}
</script>
