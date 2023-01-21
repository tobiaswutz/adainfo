<script lang="ts">
	import Select from '../lib/components/Select.svelte';
	let current: number = 1;
</script>

<div class="bg-green-900 p-12 flex flex-col gap-4 w-full sm:flex-row">
	<div class="w-full">
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
	</div>
	<div class="w-full">
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
		<Select bind:current choices={[1, 2, 3, 4, 5]} />
	</div>
</div>

<div class="bg-green-900 p-12 flex flex-col gap-4 w-full sm:flex-row">
	<input type="search" />
</div>
