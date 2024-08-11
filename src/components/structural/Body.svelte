<script>
  import MainColumn from "./MainColumn.svelte";

  export const mainColumn = [
    {
      type: "minimal-details",
      label: "Research Interests",
      details: [
        {
          description:
            "How can we effectively collaborate with others and enhance our understanding of the world, given our unique viewpoints and incomplete access to information? In other words, how do we adaptively interact with others and improve our mental models of the world in the face of uncertainty? What role does communication and other types of interaction play in this collaborative effort, and how are these processes computationally supported? To investigate these questions, I primarily use large-scale real-time online behavioral experiments, natural language processing (NLP), and computational modeling.",
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
          description:
            "Committee: Luke J. Chang, Jonathan S. Phillips, Thalia Wheatley, & Robert D. Hawkins",
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
          advisor: "Co-Advisors: Luke J. Chang & Robert D. Hawkins",
          research:
            "Research focuses: shared reality/experience, collaboration, communication, theory of mind, dyadic & group social interactions, NLP, Bayesian inference",
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
      label: "Working Papers",
      details: [
        {
          year: "In prep.",
          preWM: "",
          postWM: "Chang, L.J.",
          onlyTwo: true,
          description: "Are shared experiences blind?",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Chang, L.J.",
          onlyTwo: true,
          description:
            "Communication as behavioral annotations for experimental stimuli.",
        },
        {
          year: "In prep.",
          preWM: "Kang, J.",
          postWM:
            "Provenza, N., Nassar, M., Allam, A., Bechtold, R., Diab, N., Rajesh, S., Reddy S., Reyes, G., Dastin-van Rijn, E., Gandhi, A., Hirani, S., Banks, G., Dang, H., Avendano-Ortega, M., McKay, S., Borton, D., Frank, M.J., Storch, E., Herron, J., Goodman, W., Hayden, B., & Sheth, S.",
          description:
            "The effect of adaptive deep brain stimulation for obsessive-compulsive disorder in cognitive self-control under uncertainty.",
        },
        {
          year: "In prep.",
          preWM: "",
          postWM: "Geana, A., and Frank, M.J.",
          description:
            "Perceptual uncertainty disrupts credit assignment in stimulus value learning and perceptual categorization.",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Preprints",
      details: [
        {
          year: "2024",
          preWM: "",
          postWM: "Welker, C.*, Schmidt, H., Chang, L.J., & Hawkins, R.D.",
          joint: true,
          description: "When and why does shared reality generalize?",
          journal: "PsyArXiv",
          link: "https://osf.io/preprints/psyarxiv/g9p3e",
        },
        ,
      ],
    },
    {
      type: "pressie-details",
      label: "Proceedings Papers",
      details: [
        {
          year: "2024",
          preWM: "",
          postWM: "Welker, C.*, Schmidt, H., Chang, L.J., & Hawkins, R.D.",
          joint: true,
          journal:
            "Proceedings of the 46th Annual Conference of the Cognitive Science Society.",
          description: "When and why does shared reality generalize?",
        },
        {
          year: "2024",
          preWM: "",
          postWM: "Welker, C., Schmidt, H., Chang, L.J., & Hawkins, R.D.",
          journal:
            "Proceedings of the 7th Annual Conference on Cognitive Computational Neuroscience (CCN).",
          description: "How does shared reality generalize?",
        },
      ],
    },
    {
      type: "pressie-details",
      label: "Journal Papers",
      details: [
        {
          year: "2023",
          preWM: "Culbreth, A., Moran, E.",
          postWM:
            "Erickson, M., Boudewyn, M., Frank, M.J., Barch, D., MacDonald III, A., Ragland, J., Luck, S., Silverstein, S., Carter, C., & Gold, J.",
          journal: "Schizophrenia Bulletin.",
          description:
            "A Transdiagnostic Study of Effort-Cost Decision-Making in Psychotic and Mood Disorders.",
        },
        {
          year: "2021",
          preWM: "Provenza, N.R., Gelin, L.",
          postWM:
            "McGrath, M., Dastin-van Rijin, E., Fan, Y., Dhar, R., Frank, M.J., Restrepo, M.I., Goodman, W.K., and Borton, D.",
          description:
            "Honeycomb: a template for reproducible psychophysiological tasks for clinic, laboratory, and home use.",
          journal: "Brazillian Journal of Psychiatry.",
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
            "When and why does shared reality generalize? Lab Meeting (PIs: Matthew Apps, Romy Frömer, Arkady Konovalov, Patricia Lockwood, & Lei Zhang), University of Birmingham, Birmingham, UK.",
        },
        {
          year: "July 2024",
          description:
            "When and why does shared reality generalize? Cognitive Science Society conference at Rotterdam, Netherlands.",
        },
        {
          year: "February 2024",
          description:
            "Are shared experiences blind? Shared Reality Virtual Mini-Conference.",
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
          preWM: "",
          postWM: "Welker, C., Schmidt, H., Chang, L.J., & Hawkins, R.D.",
          year: "August 2024",
          description:
            "How does shared reality generalize? Presented at the 7th annual conference on Cognitive Computational Neuroscience (CCN). Boston, MA.",
        },
        {
          preWM: "Kang, J.",
          postWM:
            "Provenza, N., Nassar, M., Allam, A., Bechtold, R., Diab, N., Rajesh, S., Reddy S., Reyes, G., Dastin-van Rijn, E., Gandhi, A., Hirani, S., Banks, G., Dang, H., Avendano-Ortega, M., McKay, S., Borton, D., Frank, M.J., Storch, E., Herron, J., Goodman, W., Hayden, B., & Sheth, S.",
          year: "June 2024 - Forthcoming",
          description:
            "The effect of adaptive deep brain stimulation for obsessive-compulsive disorder in cognitive self-control under uncertainty. Presented at the American Society for Stereotactic & Functional Neurosurgery (ASSFN). Nashville, TN.",
        },
        {
          postWM: "Hawkins, R.D., Phillips, J.S., & Chang, L.J.",
          year: "April 2024",
          description:
            "Learning to communicate a shared wavelength facilitates social connection. Presented at the Social & Affective Neuroscience Society (SANS). Toronto, Canada.",
        },
        {
          postWM: "Chang, L.J.",
          year: "February 2024",
          onlyTwo: true,
          description:
            "Shared experiences strengthen social connectedness through shared impression formation and communication behavior. Accepted at the Society for Personality & Social Psychology (SPSP). San Diego, California.",
        },
        {
          postWM: "Chang, L.J.",
          year: "July 2023",
          onlyTwo: true,
          description:
            "Shared experiences strengthen social connectedness through shared impression formation and communication behavior. Presented virtually at the Cognitive Science Society (CogSci). Sydney, Australia.",
        },
        {
          postWM: "Chang, L.J.",
          year: "April 2023",
          onlyTwo: true,
          description:
            "Are shared experiences blind? Presented at the Social and Affective Neuroscience Society (SANS). Santa Barbara, CA.",
        },
        {
          preWM: "Geana, A.",
          postWM: "& Frank, M.J.",
          year: "October 2019",
          description:
            "The role of perceptual uncertainty in value learning and naturalistic stimulus categorization. Presented at the Society for Neuroscience (SfN). Chicago, IL.",
        },
        {
          year: "July 2019",
          postWM: "Geana, A., & Frank, M.J.",
          description:
            "Perceptual uncertainty influences stimulus value learning in perceptual categorization. Presented at the 4th Multidisplinary conference on Reinforcement Learning and Decision Making (RLDM). Montreal, CA.",
        },
        {
          preWM:
            "Provenza, P., Dastin-van Rijn, E., McLaughlin, N., Sheth, S., Viswanathan, A., Vogt, G., Ramakrishnan, R., McIngvale, E., Storch, E.",
          postWM:
            "Nassar, M., Frank, M.J., Ertugrul, I., Jeni, L., Cohn, J., Borton, D., & Goodman, W.",
          year: "April 2019",
          description:
            "Preliminary experience with developing adaptive Deep Brain Stimulation for Obsessive Compulsive Disorder. Presented at the 5th Annual BRAIN Initiative Investigators Meeting. Washington, DC.",
        },
      ],
    },
    {
      type: "honors-details",
      label: "Awards & Honors",
      details: [
        {
          year: "2024",
          description:
            "Diversity & Inclusion Conference Award | Cognitive Science Society | $1,000",
        },
        {
          year: "July 2024",
          description: "Neukom Travel Award | Dartmouth College | $1,000",
        },
        {
          year: "April 2023",
          description: "Neukom Travel Award | Dartmouth College | $1,000",
        },
        {
          year: "April 2022",
          description: "NSF Graduate Research Fellowship | Honorable Mention",
        },
        {
          year: "May 2018",
          description: "Sigma Xi | Inductee",
        },
        {
          year: "January 2018",
          description: "Deep Learning Datathon | Brown University | 1st Place",
        },
        {
          year: "2014",
          description: "QuestBridge Scholar | National College Match Finalist",
        },
        {
          year: "2013",
          description: "QuestBridge | College Prep Scholar",
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
            "Karen T. Romer Undergraduate Teaching & Research Award | Brown University | $3,500",
        },
        {
          year: "Spring 2014",
          description:
            "Karen T. Romer Undergraduate Teaching & Research Award | Brown University | $1,000",
        },
        {
          year: "2015-2017",
          description:
            "Sorensen Family Chancellor's Scholarship | Brown University",
        },
        {
          year: "Spring 2014",
          description:
            "Junior Volunteer Endowment Scholarship | Maine Medical Center | $2,000",
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
            "Podcast Guest | Svelte Radio | Episode: Svelte in Research at Dartmouth with Wasita & Eshin",
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
          year: "2021-2024",
          description:
            "Social Lab (SLAB) Talk Series Co-organizer | Dartmouth PBS",
        },
        {
          year: "2021-2024",
          description:
            "Consortium for Interacting Minds (CIM) Seminar Series Co-organizer | Dartmouth PBS",
        },
        {
          year: "2022-2023",
          description:
            "Teaching Assistant Repository Creation & Organization Committee | Dartmouth PBS",
        },
        {
          year: "2021-2023",
          description: "Meeting Harmonization Committee | Dartmouth PBS",
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
