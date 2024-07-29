<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Avir-AI/EEG_Applications_Hub">
    <img src="images/logo.png" alt="Logo" width="160" height="160">
  </a>

  <h3 align="center">EEG Applications Hub</h3>

  <p align="center">
    A Comprehensive List of Artificial Intelligence Applications in Electroencephalography
    <br />
    <a href="https://github.com/Avir-AI"><strong>Explore other projects »</strong></a>
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
      </ul>
    </li>
    <li>
      <a href="#introduction-to-the-field">Introduction to the Field</a>
      <ul>
        <li><a href="#what-is-electroencephalographyeeg">What is Electroencephalography(EEG)?</a></li>
        <li><a href="#how-is-ai-applied-to-eeg">How is AI applied to EEG?</a></li>
      </ul>
    </li>
    <li><a href="#list-of-artificial-intelligence-applications-in-electroencephalography">List of Artificial Intelligence Applications in Electroencephalography</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This meticulously curated list aims to showcase the latest breakthroughs in the fusion of Electroencephalography (EEG) and Artificial Intelligence (AI). By consolidating related fields and subfields, we've created a user-friendly framework that allows you to quickly explore them.

Whether you're a researcher, student, or hobbyist, this guide is designed to serve as a valuable resource for your endeavors. We hope you find it informative, inspiring, and useful in exploring the vast potential of EEG-AI applications.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Introduction to the Field
This part serves as a comprehensive introduction to the interdiciplinary field of EEG-AI, where the boundaries of neuroscience, computer science, and machine learning converge.

### What is Electroencephalography(EEG)?

Electroencephalography (EEG) is a non-invasive technique used to measure electrical activity in the brain. This method involves placing electrodes on the scalp, which detect tiny electrical signals produced by neurons firing in the brain. These signals are recorded as waveforms, which can be analyzed to understand brain function.
Neurons communicate through electrical impulses, and the collective activity of neurons generates electric fields that can be detected on the scalp.
EEG measures these electric fields, typically in the range of microvolts (µV).
The recorded signals are displayed as a series of waveforms, representing different frequencies and amplitudes of brain activity.
<img src="images/EEG.jpg" width="500" height="500">
Image by DC Studio on Freepik
### Why is EEG Data so Compelling?
1. EEG captures cognitive dynamics in the time frame in which cognition occurs.
    1. Cognitive, perceptual, linguistic, emotional, and motor processes are fast and most of them occur within tens to hundreds of milliseconds. 
    2. Furthermore, cognitive events occur in a temporal sequence that may span hundreds of milliseconds to a few seconds. This means EEG which is a high temporal-resolution technique is well suited to capture these fast, dynamic, and temporally sequenced cognitive events.
    3. As an example the temporal precision of the hemodynamic response which is captured by fMRI  is 2 – 3 orders of magnitude slower than that of the electrophysiological response.
2. Neural Data is valuable and contains a wealth of information within.
   1. Neural oscillations offer a window into the intricate workings of the human brain, providing valuable insights into cognition, behavior, and neural function.
   2. Oscillations that can be observed in the EEG signal are direct reflections of neural oscillations in the cortex. 
   3. The neurophysiological mechanisms that give rise to population-level oscillations are well understood and can be modeled fairly accurately.
