<script>
	import GithubLogo from './SVG/GithubLogo.svelte';
	import LinkedInLogo from './SVG/LinkedInLogo.svelte';
</script>

<div class="mx-auto flex items-center gap-4 py-12 max-lg:flex-col max-lg:px-4 lg:w-[900px]">
	<div class="flex flex-col gap-8 lg:basis-3/4">
		<h1 class="text-tn-white text-4xl font-bold">
			Hello, I'm <span class="text-tn-blue">Josh Walter</span>
		</h1>
		<p class="text-tn-white text-lg">
			I'm a problemologist and tech enthusiast with a background in project management and customer
			support looking to become a frontend developer.
		</p>
		<div class="text-tn-blue flex gap-8 self-center">
			<a href="https://github.com/AggroGoose" target="_blank"
				><GithubLogo className="h-10 hover:text-tn-white" /></a
			>
			<a href="https://www.linkedin.com/in/joshlwalter/" target="_blank"
				><LinkedInLogo className="h-10 hover:text-tn-white" /></a
			>
		</div>
	</div>
	<div class="max-lg:max-w-[50vw] lg:basis-1/4">
		<img
			class="rounded-full"
			src="/Images/JoshBowtie.png"
			alt="man wearing a pink shirt and bowtie"
		/>
	</div>
</div>
