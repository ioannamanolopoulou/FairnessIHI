# HDR001 Fairness in healthcare modelling

## Basic Information

| Course Item | Detail |
| :---- | :------ |
| Title | Fairness in healthcare modelling |
| Leader | [Brieuc Lehmann, Honghan Wu, Ioanna Manolopoulou](https://ioannamanolopoulou.github.io/) |
| Duration | 2 days |
| Location | Institute for Health Informatics, Room ??? |

## Description

### Overview 

The aim of this training is to cover the basic principles of fairness in healthcare modelling and highlight aspects of fairness that Health Data Scientists need to be aware of in their own research.

### Intended Learning Outcomes

- Participants will understand how bias can manifest itself in the different stages of predictive modelling in healthcare.
- Participants will understand the implications of biased samples, especially in the context of health data science such as genetic data or underreported medical conditions.
- Participants will have a broad understanding of how to evaluate algorithmic fairness within a given predictive model. 

### Teaching methods

The first part of the training will be largely based around discussions, but participants are expected to have read 1-2 of the key papers in this area that are listed below. In the second part, participants will be split into groups and work on a task. 

## Pre-requisites

TO BE REPLACED BY WHATEVER DATASET WE WILL USE. Students will also need access to the [Nightingale](https://app.nightingalescience.org/projects) data. Nightingale is an open platform for health data but requires registration in advance and approval can take several days, so early registration is required. The platform contains lots of information on existing projects. Students are also advised to complete the MRC [“Research, GDPR and confidentiality”](https://byglearning.com/mrcrsc-lms/course/index.php?categoryid=1) e-learning module (or another equivalent training). 

For those who may be interested in finding out more about fairness in healthcare modelling, the MIT course [“Ethical Machine Learning in Human Deployments”](https://canvas.mit.edu/courses/14219) by Dr. Marzyeh Ghassemi is excellent. 

All the group-work programming will be carried out in *Python*, so knowledge of Python would be preferred but not necessary. 

**To do:**

1. Register for access to the [Nightingale](https://app.nightingalescience.org/projects) data.
2. Complete the MRC [“Research, GDPR and confidentiality”](https://byglearning.com/mrcrsc-lms/course/index.php?categoryid=1) e-learning module.

## Timetable

### Preparation


*Reading papers ahead of the workshop:*

1. Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, and Aram Galstyan, (2022). *A Survey on Bias and Fairness in Machine Learning*. ACM Comput. Surv. 54, 6, Article 115.

2. Harini Suresh and John Guttag (2021). *Understanding Potential Sources of Harm throughout the Machine Learning Life Cycle*. MIT Case Studies in Social and Ethical Responsibilities of Computing,


### Day 1: Introduction

**9.30-10.00 What is bias in healthcare modelling?**

**10:00-10:30 Bias in data collection**

- What is selection bias? 
- What are common sources of selection bias? 
- Can we correct for selection bias? 

**10:30-11:00 Algorithmic fairness in healthcare**

- What is algorithmic fairness?
- How do we evaluate algorithmic fairness? 
- What are the limits of algorithmic solutions? 

**11:15-11:30 Race and gender in health data**

- How is race and gender encoded in health data? 
- Pros and cons of including these variables in statistical modelling. 

**11:30-12:30 External speaker**

**14:00-14:30  Summary and introduction to Day 2 task.**
**14:30-16:30  Work on task**

### Day 2: Group work

The second day will be mostly spent working on the task.

| Time | Task |
| ---- | ---- |
| 9:30-11:30 | Exploratory data analysis |
| 11:30-12:30 | External speaker|
| 14:00-14:30 | Finalise models |
| 14:30-15:00 | Submit results and evaluate outcomes |
| 15:00-15:45 | Short presentations by each group |
| 15:45-16:00 | Summary and closing remarks |

### Additional resources

1. Sahil Verma and Julia Rubin (2018). *Fairness definitions explained*. In Proceedings of the International Workshop on Software Fairness (FairWare '18). 

2. Irene Y. Chen, Emma Pierson, Sherri Rose, Shalmali Joshi, Kadija Ferryman, Marzyeh Ghassemi (2021). *Ethical Machine Learning in Healthcare*. Annual Review of Biomedical Data Science, 4:1, 123-144 

3. Laliberté V, Giguère CE, Potvin S, Lesage A; Signature Consortium (2020). *Berkson's bias in biobank sampling in a specialised mental health care setting: a comparative cross-sectional study.* BMJ Open.

4. Rory Collins (2012) *What makes UK Biobank special?*  The Lancet, Volume 379, Issue 9822. Including comment by James M. Swanson.

5. Huang, Jonathan Yinhao (2021) *Representativeness Is Not Representative: Addressing Major Inferential Threats in the UK Biobank and Other Big Data Repositories.* Epidemiology: Volume 32 - Issue 2.

6. B.C.L. Lehmann, M. Mackintosh, G. McVean, C.C. Holmes (2021). *Optimal strategies for learning multi-ancestry polygenic scores vary across traits.* BioRxiv 2021.01.15.426781.


7. Mitchell, S., Potash, E., Barocas, S., D'Amour, A., and Lum, K., (2018) *Prediction-Based Decisions and Fairness: A Catalogue of Choices, Assumptions, and Definitions*, arXiv.

8. Solon Barocas, Anhong Guo, Ece Kamar, Jacquelyn Krones, Meredith Ringel Morris, Jennifer Wortman Vaughan, W. Duncan Wadsworth, and Hanna Wallach (2021). *Designing Disaggregated Evaluations of AI Systems: Choices, Considerations, and Tradeoffs.* In Proceedings of the 2021 AAAI/ACM Conference on AI, Ethics, and Society (AIES '21). 

9. Abigail Z. Jacobs and Hanna Wallach, (2021). *Measurement and Fairness.* In Proceedings of the 2021 ACM Conference on Fairness, Accountability, and Transparency (FAccT '21).

10. Grote, T., & Keeling, G. (2022). *On Algorithmic Fairness in Medical Practice*. Cambridge Quarterly of Healthcare Ethics, 31(1), 83-94. 

11.  Margrét Vilborg Bjarnadóttir and David Anderson (2020). *Machine Learning in Healthcare: Fairness, Issues, and Challenges.* Pushing the Boundaries: Frontiers in Impactful OR/OM Research. 64-83.