4. EEG signal is multidimensional. 
    1. The multidimensionality of EEG data allows for analyses that are inspired by known physiological mechanisms. This offers the opportunity to link findings obtained through noninvasive recordings in humans to invasive recordings in nonhuman animals as well as to biophysical models of neural ensemble activity.
    2. EEG data comprise at least four dimensions: time, space, frequency, and power and phase.
        - Time series: The EEG signal is recorded over a period of time (usually several seconds or minutes), resulting in a time series of voltage values.
        - Frequency bands: EEG signals can be divided into different frequency bands, such as:
            - Delta (0.5-4 Hz): associated with sleep, relaxation, and unconsciousness
            - Theta (4-8 Hz): associated with drowsiness, meditation, and unconsciousness
            - Alpha (8-12 Hz): associated with relaxation, closed eyes, and decreased cortical activity
            - Beta (13-30 Hz): associated with attention, cognitive processing, and motor activity
            - Gamma (30-100 Hz): associated with higher-level cognitive processing, attention, and working memory
        - Electrode locations: EEG signals are recorded from multiple electrodes placed on the scalp or brain surface. spacial locations
        - Power and Phase: Power is the strength of frequency-band-specific activity and phase id the timing of it.
          - They are discrete elements of a dimension because they provide largely independent information.
          - For example, two brain regions might show similar power in the theta band but have different phases. This could indicate that they are involved in different cognitive processes, even though they are both active in the same frequency range.

### What Are the Applications of EEG-AI in Various Fields?   
Signal processing and machine learning techniques are crucial for accurately interpreting EEG data, which is challenging due to its non-stationary nature, inter-subject variability, and low signal-to-noise ratio (SNR). In recent years, deep neural networks have been increasingly employed to address these challenges, often outperforming traditional EEG analysis methods. Here are some of the broad fields where EEG-AI is utilized:
1. **Neurological Disorder Diagnosis and Monitoring:** Using EEG data to detect and monitor conditions like epilepsy, Alzheimer's, and other neurological disorders.
2. **Medical Procedures and Interventions:** Assisting in procedures such as brain surgery and neurofeedback therapy by providing real-time brain activity monitoring.
3. **Cognitive and Performance Assessment:** Evaluating cognitive functions and mental workload in educational, professional, and clinical settings.
4. **Assistive Technologies and Rehabilitation:** Developing devices and therapies for individuals with disabilities, including communication aids and mobility support.
5. **Neuroscientific Research:** Studying brain function and neural mechanisms underlying various behaviors and cognitive processes.
6. **Education and Sports:** Enhancing learning experiences and athletic performance through brain-computer interfaces and neurofeedback.
7. **Consumer Applications:** Creating products like neurofeedback games, meditation aids, and devices for mental wellness and stress management.
8. **Marketing and Consumer Behavior:** Analyzing consumer responses and decision-making processes to optimize advertising and product design.
9. **Military and Security:** Applications in monitoring alertness, cognitive load, and stress in high-risk situations, and enhancing training and performance.

### What Are the Common Preprocessing Methods?
- Filtering (FIR & IIR): Fundamental for removing noise and isolating frequency bands.
- Feature Extraction: Central to converting raw EEG data into meaningful features for classification.
- Independent Component Analysis (ICA): Widely used for artifact removal and source separation.
- Wavelet Transformation: Frequently used for time-frequency analysis of EEG signals.
- Spectral Power: Commonly used to analyze the power distribution across frequency bands.
- Spatial Filtering: Important for enhancing signal quality by focusing on relevant spatial components.
- Entropy Methods: Increasingly popular for assessing complexity and variability in EEG signals.
- Functional Connectivity: Gaining importance for studying interactions between different brain regions.
- Topological Network Analysis: Used for understanding brain network properties, but less common.
- Average Filtering: Basic noise reduction technique, but less sophisticated than others.
- Synchronization Likelihood Features: Specialized for connectivity analysis, but not as commonly used.
- Biomarkers Based Features: Emerging field focusing on disease-specific features, gaining traction.
- RVMD (Robust Variational Mode Decomposition): Advanced signal decomposition technique, less widespread.
- Network Based Fuzzy Learning: Specialized method, not widely adopted.
- SLBP (Symmetrically Weighted Local Binary Patterns): Niche method for texture-like feature extraction, less common.

### What Are the Common Cross Validation Methods?
- 5-fold Cross Validation
- 10-fold Cross Validation
- LOSO: Leave One Subject Out
- LOTO: Leave One Trial Out

