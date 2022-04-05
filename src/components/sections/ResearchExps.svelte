<script>
	import ResearchExp from '../items/ResearchExp.svelte';
	export let details;
</script>

<div>
	{#each details as { title, institution, icon, url, link, dates, location, advisor, research, list }}
		<ResearchExp {title} {institution} {icon} {url} {link} {dates} {location} {advisor} {research} {list} />
	{/each}
</div>
