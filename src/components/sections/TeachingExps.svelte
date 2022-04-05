<script>
	import TeachingExp from '../items/TeachingExp.svelte';
	export let details;
</script>

<div>
	{#each details as { title, institution, dates, location, advisor, description, list }}
		<TeachingExp {title} {institution} {dates} {location} {description} {advisor} {list} />
	{/each}
</div>
