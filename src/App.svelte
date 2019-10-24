
<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<a class="button is-primary" on:click={handleClick}>
	Clicked {count} {count === 1 ? 'time' : 'times'}
</a>
<button on:click={handleClick}>
	Clicked {count} {count === 1 ? 'time' : 'times'}
</button>