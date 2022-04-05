<script>
	import MainColumn from './MainColumn.svelte';

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
					title: 'Dartmouth College',
					subtitle: 'Ph.D. Student in Cognitive Neuroscience',
					dates: '2021 - Present',
					location: 'Hanover, NH',
					description: 'Advisor: Luke J. Chang',
				},
				{
					title: 'Brown University',
					subtitle: 'B.S., Cognitive Neuroscience (Honors)',
					dates: '2014 — 2018',
					location: 'Providence, RI',
					description: 'Advisor: Amitai Shenhav'
				},
			],
		},
		{
		type: 'research-exps',
		label: 'Research Experience',
		details: [
			{
				title: 'Graduate Student Researcher',
				institution: 'Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)',
				url: 'cosanlab.com',
				link: 'cosanlab.com',
				dates: '2021 - Present',
				location: 'Hanover, NH',
				advisor: 'Advisor: Luke J. Chang',
				research: 'Research focuses: communication, social cognitive maps, social learning, decision-making',
			},
			{
				title: 'Lab Manager/Research Assistant',
				institution: 'Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)',
				url: 'lnccbrown.com',
				link: 'lnccbrown.com',
				dates: '2018 - 2021',
				location: 'Providence, RI',
				advisor: 'Advisor: Michael J. Frank',
				research: 'Research focuses: computational psychiatry, reinforcement learning, decision-making'
			},
			{
				title: 'Undergraduate Research Assistant',
				institution: 'Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)',
				url: 'shenhavlab.org',
				link: 'shenhavlab.org',
				dates: '2016 — 2018',
				location: 'Providence, RI',
				advisor: 'Advisor: Amitai Shenhav',
				research: 'Research focuses: cognitive control, performance monitoring, task-switching'
			},
			{
				title: 'Summer Undergraduate Research Intern',
				institution: 'Providence VA Medical Center',
				url: 'https://vivo.brown.edu/display/nphilip',
				link: 'vivo.brown.edu/display/nphilip',
				dates: '2016 — 2018',
				location: 'Providence, RI',
				advisor: 'Advisor: Noah Philip',
				research: 'Research focuses: major-depressive disorder, post-traumatic stress disorder'
			},
		],
	},
	{
		type: 'teaching-exps',
		label: 'Teaching Experience',
		details: [
			{
				title: 'Graduate Teaching Assistant',
				institution: 'Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)',
				dates: 'Spring 2022',
				location: 'Hanover, NH',
				description: 'Emotion',
				advisor: 'Mark Thornton',
			},
			{
				title: 'Graduate Teaching Assistant',
				institution: 'Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)',
				dates: 'Fall 2021',
				location: 'Hanover, NH',
				description: 'Principles of Human Brain Mapping with fMRI',
				advisor: 'Luke J. Chang',
			},
			{
				title: 'Undergraduate Teaching Assistant',
				institution: 'Brown University | Dept. of Computer Science',
				dates: 'Spring 2018',
				location: 'Providence, RI',
				description: 'Intro to Scientific Computing and Problem Solving',
				advisor: 'Daniel Potter',
			},
			{
				title: 'Undergraduate Teaching Assistant',
				institution: 'Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)',
				dates: 'Fall 2017',
				location: 'Providence, RI',
				description: 'Intro to Programming',
				advisor: 'Thomas Serre',
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
</div>
