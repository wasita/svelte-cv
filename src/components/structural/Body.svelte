<script>
	import SideColumn from './SideColumn.svelte';
	import MainColumn from './MainColumn.svelte';

	export const sideColumn = [
		{
			type: 'contact',
			label: 'Contact',
			details: [
				{
					subcategory: 'Say hi',
					contactDetails: [
						{
							isLink: true,
							type: 'email',
							text: 'wasita.gr@dartmouth.edu',
							icon: 'email',
						},
						{
							text: 'Hanover, NH',
							icon: 'location',
						},
					],
				},
				{
					subcategory: 'Find me online',
					contactDetails: [
						{
							isLink: true,
							type: 'web',
							url: 'wasita.space',
							text: 'wasita.space',
						},
						{
							isLink: true,
							type: 'web',
							url: 'github.com/wasita',
							text: '/wasita',
							icon: 'github',
						},
						{
							isLink: true,
							type: 'web',
							url: 'linkedin.com/in/wasita-mahaphanit/',
							text: '/wasita-mahaphanit',
							icon: 'linkedin',
						},
					],
				},
			],
		},
		{
			type: 'skills',
			label: 'Skills',
			details: [
				'MATLAB',
				'PsychToolBox',
				'Python',
				'PsychoPy',
				'R',
				'JavaScript (ES6)',
				'JsPsych',
				'React',
				'Svelte',
				'NodeJS',
				'Firebase',
				'Socket.io',
				'HTML',
				'CSS',
				'Git'
			],
		}
	];
	export const mainColumn = [
			{
			type: 'minimal-details',
			label: 'Research Interests',
			details: [
				{
					description: 'Social learning, cognitive maps, communication, group decision-making, memory. I aim to use a combination of behavioral experiments, neuroimaging, and computational modeling to explore these interests.',
				},
			]
		},
		{
			type: 'full-details',
			label: 'Education',
			details: [
				{
					title: 'Ph.D. Student in Cognitive Neuroscience',
					subtitle: 'Dartmouth College | cosanlab.com',
					dates: '2021 - Present',
					location: 'Hanover, NH',
				},
				{
					title: 'B.S., Cognitive Neuroscience (Honors)',
					subtitle: 'Brown University | shenhavlab.org',
					dates: '2014 — 2018',
					location: 'Providence, RI',
				},
			],
		},
	];
</script>

<style>
	div {
		display: flex;
		justify-content: space-between;
		flex-direction: var(--column-order);
		margin: 0 var(--horizontal-offset);
	}
</style>

<div class="main-body">
	<MainColumn sections={mainColumn} />
	<!-- Maybe care to bring back for now prefer 1 column -->
	<!-- <SideColumn sections={sideColumn} /> -->
</div>
