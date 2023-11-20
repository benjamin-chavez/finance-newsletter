<script>
	import Header from './Header.svelte';
	import '../app.postcss';
	import Footer from './Footer.svelte';
</script>

<div class="">
	<Header />

	<main>
		<slot />
	</main>

	<Footer />
</div>
