<script>
	export let year;
	export let description;
	
</script>

<style>
	.top {
		justify-content: space-between;
		align-items: baseline;
	}

	.top-right,
	.top-left {
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}

	.top-right {
		align-items: flex-end;
		font-size: 0.9em;
		color: #000;
	}
</style>


<div class="honors-detail detail-container">
	<div class="top">
		<div class="top-left">
		{#if description}
			<div class="research">{description}</div>
		{/if}
		</div>
		<div class="top-right">
			{#if year}
				<div class="dates">{year}</div>
			{/if}
		</div>
	</div>
	<div class="bottom">
	<!-- if want further description -->
	</div>
</div>
