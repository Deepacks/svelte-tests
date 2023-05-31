<script>
	import DeclaringDefault from './components/DeclaringDefault.svelte';
	import Spread from './components/Spread/Spread.svelte';
</script>

<section class="primary">
	<h2>Props</h2>

	<section class="secondary">
		<p>Declaring & Default Value:</p>
		<DeclaringDefault answer={'42'} />
		<DeclaringDefault />
	</section>

	<section class="secondary">
		<p>Props Spread:</p>
		<Spread />
	</section>
</section>
