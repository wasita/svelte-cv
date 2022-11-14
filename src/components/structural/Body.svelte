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
					subtitle: 'Ph.D. Candidate in Cognitive Neuroscience',
					dates: '2021 — Present',
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
				dates: '2021 — Present',
				location: 'Hanover, NH',
				advisor: 'Advisor: Luke J. Chang',
				research: 'Research focuses: communication, social networks, social structure learning, fMRI',
			},
			{
				title: 'Lab Manager/Research Assistant',
				institution: 'Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)',
				url: 'lnccbrown.com',
				link: 'lnccbrown.com',
				dates: '2018 — 2021',
				location: 'Providence, RI',
				advisor: 'Advisor: Michael J. Frank',
				research: 'Research focuses: computational psychiatry (esp. OCD), reinforcement learning, decision-making, EEG, pharmacology'
			},
			{
				title: 'Undergraduate Research Assistant',
				institution: 'Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)',
				url: 'shenhavlab.org',
				link: 'shenhavlab.org',
				dates: '2016 — 2018',
				location: 'Providence, RI',
				advisor: 'Advisor: Amitai Shenhav',
				research: 'Research focuses: cognitive control, performance monitoring, task-switching, EEG'
			},
			{
				title: 'Summer Undergraduate Research Intern',
				institution: 'Providence VA Medical Center',
				url: 'https://vivo.brown.edu/display/nphilip',
				link: 'vivo.brown.edu/display/nphilip',
				dates: '2016 — 2018',
				location: 'Providence, RI',
				advisor: 'Advisor: Noah Philip',
				research: 'Research focuses: major-depressive disorder, post-traumatic stress disorder, rTMS'
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
				dates: 'Fall 2022',
				location: 'Hanover, NH',
				description: 'Principles of Human Brain Mapping with fMRI',
				advisor: 'Luke J. Chang',
			},
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
				year: 'September 2022',
				description: 'On using a chat app to study communication and shared reality. Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.',
			},
			{
				year: 'May 2022',
				description: 'Evolutionary game theory. Guest lecture for PSYC 043 (Emotion) class taught by Prof. Mark Thornton at Dartmouth College, Hanover, NH.'},
			{
				year: 'October 2021',
				description: 'On building a chat app for studying shared reality construction in communication. Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.',
			},
			{
				year: 'December 2020',
				description: 'Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. Learning, Memory, & Decision Lab (PI: Matthew Nassar) meeting. Brown University, Providence, RI.'
			},
			{
				year: 'June 2020',
				description: 'Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. 1st Annual Meeting of Brown Unconference on Computational Intelligence and Applications. Brown University, Providence, RI.'
			},
			{
				year: 'May 2018',
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
				year: 'October 2019',
				description: 'The role of perceptual uncertainty in value learning and naturalistic stimulus categorization. Presented at the Society for Neurosciecne (SfN). Chicago, IL.'
			},
			{
				year: 'July 2019',
				postWM: 'Geana, A., Frank, M.J.',
				description: 'Perceptual uncertainty influences stimulus value learning in perceptual categorization. Presented at the 4th Multidisplinary conference on Reinforcement Learning and Decision Making (RLDM). Montreal, CA.'
			},
			{
				preWM: 'Provenza, P., Dastin-van Rijn, E., McLaughlin, N., Sheth, S., Viswanathan, A., Vogt, G., Ramakrishnan, R., McIngvale, E., Storch, E.,',
				postWM: 'Nassar, M., Frank, M.J., Ertugrul, I., Jeni, L., Cohn, J., Borton, D., Goodman, W.',
				year: 'April 2019',
				description: 'Preliminary experience with developing adaptive Deep Brain Stimulation for Obsessive Compulsive Disorder. Presented at the 5th Annual BRAIN Investigator’s Meeting. Washington, DC.'
			}
		]
	},
	{
		type: 'honors-details',
		label: 'Awards & Honors',
		details: [
			{
				year: 'April 2022',
				description: 'NSF Graduate Research Fellowship | Honorable Mention'
			},
			{
				year: 'May 2018',
				description: 'B.S. in Cognitive Neuroscience with Honors'
			},
			{
				year: 'May 2018',
				description: 'Sigma Xi'
			}
		]
	},
	{
		type: 'honors-details',
		label: 'Fellowships & Scholarships',
		details: [
			{
				year: 'Summer 2017',
				description: 'Karen T. Romer Undergraduate Teaching & Research Award ($3,500) from Brown University'
			},
			{
				year: 'Spring 2014',
				description: 'Karen T. Romer Undergraduate Teaching & Research Award ($1,000) from Brown University'
			},
			{
				year: 'Spring 2014',
				description: 'Junior Volunteer Scholarship ($2,000) from Maine Medical Center'
			}
		]
	},
	{
		type: 'honors-details',
		label: 'Scientific & Community Outreach',
		details: [
			{
				year: '2020-Present',
				description: 'Pre-Grad Mentor & Consultant | Project SHORT'
			},
			{
				year: '2018-2020',
				description: 'Rhode Island Brain Week Booth Organizer | brainweekri.org'
			}
		]
	},
	{
		type: 'honors-details',
		label: 'Research Training',
		details: [
			{
				year: '2021',
				description: 'Computational Neuroscience | Neuromatch Academy'
			},
			{
				year: '2018',
				description: 'Carney Computational Modeling Workshop | Brown University'
			}
		]
	},
	{
		type: 'honors-details',
		label: 'Professional & Departmental Service',
		details: [
			{
				year: '2021',
				description: 'CLPS 0950 (Intro to Programming) Alumni Panelist | Brown CLPS'
			},
			{
				year: '2022-Present',
				description: 'Teaching Assistant Repository Creation & Organization Committee | Dartmouth PBS'
			},
			{
				year: '2021-Present',
				description: 'Social Lab (SLAB) Talk Series Co-organizer | Dartmouth PBS'
			},
			{
				year: '2021-Present',
				description: 'Consortium for Interacting Minds Seminar Series Co-organizer | Dartmouth PBS'
			},
			{
				year: '2021-Present',
				description: 'Meeting Harmonization Committee | Dartmouth PBS'
			},
			{
				year: '2019-2021',
				description: 'Managing Minds (lab manager peer mentoring group) Founder & Organizer | Brown Carney/CLPS'
			},
			{
				year: '2018',
				description: 'Cognitive Neuroscience DUG Alumni Career Panelist | Brown CLPS'
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
