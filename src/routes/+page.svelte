<script lang="ts">
	import ThreeD from '../components/ThreeD.svelte';
	import type { TypedItem } from '../components/typewriter/types';
	import Typewriter from '../components/typewriter/Typewriter.svelte';

	let typedLines: Array<TypedItem> = [
		{ text: 'React' },
		{ text: 'PHP' },
		{ text: 'SQL' },
		{ text: 'AWS' },
		{ text: 'Svelte' },
		{ text: 'Z80 Assembly', url: 'https://z80.yarbsemaj.com' },
		{ text: 'CSS' },
		{ text: 'SASS' },
		{ text: 'NodeJS' },
		{ text: 'Serverless' },
		{ text: 'HTML' },
		{ text: 'Dynamodb' },
		{ text: 'Lambda' },
		{ text: 'Webpack' },
		{ text: 'AngularJS' },
		{ text: 'Tiny CPU ASM', url: 'https://tiny-cpu-emu.yarbsemaj.com' },
		{ text: 'Javascript' },
		{ text: 'Java' },
		{ text: 'Tailwindcss' }
	];
</script>

<ThreeD />

<div class="h-screen flex flex-col justify-center items-center z-10 relative">
	<div class="text-center">
		<h1
			class="md:text-9xl text-5xl font-extrabold text-transparent bg-clip-text bg-gradient-to-br from-zinc-100 to-stone-400"
		>
			Hello there!
		</h1>
		<div class="md:text-2xl text-xl md:my-5 my-2">
			I'm Rythmn Magnani, a full stack software engineer with taste for the retro
		</div>
		<!-- <Typewriter className="sm:text-5xl text-3xl font-bold font-mono" {typedLines} /> -->

		<div class="flex justify-center md:my-5 my-2">
			<a alt="Github" class="sm:text-8xl text-5xl p-4 sm:px-9" href="https://github.com/rythmn1111">
				<i class="fa-brands fa-github" />
			</a>
			<a
				alt="Linkedin"
				class="sm:text-8xl text-5xl p-4 sm:px-9"
				href="https://www.linkedin.com/in/rythmn-magnani-8240ba210/"
			>
				<i class="fa-brands fa-linkedin" />
			</a>
			<a sveltekit:prefetch class="sm:text-8xl text-5xl p-4 sm:px-9" alt="Blog" href="https://twitter.com/soloknight05">
				<i class="fa-solid fa-book-skull" />
			</a>
		</div>
	</div>
	
</div>
