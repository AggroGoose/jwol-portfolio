<script>
	import GansoServer from './projects/GansoServer.svelte';
	import HoyMami from './projects/HoyMami.svelte';
	import MultiStepForm from './projects/MultiStepForm.svelte';
	import Sarcastonaut from './projects/Sarcastonaut.svelte';
</script>

<div class="mx-auto flex w-[900px] flex-col items-center gap-8 py-6">
	<h1 id="projects" class="text-tn-white self-center text-4xl font-bold">
		{'<'}<span class="text-tn-red">Projects</span>{'>'}
	</h1>
	<Sarcastonaut />
	<GansoServer />
	<HoyMami />
	<MultiStepForm />
	<h1 class="text-tn-white self-center text-4xl font-bold">
		{'</'}<span class="text-tn-red">Projects</span>{'>'}
	</h1>
</div>
