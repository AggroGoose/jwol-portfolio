<script>
	import DrizzleIcon from './SVG/DrizzleIcon.svelte';
	import FigmaIcon from './SVG/FigmaIcon.svelte';
	import GolangIcon from './SVG/GolangIcon.svelte';
	import JavascriptIcon from './SVG/JavascriptIcon.svelte';
	import MongoIcon from './SVG/MongoIcon.svelte';
	import NextjsIcon from './SVG/NextjsIcon.svelte';
	import PostgresIcon from './SVG/PostgresIcon.svelte';
	import PythonIcon from './SVG/PythonIcon.svelte';
	import ReactIcon from './SVG/ReactIcon.svelte';
	import SvelteIcon from './SVG/SvelteIcon.svelte';
	import TypescriptIcon from './SVG/TypescriptIcon.svelte';
</script>

<div class="bg-tn-t2 w-full">
	<div class="text-tn-bg mx-auto flex flex-col items-center gap-8 py-6 max-lg:px-4 lg:w-[900px]">
		<h1 id="stack" class="text-tn-white self-center text-4xl font-bold">
			{'<'}<span class="text-tn-red">Stack</span>{'>'}
		</h1>
		<h2 class="text-tn-white text-2xl font-bold">Languages</h2>
		<div class="flex flex-wrap justify-center gap-4">
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><JavascriptIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Javascript</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><TypescriptIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Typescript</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><PythonIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Python</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><GolangIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Go</p>
			</div>
		</div>
		<h2 class="text-tn-white text-2xl font-bold">Frameworks</h2>
		<div class="flex flex-wrap justify-center gap-4">
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><ReactIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">React</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><NextjsIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">NextJS</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><SvelteIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Svelte</p>
			</div>
		</div>
		<h2 class="text-tn-white text-2xl font-bold">Tools</h2>
		<div class="flex flex-wrap justify-center gap-4">
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><PostgresIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Postgres</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><MongoIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">MongoDB</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><FigmaIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">Figma</p>
			</div>
			<div
				class="bg-tn-light flex h-28 w-28 flex-col items-center justify-center gap-2 rounded-full"
			>
				<div><DrizzleIcon className="h-10 w-10" /></div>
				<p class="text-sm font-bold">DrizzleORM</p>
			</div>
		</div>
		<h1 class="text-tn-white self-center text-4xl font-bold">
			{'</'}<span class="text-tn-red">Stack</span>{'>'}
		</h1>
	</div>
</div>
