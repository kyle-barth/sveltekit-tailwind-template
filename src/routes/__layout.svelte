<script lang="ts">
	import '../app.css';
	import 'tailwindcss/tailwind.css';
	import Header from '$lib/header.svelte';
	import Footer from '$lib/footer.svelte';
</script>

<Header />

<main>
	<slot />
</main>

<Footer />
