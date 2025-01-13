---
title: "Project 2"
collection: projects
type: "Project"
venue: "University 1, Department"
date: 2014-01-01
location: "City, Country"
---


**Motion-Language Model (MLM) for Real-time Human Motion Generation and Ergonomic Analysis:**
For reducing workplace injuries, we are working on predicting a worker’s path trajectory given their prior path and alerting them in natural language to avoid any collisions.  To build a model for this task, I first carefully curated in-house motion-capture data parametrized using MoSh++ body solver as there are no existing datasets in this space. Next, to construct a training dataset, I developed a GPT-4o-assisted toolbox that takes the human motion as input and generates a text description analyzing the body ergonomics. Next, I fine-tuned an in-domain MLM on the above data to do both motion-to-text and text-to-motion generation.  In order to use this model for generating safety alerts, we take real-time 3D human pose estimates of the worker, automatically generate their SMPL-compatible keypoints, and provide them to our fine-tuned in-domain MLM that generates the ergonomic feedback in natural language. We have been [awarded a grant of 1.3M$](https://info.bwc.ohio.gov/news-and-events/news/BWC-awards-9.4-million-in-grants-for-workforce-safety-innovation-projects ) by the  Ohio Bureau of Workers’ Compensation (BWC) for this effort. Furthermore, our work was covered by [Spectrum News](https://spectrumnews1.com/oh/columbus/news/2024/10/23/ohio-worker-safety--artificial-intelligence--ohio-bureau-of-workers-compensation--dr--manish-kumar--dr--sam-anand).

![](/images/Human_Digital_Twin.mp4)
