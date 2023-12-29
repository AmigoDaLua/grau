<script>
    export let dandoGrau;
</script>

<div class="container__moto">
    <img class="moto" class:active={dandoGrau} src="/moto.png" alt="motociclista"> 
</div>

<style>
    .active {
    transform: rotate(-45deg);
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    }

  .container__moto{
    align-items: center;
    display: flex;
    flex-direction: column;
    gap: 1em;
    height: 250px;
    margin-top: -17.5rem;
  }

.moto {
    width: 250px;
    -webkit-transition-duration: 1s;
    -moz-transition-duration: 1s;
    -o-transition-duration: 1s;
    transition-duration: 1s;
    -webkit-transition-property: -webkit-transform;
    -moz-transition-property: -moz-transform;
    -o-transition-property: -o-transform;
    transition-property: transform;
}


</style>