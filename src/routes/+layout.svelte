<script>
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	import '@skeletonlabs/skeleton/styles/all.css';
	import "../app.postcss";
</script>

<main class="container">
  	<slot />
</main>

<style>
	main {
		padding: 0;
		max-width: none;
	}
</style>
