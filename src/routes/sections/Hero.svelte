<script>
	import GithubLogo from './SVG/GithubLogo.svelte';
	import LinkedInLogo from './SVG/LinkedInLogo.svelte';
</script>

<div class="mx-auto flex w-[900px] items-center gap-4 pt-12">
	<div class="flex basis-3/4 flex-col gap-8">
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
	<div class="basis-1/4">
		<img
			class="rounded-full"
			src="/Images/JoshBowtie.png"
			alt="man wearing a pink shirt and bowtie"
		/>
	</div>
</div>
