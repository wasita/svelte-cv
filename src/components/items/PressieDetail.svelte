<script>
	export let description;
	export let author = 'Mahaphanit, W.';
	export let preWM;
	export let postWM;
	export let year;
</script>

<style>
	.pressie-details:last-child {
		margin-bottom: 6px;
	}
</style>

<div class="pressie-details detail-container">
	<div class="bottom">
		{#if description}
			{#if preWM}
				<div class="description">{preWM} <b>{author}</b>, {postWM} ({year}). {description}</div>
			{:else if postWM}
				<div class="description"><b>{author}</b>, {postWM} ({year}). {description}</div>
			{:else}
				<div class="description"><b>{author}</b> ({year}). {description}</div>
			{/if}
		{/if}
	</div>
</div>

