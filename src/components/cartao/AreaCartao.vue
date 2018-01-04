<template>
  <section class="area-cartao">
    <my-card></my-card>
  </section>
</template>

<script>
  import Cartao from './Cartao';
  export default {
    components: {
      'my-card': Cartao,
    },
    name:'area-cartao',
    data(){
      return {

      }
    },
  }
</script>

<style scoped>
  .area-cartao{
    background-color: #00d3ae;
    padding: 1rem;
  }

</style>