### What Are the Common Classifiers?
**Machine Learning**
- SVM - Support Vector Machine
- KNN - K-Nearest Neighbors
- DT - Decision Tree
- RF - Random Forest
- Logit Boost - LogitBoost (a boosting algorithm for binary classification)
- ELM - Extreme Learning Machine
- LDA - Linear Discriminant Analysis
- N-TSK - Neuro-Fuzzy Takagi-Sugeno-Kang

**Deep Learning:**
- CNN - Convolutional Neural Network
- Deep ConvNet - Deep Convolutional Network
- DP CNN - DeepPyramid Convolutional Neural Network 
- LSTM RNN - Long Short-Term Memory Recurrent Neural Network
- SNN - Spiking Neural Network / Siamese Neural Network
- MLP - Multilayer Perceptron
- GRU - Gated Recurrent Unit
- Conv-AE - Convolutional Autoencoder
- EEGNet - A specific Convolutional Neural Network architecture designed for EEG signal classification
- AlexNet - A deep Convolutional Neural Network architecture named after Alex Krizhevsky
- ViT - Vision Transformer
- ResNet18 - A version of the Residual Network (ResNet) architecture with 18 layers


## List of Artificial Intelligence Applications in Electroencephalography

### Neurological Disorder Diagnosis and Monitoring

<details>
  <summary>Alzheimer’s</summary>
  Alzheimer's disease (AD) is a progressive neurodegenerative disorder characterized by cognitive decline, memory impairments, and behavioral changes. The presence of abnormal beta-amyloid plaques and tau protein tangles in the brain is known to be associated with AD. However, current limitations of imaging technology hinder the direct detection of these substances. Consequently, researchers are exploring alternative approaches, such as indirect assessments involving monitoring brain signals, cognitive decline levels, and blood biomarkers.
  
  **Useful Resources:**
  <li><a href="https://journals.uob.edu.bh/handle/123456789/5648">Intelligent Approaches for Alzheimer's Disease Diagnosis from EEG Signals: Systematic Review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0010482524007066">Comparative analysis of machine learning algorithms for Alzheimer's disease classification using EEG signals and genetic information
</a></li>
  <li><a href="https://content.iospress.com/articles/journal-of-alzheimers-disease/jad180300">EEG Theta Power Is an Early Marker of Cognitive Decline in Dementia due to Alzheimer’s Disease</a></li>
  <li><a href="https://www.nature.com/articles/s41598-023-32664-8">Computational methods of EEG signals analysis for Alzheimer’s disease classification</a></li>
  <li><a href="https://journals.sagepub.com/doi/10.1177/15500594221125033?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed">What a Single Electroencephalographic (EEG) Channel Can Tell us About Alzheimer's Disease Patients With Mild Cognitive Impairment</a></li>
  <li><a href="https://www.researchgate.net/publication/376820004_Identification_of_new_electrophysiological_biomarkers_of_Alzheimer's_disease_with_fast_periodic_visual_stimulation_and_electroencephalography">Identification of new electrophysiological biomarkers of Alzheimer’s disease with fast periodic visual stimulation and electroencephalography
</a></li>
  <li><a href="https://www.worldscientific.com/doi/abs/10.1142/S0129065721300023">Machine Learning Algorithms and Statistical Approaches for Alzheimer's Disease Analysis Based on Resting-State EEG Recordings: A Systematic Review.</a></li>

  </details>

<details>
  <summary>Parkinson's</summary>
  
  Parkinson’s disease (PD) is a prevalent neurodegenerative disorder affecting millions globally. It encompasses both motor and non-motor symptoms, with a notable impact on patients’ quality of life. Electroencephalogram (EEG) is a non-invasive tool that is increasingly utilized to investigate neural mechanisms in PD, identify early diagnostic markers, and assess therapeutic responses.
  
  **Useful Resources:**
  <li><a href="Feature Extraction from EEG signals for detection of Parkinsons Disease">Detection of Parkinson’s disease from EEG signals using discrete wavelet transform, different entropy measures, and machine learning techniques</a></li>
  <li><a href="https://ieeexplore.ieee.org/document/10173532">EEG-Based Parkinson's Disease Recognition Via Attention-based Sparse Graph Convolutional Neural Network
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S156816372400103X">Parkinson’s disease diagnosis using deep learning: A bibliometric analysis and literature review
</a></li>
  <li><a href="https://www.nature.com/articles/s41531-023-00602-0">Resting-state EEG measures cognitive impairment in Parkinson’s disease</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1433583/full">Bibliometric analysis of electroencephalogram research in Parkinson’s disease from 2004 to 2023</a></li>
