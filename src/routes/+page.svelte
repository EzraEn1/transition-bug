<script>
	import { goto } from "$app/navigation";
	import Layout from "$lib/Layout.svelte";


  function goPlaces() {
    goto('/places')
  }
</script>

<Layout>
  <h1>You are Home</h1>
  <button on:click={goPlaces}>
    Go Places
  </button>
</Layout>