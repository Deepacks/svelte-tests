<script>
	import Nested from '../components/1-introduction/Nested.svelte';
	import Assignment from '../components/2-reactivity/Assignment.svelte';
	import Declaration from '../components/2-reactivity/Declaration.svelte';
	import Statement from '../components/2-reactivity/Statement.svelte';
	import UpdateObjects from '../components/2-reactivity/UpdateObjects.svelte';
</script>

<main>
	<section class="primary">
		<h2>1. Introduction</h2>

		<section class="secondary">
			<p>1.1 Nested Component:</p>
			<Nested />
		</section>
	</section>

	<section class="primary">
		<h2>2. Reactivity</h2>

		<section class="secondary">
			<p>2.1 Assignments:</p>
			<Assignment />
		</section>

		<section class="secondary">
			<p>2.2 Declarations:</p>
			<Declaration />
		</section>

		<section class="secondary">
			<p>2.3 Statement:</p>
			<Statement />
		</section>

		<section class="secondary">
			<p>2.4 Update Objects:</p>
			<UpdateObjects />
		</section>
	</section>
</main>

<style>
	main {
		height: 100%;
	}

	h2 {
		margin-bottom: 10px;
	}

	section.primary {
		border: 2px solid red;
		margin-bottom: 20px;
	}

	section.secondary {
		border-bottom: 1px solid red;
	}

	section.secondary:last-of-type {
		border-bottom: none;
	}

	section > p {
		font-weight: 600;
	}
</style>
