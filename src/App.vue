<template>
  <div id="app">
    <h3>Projecto 1 - Produccion de Software y normativas de propiedad intelecual</h3>
    <p>Contador: {{ counter }}</p>
    <button @click="counter++">Incrementar</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0
    };
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
