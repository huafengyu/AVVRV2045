# 2022 Autonomy Verification & Validation Workshop

In order to support the development of a V&V roadmap ([Vision 2045 of V&V for Autonomy](#vision-2045-of-verification-&-validation-for-autonomy)) for Autonomy, Boeing and NASA are holding an Autonomy Verification & Validation Workshop on May 23, 2022 in Boeing’s El Segundo site in California.  The workshop is open to all (industry, academics, and government). More information about the workshop (registration, agenda, location, ...) can be found [here](#autonomy-verification-and-validation-workshop-information).

Note that the workshop is being held just before the <a href="https://nfm2022.caltech.edu/">NASA Formal Methods</a> (NFM) Symposium on May 24-27, 2022 in Pasadena, California.

## Vision 2045 of Verification & Validation for Autonomy

Industry is developing autonomous solutions that expand the role of aviation in our daily lives and deliver faster services to society at large. Many of those new aeronautical-related services will start with humans in control; but are expected to evolve towards increasingly autonomous solutions in order to remain economically viable. The roles of humans will shift from controlling to monitoring as technical solutions rely more and more on technologies such as Artificial Intelligence, i.e., machine learning, reinforcement learning, multi-objective optimization, and planning & scheduling. The shift will be progressive and require increasingly pervasive use of runtime monitoring. Moreover, as “smarter” technologies are increasingly utilized on both ground and airborne systems, the assurance needs will also evolve. As design-time and operational safety merge together, V&V will have to expand and morph into novel runtime solutions. As the landscape of autonomy changes so does safety assurance and software V&V.

The goal of this effort "Vision 2045 of Verification & Validation for Autonomy" is to build that comprehensive list of V&V needs, develop a roadmap to achieve them, identify the services they can enable, and point to the certification gaps they fill. This effort will serve as support for NASA’s internal, long range, planning exercises which will inform the funding requirements that support this evolution of technology. Questions that need to be addressed include:
1. What are the new technologies needed to enable increasingly autonomous air services? Each new technology should be accompanied by examples of services it enables.
2. What are the limitations of current V&V capabilities with respect to these new technologies? For example, are current testing techniques sufficient for deploying ML-enabled systems? Answers should consider the projected use of these technologies as well as their possible re-use in different contexts (applications, environments, and so on).
3. Where do the current certification standards (such as DO-178C) fail to address assurance needs for these technologies or fail to take into account V&V results associated with the new technologies?
4. What role can new certification approaches such as Overarching Properties or safety cases play in the certification of increasingly autonomous systems?
5. What paradigm shifts in the existing regulations are necessary to implement new certification approaches?
6. How will the assurance of cyber-physical-human systems need to change to accommodate shifting roles and responsibilities between humans and automation? What new technologies will be required to assure anticipated systems architectures? How will we account for the implicit contributions to safety that are provided by humans in today’s systems?

While the individual needs of external customers/organizations/agencies and application domains will vary greatly, they need to be identified so that the community including industry, academia and government agencies can each determine what they can address given their means and their particular focus. To identify these threads, a realistic definition of a “Vision 2045 of V&V for Autonomy” is expected to be built. This effort will involve development of a mapping from V&V needs to technologies to enabled services with a particular interest in how new V&V technologies can fill existing or anticipated gaps in the regulatory framework. Furthermore, since the increasing use of autonomy implies a shift in the role played by humans, new V&V approaches addressing the changing roles and responsibilities should be addressed. At a minimum, the aforementioned questions should be answered with defensible positions. 

## Autonomy V&V Roadmap and Vision 2045 project
To create the Vision 2045 of V&V for Autonomy and a roadmap to achieve this vision, a collaboration team of recognized researchers from industry and academia was built, with support from government agencies.

### The team
- NASA Program Manager: Guillaume Brat
- Boeing Principle Investigator: Huafeng Yu
- Technical team
   - Collins Aerospace Lead: Darren Cofer
   - GE Research Lead: Mike Durling
   - MIT Lead: Chuchu Fan
   - UT Austin Lead: Ufuk Topcu
   - University of Michigan Leads: Ella Atkins & Prashin Santosh Sharma 
- NASA panelists: Aaron Dutle, Adrian Agogino, Alwyn Goodloe, Paul Miner
- FAA advisors: George Romanski, Liz Brandli, Mike Vukas, Ritesh Ghimire, Srini Mandalapu
- AFRL advisors: Kerianne Hobbs
- NRL advisors: Ramesh Bharadwaj
- Boeing advisors: Benjamin Ivers, Christina Westover, Matthew Moser, Joseph Brinker, Steven Beland, William Bosworth

### Team meetings
We have regular meetings to discuss different topics of autonomy V&V:
- Biweekly meetings: technical team members
- Monthly meetings:  technical team members + NASA panelists
- Quarterly meetings: technical team members + NASA panelists + all advisors

### Expected Outcomes of this project include:
- A list of the V&V technologies needed to enable the use of autonomy in aviation.
- A mapping of the V&V needs to (possibly AI-based) technologies and the enabled services in aviation.
- A study of the gaps in the current certification processes and an assessment of potential technologies that could fill those gaps.
- Answers to the above six questions, and other questions deemed relevant by the proposer, including thorough justification for all answers.

## Autonomy Verification and Validation Workshop Information
To support this project, an Autonomy Verification \& Validation workshop will be held on May 23, 2022 in Boeing' El Segundo site. The participants are not limited to our project team members, but a visitor's badge is required, and should be applied 2 weeks before the workshop.

### Time of the workshop

May 23, 1:00-5:45pm Pacific time

### Venue and access requirement

Boeing El Segundo S30 Building

1st Floor Tracy Center (PRS16105)

Building S30 located adjacent to 915 North Selby St.

El Segundo, CA 90245

Visitor badge required (application 2 weeks before the workshop)

### Schedule of the workshop
- 12:00 - 1:00pm Workshop preparation
- 1:00 - 1:10pm Introduction
- 1:10 - 2:20pm Project report
- 2:20 - 2:30pm  Break
- 2:30 - 5:45pm Deep dive discussions
   - 2:30 - 3:15pm Model-Based Systems Engineering (MBSE) for AI/ML, moderator: Mike Durling (GE Research)
   - 3:15 - 4:00pm Safety in Human-autonomy Interaction (HAI), moderator: Chuchu Fan (MIT)
   - 4:00 - 4:15pm Break
   - 4:15 - 5:00pm Autonomy for Contingency Planning, moderator: Ella Atkins (University of Michigan)
   - 5:00 - 5:45pm Certification Guidance for AI/ML, moderator: Darren Cofer (Collins Aerospace)

Details of the the deep dive discussions:
- **Model-Based Systems Engineering (MBSE) for AI/ML**. In this session we will review application of Model Based Systems Engineering (MBSE) to develop and certify AI/ML for aerospace applications. The session will start with the motivation for and trend of MBSE adoption across the full product lifecycle in the aerospace domain. Next will be a discussion on how legacy model based tools and technology are being connected to support MBSE. The session will wrap up with a discussion on mapping of AI/ML use cases and tools into the MBSE process and toolchain. The session will highlight use cases, potential benefits and technology challenges associated with including AI/ML in an MBSE framework. 
- **Safety in Human-autonomy Interaction (HAI)**. In this session, we will review different levels of explainability of algorithms for human-autonomy interaction, as well as potential methods of ensuring safety during HAI. The session will start with the discussion on the necessary information in HAI to enhance human understanding and human-autonomy team performance. Next will be a discussion on what techniques at different levels of the computation can be used to ensure HAI safety. The session will wrap up with a discussion on mapping these techniques and levels into the case studies and design processes we care about in this project.
- **Autonomy for Contingency Planning**. Contingency management plays a critical role in Aerospace system safety. This session will begin with a brief overview of essential contingency management functions. We will overview contingency management functional requirements and present progress toward prognostics-informed decision systems. We will then discuss map-based emergency landing site selection and planning to improve safety for Advanced Air Mobility (AAM) operations expected to occur at low altitudes over and near densely populated regions.  We will conclude with a discussion of verification and validation challenges associated with autonomy for contingency management. 
- **Certification Guidance for AI/ML**. In this session we will review emerging certification guidance for the AL/ML technologies that may be used in autonomous aircraft.  We will start with the rationale and methods for detecting unintended behavior in airborne software as defined in current certification processes, and the challenges presented for AI/ML.  EASA has initiated work to address these challenges, including a roadmap for the gradual certification and deployment of AI/ML technologies in applications with increasing levels of criticality.  The SAE G34 / EUROCAE WG114 joint committee is moving forward to produce industry consensus certification guidance that is intended to address the challenges posed by AI/ML, enabling its use in increasingly autonomous aircraft.  

### Workshop organizers

- Guillaume Brat (NASA)
- Huafeng Yu (Boeing)
- Chad McFarland (Boeing)


