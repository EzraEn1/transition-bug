<script lang="ts">
	import { fade } from 'svelte/transition';
</script>

<main class="flex flex-col min-h-full" out:fade={{ duration: 150 }}>
	<slot />
</main>