</details>

<details>
  <summary>Schizophrenia</summary>
  Schizophrenia (ScZ) is a chronic neuropsychiatric disorder characterized by disruptions in cognitive, perceptual, social, emotional, and behavioral functions. In the traditional approach, the diagnosis of ScZ primarily relies on the subject’s response and the psychiatrist’s experience, making it highly subjective, prejudiced, and time-consuming. In recent medical research, incorporating deep learning (DL) into the diagnostic process improves performance by reducing inter-observer variation and providing qualitative and quantitative support for clinical decisions.
  
  **Useful Resources:**
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2024.1347082/full">A systematic review of EEG based automated schizophrenia classification through machine learning and deep learning</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423034395">A novel approach to schizophrenia Detection: Optimized preprocessing and deep learning analysis of multichannel EEG data</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0920996424003220">Identification and diagnosis of schizophrenia based on multichannel EEG and CNN deep learning model</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10581211">Schizophrenia Detection using Electroencephalography Signals Using Deep Learning</a></li>
  <li><a href="https://www.mdpi.com/2227-7390/12/13/1989">CALSczNet: Convolution Neural Network with Attention and LSTM for the Detection of Schizophrenia Using EEG Signals
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0165032723013770">Diagnostic deep learning algorithms that use resting EEG to distinguish major depressive disorder, bipolar disorder, and schizophrenia from each other and from healthy volunteers
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1746809422006875">Schizophrenia classification using machine learning on resting state EEG signal</a></li>


</details>

<details>
  <summary>ADHD</summary>
 Attention-Deficit Hyperactivity Disorder (ADHD) is one of the most widespread neurodevelopmental disorders diagnosed in childhood. ADHD is diagnosed by following the guidelines of Diagnostic and Statistical Manual of Mental Disorders, Fifth Edition (DSM-5). According to DSM-5, ADHD has not yet identified a specific cause, and thus researchers continue to investigate this field.
  
  **Useful Resources:**
  <li><a href="https://www.cell.com/heliyon/fulltext/S2405-8440(24)02059-0#:~:text=Results%20and%20conclusions,0.8067%20f1%2Dscore).">A novel approach to identify the brain regions that best classify ADHD by means of EEG and deep learning</a></li>
  <li><a href="https://figshare.utas.edu.au/articles/thesis/The_classification_of_ADHD_using_machine_learning_and_EEG_data_a_systematic_review/25711794">The classification of ADHD using machine learning and EEG data : a systematic review</a></li>
  <li><a href="https://drpress.org/ojs/index.php/HSET/article/view/20004">Detection and Classification of ADHD Using Deep Learning Based on EEG Signals</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10165395">Comparative Study of Detection of ADHD using EEG Signals</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-40688-1_8">Machine and Deep Learning Algorithms for ADHD Detection: A Review</a></li>

</details>


<details>
  <summary>Bipolar and Borderline personality disorder</summary>
  Bipolar disorder (BD) is a mental disorder characterized by depressive and manic or hypomanic episodes. The complexity in the diagnosis of Bipolar disorder (BD) due to its overlapping symptoms with other mood disorders prompted researchers and clinicians to seek new and advanced techniques for the precise detection of Bipolar disorder (BD). One of these methods is the use of advanced machine learning algorithms such as deep learning (DL).
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0165032723013770">Diagnostic deep learning algorithms that use resting EEG to distinguish major depressive disorder, bipolar disorder, and schizophrenia from each other and from healthy volunteers</a></li>
  <li><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0303699">A machine learning approach for differentiating bipolar disorder type II and borderline personality disorder using electroencephalography and cognitive abnormalities
