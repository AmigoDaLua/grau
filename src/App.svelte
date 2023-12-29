<script>
  import Background from './components/Background/Background.svelte';
  import BotaoGrau from './components/BotaoGrau/BotaoGrau.svelte';
  import Footer from './components/Footer/Footer.svelte';
  import Header from './components/Logo/Logo.svelte';
  import Moto from './components/Moto/Moto.svelte';
  import Text from './components/Text/Text.svelte';

  // A variável que controla tudo
  let dandoGrau = false; 
</script>

<main>
  <Header />  
  <Background />
  <Moto dandoGrau={dandoGrau} />
  <BotaoGrau bind:dandoGrau />
  <Text />
</main>
  <Footer />




