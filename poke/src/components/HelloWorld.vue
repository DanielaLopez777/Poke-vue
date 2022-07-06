<template>
  <div class="hello">
    <h1>Pokedex en VUE </h1>
    <form action="">
      <input type="text">
      <button>Buscar</button>
    </form>
    <div class="card" style="width: 18rem;">
      <img src="" class="card-img-top" alt="">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .card{
    margin-left: 480px;;
    margin-top: 100px;
  }
  

</style>
