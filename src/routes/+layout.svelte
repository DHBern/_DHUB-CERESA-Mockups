<script lang="ts">
	import '../app.css';
	import { base } from '$app/paths';

	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<nav class="fixed top-0 flex min-h-15 w-full flex-wrap gap-x-10 bg-white pt-5 pl-5 font-bold">
	<a class="text-red-300" href={`${base}/markup-guide`}>Guide</a>
	<a href={`${base}/docs/eloisa1`}>Eloisa frammento 1</a>
	<a href={`${base}/docs/eloisa2`}>Eloisa frammento 2</a>
	<a href={`${base}/docs/poesie`}>Poesie</a>
	<a href={`${base}/docs/adamo`}>Adamo</a>
	<a href={`${base}/docs/anima`}>Anima</a>
	<a href={`${base}/docs/aborto`}>Aborto</a>
	<a href={`${base}/docs/carson-de`}>Carson McCullers (de)</a>
	<a href={`${base}/docs/carson-it`}>Carson McCullers (it)</a>
</nav>

<div class="mx-auto mt-50 mb-100 max-w-250">
	{@render children()}
</div>
