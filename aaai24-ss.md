---
title: AAAI-24 Spring Symposium on Human-Like Learning
nav_title: AAAI-24 Spring Symposium
permalink: /aaai24-ss/
layout: page
order: 1
---

* TOC
{:toc}

## Important Event Information

| Key Dates                                         |                     |
|---------------------------------------------------|---------------------|
| Abstracts Due                                     | December 22nd, 2023 |
| Selected Presenters Notified                      | January 5th, 2024   |
| AAAI Symposium Registration Opens                 | January 10th, 2024  |
| Finalized Abstracts Due                           | January 19th, 2024  |
| Deadline for Registration                         | Febuary 29th, 2024  |
| Finalized Schedule Released                       | March 2nd, 2024     |
| Symposium Takes Place at Stanford University      | March 25-27, 2024   |

When preparing abstracts use the [AAAI-24 Author
Kit](https://aaai.org/authorkit24-2/). The abstracts can be brief, but should
provide sufficient detail for the organizing committee to determine the focus
and substance of your proposed talk for planning purposes.

Please submit abstract via
[easychair](https://easychair.org/my/conference?conf=sss24) to the "Symposium
on Human-Like Learning" track. 

The symposium registration details will be posted here when they become
available from AAAI. 

## Motivation and Background

<div style="float:right; padding: 15px;">
<img src="/files/symposium.png" alt="A futuristic classroom setting illuminated with soft blue lighting showcases a mix of technology and traditional learning. In the center of the room, a large holographic projection of a human head, half-transparent with digital components and circuits, stands prominently, symbolizing the blend of humanity and technology. Around the hologram, two individuals, a man and a woman, stand behind podiums, engaged in a discussion or debate. Students sit at sleek desks equipped with advanced touch-screen monitors, actively interacting with the digital content. Floating holographic books and a digital brain hover in the space, suggesting a deep integration of knowledge and technology. The room's boundaries are framed by bookshelves on one side and a window with a serene view of a green landscape on the other. The overall ambiance combines the traditional elements of a learning environment with state-of-the-art technological advancements." style="height: 350px;">
</div>

Recent machine-learning research has made incredible progress across a wide
range of tasks. While many systems can achieve human-like performance, one area
that is currently under explored is how to realize human-like learning
capabilities within these systems. For example, machine learning typically
employs batch training and requires more data and computation than people to
achieve similar capabilities. The resulting models are effective, but difficult
to update in the face of new data without costly retraining. In contrast,
humans excel at rapidly assimilating new information on the fly from a limited
number of examples. More research is needed to investigate human-like
capabilities, such as efficient, incremental learning, and to explore the
design of artificial systems that can also exhibit them.

Historically, the fields of Artificial Intelligence and Cognitive Science have
maintained close theoretical ties. As a result, early machine-learning research
placed a strong emphasis on human-like learning. For example, early research
with systems like ACT (Anderson, 1982; 1983) and EPAM (Feigenbaum, 1959;
Feigenbaum & Simon, 1984) aimed to both improve our understanding of human
learning and to reproduce human-like learning capabilities within artificial
systems. Other early research with Soar (Laird, Newell, & Rosenbloom, 1987)
composed many human-like capabilities to propose a unified account of human
cognition (both problem-solving and learning). Research within the Parallel
Distributed Processing group (Rumelhart, McClelland, and the PDP Group, 1986)
explored how parallel processing and distributed representations—often within
neural networks—could account for human cognition and learning. Despite the
success of these early efforts (many of which led directly to today's dominant
paradigms), the connection between Artificial Intelligence and Cognitive
Science has weakened over the past decades; there has been an increasing
emphasis on functional applications and the development of artificial systems
that process data in ways and at scales that exceed human processing
capacities. A symposium on human-like learning is timely because it can
re-strengthen this theoretical connection and enable researchers to revisit
this topic in light of recent computational advancements. A renewed focus on
human learning should prove valuable, both in enhancing our comprehension of
human capabilities and in enabling new advancements in applications, such as
more efficient machine-learning systems.


## Themes of the Symposium

At a high-level, the symposium aims to encourage discussion on the following
themes:
- Identification of key characteristics of human-like learning to target in
  AI/ML research, along with what makes these characteristics challenging for
  current approaches;
- Ongoing and proposed research into how to create artificial systems that
  exhibit human-like learning;
- Approaches for evaluating human-like learning systems; and
- Exploration of the broader context for and impacts of human-like learning
  systems, such as how they might complement/benefit current machine learning
  systems and humanity.

### Characteristics of Human Learning

There are several characteristics of human learning that could serve as targets
for a general research program. Langley (2022) highlights several that could
serve as anchors to motivate the symposium discussions:
- Expertise is acquired in a **piecemeal** manner, with one element being added at a time.
- Learning is an **incremental** activity that processes one experience at a time.
- Learning is **guided by prior experience**, which aids in the interpretation of new experiences.
- Expertise is acquired and refined **rapidly**, from **few training cases**.

This list is not exhaustive and only serves to provide initial motivation. We
will encourage participants to propose, highlight, and discuss features of
human learning that are central to their work and could inspire future
computational work. A major output of the symposium will be a list of
human-like capabilities that could be the focus for a sustained research
program. We also hope that by encouraging researchers to emphasize and discuss
human-like capabilities, rather than emphasizing their particular
methodological approach, we can foster more effective communication between
people that come from different disciplines (e.g., Psychology or AI) and
methodological perspectives (e.g., Cognitive Architectures and Deep Learning)
backgrounds.

### Creating Human-Like Learning Systems

Given these characteristics, the major focus of the symposium will be to
explore ongoing and proposed research into how to create artificial systems
that exhibit human-like learning capabilities. Many different research
efforts—spanning multiple methodological paradigms—have emphasized some aspects
of human-like learning:
- **Cognitive architectures**: Researchers in this area have identified and
  operationalized several human-like learning assumptions, such as the
  assumption that "learning occurs online and incrementally" (Laird, Lebiere, &
  Rosenbloom, 2017).
- **Interactive task learning**: This paradigm emphasizes the incremental,
  multimodal acquisition of new task knowledge from a limited amount of
  interactive instruction provided by human teachers (Laird et al., 2017); early
  examples include systems like AnimNL (Webber, Badler, Di Eugenio, Geib,
  Levison, & Moore, 1995)  and more recent examples include  AILEEN (Mohan,
  Klenk, Shreve, Evans, Ang, & Maxwell, 2020) and ONYX (Ruoff, Myers, & Maedche,
  2023).
- **Extended/continual learning**: A class of approaches that emphasizes learning
  of different types of knowledge or functions over extended durations (e.g.,
  years); a notable example is NELL (Mitchell et al., 2018), which continually
  crawls the web and grows and refines its relational ontology based on what it
  learns.
- **Probabilistic programming**: This paradigm emphasizes the use of Bayesian
  priors (over both internal structures and parameters) to guide and constrain
  learning, which enables the acquisition of new concepts with few examples
  (Lake, Salakhutdinov, & Tenenbaum, 2015).
- **Concept formation**: Systems like Cobweb (Fisher & Langley, 1990; Fisher & Yoo,
  1993; MacLellan, Matsakis, & Langley, 2022) emphasize the incremental,
  piecemeal acquisition of concepts and rapid, few-example learning. 
- **Analogical and case-based learning**: The SAGE (McLure, Friedman, & Forbus,
  2015) system leverages analogical processing to support efficient, few
  example learning over structured representations.
- **Logic-based learning**: Recent work on this topic emphasizes the induction of
  modular knowledge structures that can be composed at performance and guide
  subsequent learning (Cropper, Dumančić, & Muggleton, 2020).
- **Simulated students**: Efforts to simulate human novices has highlighted the
  importance of prior knowledge and self-explanation in guiding subsequent
  learning (VanLehn, Jones, & Chi, 1991) and emphasized comparison of human and
  machine behavior—both correct and incorrect—as a tool to better understand and
  simulate human learning (MacLellan, Harpstead, Patel, Koedinger, 2016;
  Weitekamp, Ye, Rachatasumrit, Harpstead, & Koedinger, 2020).
- **Human-like neural network approaches**: Although most current neural network
  approaches do not emphasize human-like learning, there are some efforts that
  do. One recent example investigates how to model humans’ ability to learn
  increasingly complex skills across a lifespan without major instances of
  catastrophic interference or forgetting (Lyndgaard, Tidler, Provine, & Varma,
  2022).

These are just a few examples of research lines that emphasize human-like
learning. The symposium aims to bring together individual researchers working
across different paradigms who may feel isolated in their commitment to
human-like learning, and to create a community that can foster collaboration
and inspire innovation on this topic. Many of these efforts share similar
goals, but there has only been limited discussion about common insights for
creating human-like learning systems that span across paradigms. The symposium
will encourage discussion on this topic by having speakers representing
different paradigms present in the same session and facilitating a broader
group discussion about cross-paradigm commonalities.

### Evaluating Human-Like Learning Systems

Research on this topic will need some way to measure progress. Thus, another
major aim of the symposium will be to discuss how to evaluate systems with
human-like capabilities. Here are a few potential evaluations participants
might discuss:
- assessing systems based on their **learning efficiency**, rather than final
  performance; 
- measuring **fits to human behavioral data**, both quantitative and qualitative;
- establishing a set of **target capabilities**, with qualitative measures of
  attainment; and
- evaluating human-like learning systems in terms of **ease of use** and
  acceptance by **human users** who are interacting with them.

These are just a selection of several potential evaluation ideas and a key
deliverable of the symposium will be to solicit participants ideas about
evaluations and to encourage formation of a community consensus around
appropriate evaluations. 

### Broader Impacts of Human-Like Learning Systems

Lastly, we envision that research into human-like learning will have
substantial broader impacts across several research communities. For example,
it could lead to improvements in the efficiency and sustainability of
machine-learning models, and enable them to be more adaptable and flexible. It
could also contribute to a deeper understanding of human learning, and lead to
the reproduction and modeling of human learning capabilities. Finally, it could
lead to more user-friendly AI systems with more relatable, human-like
capabilities. A final aim of the symposium will be to reflect on and discuss
the broader implications for research into human-like learning.

## Organization and Schedule

The event will occur at the AAAI Spring Symposium at Stanford from March 25th
to March 27th. To support the above aims, we plan to dedicate time in the
schedule for group discussions, so we can work towards a consensus on questions
like: 
- What are the key characteristics of human learning that should be reproduced?
- How do different frameworks reproduce these features?
- How can we evaluate the adequacy of a given model?
- What are the broader impacts for human-like learning research?

We will have a small number of invited speakers set the context for the
symposium. The remaining talks will be selected by the organizing committee
based on abstracts submitted by participants. We aim to solicit around 20
technical presentations through this process. The talks will be organized into
thematic groups that will be presented together, with the intention of
highlighting commonalities across research efforts and paradigms. Each
presentation will be allotted 30 minutes, with 20 minutes for the presentation
and 10 minutes for discussion. We also plan to schedule time for general
reflection and discussion to support the symposium's aims (e.g., discussion of
the evaluation of human-like learning systems). Exactly when we schedule these
discussions will depend on the overall scheduling of submissions received, but
we aim to have some discussion around the end of each day. Below is a tentative
schedule.

### Tentative Day 1 Schedule (3/25)

| Start | End   | Activity                                     |
|-------|-------|----------------------------------------------|
| 9:00  | 9:30  | Welcome & Introduction                       |
| 9:30  | 10:00 | Invited Speaker 1                            |
| 10:00 | 10:30 | Invited Speaker 2                            |
| 10:30 | 11:00 | Break                                        |
| 11:00 | 11:30 | Technical Presentation 1                     |
| 11:30 | 12:00 | Technical Presentation 2                     |
| 12:00 | 12:30 | Technical Presentation 3                     |
| 12:30 | 2:00  | Lunch                                        |
| 2:00  | 2:30  | Technical Presentation 4                     |
| 2:30  | 3:00  | Technical Presentation 5                     |
| 3:00  | 3:30  | Technical Presentation 6                     |
| 3:30  | 4:00  | Break                                        |
| 4:00  | 5:30  | Poster Session                               |
| 6:00  | 7:00  | AAAI Symposium Reception                     |

### Tentative Day 2 Schedule (3/26)

| Start | End   | Activity                                     |
|-------|-------|----------------------------------------------|
| 9:00  | 9:30  | Technical Presentation 7                     |
| 9:30  | 10:00 | Technical Presentation 8                     |
| 10:00 | 10:30 | Technical Presentation 9                     |
| 10:30 | 11:00 | Break                                        |
| 11:00 | 11:30 | Technical Presentation 10                    |
| 11:30 | 12:00 | Technical Presentation 11                    |
| 12:00 | 12:30 | Technical Presentation 12                    |
| 12:30 | 2:00  | Lunch                                        |
| 2:00  | 2:30  | Technical Presentation 13                    |
| 2:30  | 3:00  | Technical Presentation 14                    |
| 3:00  | 3:30  | Technical Presentation 15                    |
| 3:30  | 4:00  | Break                                        |
| 4:00  | 4:30  | Technical Presentation 16                    |
| 4:30  | 5:00  | Technical Presentation 17                    |
| 5:00  | 5:30  | Reflection & Discussion Session              |
| 6:00  | 7:00  | AAAI Plenary Session                         |

### Tentative Day 3 Schedule (3/27)

| Start | End   | Activity                                     |
|-------|-------|----------------------------------------------|
| 9:00  | 9:30  | Day 3 Introduction                           |
| 9:30  | 10:00 | Technical Presentation 18                    |
| 10:00 | 10:30 | Technical Presentation 19                    |
| 10:30 | 11:00 | Coffee Break                                 |
| 11:00 | 11:30 | Technical Presentation 20                    |
| 11:30 | 12:30 | Reflection & Discussion Session              |

We believe that this structure will encourage high-quality interaction among
participants and foster cross-paradigm communication and collaboration. By
emphasizing discussion of key human learning capabilities rather than centering
the discussion on methodologies, we hope to make the symposium broadly
accessible to researchers from different perspectives and paradigms. By
intentionally grouping talks to highlight similarities across efforts, we hope
to promote discussion across perspectives and methodologies. Finally, by
discussing evaluation and broader impacts, we hope to support the creation of a
community of dedicated researchers who are enthusiastic about investigating
human-like learning. This in turn should promote additional research in this
important area. If there is sufficient interest, we will organize a publication
(e.g., a journal special issue) that reports results from the event.

## Abstract Submissions

Authors will submit abstracts, which the organizing committee will use to
decide on session topics and presentations. Abstracts will also be
shared with attendees before the start of the symposium. Authors of submissions
that are not presented as talks will be invited to participate in a poster
session during the first day. In choosing presenters, the committee will give
preference to submissions that are more closely aligned to the overarching
theme, while also trying to give coverage to different aspects of the theme.

Please use the [AAAI Author Kit](https://aaai.org/authorkit24-2/)
for your abstract submission, to ensure formatting across submissions is
consistent.

Please submit abstracts via [easychair](https://easychair.org/my/conference?conf=sss24).

## Symposium Organizers

- [Christopher J. MacLellan](https://chrismaclellan.com/), [Teachable AI Lab](https://tail.cc.gatech.edu), Georgia Institute of Technology, <cmaclell@gatech.edu>
- [Ute Schmid](https://www.uni-bamberg.de/en/cogsys/team/schmid-ute/), University of Bamberg, <ute.schmid@uni-bamberg.de> 
- [Douglas Fisher](https://engineering.vanderbilt.edu/bio/douglas-fisher), Vanderbilt University, <douglas.h.fisher@vanderbilt.edu>
- Randolph M. Jones, Soar Technology, LLC, <rjones@soartech.com>

## References

- Anderson, J. R. (1982). Acquisition of cognitive skill. Psychological review, 89(4), 369.
- Anderson, J. R. (1983). A spreading activation theory of memory. Journal of verbal learning and verbal behavior, 22(3), 261-295.
- Cropper, A., Dumančić, S., & Muggleton, S. H. (2020). Turning 30: New ideas in inductive logic programming. arXiv preprint arXiv:2002.11002.
- Feigenbaum, E.A. (1959) An Information Processing Theory of Verbal Learning. RAND Report P-1817. Santa Monica, CA: RAND Corporation.
- Feigenbaum, E. A., & Simon, H. A. (1984). EPAM-like models of recognition and learning. Cognitive Science, 8, 305–336.
- Fisher, D., & Langley, P. (1990). “The Structure and Formation of Natural Categories,” in G. Bower (ed.), The Psychology of Learning and Motivation, 26, San Diego, CA: Academic Press, 241–284.
- Fisher, D., & Yoo, J. (1993). “Problem solving, categorization, and concept learning: A unifying view,” in G. Nakamura, R. Taraban, & D. Medin (eds.), The Psychology of Learning and Motivation, 29, San Diego, CA: Academic Press, 219–255.
- Laird, J. E., Gluck, K., Anderson, J., Forbus, K. D., Jenkins, O. C., Lebiere, C., ... & Kirk, J. R. (2017). Interactive task learning. IEEE Intelligent Systems, 32(4), 6-21.
- Laird, J. E., Lebiere, C. & Rosenbloom, P. S. (2017). A Standard Model for the Mind: Toward a Common Computational Framework across Artificial Intelligence, Cognitive Science, Neuroscience, and Robotics, AI Magazine 38(4). https://doi.org/10.1609/aimag.v38i4.2744
- Laird, J. E., Newell, A., & Rosenbloom, P. S. (1987). Soar: An architecture for general intelligence. Artificial intelligence, 33(1), 1-64.
- Lake, B. M., Salakhutdinov, R., & Tenenbaum, J. B. (2015). Human-level concept learning through probabilistic program induction. Science, 350(6266), 1332-1338.
- Langley, P. (2022). The computational gauntlet of human-like learning. In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 36, No. 11, pp. 12268-12273).
- Lyndgaard, S., Tidler, Z. R., Provine, L., & Varma, S. (2022). Catastrophic interference in neural network models is mitigated when the training data reflect a power-law environmental structure. In Proceedings of the Annual Meeting of the Cognitive Science Society (Vol. 44, No. 44).
- MacLellan, C.J., Harpstead, E., Patel, R., Koedinger, K.R. (2016). The Apprentice Learner Architecture: Closing the loop between learning theory and educational data. In Proceedings of the 9th International Conference on Educational Data Mining. Raleigh, NC: International Educational Data Mining Society.
- MacLellan, C.J., Matsakis, P., & Langley, P. (2022). Efficient Induction of Language Models via Probabilistic Concept Formation. In Proceedings of the Tenth Annual Conference on Advances in Cognitive Systems.
- McLure, M. D., Friedman, S. E., and Forbus, K. D. (2015). Extending analogical generalization with near-misses. In Proceedings of the Twenty-Ninth AAAI Conference on Artificial Intelligence, 565–571. Austin, TX: AAAI Press.
- Mitchell, T., Cohen, W., Hruschka, E., Talukdar, P., Yang, B., Betteridge, J., ... & Welling, J. (2018). Never-ending learning. Communications of the ACM, 61(5), 103-115.
- Mohan, S., Klenk, M., Shreve, M., Evans, K., Ang, A., & Maxwell, J. (2020). Characterizing an Analogical Concept Memory for Architectures Implementing the Common Model of Cognition. In Proceedings of the Annual Conference on Advances in Cognitive Systems 2020. 
- Rumelhart, D.E., J.L. McClelland and the PDP Research Group (1986). Parallel Distributed Processing: Explorations in the Microstructure of Cognition. Volume 1: Foundations, Cambridge, Massachusetts: MIT Press, ISBN 978-0262680530
- Ruoff, M., Myers, B. A., & Maedche, A. (2023). ONYX: Assisting Users in Teaching Natural Language Interfaces Through Multi-Modal Interactive Task Learning. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (pp. 1-16).
- VanLehn, K., Jones, R. M., & Chi, M. T. H. (1991). Modeling the self-explanation effect with Cascade 3. In Proceedings of the human factors in computing systems conference (pp. 132–137).
- Webber, B., Badler, N., Di Eugenio, B., Geib, C., Levison, L., & Moore, M. (1995). Instructions, intentions and expectations. Artificial Intelligence, 73(1-2), 253-269.
- Weitekamp, D., Ye, Z., Rachatasumrit, N., Harpstead, E., & Koedinger, K. (2020). Investigating differential error types between human and simulated learners. In Proceedings of the 21st International Conference on Artificial Intelligence in Education, 586-597. Ifrane, Morocco: Springer International Publishing.

