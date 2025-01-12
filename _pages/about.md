---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate at the University of Cincinnati in the Smart Manufacturing Lab, College of Engineering and Applied Science, advised by [Dr. Sam Anand](https://www.linkedin.com/in/sam-anand-7b917ab3).

My research focuses on applying computer vision and generative AI models for industrial automation. In particular, I am developing vision-language models (VLMs) and human digital twins (HDTs) for motion prediction applications in real-time manufacturing environments. 

See my full publications at the [publication page](https://scholar.google.com/citations?user=LZ4UdG8AAAAJ&hl=en&oi=sra). You can see my CV [here](https://sopdeshpande.github.io/files/Resume_Sourabh_Deshpande.pdf). Below is a summary of some of my selected works:

- **Motion-Language Model (MLM) for Real-time Human Motion Generation and Ergonomic Analysis:**
For reducing workplace injuries, we are working on predicting a worker’s path trajectory given their prior path and alerting them in natural language to avoid any collisions.  To build a model for this task, I first carefully curated in-house motion-capture data parametrized using MoSh++ body solver as there are no existing datasets in this space. Next, to construct a training dataset, I developed a GPT-4o-assisted toolbox that takes the human motion as input and generates a text description analyzing the body ergonomics. Next, I fine-tuned an in-domain MLM on the above data to do both motion-to-text and text-to-motion generation.  In order to use this model for generating safety alerts, we take real-time 3D human pose estimates of the worker, automatically generate their SMPL-compatible keypoints, and provide them to our fine-tuned in-domain MLM that generates the ergonomic feedback in natural language. We have been [awarded a grant of 1.3M$](https://info.bwc.ohio.gov/news-and-events/news/BWC-awards-9.4-million-in-grants-for-workforce-safety-innovation-projects ) by the  Ohio Bureau of Workers’ Compensation (BWC) for this effort. Furthermore, our work was covered by [Spectrum News](https://spectrumnews1.com/oh/columbus/news/2024/10/23/ohio-worker-safety--artificial-intelligence--ohio-bureau-of-workers-compensation--dr--manish-kumar--dr--sam-anand). 

- **Synthetic Image Data Generation for Model Training:**
Due to limited access to the factory, we did not have sufficient images to train the 3D component recognition model, a key model in the above-mentioned motion prediction framework. This model is required for identifying any obstacles present in the worker’s projected path. Therefore, to build a high-quality model in such low-resource settings, I leveraged physics-based rendering methods to automatically generate image segmentation masks and labels for model training. This solution was deployed through an augmented reality (AR) application to identify objects in real-time. [ASME, 2024](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A007/1203234)

![image](/images/Component_Recognition_Summary.png)

- **Enhancing Digital Twins and IoT with LLM:**
To access and interpret real-time and historical data from both legacy and smart factory machines , I developed a Digital Twin and a multi-agent LLM framework,  using Retrieval Augmented Generation (RAG). I deployed this model on mixed reality devices such as AR/VR headsets, which allows users to control the machine in real-time. [SME 2023](https://www.sciencedirect.com/science/article/pii/S2213846323001153), 
[SME NAMRC, 2025 and CAAD Futures, 2025](https://ming3d.com/new/2024/01/24/digital-twin-with-iiot/ )

Along with these projects, I developed predictive models using probabilistic techniques for causal inferences and uncertainty quantification. I also have research interests in the industrial metaverse and lightweight cloud-edge frameworks.

News
======
- Dec 2024: Social media coverage of the [Human Digital Twin](https://www.linkedin.com/posts/manish-kumar-b878143a_as-co-directors-of-the-university-of-cincinnatis-activity-7267390669843759104-s7N4?utm_source=share&utm_medium=member_desktop) project successfully accomplished as a part of the UC Industry 4.0/5.0 Consortium Project 2024
- Nov 2024: Full-length paper "IIoT-enabled Digital Twin for legacy and smart factory machines with 
LLM integration" submitted at SME North American Manufacturing Research Conference 53 (*Full length paper under review*)
- Nov 2024: Abstract "Enhancing Digital Twins with Internet of Things, Large Language Models: Assessment of DT Development Platforms" accepted for CAAD Futures 2025: Catalytic Interfaces, University of Hong Kong. (*Full length paper under review*)
- Oct 2024: Press coverage by [Spectrum News] (https://spectrumnews1.com/oh/columbus/news/2024/10/23/ohio-worker-safety--artificial-intelligence--ohio-bureau-of-workers-compensation--dr--manish-kumar--dr--sam-anand) for our project on improving worker safety
- Aug 2024: Full-length manufscript on [Deep learning-based image segmentation for defect detection in additive manufacturing: an overview](https://link.springer.com/article/10.1007/s00170-024-14191-6) accepted and published at the International Journal of Advanced Manufacturing Technology
- July 2024: Successfully proposed PhD dissertation titled "Machine Learning and Industrial IoT assisted Computer Vision Frameworks for Smart and Safe Manufacturing"
- June 2024: Two conference papers accepted and presented at ASME Manufacturing Science and Engineering Conference. University of Tennessee, Knoxville, TN. The peer reviewed articles are [Deep Learning-Based Recognition of Manufacturing Components Using Augmented Reality for Worker Training of Assembly Tasks](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A007/1203234) and [ImVR: Enabling Immersive Design Exploration and Process Integration for Additive Manufacturing of Complex Organic Geometries](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88100/V001T01A001/1203142)
- Jan 2024: Honored to be chosen as one of the top four candidates at [UC Digital Futures](https://ucdigitalfutures.com/) to receive Graduate Research Fellowship
- June 2023: Two conference papers accepted and presented at SME North American Manufacturing Research Conference, 51. Rutgers University, NJ. The peer reviewed articles are [IIoT based framework for data communication and prediction using augmented reality for legacy machine artifacts](https://www.sciencedirect.com/science/article/pii/S2213846323001153) and [Smart monitoring and automated real-time visual inspection of a sealant applications (SMART-VIStA)]([https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88100/V001T01A001/1203142](https://www.sciencedirect.com/science/article/pii/S2213846323001761)). SMART-VIStA project was an [MxD -Department of Army awarded grant](https://www.mxdusa.org/projects/visual-inspections-perfected-using-ai/) and collaboration with Siemens Technology and Boeing. Two invention disclosures on object localization approved at UC.
- April 2022: Accepted white paper at Siemens Realize live 
- June 2021: Recognition by the SME and ASME for [graduate student lead](https://issuu.com/sme_us/docs/13320_2021_namri-namrc_awards_brochure_2021-07-07_) in organizing NAMRC 49 and MSEC, 2021
- June 2021: Conference paper accepted and presented at SME North American Manufacturing Research Conference, 49. University of Cincinnati, OH. [IIoT based Augmented Reality for Factory Data Collection and Visualization (https://www.sciencedirect.com/science/article/pii/S235197892100072X). The research was conducted at Volvo Trucks facility in Hagerstown, MD.
- June 2020: Full-length manufscript on [Prediction of selective laser melting part quality using hybrid Bayesian network](https://www.sciencedirect.com/science/article/pii/S2214860419307328)) accepted and published at the Additive Manufacturing journal
- August 2018: Accepted for the PhD program at the University of Cincinnati with Graduate Incentive Award
- May 2017: Graduated with Master of Science at Michigan Technological University, Houghton, MI
