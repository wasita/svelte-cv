<script>
	import HonorsDetail from '../items/HonorsDetail.svelte';
	export let details;
</script>

<div>
	{#each details as { year, description }}
		<HonorsDetail {year} {description} />
	{/each}
</div>
