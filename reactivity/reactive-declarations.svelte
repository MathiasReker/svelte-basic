<!-- https://svelte.dev/tutorial/reactive-declarations -->

<script>
    let count = 0;

    function handleClick() {
        ++count;
    }
</script>

<button on:click={handleClick}>
    Clicked {count} {count === 1 ? 'time' : 'times'}
</button>