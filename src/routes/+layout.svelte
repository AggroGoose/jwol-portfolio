<script>
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Josh Walter Portfolio</title>
	<meta name="description" content="Developer portfolio for Josh Walter" />
</svelte:head>

<main class="bg-tn-bg min-h-screen max-w-screen">
	{@render children()}
</main>
