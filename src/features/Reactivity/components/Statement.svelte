<script>
	let count = 0;

	$: if (count >= 10) {
		alert('Count is dangerously high!');
		count = 0;
	}

	function increment() {
		count += 1;
	}
</script>

<button on:click={increment}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>
