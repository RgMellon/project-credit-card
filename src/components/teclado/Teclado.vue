<template>
  <section class="teclado">
    <div class="area-teclado">
      <div class="wrapper-teclado">
          <div v-for="item of numeros" class="botoes">
              <p> {{ item }} </p>
          </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'teclado',
    data(){
       return {
        numeros: [1, 2, 3, 4, 5, 6, 7, 8, 9, "", 0]
      }
    },
  }
</script>

<style scoped>
  .teclado{
    margin-top: 4rem;
  }
  .area-teclado{
    width: 80%;
    margin: auto;
  }
  .wrapper-teclado{
    clear:both;
    width: 90%;
    background-color:red;
    margin:auto;
  }
  .botoes{
    line-height: 2;
    height: 4rem;
    width: 29.333%;
    text-align: center;
    padding: 4px;
    float: left;
  }
  .botoes p{
    color: #00000070;
    font-size: 150%;
    padding: 0.5rem;
  }
</style>
