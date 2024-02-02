<script>
	export let link = false
</script>

{#if isLink}
<a href=link>
	<slot />
</a>
{:else}
<div>
	<slot />
</div>
{/if}