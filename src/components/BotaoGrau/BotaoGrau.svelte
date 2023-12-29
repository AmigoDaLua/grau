<script>
    export let dandoGrau;
</script>

<button on:click={() => {dandoGrau = !dandoGrau}} class="botao__grau">{ dandoGrau ? "parar grau" : "dar grau!"}</button>

<style>
 .botao__grau{
    border: 2px solid orangered;
    color: white;
    background-color: orangered;
  }

  .botao__grau:hover {
  border: 2px solid orangered;
  color: orangered;
  background-color: white;
}


  .botao_grau{
    background-color: rgba(241, 106, 33, 0.7);
    color: white;
  }

</style>