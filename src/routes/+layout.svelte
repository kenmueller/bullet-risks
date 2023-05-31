<script lang="ts">
	import margo from '$lib/margo.jpg'

	import './layout.scss'
</script>

<svelte:head>
	<link rel="icon" href={margo} />
</svelte:head>

<slot />
