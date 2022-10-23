<!-- https://svelte.dev/tutorial/dynamic-attributes -->

<script>
    let src = '/tutorial/image.gif';
    let name = 'A man dances.';
</script>

<img {src} alt="{name}">
