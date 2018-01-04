<template>
  <section class="cartao" text-align="center">
    <div class="col-50">
      <div class="minha-imagem">
        <img src="../../assets/img/visa.png">
      </div>
    </div>
    <div class="col-50">
       <div class="area-valor">
          <p> R$: 900 </p>
       </div>
    </div>
    <div class="numero-cartao">
        <p> 4230 1982 9823 1920 </p>
    </div>
    <div class="validade">
      <p> Validade : <span> 22/02 </span> </p>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'cartao',
    data(){
       return {

      }
    },
  }
</script>

<style scoped>
  .validade {
    width: 80%;
    margin:auto;
    color: #00000070;
  }
  .validade p {
    font-size: 85%;
  }
  .numero-cartao{
    height: 30%;
    width:80%;
    margin:auto;
    clear:both;
  }
  .numero-cartao p{
    line-height: 3;
    color: #00000070;
  }
  .cartao{
    border-radius: 10px;
    height: 9rem;
    width: 80%;
    background-color:white;
    margin:auto;
  }

  .minha-imagem{
    margin-left: 0.5rem;
    width: 37%;
  }
  .area-valor{
    font-size: 130%;
    padding-top: 1.2rem;
    padding-right:1.5rem;
    float: right;
  }
  img{
    max-width: 100%;
  }
  .col-50{
    margin-left: 4px;
    margin-top: 1rem;
    float:left;
    width: 48%;
  }
</style>
