<script>
	let fassung = $state('LF');
	let { children } = $props();
</script>

<button
	onclick={() => {
		fassung = fassung == 'DF' ? 'LF' : 'DF';
	}}
	class={[
		'pointer fixed top-30 left-20 rounded-full p-2 px-5 font-bold',
		fassung == 'DF' ? 'bg-red-200' : 'bg-blue-200'
	]}>{fassung == 'DF' ? 'change to LF' : 'change to DF'}</button
>

<div data-fassung={fassung}>
	{@render children()}
</div>
