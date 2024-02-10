<script>
  import "../app.css";
	import Navbar from '$lib/Navbar.svelte'
// import Footer from '$lib/Footer.svelte'
</script>

<svelte:head>
    <title>Portix</title>
</svelte:head>

<div class="layout">
  <Navbar />
  <slot />
</div>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.900);
  }
</style>