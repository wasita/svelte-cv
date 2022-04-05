<script>
	export let description;
</script>

<style>
	.simple-detail:last-child {
		margin-bottom: 6px;
	}
</style>

<div class="minimal-detail detail-container">
	<div class="bottom">
		{#if description}
			<div class="description">{description}</div>
		{/if}
	</div>
</div>
