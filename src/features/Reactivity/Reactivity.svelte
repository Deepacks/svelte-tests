<script>
	import Assignment from './components/Assignment.svelte';
	import Declaration from './components/Declaration.svelte';
	import Statement from './components/Statement.svelte';
	import UpdateObjects from './components/UpdateObjects.svelte';
</script>

<section class="primary">
	<h2>Reactivity</h2>

	<section class="secondary">
		<p>Assignments:</p>
		<Assignment />
	</section>

	<section class="secondary">
		<p>Declarations:</p>
		<Declaration />
	</section>

	<section class="secondary">
		<p>Statement:</p>
		<Statement />
	</section>

	<section class="secondary">
		<p>Update Objects:</p>
		<UpdateObjects />
	</section>
</section>
