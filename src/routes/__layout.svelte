<script>
	import Header from "$lib/Header.svelte";
	import Nav from "$lib/Nav.svelte";
	import "../app.css";
</script>

<Header />
<Nav />

<main>
	<slot />
</main>