</a></li>

  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1388245722009518">Discriminating between bipolar and major depressive disorder using a machine learning approach and resting-state EEG data
</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/15500594221137234">The Deep Learning Method Differentiates Patients with Bipolar Disorder from Controls with High Accuracy Using EEG Data
</a></li>


</details>

<details>
  <summary>Depression</summary>
  Mental Status Assessment (MSA) holds significant importance in psychiatry. In recent years, several studies have leveraged Electroencephalogram (EEG) technology to gauge an individual's mental state or level of depression.
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2001037024000758#tbl0020">Depression assessment using integrated multi-featured EEG bands deep neural network models: Leveraging ensemble learning techniques</a></li>
  <li><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0299127">A machine learning based depression screening framework using temporal domain features of the electroencephalography signals</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S000632232301569X">Evaluating Robustness of Brain Stimulation Biomarkers for Depression: A Systematic Review of Magnetic Resonance Imaging and Electroencephalography Studies</a></li>
  <li><a href="https://www.mdpi.com/2075-4418/13/10/1779">Electroencephalography-Based Depression Detection Using Multiple Machine Learning Techniques</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1219133/full">Generation of synthetic EEG data for training algorithms supporting the diagnosis of major depressive disorder</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/20/8639">Depressive Disorder Recognition Based on Frontal EEG Signals and Deep Learning</a></li>

</details>


<details>
  <summary>Anxiety</summary>
  Anxiety is a psycho-physiological phenomenon related to the mental health of a person. Persistence of anxiety for an extended period of time can manifest into anxiety disorder, which is a root cause of multiple mental health issues. 
  
  **Useful Resources:**
  <li><a href="https://peerj.com/articles/cs-1829/">A comprehensive exploration of machine learning techniques for EEG-based anxiety detection</a></li>
  <li><a href="https://iopscience.iop.org/book/edit/978-0-7503-5182-9/chapter/bk978-0-7503-5182-9ch1">Anxiety recognition using a new EEG signal analysis approach based on sample density in a Chebyshev chaotic</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-15-5232-8_17">Electroencephalography Based Machine Learning Framework for Anxiety Classification</a></li>

</details>

<details>
  <summary>Autism Spectrum Disorder(No Reliable Method)</summary>
  
  Autism Spectrum Disorder (ASD) is a neurodevelopmental disorder characterized by difficulties in social communication and repetitive and stereotyped behaviors. According to the World Health Organization, about 1 in 100 children worldwide has autism. With the global prevalence of ASD, timely and accurate diagnosis has been essential in enhancing the intervention effectiveness for ASD children. Traditional ASD diagnostic methods rely on clinical observations and behavioral assessment, with the disadvantages of time-consuming and lack of objective biological indicators. Therefore, automated diagnostic methods based on machine learning and deep learning technologies have emerged and become significant since they can achieve more objective, efficient, and accurate ASD diagnosis. 

  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0010482524001598">Identification of autism spectrum disorder based on electroencephalography: A systematic review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S027858462200197X">Machine learning approaches for electroencephalography and magnetoencephalography analyses in autism spectrum disorder: A systematic review</a></li>
  <li><a href="https://www.tandfonline.com/doi/full/10.2147/NDT.S394363#abstract">Systematic Review on EEG Analysis to Diagnose and Treat Autism by Evaluating Functional Connectivity and Spectral Power
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809423005074">Classification of low-functioning and high-functioning autism using task-based EEG signals
</a></li>
  <li><a href="https://www.bio-conferences.org/articles/bioconf/abs/2024/30/bioconf_icbb2024_03010/bioconf_icbb2024_03010.html">The Role of Electroencephalography (EEG) in the Diagnosis and Subtyping of Autism Spectrum Disorder: A Review
</a></li>

</details>


