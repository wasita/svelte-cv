<script>
	import Contact from '../sections/Contact.svelte';
	import Skills from '../sections/Skills.svelte';
	import FullDetails from '../sections/FullDetails.svelte';
	import SimpleDetails from '../sections/SimpleDetails.svelte';
	import MinimalDetails from '../sections/MinimalDetails.svelte';
	import ResearchExps from '../sections/ResearchExps.svelte';
	import TeachingExps from '../sections/TeachingExps.svelte';
	import PressieDetails from '../sections/PressieDetails.svelte';
	import HonorsDetails from '../sections/HonorsDetails.svelte';

	export let label;
	export let details;
	export let type;
</script>

<div class="section">
	<h2 class="section-label">{label}</h2>
	<hr class="section-underline" />
	{#if type === 'simple-details'}
		<SimpleDetails {label} {details} />
	{:else if type === 'minimal-details'}
		<MinimalDetails {details} />
	{:else if type === 'pressie-details'}
		<PressieDetails {details} />
	{:else if type === 'full-details'}
		<FullDetails {details} />
	{:else if type === 'research-exps'}
		<ResearchExps {details} />
	{:else if type === 'teaching-exps'}
		<TeachingExps {details} />
	{:else if type === 'honors-details'}
		<HonorsDetails {details} />
	{:else if type === 'skills'}
		<Skills {label} {details} />
	{:else if type === 'contact'}
		<Contact {label} {details} />
	{/if}
</div>
