<script>
	import { page } from '$app/state';

	let domain = $derived(page.url.origin);
</script>

<main class="flex h-screen w-screen items-center justify-center">
	<h1 class="font-mono text-5xl font-black">{domain}</h1>
</main>
