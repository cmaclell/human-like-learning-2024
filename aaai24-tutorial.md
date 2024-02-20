---
title: AAAI Tutorial on Probabilistic Concept Formation with Cobweb
nav_title: AAAI-24 Tutorial
permalink: /aaai24-tutorial/
layout: page
order: 2
---


* TOC
{:toc}

## Important Event Information

| Key Dates                                                |                     |
|----------------------------------------------------------|---------------------|
| AAAI Early Registration Deadline                         | December 20th, 2023 |
| Course Materials Posted to Website                       | February 1st, 2024   |
| AAAI-24 Tutorial Takes Place in Vancouver, BC, Canada    | February 21st, 2024 from 8:30am-12:30pm  |

You can register for AAAI and the Tutorial and Lab Forum at the [conference
website](https://aaai.org/aaai-conference/registration/). We recommend
registering early, but it is also possible to register anytime up until the
event itself (AAAI-24 allows for late and on-site registration).

## Tutorial Description

### Overview

<div style="float:right; padding: 15px;">
<img src="/files/cobweb-tutorial.png" alt="A detailed illustration depicts a modern classroom or workshop setting with a large digital display at the front. The screen showcases various machine learning concepts, including Bayesian Models, Decision Trees, Nearest Neighbor, and Clustering. Each concept is visually represented by corresponding graphs and models. A tree-like network structure with vibrant nodes radiates from the center of the screen. In front of the display, an instructor, holding a pointer, explains the concepts to an older individual. Below them, a group of diverse individuals sits around a horseshoe-shaped table, equipped with advanced touch-screen monitors, attentively listening and interacting with their devices. The ambiance is studious, with a futuristic touch symbolizing the advanced nature of the subject matter." style="height: 350px;">
</div>

This tutorial will offer an introduction to the
[Cobweb](https://github.com/cmaclell/concept_formation) family of concept
formation approaches (Fisher, 1987). This class of methods supports
incremental, unsupervised learning from a continuous stream of examples
(Fisher, Pazzani, & Langley, 2014). Throughout the tutorial, we explore the
core theory underlying Cobweb as well as several extensions and applications
(e.g., to language and vision tasks). We will also demonstrate its use through
practical examples to real-world scenarios. This tutorial will provide
participants with the knowledge and hands-on experience required to effectively
apply Cobweb to their own tasks.

**Keywords:** Concept formation, Incremental learning, Unsupervised Classification, Cobweb

### Why have a tutorial on Cobweb?

As humans, we excel at learning knowledge and skills across different domains,
forming concepts based on our observations. We then use our concept knowledge
to guide classification and learning over future experiences. Creating a model
of human concept formation, has been one of the primary areas of focus in
machine learning (Gennari, Langley, & Fisher, 1989). The aim of this tutorial
is to offer an overview of the Cobweb family of approaches, which adopt a
probabilistic formalism and support incremental, unsupervised learning. Our
goal is to introduce this approach to a broader audience of researchers in
machine learning and demonstrate its practical applications to real-world
scenarios.

Throughout this tutorial, we will introduce multiple Cobweb approaches and
provide practical guidance on obtaining and running code for each approach.
More generally, we wish to present a new framework for continual, human-like
learning, offering a unique perspective on how machines can utilize concepts
for classifying observations. We will illustrate this through practical
applications and conclude by sharing our thoughts on the future of research in
Cobweb and human-like learning.
 
Our tutorial seeks to bring together researchers from diverse backgrounds
(e.g., cognitive modeling and machine learning) and applications (e.g.,
language and vision). By fostering interdisciplinary collaboration, we envision
integrating methodologies and ideas from different fields, potentially leading
to novel approaches and breakthroughs in AI research. The tutorial will provide
an enriching and collaborative learning experience that enhances attendee
understanding of incremental concept formation and human-like learning. It will
also promote interdisciplinary collaboration--encouraging the integration of
different of machine learning paradigms and methodologies.

## Schedule

The tutorial will be structured into three parts, with additional Q&A sessions and hand-on activities:

| Start   | End     | Session                                               | Speaker                  |
|---------|---------|-------------------------------------------------------|--------------------------|
| 8:30am  |  9:15am | [Overview of Basic Cobweb](/files/tutorial-slides/Fisher-Overview-of-Basic-Cobweb.pdf) (35 min talk + 10 min Q&A) | Doug Fisher              |
| 9:15am  |  9:30am | [Hands-On Example of Cobweb with Tabular Data](https://github.com/Teachable-AI-Lab/cobweb/blob/main/examples/tabular/)          | Christopher J. MacLellan |
| 9:30am  | 10:15am | [Early Extensions to Cobweb](files/tutorial-slides/Langley-Cobweb-Extensions.pdf) (35 min talk + 10 min Q&A)    | Pat Langley              |
| 10:15am | 10:30am | [Hands-On Example of Cobweb with Continuous Data](https://github.com/Teachable-AI-Lab/cobweb/tree/main/examples/continuous)     | Christopher J. MacLellan |
| 10:30am | 11:00am | Break                                                 | ---                      |
| 11:00am | 11:45am | [New & Future Extensions to Cobweb](files/tutorial-slides/MacLellan-cobweb-new-and-future-directions.pdf) (35 min talk + 10 min Q&A) | Christopher J. MacLellan |
| 11:45am | 12:00pm | [Hands-On Example of Cobweb on a Vision Task](https://github.com/Teachable-AI-Lab/cobweb/tree/main/examples/vision)          | Christopher J. MacLellan |
| 12:00pm | 12:15pm | [Hands-On Example of Cobweb on a Language Task](https://github.com/Teachable-AI-Lab/cobweb/tree/main/examples/language-roc)            | Christopher J. MacLellan |
| 12:15pm | 12:30pm | General Q&A                          | --- |

<!---
### Focused Topics for the Tutorial
We will start the tutorial with a theory section, which consists of an
introduction to concept formation, and the core assumptions and ideas of the
Cobweb family. In the next two sections we will present the early and more
recent extensions and applications of Cobweb through hands-on examples. The
final section will be a discussion about the future promise of the Cobweb
paradigm.
- **Theory:** This section provides an introduction to concept formation and
  covers the Cobweb core algorithm. We then proceed to practical examples using
  tabular data.
- **Early Extensions:** The second section focuses on early
  extensions and applications of Cobweb, including support for relational and
  structured representations. 
- **Recent and Future Directions:** In the third section, we explore new
  Cobweb approaches that support language and vision tasks. In each case, we
  outline key extensions with examples. Additionally, we share insights on
  potential improvements and future directions. In the hands-on part we guide the
  audience through setting up and running the code, as well as evaluating and
  visualizing results.
--->

### Tutorial Example Code

We've created a repository specifically for this tutorial
[here](https://github.com/Teachable-AI-Lab/cobweb). Please check out the repo
before coming and consider trying to install the package (via pip install)
beforehand.  Links to the specific tutorial activities from this repo are
included in the schedule above. You can also find another relevant repo
[here](https://github.com/cmaclell/concept_formation), however, the main branch
of this repo is still being updated and so does not reflect the latest cobweb
extensions we plan to discuss (e.g., for language and vision tasks). 

### Prerequisite Knowledge

This tutorial is tailored to participants with a basic background in computer
science and AI/ML. Anyone with intro-level coursework in Algorithms and Machine
Learning will be able to fully engage with the tutorial. The emphasis here lies
in understanding the concept formation approach, which is based on
psychological studies of how humans incrementally develop and utilize concepts.

## Organizing Committee

- [Christopher J. MacLellan](https://chrismaclellan.com/), [Teachable AI Lab](https://tail.cc.gatech.edu), Georgia Institute of Technology, <cmaclell@gatech.edu>
- [Douglas Fisher](https://engineering.vanderbilt.edu/bio/douglas-fisher),
  Vanderbilt University, <douglas.h.fisher@vanderbilt.edu>
- [Pat Langley](http://www.isle.org/~langley/), [Institute for the Study of Learning and Expertise](http://www.isle.org), <patrick.w.langley@gmail.com>
- [Nicki Barari](https://tail.cc.gatech.edu/people.html), Drexel University, <nb895@drexel.edu>

## References

- Fisher, D. 1996. Iterative optimization and simplification of hierarchical clusterings. Journal of artificial intelligence research, 4: 147–178.
- Fisher, D. H. 1987. Knowledge acquisition via incremental conceptual clustering. Machine learning, 2: 139–172.
- Fisher, D. H. 1988. A computational account of basic level and typicality effects. In AAAI, 233–238.  Fisher, D. H.; Pazzani, M. J.; and Langley, P. 2014. Concept formation: Knowledge and experience in unsupervised learning. Morgan Kaufmann.
- Gennari, J. H.; Langley, P.; and Fisher, D. 1989. Models of incremental concept formation. Artificial intelligence, 40(1- 3): 11–61.
- Langley, P. 2022. The computational gauntlet of human- like learning. In Proceedings of the AAAI Conference on Artificial Intelligence, volume 36, 12268–12273.
- Lebowitz, M. 1987. Experiments with incremental concept formation: UNIMEM. Machine learning, 2: 103–138.
- MacLellan, C. J.; Harpstead, E.; Aleven, V.; and Koedinger, K. R. 2015. Trestle: Incremental learning in structured do- mains using partial matching and categorization. In Proceedings of the 3rd Annual Conference on Advances in Cognitive Systems.
- MacLellan, C. J.; Matsakis, P.; and Langley, P. 2022. Efficient Induction of Language Models Via Probabilistic Concept Formation. arXiv preprint arXiv:2212.11937.
- MacLellan, C. J.; and Thakur, H. 2022. Convolutional Cob- web: A Model of Incremental Learning from 2D Images.  arXiv preprint arXiv:2201.06740.
- McKusick, K.; and Thompson, K. 1990. Cobweb/3: A portable implementation. Technical report.
- McKusick, K. B.; and Langley, P. 1991. Constraints on Tree Structure in Concept Formation. In IJCAI, volume 91, 810– 816. Citeseer.
- Thompson, K.; and Langley, P. 1991. Concept formation in structured domains. In Concept formation, 127–161. Elsevier.
