<script>
	import GithubLogo from './SVG/GithubLogo.svelte';
	import LinkedInLogo from './SVG/LinkedInLogo.svelte';
</script>

<div class="text-tn-white flex w-full flex-col bg-black py-6">
	<div class="text-tn-white mx-auto flex w-[900px] flex-col gap-8 text-center">
		<h1 id="Contact" class=" self-center text-4xl font-bold">
			{'<'}<span class="text-tn-red">Contact</span>{'>'}
		</h1>
		<p>
			If you're interested in working with me, you can reach me at <a
				class="text-tn-red hover:text-tn-blue hover:underline"
				href="mailto:josh@jwolmedia.com">josh@jwolmedia.com</a
			>
		</p>
		<div class="text-tn-blue flex gap-8 self-center">
			<a href="https://github.com/AggroGoose" target="_blank"
				><GithubLogo className="h-8 hover:text-tn-white" /></a
			>
			<a href="https://www.linkedin.com/in/joshlwalter/" target="_blank"
				><LinkedInLogo className="h-8 hover:text-tn-white" /></a
			>
		</div>
		<p class="text-sm">
			You can view the repo for <a
				class="text-tn-red hover:text-tn-blue hover:underline"
				href="https://github.com/AggroGoose/jwol-portfolio">this portfolio here.</a
			>
		</p>
	</div>
</div>
