<script lang="ts">
  import Router from 'svelte-spa-router';
  import Navbar from './lib/Navbar.svelte';
  import Footer from './lib/Footer.svelte';

  // Routes
  import Home from './routes/Home.svelte';
  import Bio from './routes/Bio.svelte';
  import Experience from './routes/Experience.svelte';
  import Portfolio from './routes/Portfolio.svelte';
  import NotFound from './routes/NotFound.svelte';

  const routes = {
    "/": Home,
    "/bio": Bio,
    "/experience": Experience,
    "/portfolio": Portfolio,

    "*": NotFound 
  }
</script>

<Navbar />
<main>
  <Router {routes}/>
</main>
<Footer />
<style>
</style>