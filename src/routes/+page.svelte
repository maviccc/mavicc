<script>
	import Button from "$lib/Button.svelte";
	console.log('rendering');
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="container bg-green-100 m-auto">
	<h1 class="bg-slate-600 text-5xl text-white">mavic page</h1>
	<Button>Click me</Button>
</section>


<style lang="postcss">
	:global(html) {
	  background-color: theme(colors.gray.100);
	}
</style>