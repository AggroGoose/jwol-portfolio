<script>
	import '../app.css';

	let { children } = $props();
</script>

<main class="bg-tn-bg min-h-screen">
	{@render children()}
</main>
