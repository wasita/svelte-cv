<script>
	export let description;
</script>

<style>
	.minimal-details:last-child {
		margin-bottom: 6px;
	}
</style>

<div class="minimal-details detail-container">
	<div class="bottom">
		{#if description}
			<div class="description">{description}</div>
		{/if}
	</div>
</div>