<details>
  <summary>Dementia</summary>
  Dementia has been defined as a deterioration in cognitive capacities which impairs an individual’s capacity to carry out tasks independently daily. It is critical to recognize that dementia is more accurately defined as a syndrome than as a single disease. Electroencephalogram (EEG) is a nonintrusive neural imaging approach, which tracks the brain’s electrical activities. EEG signals have shown notable alterations in dementia patients, making EEG a helpful tool for early-stage dementia recognition and diagnosis. Machine learning algorithms have shown potential in detecting patterns in EEG data that correspond to different stages of dementia. This allows the creation of a unique dementia diagnostic tool that outperforms existing approaches in terms of accuracy and cost-effectiveness. However, further research is needed to evaluate these algorithms in clinical settings. The research dives into the implementation of multiple machine-learning methods, the extraction of attributes from EEG data, and the evaluation of these algorithms’ performance.

  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1053811923002008">Deep learning-based EEG analysis to classify normal, mild cognitive impairment, and dementia: Algorithms and dataset
</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10544436">Review on EEG-based Dementia Staging using Machine Learning
</a></li>
  <li><a href="https://alz-journals.onlinelibrary.wiley.com/doi/full/10.1002/alz.12948">Interpretable machine learning for dementia: A systematic review</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10916-023-01906-7">Machine Learning for Dementia Prediction: A Systematic Review and Future Research Directions
</a></li>
  <li><a href="https://www.nature.com/articles/s43856-024-00437-7#:~:text=Parsimonious%20machine%2Dlearning%20models%20can,to%20heterogeneous%20dementia%20patient%20populations.">Machine learning models identify predictive features of patient mortality across dementia types</a></li>

</details>


<details>
  <summary>Learning Disabilities</summary>
  Developmental Dyslexia (DD) is a neurobiological condition affecting the ability to read fluently and/or accurately. Analyzing resting-state electroencephalographic (EEG) activity in DD may provide a deeper characterization of the underlying pathophysiology and possible biomarkers.
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809422010072">EEG based classification of children with learning disabilities using shallow and deep neural network</a></li>
  <li><a href="https://www.mdpi.com/2227-9059/11/6/1607">Periodic and Aperiodic EEG Features as Potential Markers of Developmental Dyslexia</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11042-022-13939-0">A comprehensive review of machine learning approaches for dyslexia diagnosis</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11881-022-00273-1">EEG correlates of developmental dyslexia: a systematic review</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s12539-024-00634-x">Unraveling Brain Synchronisation Dynamics by Explainable Neural Networks using EEG Signals: Application to Dyslexia Diagnosis
</a></li>

</details>


<details>
  <summary>Epilepsy and Seizure</summary>
  Epilepsy is a central nervous system disorder. In epilepsy brain activity becomes abnormal, leading to times of abnormal behavior or seizures, and at times loss of awareness. Consequently, epilepsy patients face problems in daily life due to precautions they must take to adapt to this condition, particularly when they use heavy equipment, e.g., vehicle derivation. Epilepsy studies rely primarily on electroencephalography (EEG) signals to evaluate brain activity during seizures. It is troublesome and time-consuming to manually decide the location of seizures in EEG signals.
  

  **Useful Resources:**
  <li><a href="https://link.springer.com/article/10.1007/s11042-023-15052-2">EEG seizure detection: concepts, techniques, challenges, and future trends</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.13374">A review on software and hardware developments in automatic epilepsy diagnosis using EEG datasets</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2001037023004804">Computer-assisted analysis of routine EEG to identify hidden biomarkers of epilepsy: A systematic review</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s42979-023-01958-z">EEG datasets for seizure detection and prediction— A review
</a></li>
  <li><a href="https://www.mdpi.com/2075-4418/13/6/1058">Epileptic Seizure Detection Using Machine Learning: Taxonomy, Opportunities, and Challenges</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10442940">A Machine Learning Framework for Robust Epileptic Seizure Detection from EEG Sign</a></li>
  <li><a href="https://www.degruyter.com/document/doi/10.1515/bmt-2023-0332/html">Epileptic EEG patterns recognition through machine learning techniques and relevant time–frequency features</a></li>

