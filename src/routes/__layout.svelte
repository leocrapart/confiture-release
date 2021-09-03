<script>
	import Header from "$lib/Header.svelte";
	import Nav from "$lib/Nav.svelte";
	import "../styles/tailwind-output.css";
</script>

<Header />
<Nav />

<main>
	<slot />
</main>
