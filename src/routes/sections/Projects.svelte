<script>
	import GansoServer from './projects/GansoServer.svelte';
	import HoyMami from './projects/HoyMami.svelte';
	import MultiStepForm from './projects/MultiStepForm.svelte';
	import Sarcastonaut from './projects/Sarcastonaut.svelte';
</script>

<div class="mx-auto flex flex-col items-center gap-8 py-6 max-lg:px-4 lg:w-[900px]">
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
