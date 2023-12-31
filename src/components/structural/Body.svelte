<script>
  import MainColumn from "./MainColumn.svelte";

  export const mainColumn = [
    {
      type: "minimal-details",
      label: "Research Interests",
      details: [
        {
          description:
            "How can we effectively collaborate with others and enhance our understanding of the world, given our unique viewpoints and incomplete access to information? In other words, how do we adaptively interact with others and improve our mental models of the world in the face of uncertainty? What role does communication and other types of interaction play in this collaborative effort, and how are these processes computationally supported? To investigate these questions, I employ a range of techniques, including large-scale real-time online behavioral experiments, natural language processing (NLP), and computational modeling.",
        },
      ],
    },
    {
      type: "full-details",
      label: "Education",
      details: [
        {
          title: "Dartmouth College",
          subtitle: "Ph.D. Candidate in Cognitive Neuroscience",
          dates: "2021 — Present",
          location: "Hanover, NH",
          description: "Advisor: Luke J. Chang",
        },
        {
          title: "Brown University",
          subtitle: "B.S., Cognitive Neuroscience (Honors)",
          dates: "2014 — 2018",
          location: "Providence, RI",
          description: "Advisor: Amitai Shenhav",
        },
      ],
    },
    {
      type: "research-exps",
      label: "Research Experience",
      details: [
        {
          title: "Graduate Student Researcher",
          institution:
            "Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)",
          url: "cosanlab.com",
          link: "cosanlab.com",
          dates: "2021 — Present",
          location: "Hanover, NH",
          advisor: "Advisor: Luke J. Chang",
          research:
            "Research focuses: collaboration, communication, theory of mind, dyadic & group social interactions, social networks, fMRI",
        },
        {
          title: "Lab Manager/Research Assistant",
          institution:
            "Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)",
          url: "lnccbrown.com",
          link: "lnccbrown.com",
          dates: "2018 — 2021",
          location: "Providence, RI",
          advisor: "Advisor: Michael J. Frank",
          research:
            "Research focuses: computational psychiatry (esp. OCD), reinforcement learning, decision-making, EEG, pharmacology, Parkinson's Disease",
        },
        {
          title: "Undergraduate Research Assistant",
          institution:
            "Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)",
          url: "shenhavlab.org",
          link: "shenhavlab.org",
          dates: "2016 — 2018",
          location: "Providence, RI",
          advisor: "Advisor: Amitai Shenhav",
          research:
            "Research focuses: cognitive control, performance monitoring, task-switching, EEG",
        },
        {
          title: "Summer Undergraduate Research Intern",
          institution: "Providence VA Medical Center",
          url: "https://vivo.brown.edu/display/nphilip",
          link: "vivo.brown.edu/display/nphilip",
          dates: "2016 — 2018",
          location: "Providence, RI",
          advisor: "Advisor: Noah Philip",
          research:
            "Research focuses: major-depressive disorder, post-traumatic stress disorder, rTMS",
        },
      ],
    },
    {
      type: "teaching-exps",
      label: "Teaching Experience",
      details: [
        {
          title: "Graduate Teaching Assistant",
          institution:
            "Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)",
          dates: "Spring 2023",
          location: "Hanover, NH",
          description: "Cognitive Psychology",
          advisor: "Viola Störmer",
        },
        {
          title: "Graduate Teaching Assistant",
          institution:
            "Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)",
          dates: "Fall 2022",
          location: "Hanover, NH",
          description: "Principles of Human Brain Mapping with fMRI",
          advisor: "Luke J. Chang",
        },
        {
          title: "Graduate Teaching Assistant",
          institution:
            "Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)",
          dates: "Spring 2022",
          location: "Hanover, NH",
          description: "Emotion",
          advisor: "Mark Thornton",
        },
        {
          title: "Graduate Teaching Assistant",
          institution:
            "Dartmouth College | Dept. of Psychological & Brain Sciences (PBS)",
          dates: "Fall 2021",
          location: "Hanover, NH",
          description: "Principles of Human Brain Mapping with fMRI",
          advisor: "Luke J. Chang",
        },
        {
          title: "Undergraduate Teaching Assistant",
          institution: "Brown University | Dept. of Computer Science",
          dates: "Spring 2018",
          location: "Providence, RI",
          description: "Intro to Scientific Computing and Problem Solving",
          advisor: "Daniel Potter",
        },
        {
          title: "Undergraduate Teaching Assistant",
          institution:
            "Brown University | Dept. of Cognitive, Linguistic, & Psychological Sciences (CLPS)",
          dates: "Fall 2017",
          location: "Providence, RI",
          description: "Intro to Programming",
          advisor: "Thomas Serre",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Papers",
      details: [
        {
          year: "2023",
          preWM: "Culbreth, A., Moran, E.",
          postWM:
            "Erickson, M., Boudewyn, M., Frank, M.J., Barch, D., MacDonald III, A., Ragland, J., Luck, S., Silverstein, S., Carter, C., & Gold, J.",
          description:
            "A Transdiagnostic Study of Effort-Cost Decision-Making in Psychotic and Mood Disorders. Schizophrenia Bulletin.",
        },
        {
          year: "2021",
          preWM: "Provenza, N.R., Gelin, L.,",
          postWM:
            "McGrath, M., Dastin-van Rijin, E., Fan, Y., Dhar, R., Frank, M.J., Restrepo, M.I., Goodman, W.K., and Borton, D.",
          description:
            "Honeycomb: a template for reproducible psychophysiological tasks for clinic, laboratory, and home use. Brazillian Journal of Psychiatry.",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Papers in Preparation",
      details: [
        {
          year: "In prep.",
          preWM: "",
          postWM: "Welker, C., Schmidt, H., Chang, L.J., & Hawkins, R.X.D.",
          description: "Does shared reality generalize?",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Chang, L.J.",
          description: "Are shared experiences blind?",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Chang, L.J.",
          description:
            "Communication as behavioral annotations for experimental stimuli",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Provenza, N., Frank, M.J., Borton, D., and Nassar, M.",
          description:
            "Computations in information-seeking behavior and decision-making in obsessive-compulsive disorder (OCD)",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Geana, A., and Frank, M.J.",
          description:
            "Perceptual uncertainty disrupts credit assignment in stimulus value learning and perceptual categorization",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Talks",
      details: [
        {
          year: "September 2024 - Forthcoming",
          description:
            "Collaboratively learning to communicate a shared wavelength. Lab Meeting (PIs: Matthew Apps, Romy Froemer, Arkady Konovalov, Patricia Lockwood, & Lei Zhang), University of Birmingham, Birmingham, UK.",
        },
        {
          year: "December 2023",
          description:
            "Web dev approaches to studying social interactions. Social Interaction Lab (PI: Robert Hawkins) meeting. University of Wisconsin-Madison, WI.",
        },
        {
          year: "November 2023",
          description:
            "Learning to communicate a shared wavelength. New England Research on Decision-Making (NERD) conference at Harvard University, Cambridge, MA.",
        },
        {
          year: "October 2023",
          description:
            "Learning to collaboratively communicate a shared wavelength. Social Interaction Lab (PI: Robert Hawkins) meeting. University of Wisconsin-Madison, WI.",
        },
        {
          year: "October 2023",
          description:
            "Does shared reality generalize? Social Interaction Lab (PI: Robert Hawkins) meeting. University of Wisconsin-Madison, WI.",
        },
        {
          year: "September 2023",
          description:
            "Learning to collaboratively communicate a shared wavelength. Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.",
        },
        {
          year: "August 2023",
          description:
            "Does shared reality generalize? Methods in Neuroscience at Dartmouth (MIND) Summer School at Dartmouth College, Hanover, NH.",
        },
        {
          year: "May 2023",
          description:
            "Decision-Making. Guest lecture for PSYC 028 (Cognitive Psychology) class taught by Prof. Viola Störmer at Dartmouth College, Hanover, NH.",
        },
        {
          year: "September 2022",
          description:
            "On using a chat app to study communication and shared reality. Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.",
        },
        {
          year: "May 2022",
          description:
            "Evolutionary game theory. Guest lecture for PSYC 043 (Emotion) class taught by Prof. Mark Thornton at Dartmouth College, Hanover, NH.",
        },
        {
          year: "October 2021",
          description:
            "On building a chat app for studying shared reality construction in communication. Social Lab (SLAB) Talk Series at Dartmouth College, Hanover, NH.",
        },
        {
          year: "December 2020",
          description:
            "Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. Learning, Memory, & Decision Lab (PI: Matthew Nassar) meeting. Brown University, Providence, RI.",
        },
        {
          year: "November 2020",
          description:
            "Intro to Honeycomb: a template for reproducible psychophysiological task creation. Center for Computation & Visualization (CCV) tutorial series. Brown University, Providence, RI.",
        },
        {
          year: "June 2020",
          description:
            "Computations in information-seeking and decision-making in Obsessive Compulsive Disorder. Brown Unconference on Computational Intelligence and Applications. Brown University, Providence, RI.",
        },
        {
          year: "May 2018",
          description:
            "The costs of having better alternatives. Departmental undergraduate honors thesis oral defense presentation. Brown University, Providence, RI.",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Posters",
      details: [
        {
          postWM: "Chang, L.J.",
          year: "February 2024",
          description:
            "Shared experiences strengthen social connectedness through shared impression formation and communication behavior. Accepted at the Society for Personality & Social Psychology (SPSP). San Diego, California.",
        },
        {
          postWM: "Chang, L.J.",
          year: "July 2023",
          description:
            "Shared experiences strengthen social connectedness through shared impression formation and communication behavior. Presented at the Cognitive Science Society (CogSci). Sydney, Australia.",
        },
        {
          postWM: "Chang, L.J.",
          year: "April 2023",
          description:
            "Are shared experiences blind? Presented at the Social and Affective Neuroscience Society (SANS). Santa Barbara, CA.",
        },
        {
          preWM: "Geana, A.,",
          postWM: "Frank, M.J.",
          year: "October 2019",
          description:
            "The role of perceptual uncertainty in value learning and naturalistic stimulus categorization. Presented at the Society for Neuroscience (SfN). Chicago, IL.",
        },
        {
          year: "July 2019",
          postWM: "Geana, A., Frank, M.J.",
          description:
            "Perceptual uncertainty influences stimulus value learning in perceptual categorization. Presented at the 4th Multidisplinary conference on Reinforcement Learning and Decision Making (RLDM). Montreal, CA.",
        },
        {
          preWM:
            "Provenza, P., Dastin-van Rijn, E., McLaughlin, N., Sheth, S., Viswanathan, A., Vogt, G., Ramakrishnan, R., McIngvale, E., Storch, E.,",
          postWM:
            "Nassar, M., Frank, M.J., Ertugrul, I., Jeni, L., Cohn, J., Borton, D., Goodman, W.",
          year: "April 2019",
          description:
            "Preliminary experience with developing adaptive Deep Brain Stimulation for Obsessive Compulsive Disorder. Presented at the 5th Annual BRAIN Investigator’s Meeting. Washington, DC.",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Awards & Honors",
      details: [
        {
          year: "July 2024",
          description: "Neukom Travel Award ($1,000) | Dartmouth College",
        },
        {
          year: "April 2023",
          description: "Neukom Travel Award ($1,000) | Dartmouth College",
        },
        {
          year: "April 2022",
          description: "NSF Graduate Research Fellowship | Honorable Mention",
        },
        {
          year: "May 2018",
          description: "B.S. in Cognitive Neuroscience with Honors",
        },
        {
          year: "May 2018",
          description: "Sigma Xi | Nominated to Brown University Chapter",
        },
        {
          year: "January 2018",
          description: "Deep Learning Datathon @ Brown University | 1st Place",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Fellowships & Scholarships",
      details: [
        {
          year: "Summer 2017",
          description:
            "Karen T. Romer Undergraduate Teaching & Research Award ($3,500) | Brown University",
        },
        {
          year: "Spring 2014",
          description:
            "Karen T. Romer Undergraduate Teaching & Research Award ($1,000) | Brown University",
        },
        {
          year: "2015-2017",
          description:
            "Sorensen Family Chancellor's Scholarship | Brown University",
        },
        {
          year: "Spring 2014",
          description:
            "Junior Volunteer Endowment Scholarship ($2,000) | Maine Medical Center",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Scientific & Community Outreach",
      details: [
        {
          year: "May 2023",
          description:
            "Software Engineer for Featured Trust Game & fMRI Operator | PBS NOVA | Episode: Who's in Control?",
        },
        {
          year: "April 2023",
          description:
            "Podcast Guest | Svelte Radio | Svelte in Research at Dartmouth with Wasita & Eshin",
        },
        {
          year: "2022-Present",
          description:
            "Site Maintainer | Website Working Group | Women in Network Science (WiNS) Society",
        },
        {
          year: "2022-Present",
          description:
            "Content Contributor & Site Maintainer | Info Theory Book (cosanlab.github.io/info-theory-book)",
        },
        {
          year: "2021-Present",
          description:
            "Content Contributor & Site Maintainer | Intro to FMRI at Dartmouth (dartbrains.org)",
        },
        {
          year: "2020-Present",
          description: "Pre-Grad Mentor & Consultant | Project SHORT",
        },
        {
          year: "2019-2021",
          description:
            "Contributing Software Engineer | Honeycomb (brown-ccv.github.io/honeycomb-docs)",
        },
        {
          year: "2018-2020",
          description:
            "Rhode Island Brain Week Booth Organizer | brainweekri.org",
        },
        {
          year: "2017-2018",
          description:
            "Rhode Island Brain Week Booth Volunteer | brainweekri.org",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Research Training",
      details: [
        {
          year: "2023",
          description:
            "Methods in Neuroscience at Dartmouth (MIND) Summer School | Dartmouth College",
        },
        {
          year: "2021",
          description: "Computational Neuroscience | Neuromatch Academy",
        },
        {
          year: "2018",
          description:
            "Carney Computational Modeling Workshop | Brown University",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Professional & Departmental Service",
      details: [
        {
          year: "2021-Present",
          description:
            "Social Lab (SLAB) Talk Series Co-organizer | Dartmouth PBS",
        },
        {
          year: "2021-Present",
          description:
            "Consortium for Interacting Minds (CIM) Seminar Series Co-organizer | Dartmouth PBS",
        },
        {
          year: "2021-Present",
          description: "Meeting Harmonization Committee | Dartmouth PBS",
        },
        {
          year: "2022-2023",
          description:
            "Teaching Assistant Repository Creation & Organization Committee | Dartmouth PBS",
        },
        {
          year: "2021",
          description:
            "Transitioning from Intro to Programming to Career in Computation | Alumni Panelist | Brown CLPS",
        },
        {
          year: "2019-2021",
          description:
            "Managing Minds (lab manager peer mentoring group) Founder & Organizer | Brown Carney/CLPS",
        },
        {
          year: "2018",
          description:
            "Cognitive Neuroscience DUG Alumni Career Panelist | Brown CLPS",
        },
      ],
    },
  ];
</script>

<div class="main-body">
  <MainColumn sections={mainColumn} />
</div>

<style>
  div {
    display: flex;
    justify-content: space-between;
    flex-direction: var(--column-order);
    margin: 0 var(--horizontal-offset);
  }
</style>