</details>


<details>
  <summary>Brain Tumor</summary>
  
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>
</details>


<details>
  <summary>Traumatic Brain Injury</summary>
  
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

</details>

<details>
  <summary>Coma</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Stroke</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

<details>
  <summary>Brain Age Prediction</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Brain Health assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Stress assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Sleep disorders</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Suicidal Ideation</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>
</details>


<details>
  <summary>Addiction</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

### Medical procedures or interventions

</details>

<details>
  <summary>Anesthesia</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Drug development and Pharmacology</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>
</details>

<details>
  <summary>Neurostimulation</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Pain assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Communication for locked-in patients</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Amblyopia</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

### Cognitive and Performance Assessment

<details>
  <summary>Cognitive Load</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Working Memory</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


</details>

<details>
  <summary>Memory function</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Attention and Vigilance</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

<details>
  <summary>Lie Detection</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Fatigue</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Objective Performance Evaluation </summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Senses</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Neuroergonomics</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

### Assistive Technologies and Rehabilitation

<details>
  <summary>Brain-Computer Interfaces (BCIs)</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


</details>

<details>
  <summary>Neurorehabilitation</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

<details>
  <summary>Neurolinguistics</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

### Neuroscientific Research

<details>
  <summary>Functional Connectivity</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

<details>
  <summary>Developmental Neuroscience</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>

### Education and Sports


<details>
  <summary>Personalized Learning</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Skill Acquisition and Training</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


<details>
  <summary>Neurofeedback Training</summary>

  
  **Useful Resources:**
  <li><a href="https://www.frontiersin.org/journals/aging-neuroscience/articles/10.3389/fnagi.2022.780817/full
">Sharpening Working Memory With Real-Time Electrophysiological Brain Signals: Which Neurofeedback Paradigms Work?
</a></li>
  <li><a href="https://www.mdpi.com/2075-4426/14/7/763">A Systematic Review of the Effects of EEG Neurofeedback on Patients with Schizophrenia
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10484-022-09562-2">Evaluation of Neurofeedback Learning in Patients with ADHD: A Systematic Review
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S092549272300001X
">Review of EEG-based neurofeedback as a therapeutic intervention to treat depression
</a></li>

</details>

### Consumer Applications

<details>
  <summary>Emotional State Analysis</summary>
  
  
  **Useful Resources:**
  <li><a href="https">techniques</a></li>
  <li><a href="https">signals</a></li>
  <li><a href="https">Studies</a></li>
  <li><a href="https">Techniques</a></li>
  <li><a href="https">disorder</a></li>
  <li><a href="https">Learning</a></li>

</details>


</details>

<details>
  <summary>Immersive Gaming and Entertainment</summary>
  
  ```
  To be Filled
  ```

</details>


<details>
  <summary>Meditation and Mindfulness</summary>
  
  ```
  To be Filled
  ```

</details>

<details>
  <summary>Smart Home Systems</summary>
  
  ```
  To be Filled
  ```

</details>


<details>
  <summary>Wearable Technology</summary>
  
  ```
  To be Filled
  ```

</details>

### Marketing and Consumer Behavior

<details>
  <summary>Human-Computer Interaction (HCI)</summary>
  
  ```
  To be Filled
  ```

</details>


<details>
  <summary>Neuromarketing and Advertisement</summary>
  
  ```
  To be Filled
  ```

</details>


<details>
  <summary>Neuroaesthetics</summary>
  
  ```
  To be Filled
  ```

</details>


<details>
  <summary>User Experience</summary>
  
  ```
  To be Filled
  ```

</details>


</details>

<details>
  <summary>Workforce Monitoring</summary>
  
  ```
  To be Filled
  ```

</details>

### Military and Security

<details>
  <summary>Biometric Authentication</summary>
  
  ```
  To be Filled
  ```

</details>






<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
