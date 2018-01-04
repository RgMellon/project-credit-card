<template>
  <div id="app">
  <area-cartao> </area-cartao>
  <teclado> </teclado>
  </div>
</template>

<script>
import AreaCartao from './components/cartao/AreaCartao';
import Teclado from './components/teclado/Teclado';
export default {
  name: 'app',
  components: {
    'area-cartao': AreaCartao,
    'teclado': Teclado
  },
  data () {
    return {

    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
