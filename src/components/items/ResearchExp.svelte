<script>
	import ContactItem from './ContactItem.svelte';
	export let title;
	export let institution;
	export let url;
	export let dates;
	export let location;
	export let advisor;
	export let research;
	export let list;
	export let link;
	export let icon;
	
	// let linkDetail = { text: link };
	export let detail = {
	isLink: true,
	type: 'web',
	icon: icon,
	url: url,
	text: link,
	};
	let locationDetail = { text: location, icon: 'location' };
	
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

<div class="research-exp detail-container">
	<div class="top">
		<div class="top-left">
			<div class="title">{title}</div>
			<div class="institution">{institution}</div>
			{#if url}
				<ContactItem detail={detail} />
			{/if}
		</div>
		<div class="top-right">
			{#if dates}
				<div class="dates">{dates}</div>
			{/if}
			{#if location}
				<ContactItem detail={locationDetail} />
			{/if}
		</div>
	</div>
	<div class="bottom">
		{#if advisor}
			<div class="advisor">{advisor}</div>
		{/if}
		{#if research}
		<div class="research">{research}</div>
		{/if}
		{#if list}
			<ul class="list">
				{#each list as listItem}
					<li class="list-item">{listItem}</li>
				{/each}
			</ul>
		{/if}
	</div>
</div>
