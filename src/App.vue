<template>
  <div id="app">
    <h1 class="title">CALCULATOR</h1>
    <Calculator />
  </div>
  <router-view/>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: "app",
  components: {
    Calculator
  }
}
</script>

<style>
.title {
  height: 50px;
  justify-content: center;
  align-items: center;
  display: flex;
  border-bottom: 1px solid orangered;
}
</style>
