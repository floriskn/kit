<script>
	let { children } = $props();
</script>

<a href="/params-prop/123" data-sveltekit-preload-data="hover">123</a>
<a href="/params-prop/456" data-sveltekit-preload-data="hover">456</a>

{@render children()}
