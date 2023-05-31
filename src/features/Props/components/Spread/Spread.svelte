<script>
	import SpreadNested from './SpreadNested.svelte';

	const pkg = {
		name: 'svelte',
		speed: 'blazing',
		version: 3,
		website: 'https://svelte.dev'
	};
</script>

<SpreadNested {...pkg} />
