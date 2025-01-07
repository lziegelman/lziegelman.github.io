---

layout: post
title: "Classification of Neuromechanical Control Strategy in a Wrist Rotation Task"
date: 2024-01-01 12:00:00 -0000
categories: Design Management Signal-Processing ML Statistics

---

#A Test for Main vs _posts

# Project Description

The intent of our action shapes both the signal created by the brain and determines how we move our body. 

This means that we need to find ways to characterize the effects of intentionality, specifically control strategy, so we can produce better models of neural and behavioral signal, which would in turn, allow for creation of better tools for neurorehabilitation tasks or even more accurate neuroprosthetics. 




# Phase 1: Experimental and methodological design

Designed an eight-hour research protocol collecting data for this and other projects resulting in more than 10 peer-reviewed publications and proceedings

Transformed and modernized survey methodology, reducing completion time and minimizing privacy risk

Created methodological standard for cleaning, consolidation, and analysis of data, including the creation of automated scripts for future work in this area for the lab group




# Phase 2: Team training and people management

Created a standard training procedure for research assistants using EEG, EMG, EKG, and accelerometry tools in the lab group including written and video documentation

Held small group and individual evaluations to assess trainee readiness

Lead a team of 4 graduate and over 10 undergraduate research assistants

Recruited 40 participants and maintained a secure patient participation database




# Phase 3: Signal Processing

Data cleaning of motion data in MATLAB

Data cleaning of EEG data in Python (MNE)

Temporal synchronization in Python

Consolidation of data sources in Python

Database creation in Python and R

All statistical analysis were performed using R




# Phase 4: Traditional machine learning analyses

Use of elbow plotting to confirm the number of strategy profiles in motion data

Variance testing to assess presence of confounds

 Cluster analysis to divide all motion data into two classifiers of control strategy




# Phase 5: Traditional statistical analyses

Linear and non-linear regression modeling relating motion parameters to control strategy profiles

Post-hoc tests of mean and variance defining motion parameters

ANOVA models relating EEG alpha and beta power to control strategy

Mean separation tests to test age-related changes

Linear models are run for EEG event-related potentials onto all patient variables

Mean separation tests to test effects of control strategy




# Phase 6: Novel machine learning analyses

Created control random forest model

Created test Neural Ordinary Differential Equation (NODE), a type of deep network model

Both models were created in Python using TensorFlow, PyTorch, TorchDyn, and SciKit

Each model was trained and tested using epoched EEG data

(The NODE was much faster at processing long form EEG data than the random forest)
