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
	{
		type: 'pressie-details',
		label: 'Papers',
		details: [
			{
				year: '2021',
				preWM: 'Provenza, N.R., Gelin, L.,',
				postWM: 'McGrath, M., Dastin-van Rijin, E., Fan, Y., Dhar, R., Frank, M.J., Restrepo, M.I., Goodman, W.K., and Borton, D.',
				description: 'Honeycomb: a template for reproducible psychophysiological tasks for clinic, laboratory, and home use. Brazillian Journal of Psychiatry.'
			},
		]
	},
	{
		type: 'pressie-details',
		label: 'Talks',
		details: [
			{
				year: 'October, 2021',
				description: 'On building a chat app for studying shared reality construction in communication. Presented at the Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.',
			},
			{
				year: 'December, 2020',
				description: 'Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. Presented at the Learning, Memory, & Decision Lab at Brown University (PI: Matthew Nassar). Providence, RI.'
			},
			{
				year: 'June, 2020',
				description: 'Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. 1st Annual Meeting of Brown Unconference on Computational Intelligence and Applications. Providence, RI.'
			},
			{
				year: 'May, 2018',
				description: 'The costs of having better alternatives. Departmental undergraduate honors thesis oral defense presentation. Brown University, Providence, RI.'
			}
		]
	},
	{
		type: 'pressie-details',
		label: 'Posters',
		details: [
			{
				preWM: 'Geana, A.,',
				postWM: 'Frank, M.J.',
				year: 'October, 2019',
				description: 'The role of perceptualuncertainty in value learning and naturalistic stimulus categorization. Presented at the Society for Neurosciecne (SfN). Chicago, IL.'
			},
			{
				year: 'July, 2019',
				description: 'Perceptual uncertaintyinfl uences stimulus value learning in perceptual categorization. Presented at the 4th Multidisplinary conference on Reinforcement Learning and Decision Making (RLDM). Montreal, CA.'
			},
			{
				preWM: 'Provenza, P., Dastin-van Rijn, E., McLaughlin, N., Sheth, S.,Viswanathan, A., Vogt, G., Ramakrishnan, R., McIngvale, E., Storch, E.,',
				postWM: 'Nassar, M., Frank, M.J., Ertugrul, I., Jeni, L., Cohn, J., Borton, D., Goodman, W.',
				year: 'April, 2019',
				description: 'Preliminary experience with developing adaptive Deep Brain Stimulation for Obsessive Compulsive Disorder. Presented at the 5th Annual BRAIN Investigator’s Meeting. Washington, DC.'
			}
		]
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
