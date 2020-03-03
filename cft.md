---
title: SemEval-2021: Call for Task Proposals
---

# Call for Task Proposals – SemEval-2021: International Workshop on Semantic Evaluation

We invite proposals for tasks to be run as part of SemEval-2021. SemEval (the International Workshop on Semantic Evaluation) is an ongoing series of evaluations of computational semantics systems, organized under the umbrella of SIGLEX, the Special Interest Group on the Lexicon of the Association for Computational Linguistics.

The SemEval evaluations explore the nature of meaning in natural languages in practical terms, by providing a mechanism to identify problems (e.g., how to characterize meaning and what is necessary to compute it) and to explore the strengths of possible solutions by means of standardized evaluation on shared datasets. SemEval evaluations initially focused on identifying word senses computationally, but have later grown to investigate the interrelationships among elements in a sentence (e.g., semantic relations, semantic parsing, semantic role labeling), relations between sentences (e.g., coreference), and author attitudes (e.g., sentiment analysis), among other research directions.

For SemEval-2021, we welcome any task that can test an automatic system for semantic analysis of text, be it application-dependent or application-independent. We especially welcome tasks for different languages, cross-lingual tasks, tasks requiring semantic interpretation, and tasks with both intrinsic and application-based evaluation. See the websites of previous editions of SemEval to get an idea about the range of tasks explored, e.g., for [SemEval-2019](http://alt.qcri.org/semeval2019/) and [SemEval-2020](http://alt.qcri.org/semeval2020/).

We strongly encourage proposals based on pilot studies that have already generated initial data and that can provide concrete examples and foresee the challenges of preparing the full task. In the event of receiving many proposals, preference will be given to tasks that have already run a pilot study for the proposed task.

We especially welcome tasks that are devoted to developing novel applications of computational semantics. We will encourage tasks that have a clearly defined end-user application showcasing and enhancing our understanding of computational semantics, as well as extending the current state-of-the-art.

## Task Selection

Task proposals will be reviewed by experts, and reviews will serve as the basis for acceptance decisions. Everything else being equal, more innovative new tasks will be given preference over task re-runs. Task proposals will be evaluated on:
- Novelty: Is the task on a compelling new problem that has not been explored much in the community? Is the task a rerun, but covering substantially new ground (new sub-tasks, new types of data, new languages, etc.)?
- Interest: Is the proposed task likely to attract a sufficient number of participants?
- Data: Are the plans for collecting data convincing? Will the resulting data be of high quality? Will annotations have meaningfully high inter-annotator agreements? Have all appropriate licenses for use and re-use of the data after the evaluation been secured? Have all international privacy concerns been addressed? Will the data annotation be ready on time?
- Evaluation: Is the methodology for evaluation sound? Is the necessary infrastructure available or can it be built in time for the shared task? Will research inspired by this task be able to evaluate in the same manner and on the same data after the initial task?
- Impact: What is the expected impact of the data in this task on future research beyond the SemEval Workshop?

## New Tasks vs. Task Reruns

We welcome both new tasks and task reruns. For a new task, an aspect to be addressed in the proposal is whether it would be able to attract participants. Preference will be given to novel tasks that have not received much attention yet.

For task reruns, the organizers should in their proposal defend the need for another iteration of their task. Valid reasons for a rerun would be: the need for a new form of evaluation (e.g., a new metric to test new phenomena, a new application-oriented scenario, etc.), the need to test on new types of data (e.g., social media, domain-specific corpora), a significant expansion in scale over a previous trial run of the task, etc.

In the case of a rerun, we further discourage carrying over the same tasks and just adding new subtasks as this can lead to the accumulation of too many subtasks. Evaluating on a different dataset with the same task formulation typically should not be considered a separate subtask.

Tasks that have already run for three years will not be accepted for SemEval-2021. If however the organizers estimate there is need for another iteration of their task, they are welcome to submit a task rerun proposal for SemEval-2021. Solid justification for the rerun will be needed, highlighting its novel aspects compared to previous editions, in respect to the criteria discussed above.

## Task Organization

We welcome people who have never organized a SemEval task before, as well as those who have. Apart from providing trial, training, and test data, task organizers are expected to:
- provide to task participants format checkers and standard scorers.
- provide baseline systems that participants can use as a starting point (in order to lower the obstacles to participation). A baseline system typically contains code that reads the data, creates a baseline response (e.g., random guessing, majority class prediction, etc.), and outputs the evaluation results. Whenever possible, baseline systems should be written in widely used programming languages and/or should be implemented as a component for standard NLP pipelines such as UIMA or GATE.
- verify the data annotations have sufficient inter-annotator agreement, and verify licenses for the data allow its use in the competition and afterward, and any potential security or privacy concerns have been resolved
- create a mailing group (and optionally website) for the task and post all relevant information there.
- create a CodaLab or other similar competition for the task and upload the evaluation script.
- manage submissions on CodaLab or the similar competition site.
- write a task description paper to be included in SemEval proceedings.
- manage participants’ system description submissions to the task; and possibly shepherd papers that need additional help in improving the writing.
- review one or two other task description papers.
 
## Important Dates

- __Task proposals due: March 20, 2020__
- Task selection notification: May 8, 2020
- Trial data ready: July 31, 2020
- Training data ready: September 4, 2020
- Test data ready: December 3, 2020
- __Evaluation start: January 10, 2021__
- __Evaluation end: January 31, 2021__
- Paper submission due: February 23, 2021
- Notification to authors: March 29, 2021
- Camera ready due: April 5, 2021
- __SemEval workshop: Summer 2021__

Tasks that fail to keep up with crucial deadlines such as the dates for having the task and CodaLab website up and dates for uploading trial, training, and test data may be cancelled at the discretion of SemEval organizers. While consideration will be given to extenuating circumstances, our goal is to provide sufficient time for the participants to develop strong and well-thought-out systems. Cancelled tasks will be encouraged to submit proposals for the subsequent year’s SemEval.

The SemEval-2021 Workshop will be co-located with a major NLP conference in 2021.

## Submission Details

The task proposals should be a self-contained document of no longer than 3 pages, and should follow the ACL 2020 style guidelines. References do not count against the page limit. The submissions should use the official ACL 2020 style templates:

- [LaTeX and Microsoft Word](http://acl2020.org/downloads/acl2020-templates.zip)
- [Overleaf](https://www.overleaf.com/latex/templates/acl-2020-proceedings-template/zsrkcwjptpcd)

All submissions must be in PDF format.

Each proposal should contain the following:

- Overview
  * A summary of the task in general
  * Motivation, why this task is needed and which communities would be interested in participating
  * What the expected impact of the task will be
- Data & Resources
  * How the training/testing data will be built and/or procured
  * What source texts/corpora are going to be used? Please discuss whether existing corpora have been re-used or not.
  * How much data is going to be produced
  * How will quality of the data be ensured and evaluated
  * An example of what a data instance would look like
  * The anticipated availability of the necessary resources to the participants (copyright, etc.)
  * The resources required to prepare the task (computation and annotation time, costs of annotations, etc.) and their availability
  * Details regarding secured or to-be-secured permissions for use of this data by the copyright holders by participants in the SemEval evaluation and by the research community in perpetuity after the SemEval evaluation
  * Details that address any potential concerns that could arise with respect to privacy, confidentiality, or security (e.g. if personally identifiable information of private individuals is released or detectable, if medical information is present)
- Pilot Task
  * Details of the pilot task, if any
  * What lessons were learned and how these will impact the future task design
- Evaluation
  * The evaluation methodology to be used, including clear evaluation criteria
- For Task Reruns
  * Justification for why a new iteration of the task is needed, using the criteria discussed above
  * What will differ from the previous instance
  * The expected impact of the re-run compared with the previous instance
- Task organizers
  * Names, affiliations, brief description of research interests and relevant experience, contact information (email) including a single email address that SemEval organizers can use to contact all task organizers at once.
  * The names of SemEval tasks you have run in the past along with year the task was run.
  
Proposals will be reviewed by an independent group of area experts who may not have familiarity with recent SemEval tasks and therefore, all proposals should be written in a self-explanatory manner and contain sufficient examples.

__The submission webpage will be made available soon.__ Please check this page for updates.

In case you are not sure whether a task is suitable for SemEval, please feel free to get in touch with the SemEval organizers at <semeval-organizers@googlegroups.com> to discuss your idea.

## Chairs

- Nathan Schneider, Georgetown University
- Alexis Palmer, University of North Texas
- Aurelie Herbelot, University of Trento
- Xiaodan Zhu, Queen’s University

Contact: <semeval-organizers@googlegroups.com>
