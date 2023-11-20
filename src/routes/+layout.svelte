<script>
	import Header from './Header.svelte';
	import '../app.postcss';
	import Footer from './Footer.svelte';
</script>

<div class="">
	<Header />

	<main class="min-h-screen">
		<slot />
	</main>

	<Footer />
</div>
