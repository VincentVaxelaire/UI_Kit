<script>
	import { Accordion, AccordionItem } from '$lib/components/accordion';

	const items = [
		{ title: 'title 1', content: 'Content 1' },
		{ title: 'title 2', content: 'Content 2' },
		{ title: 'title 3', content: 'Content 3' }
	];
</script>

<Accordion collapse>
	<AccordionItem open heading="h3" caret-position="right">
		<svelte:fragment slot="title"></svelte:fragment>
		<svelte:fragment slot="content"></svelte:fragment>
	</AccordionItem>
</Accordion>
