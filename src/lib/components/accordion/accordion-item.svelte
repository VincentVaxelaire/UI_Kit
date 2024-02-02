<script>
	export let open = false
    export let heading = h3
    export let caretPosition = right
</script>

<div>
	<button>
		<div>
			<slot name="title" />
		</div>

		<div class="accordion-caret">👉️</div>
	</button>

	{#if isOpen}
		<div>
			<slot name="content" />
		</div>
	{/if}
</div>