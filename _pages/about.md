---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate at the University of Cincinnati in the Smart Manufacturing Lab, College of Engineering and Applied Science, advised by [Dr. Sam Anand](https://ceas.uc.edu/research/centers-labs/center-for-global-design-and-manufacturing.html).

My research focuses on applying computer vision and generative AI models for building Industry 4.0/5.0 solutions. For instance, currently I am developing vision-language models (VLMs) and digital twins (DTs) for motion prediction applications in real-time manufacturing environments. I am also interested in the industrial metaverse, IoT and human-machine interactions.

See my full publications at the [publication page](https://scholar.google.com/citations?user=LZ4UdG8AAAAJ&hl=en&oi=sra). You can see my CV [here](https://sopdeshpande.github.io/files/Resume_Sourabh_Deshpande.pdf). Below is a summary of some of my selected works:

- **Motion-Language Model (MLM) for Real-time Human Motion Prediction, Generation, and Ergonomic Analysis:**
For reducing workplace injuries, we are working on predicting a worker’s trajectory given their prior path and alerting them to avoid any collisions.  To build a model for this task, I have curated an in-house motion-capture data as there are no existing datasets in this space. To construct a training dataset, I developed a GPT-4o-assisted toolbox to generate labels for captured motions. I then fine-tuned an in-domain MLM to do both motion-to-text and text-to-motion generation.  For generating safety alerts, I took real-time 3D human pose estimates of the worker, automatically generated their SMPL-compatible keypoints, and provided them to the fine-tuned MLM that generates the ergonomic feedback in natural language. This project has been [awarded a grant of $1.3M](https://info.bwc.ohio.gov/news-and-events/news/BWC-awards-9.4-million-in-grants-for-workforce-safety-innovation-projects ) by the  Ohio Bureau of Workers’ Compensation and was covered by [Spectrum News](https://spectrumnews1.com/oh/columbus/news/2024/10/23/ohio-worker-safety--artificial-intelligence--ohio-bureau-of-workers-compensation--dr--manish-kumar--dr--sam-anand). 

<video src="https://github.com/user-attachments/assets/ad0fdd64-7516-4cc0-a0bc-268460fceea3" controls="controls" style="max-width: 630px;padding-left: 10em">
</video>

- **Synthetic Image Data Generation for Model Training:**
Due to limited access to the factory, we did not have sufficient images to train the 3D component recognition model, a key model in the motion prediction framework. This model is required for identifying any obstacles present in the worker’s projected path. Therefore, to build a high-quality model in such low-resource settings, I leveraged physics-based rendering methods to automatically generate image segmentation masks and labels for training. This solution was deployed through an augmented reality (AR) application to identify objects in real-time. [ASME, 2024](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A007/1203234)

<img src="/images/Component_Recognition_Summary.png"
     alt="Component Recognition"
     style="max-width: 630px;padding-left: 10em" />

- **Enhancing Digital Twins and IoT with LLM:**
To access and interpret real-time and historical data from both legacy and smart factory machines, I developed a Digital Twin and a multi-agent LLM framework, using Retrieval Augmented Generation (RAG). I deployed this model on mixed reality devices such as AR/VR headsets, which allows users to control the machine in real-time. [SME NAMRC, 2023](https://www.sciencedirect.com/science/article/pii/S2213846323001153), 
[SME NAMRC, 2025 and CAAD Futures, 2025](https://ming3d.com/new/2024/01/24/digital-twin-with-iiot/)

- **Visual Inspections Perfected using AI:**
This collaborative project with Siemens Technology and Boeing involved developing real-time sealant deposition monitoring for automated quality control using computer vision. In this work, I conducted object and shape localization on images captured by a camera mounted on a robotic arm. Further, I also designed a Bayesian network to predict the real-time sealant parameters for space-grade solar panel. Two invention disclosures on object localization approved at UC. [SME NAMRC, 2023](https://www.sciencedirect.com/science/article/pii/S2213846323001761)

- **Industrial IoT for Smart Factory:**
As part of the legacy machine digitazation effort, I leveraged computer vision algorithms to automatically predict product part quality of the injection molding machine. For this, I acquired digitized data (e.g. temperature, pressure) from the machine in real-time, trained a model to predict any volumetric shrinkage and deflection, and visualized it using an augmented reality (AR) app. The framework combines cameras, computing and networking technology to seamlessly integrate machine data through MTConnect®, MQTT, WebSocket with cloud and AR application. [SME NAMRC, 2023](https://www.sciencedirect.com/science/article/pii/S2213846323001153)

<img src="/images/Industrial_IoT_Smart_Factory.png"
     alt="Industrial IoT Smart Factory"
     style="max-width: 630px;padding-left: 10em" />
     
News
======
- **Dec 2024**: Social media coverage of the [Human Digital Twin project](https://www.linkedin.com/posts/manish-kumar-b878143a_as-co-directors-of-the-university-of-cincinnatis-activity-7267390669843759104-s7N4?utm_source=share&utm_medium=member_desktop), successfully accomplished as a part of the UC Industry 4.0/5.0 Consortium Project 2024

- **Nov 2024**: "IIoT-enabled Digital Twin for legacy and smart factory machines with 
LLM integration" paper submitted at SME North American Manufacturing Research Conference (NAMRC), 2025 (*Full length paper under review*)

- **Nov 2024**: Abstract "Enhancing Digital Twins with Internet of Things, Large Language Models: Assessment of DT Development Platforms" accepted for CAAD Futures 2025: Catalytic Interfaces (*Full length paper under review*)

- **Oct 2024**: Press coverage by [Spectrum News](https://spectrumnews1.com/oh/columbus/news/2024/10/23/ohio-worker-safety--artificial-intelligence--ohio-bureau-of-workers-compensation--dr--manish-kumar--dr--sam-anand) on our project on improving worker safety

- **Aug 2024**: [Deep learning-based image segmentation for defect detection in additive manufacturing: an overview](https://link.springer.com/article/10.1007/s00170-024-14191-6) published at the *International Journal of Advanced Manufacturing Technology*, 2024

- **July 2024**: Successfully proposed PhD dissertation titled "Machine Learning and Industrial IoT assisted Computer Vision Frameworks for Smart and Safe Manufacturing"

- **June 2024**: Two conference papers presented at ASME Manufacturing Science and Engineering Conference, 2024 -- [Deep Learning-Based Recognition of Manufacturing Components Using Augmented Reality for Worker Training of Assembly Tasks](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88117/V002T07A007/1203234) and [ImVR: Enabling Immersive Design Exploration and Process Integration for Additive Manufacturing of Complex Organic Geometries](https://asmedigitalcollection.asme.org/MSEC/proceedings/MSEC2024/88100/V001T01A001/1203142)

- **Jan 2024**: Honored to be chosen as one of the top four candidates at [UC Digital Futures](https://ucdigitalfutures.com/) to receive Graduate Research Fellowship

- **June 2023**: [IIoT based framework for data communication and prediction using augmented reality for legacy machine artifacts](https://www.sciencedirect.com/science/article/pii/S2213846323001153) and [Smart monitoring and automated real-time visual inspection of a sealant applications (SMART-VIStA)](https://www.sciencedirect.com/science/article/pii/S2213846323001761). SMART-VIStA project was an [MxD -Department of Army awarded grant](https://www.mxdusa.org/projects/visual-inspections-perfected-using-ai/) and collaboration with Siemens Technology and Boeing. 

- **April 2022**: White paper accepted at Siemens Realize Live, 2022 

- **June 2021**: Recognized by SME and ASME for [co-organizing NAMRC and MSEC](https://issuu.com/sme_us/docs/13320_2021_namri-namrc_awards_brochure_2021-07-07_), 2021

- **June 2021**: Paper presented at SME NAMRC, 2021 [IIoT based Augmented Reality for Factory Data Collection and Visualization](https://www.sciencedirect.com/science/article/pii/S235197892100072X).

- **June 2020**: [Prediction of selective laser melting part quality using hybrid Bayesian network](https://www.sciencedirect.com/science/article/pii/S2214860419307328) published at the *Additive Manufacturing* Journal, 2020
