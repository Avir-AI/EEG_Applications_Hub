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
        <li><a href="#why-is-eeg-data-so-compelling">Why is EEG Data so Compelling?</a></li>
        <li><a href="#what-are-the-applications-of-eeg-ai-in-various-fields">What Are the Applications of EEG-AI in Various Fields?</a></li>
        <li><a href="#what-are-the-common-preprocessing-methods">What Are the Common Preprocessing Methods?</a></li>
        <li><a href="#what-are-the-common-cross-validation-methods">What Are the Common Cross Validation Methods?</a></li>
        <li><a href="#what-are-the-common-classifiers">What Are the Common Classifiers?</a></li>
      </ul>
    </li>
    <li><a href="#list-of-artificial-intelligence-applications-in-electroencephalography">🔶List of Artificial Intelligence Applications in Electroencephalography🔶</a></li>
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

### 🔶 Neurological and Mental Health Disorders

<details>
  <summary>Alzheimer’s Disease</summary>
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
  <summary>Parkinson's Disease</summary>
  
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
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9693921">Exploration of EEG-Based Depression Biomarkers Identification Techniques and Their Applications: A Systematic Review</a></li>

</details>


<details>
  <summary>Anxiety Disorders</summary>
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
  <summary>Brain Tumors</summary>
  According to the International Agency for Research on Cancer (IARC), the mortality rate due to brain tumors is 76%. It is required to detect the brain tumors as early as possible and to provide the patient with the required treatment to avoid any fatal situation. Scalp EEG can be used to diagnose brain diseases mainly because the electrical activity of the cerebral cortex has a great influence on EEG. The abnormality of EEG can be understood as the abnormality of brain activity.
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10193098">Brain Tumor Prediction from EEG Signal using Machine Learning Algorithm</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9385291">Evaluation and Diagnosis of Brain Diseases based on Non-invasive BCI</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9972643">Brain Tumor Detection using Machine Learning Techniques with Internet of Things</a></li>
  <li><a href="https://www.ingentaconnect.com/content/ben/cmir/2019/00000015/00000006/art00010">
Detecting Brain Tumor using Machines Learning Techniques Based on Different Features Extracting Strategies
</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1742-6596/2115/1/012039/meta">Evolution in diagnosis and detection of brain tumor – review</a></li>
</details>


<details>
  <summary>Traumatic Brain Injury</summary>
  
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9364756">Evaluating Performance of EEG Data-Driven Machine Learning for Traumatic Brain Injury Classification</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/15500594231202265">Quantitative Electroencephalography Objectivity and Reliability in the Diagnosis and Management of Traumatic Brain Injury: A Systematic Review</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/ac1982/meta">Review of wearable technologies and machine learning methodologies for systematic detection of mild traumatic brain injuries</a></li>
  <li><a href="https://www.mdpi.com/2227-9059/10/10/2472"> Traumatic Brain Injury (TBI) Detection: Past, Present, and Future </a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9630242">Automatic Detection of EEG Epileptiform Abnormalities in Traumatic Brain Injury using Deep Learning</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2213158223000396">Early EEG monitoring predicts clinical outcome in patients with moderate to severe traumatic brain injury</a></li>
</details>


<details>
  <summary>Coma</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.mdpi.com/2075-4418/13/8/1383"> Quantitative Electroencephalography Analysis for Improved Assessment of Consciousness Levels in Deep Coma Patients Using a Proposed Stimulus Stage </a></li>
  <li><a href="https://www.mdpi.com/2076-3425/11/6/697"> Narrative Review: Quantitative EEG in Disorders of Consciousness </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S138824572200904X">EEG-based methods for recovery prognosis of patients with disorders of consciousness: A systematic review</a></li>
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2022.1040816/full?trk=public_post_comment-text">EEG-based Brain-Computer Interfaces for people with Disorders of Consciousness: Features and applications. A systematic review
</a></li>

</details>


<details>
  <summary>Stroke</summary>
  
  
  **Useful Resources:**
  <li><a href="https://link.springer.com/article/10.1186/s12873-022-00585-w">Surface electroencephalography (EEG) during the acute phase of stroke to assist with diagnosis and prediction of prognosis: a scoping review</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9145945">Encoding Rich Frequencies for Classification of Stroke Patients EEG Signals</a></li>
  <li><a href="https://www.proquest.com/openview/5d08fb73ccb0f77d18a5d815c9a5ca25/1?pq-origsite=gscholar&cbl=2045096">A Comprehensive Method for Identification of Stroke using Deep Learning</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/21/13/4269"> Deep Learning-Based Stroke Disease Prediction System Using Real-Time Bio Signals </a></li>

</details>


<details>
  <summary>Suicidal Ideation</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0747563221004180">Machine learning for suicidal ideation identification: A systematic literature review</a></li>
  <li><a href="https://www.nature.com/articles/s44277-024-00012-x">Neural activity during inhibitory control predicts suicidal ideation with machine learning</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0278584624000332">Differentiation between suicide attempt and suicidal ideation in patients with major depressive disorder using cortical functional network</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11571-022-09904-0">Artificial intelligence assisted tools for the detection of anxiety and depression leading to suicidal ideation in adolescents: a review</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/1550059421991685">Differences of EEG Frequency and Spatial Parameters in Depressive Female Adolescents With Suicidal Attempts and Non-suicidal Self-injuries</a></li>
  
</details>


<details>
  <summary>Addiction</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2022.995534/full">A scoping review of electroencephalographic (EEG) markers for tracking neurophysiological changes and predicting outcomes in substance use disorder treatment
</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/15500594221076347">Resting-state EEG, Substance use and Abstinence After Chronic use: A Systematic Review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0010482520303024">Profiling of pornography addiction among children using EEG signals: A systematic literature review☆</a></li>
  <li><a href="https://avesis.bozok.edu.tr/yayin/d6a6f040-517e-4b5a-a32f-010171bc5089/eeg-based-cigarette-addiction-detection-with-deep-learning"> EEG Based Cigarette Addiction Detection with Deep Learning </a></li>
  <li><a href="http://www.prof-buettner.de/downloads/gross2020a.pdf">A Novel Machine Learning Approach for High-Performance Diagnosis of Premature Internet Addiction Using the Unfolded EEG Spectra</a></li>
  <li><a href="https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2020.00676/full">Neuropsychophysiological Measures of Alcohol Dependence: Can We Use EEG in the Clinical Assessment?
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10899-024-10332-4">Problematic Gaming and Gambling: A Systematic Review of Task-Specific EEG Protocols</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0022395624004059">Multimodal Analysis of Cortical Activation in Young Male Adults with Internet Gaming Disorder: A Resting State EEG-fNIRS Study</a></li>


</details>

### 🔶 Medical Procedures and Treatments


<details>
  <summary>Anesthesia</summary>
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9385837">A Combinatorial Deep Learning Structure for Precise Depth of Anesthesia Estimation From EEG Signals</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10877-023-01088-0">Artificial intelligence and its clinical application in Anesthesiology: a systematic review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0933365724001118">Harnessing machine learning for EEG signal analysis: Innovations in depth of anaesthesia assessment</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2095809921005269">Progress of Brain Network Studies on Anesthesia and Consciousness: Framework and Clinical Applications</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9755157">Inference of Brain States Under Anesthesia With Meta Learning Based Deep Learning Models</a></li>
  <li><a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0246165">Machine learning of EEG spectra classifies unconsciousness during GABAergic anesthesia</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9360837">An EEG-Based Hypnotic State Monitor for Patients During General Anesthesia</a></li>
  

</details>


<details>
  <summary>Drug development and Pharmacology</summary>
  The analysis of electroencephalogram (EEG) signals has become a pivotal tool in drug development and pharmacology, providing valuable insights into neural responses and cognitive effects induced by pharmacological interventions. This method has significantly contributed to the understanding of drug mechanisms and their impact on the brain. As the field advances, numerous drugs are being developed to address various neurological and psychiatric conditions, and research papers focusing on these diseases are readily available for further exploration based on specific areas of interest.

<details>
  <summary>Neurostimulation</summary>
  Electroencephalogram (EEG) signal analysis, empowered by machine learning (ML) and deep learning (DL) techniques, has shown transformative potential in the optimization of neurostimulation therapies. 
  
  **Useful Resources:**
  <li><a href="https://www.nature.com/articles/s41746-023-00779-x">Landscape and future directions of machine learning applications in closed-loop brain stimulation</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9540268">Closed-Loop Neural Prostheses With On-Chip Intelligence: A Review and a Low-Latency Machine Learning Model for Brain State Detection</a></li>
  <li><a href="https://www.mdpi.com/2227-9059/10/11/2677"> Responsive Neurostimulation for Seizure Control: Current Status and Future Directions </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0014488622000188">Machine learning based brain signal decoding for intelligent adaptive deep brain stimulation</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1388245721000602">Machine learning for automated EEG-based biomarkers of cognitive impairment during Deep Brain Stimulation screening in patients with Parkinson’s Disease</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s00415-023-11873-1">Machine learning for adaptive deep brain stimulation in Parkinson’s disease: closing the loop</a></li>

</details>


<details>
  <summary>Pain assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1526590021003151">Systematic Review of the Effectiveness of Machine Learning Algorithms for Classifying Pain Intensity, Phenotype or Treatment Outcomes Using Electroencephalogram Data</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1186418/full">In search of a composite biomarker for chronic pain by way of EEG and machine learning: where do we currently stand?
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/B9780128186626000194">EEG biomarkers of pain and applications of machine learning</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1053811922004700">Resting-state electroencephalography (EEG) biomarkers of chronic neuropathic pain. A systematic review</a></li>
  <li><a href="https://journals.lww.com/pain/fulltext/2023/06000/resting_state_electroencephalography_and.3.aspx">Resting-state electroencephalography and magnetoencephalography as biomarkers of chronic pain: a systematic review</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/09544119221122012">Role of Artificial Intelligence and Machine Learning in the prediction of the pain: A scoping systematic review</a></li>

</details>

### 🔶 Diagnostic and Monitoring Technologies


<details>
  <summary>Brain Age Prediction</summary>
  
  
  **Useful Resources:**
  <li><a href="https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00210/122334"> Brain age revisited: Investigating the state vs. trait hypotheses of EEG-derived brain-age dynamics with deep learning </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S105381192200636X?ref=cra_js_challenge&fr=RR-1">A reusable benchmark of brain-age prediction from M/EEG resting-state signals</a></li>
  <li><a href="https://www.mdpi.com/2306-5354/11/5/418"> Age-Related Characteristics of Resting-State Electroencephalographic Signals and the Corresponding Analytic Approaches: A Review </a></li>
  <li><a href="https://www.cell.com/patterns/fulltext/S2666-3899(23)00049-1">A systematic review of multimodal brain age studies: Uncovering a divergence between model accuracy and utility</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/22/21/8112"> Brain Age Prediction/Classification through Recurrent Deep Learning with Electroencephalogram Recordings of Seizure Subjects </a></li>
  <li><a href="https://www.frontiersin.org/journals/aging-neuroscience/articles/10.3389/fnagi.2022.1019869/full?trk=organization_guest_main-feed-card_feed-article-content">Predicting age from resting-state scalp EEG signals with deep convolutional neural networks on TD-brain dataset
</a></li>
<li><a href="https://ieeexplore.ieee.org/abstract/document/10560863"> Enhancing Brain Age Prediction: A Generative AI Approach for EEG Machine Learning Models </a></li>
<li><a href="https://www.mdpi.com/1424-8220/22/21/8112"> Brain Age Prediction/Classification through Recurrent Deep Learning with Electroencephalogram Recordings of Seizure Subjects </a></li>

</details>


<details>
  <summary>Brain Health assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.mdpi.com/2076-3417/12/19/9560"> Quantitative Electroencephalogram (qEEG) as a Natural and Non-Invasive Window into Living Brain and Mind in the Functional Continuum of Healthy and Pathological Conditions </a></li>
  <li><a href="https://www.nature.com/articles/s41598-023-37128-7">Decoding information about cognitive health from the brainwaves of sleep</a></li>
  <li><a href="https://www.biorxiv.org/content/10.1101/2024.02.27.581950v1.abstract">On Monitoring Brain Health from the Depths of Sleep: Feature Engineering and Machine Learning Insights for Digital Biomarker Development</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1757-899X/1055/1/012091/meta">A Machine learning approach to monitor Brain Health and epilepsy detection</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s12021-022-09572-9">How Machine Learning is Powering Neuroimaging to Improve Brain Health</a></li>

</details>


<details>
  <summary>Stress assessment</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.mdpi.com/1424-8220/21/15/5043"> A Review on Mental Stress Assessment Methods Using EEG Signals </a></li>
  <li><a href="https://link.springer.com/article/10.1007/s00521-024-09809-5">A review on evaluating mental stress by deep learning using EEG signals</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9795221">Methods and Measures for Mental Stress Assessment in Surgery: A Systematic Review of 20 Years of Literature</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10243151">Mental Stress Assessment in the Workplace: A Review</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/full/10.1155/2022/4565968">A Novel Stress State Assessment Method for College Students Based on EEG</a></li>
  <li><a href="https://arxiv.org/abs/2202.03033">Human Stress Assessment: A Comprehensive Review of Methods Using Wearable Sensors and Non-wearable Techniques</a></li>

</details>


<details>
  <summary>Sleep disorders</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0010482522008083">A review of automated sleep disorder detection</a></li>
  <li><a href="https://www.mdpi.com/2079-9292/10/13/1531"> Automated Identification of Sleep Disorder Types Using Triplet Half-Band Filter and Ensemble Machine Learning Techniques with EEG Signals </a></li>
  <li><a href="https://www.scirp.org/journal/paperinformation?paperid=112539"> The Role of EEG in the Diagnosis and Management of Patients with Sleep Disorders </a></li>
  <li><a href="https://www.mdpi.com/2076-3417/10/24/8963"> Automated Detection of Sleep Stages Using Deep Learning Techniques: A Systematic Review of the Last Decade (2010–2020) </a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/7/3468"> Simultaneous Sleep Stage and Sleep Disorder Detection from Multimodal Sensors Using Deep Learning </a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9445159">Deep Learning for Sleep Disorders: A Review</a></li>

</details>


<details>
  <summary>Cognitive Load</summary>
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9551143">Deep Learning Architectures Used In Eeg-Based Estimation Of Cognitive workload: A Review</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/20/8528"> Characterisation of Cognitive Load Using Machine Learning Classifiers of Electroencephalogram Data </a></li>
  <li><a href="https://www.mdpi.com/2306-5354/10/3/361"> Prediction of Cognitive Load from Electroencephalography Signals Using Long Short-Term Memory Network </a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9458953">Cognitive Workload Recognition Using EEG Signals and Machine Learning: A Review</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10263778">Deep Learning Framework for Modeling Cognitive Load From Small and Noisy EEG Data</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10416860">A Comprehensive Survey of EEG Preprocessing Methods for Cognitive Load Assessment</a></li>

</details>


<details>
  <summary>Working Memory</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809421008466">Analysis of working memory from EEG signals under different emotional states</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/full/10.1111/psyp.13735">Oscillatory brain activity and maintenance of verbal and visual working memory: A systematic review</a></li>
  <li><a href="https://www.researchgate.net/profile/Ricardo-Buettner/publication/358104193_A_Novel_Machine_Learning_Approach_to_Working_Memory_Evaluation_Using_Resting-State_EEG_Data/links/61f011dac5e3103375bd75e4/A-Novel-Machine-Learning-Approach-to-Working-Memory-Evaluation-Using-Resting-State-EEG-Data.pdf">A Novel Machine Learning Approach to Working Memory Evaluation Using Resting-State EEG Data</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/ac8b38/meta">Decoding working memory-related information from repeated psychophysiological EEG experiments using convolutional and contrastive neural networks</a></li>
  <li><a href="https://direct.mit.edu/jocn/article-abstract/34/4/551/108895/How-Working-Memory-and-Reinforcement-Learning-Are"> How Working Memory and Reinforcement Learning Are Intertwined: A Cognitive, Neural, and Computational Perspective </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2095263521000972">The impact of the design of learning spaces on attention and memory from a neuroarchitectural approach: A systematic review</a></li>

</details>


</details>

<details>
  <summary>Memory Function</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.taylorfrancis.com/chapters/edit/10.1201/9781003145004-11/performance-evaluation-machine-learning-classifiers-memory-assessment-using-eeg-signal-shipra-swati-mukesh-kumar"> Performance Evaluation of Machine Learning Classifiers for Memory Assessment Using EEG Signal </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0165027024001651">Decoding EEG for optimizing naturalistic memory</a></li>
  <li><a href="https://www.science.org/doi/full/10.1126/science.abi8370">Brain neural patterns and the memory function of sleep</a></li>
  <li><a href="https://academic.oup.com/brain/article/146/6/2214/6835141"> Direct electrical brain stimulation of human memory: lessons learnt and future perspectives </a></li>
  <li><a href="https://arxiv.org/abs/2307.13181">Neural Memory Decoding with EEG Data and Representation Learning</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0168010222003030">Sleep, learning, and memory in human research using noninvasive neuroimaging techniques</a></li>

</details>


<details>
  <summary>Attention</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.nature.com/articles/s41598-022-24417-w">Decoding the cognitive states of attention and distraction in a real-life setting using EEG</a></li>
  <li><a href="https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2021.727840/full">Attention Detection in Virtual Environments Using EEG Signals: A Scoping Review
</a></li>
  <li><a href="https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2021.661178/full">EEG-Based Auditory Attention Detection and Its Possible Future Applications for Passive BCI
</a></li>
  <li><a href="https://www.mdpi.com/2079-9292/11/5/770"> Physical Exercise Effects on University Students’ Attention: An EEG Analysis Approach </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1744388121000281">EEG based interpretation of human brain activity during yoga and meditation using machine learning: A systematic review</a></li>
  

</details>

<details>
  <summary>Vigilance</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0167876022002720">Vigilance described by the time-on-task effect in EEG activity during a cued Go/NoGo task</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1568494622003143">Driver vigilance detection for high-speed rail using fusion of multiple physiological signals and deep learning</a></li>
  <li><a href="https://essopenarchive.org/doi/full/10.22541/au.171052497.72177186">EEG Band Patterns for Top-Down vs Bottom-Up Control During the Psychomotor Vigilance Task: A Meta-Analysis</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/21/16/5617"> Generalized Deep Learning EEG Models for Cross-Participant and Cross-Task Detection of the Vigilance Decrement in Sustained Attention Tasks </a></li>
  <li><a href="https://www.frontiersin.org/journals/psychiatry/articles/10.3389/fpsyt.2022.874757/full">Revisiting the Concept of Vigilance</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9335936">Cognitive Vigilance Enhancement Using Audio Stimulation of Pure Tone at 250 Hz</a></li>
  li><a href="https">Estimating the Vigilance of High-Speed Rail Drivers Using a Stacking Ensemble Learning Method</a></li>
  li><a href="https://ieeexplore.ieee.org/abstract/document/9420749">techniques</a></li>
  li><a href="https://ieeexplore.ieee.org/abstract/document/10122849">Driver Vigilance Detection Based on Limited EEG Signals</a></li>
  li><a href="https://link.springer.com/referenceworkentry/10.1007/978-981-15-2848-4_75-1">Vigilance Assessment and Enhancement</a></li>

</details>


<details>
  <summary>Fatigue</summary>
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10185973">Application of Artificial Intelligence Techniques for Brain–Computer Interface in Mental Fatigue Detection: A Systematic Review (2011–2022)</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0926580523001474">Identifying mental fatigue of construction workers using EEG and deep learning</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s00521-023-08491-3">A new hand-modeled learning framework for driving fatigue detection using EEG signals</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1474034623001064">Deep learning-based construction equipment operators’ mental fatigue classification using wearable EEG sensor data</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0925231223008329">EEG-based neural networks approaches for fatigue and drowsiness detection: A survey</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11042-023-15054-0">Machine learning and deep learning techniques for driver fatigue and drowsiness detection: a review</a></li>
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2023.1248474/full">Fatigue factors and fatigue indices in SSVEP-based brain-computer interfaces: a systematic review and meta-analysis
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2590005623000450">Multiple robust approaches for EEG-based driving fatigue detection and classification</a></li>

</details>


<details>
  <summary>Objective Performance Evaluation </summary>
  
  
  **Useful Resources:**
  <li><a href="https://physionet.org/content/eeg-eye-gaze-for-fls-tasks/1.0.0/EYE_FLS/">Integration of Electroencephalogram and Eye-Gaze Datasets for Performance Evaluation in Fundamentals of Laparoscopic Surgery (FLS) Tasks</a></li>
  <li><a href="https://www.nature.com/articles/s41598-024-65648-3">Prediction of Robotic Anastomosis Competency Evaluation (RACE) metrics during vesico-urethral anastomosis using electroencephalography, eye-tracking, and machine learning</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1361-6579/acd51b/meta">State-of-the-art mental tasks classification based on electroencephalograms: a review</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/acbfe0/meta">Confused or not: decoding brain activity and recognizing confusion in reasoning learning using EEG</a></li>
  <li><a href="https://www.imrpress.com/journal/JIN/22/3/10.31083/j.jin2203062/htm?utm_source=TrendMD&utm_medium=cpc&utm_campaign=Journal_of_Integrative_Neuroscience_TrendMD_1">Electroencephalography (EEG) Physiological Indices Reflecting Human Physical Performance: A Systematic Review Using Updated PRISMA</a></li>

</details>

### 🔶 Assistive Technologies and Rehabilitation

<details>
  <summary>Brain-Computer Interfaces (BCIs)</summary>
  
  
  **Useful Resources:**
    
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10462-023-10690-2">Role of machine learning and deep learning techniques in EEG-based BCI emotion recognition system: a review
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/B9780443137723000042">Artifacts removal techniques in EEG data for BCI applications: A survey</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10509679">Data Constraints and Performance Optimization for Transformer-Based Models in EEG-Based Brain-Computer Interfaces: A Survey
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809423009813">Integration of cloud computing in BCI: A review
</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10579740">Motor Imagery Signal Classification Using Adversarial Learning: A Systematic Literature Review
</a></li>
  <li><a href="https://arxiv.org/abs/2404.15319">The largest EEG-based BCI reproducibility study for open science: the MOABB benchmark
</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10605127">Speech imagery decoding using EEG signals and deep learning: A survey
  <li><a href="https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2022.1006763/full">Status of deep learning for EEG-based brain–computer interface applications</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10305163">Deep Learning in EEG-Based BCIs: A Comprehensive Review of Transformer Models, Advantages, Challenges, and Applications
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S2214785321048033">Advances in modern EEG-BCI signal processing: A review
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2665917423001599">Machine learning techniques for electroencephalogram based brain-computer interface: A systematic literature review
</a></li>
<li><a href="https://www.mdpi.com/1424-8220/23/5/2798">EEG-Based BCIs on Motor Imagery Paradigm Using Wearable Technologies: A Systematic Review</a></li>

</details>


<details>
  <summary>Neurorehabilitation</summary>
  
  
  **Useful Resources:**
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10268416">A Survey of EEG and Machine Learning-Based Methods for Neural Rehabilitation
</a></li>
  <li><a href="https://www.nature.com/articles/s41598-024-65910-8">Avoidance of specific calibration sessions in motor intention recognition for exoskeleton-supported rehabilitation through transfer learning on EEG data
</a></li>
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2024.1245707/full">Motor imagery for paediatric neurorehabilitation: how much do we know? Perspectives from a systematic review
</a></li>
  <li><a href="https://link.springer.com/article/10.1186/s12984-023-01294-6">A review of combined functional neuroimaging and motion capture for motor rehabilitation
</a></li>
  <li><a href="https://www.mdpi.com/2218-6581/13/3/49">Intelligent Robotics in Pediatric Cooperative Neurorehabilitation: A Review
</a></li>
  <li><a href="https://www.frontiersin.org/journals/rehabilitation-sciences/articles/10.3389/fresc.2023.1198679/full">Enhancing neurorehabilitation by targeting beneficial plasticity</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/15500594221123690">EEG Dynamics of Locomotion and Balancing: Solution to Neuro-Rehabilitation</a></li>
  <li><a href="https://sappg.ufes.br/tese_drupal/tese_17478_Disserta%E7%E3o%20de%20Mestrado%20-%20Cristian%20Felipe%20Blanco%20D%EDaz.pdf">Brain-Computer Interface for Lower-Limb Neurorehabilitation: From Signal Analysis to Practical Applications</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10504349">Incorporating Motor Imagery-Controlled Gaming into Paralysis Rehabilitation</a></li>

</details>

<details>
  <summary>Neurolinguistics</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.nature.com/articles/s41599-023-01926-1">Emotional processing in bilinguals: a systematic review aimed at identifying future trends in neurolinguistics</a></li>
  <li><a href="https://ojs.aaai.org/index.php/AAAI/article/view/25745">Towards Voice Reconstruction from EEG during Imagined Speech
</a></li>
  <li><a href="https://www.mdpi.com/2306-5354/10/6/649">Imagined Speech Classification Using EEG and Deep Learning
</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/12/5575">Machine-Learning Methods for Speech and Handwriting Detection Using Neural Signals: A Review</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/ace73f/meta">Relating EEG to continuous speech using deep neural networks: a review</a></li>
  <li><a href="https://www.nature.com/articles/s41598-024-57426-y">Language prediction in monolingual and bilingual speakers: an EEG study</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0911604424000113">Neurodynamics of selected language processes involved in word reading: An EEG study with French dyslexic adults</a></li>
  <li><a href="https://www.mdpi.com/2076-3425/13/12/1613">Cognitive Neuroscience Perspectives on Language Acquisition and Processing
</a></li>
  

</details>



### 🔶 Cognitive and Performance Evaluation

<details>
  <summary>Lie Detection</summary>
  
  
  **Useful Resources:**
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-99-3177-4_7">Comprehensive Review of Lie Detection in Subject Based Deceit Identification</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10017818">EEG-based lie detection using ERP P300 in response to known and unknown faces: An overview</a></li>
  <li><a href="https://dl.acm.org/doi/abs/10.1145/3458791">An Efficient Deep Learning Paradigm for Deceit Identification Test on EEG Signals</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9773469">EEG Guided Multimodal Lie Detection with Audio-Visual Cues</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-97-0641-9_12">Supervised Learning Approaches for Deceit Identification: Exploring EEG as a Non-invasive Technique</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11042-023-16847-z">LSTMNCP: lie detection from EEG signals with novel hybrid deep learning method</a></li>

</details>


<details>
  <summary>Sensory Neuroscience</summary>
  
  
  **Useful Resources:**
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/acb9be/meta">EEG-based detection of modality-specific visual and auditory sensory processing
</a></li>
  <li><a href=https://www.nature.com/articles/s41598-023-37829-z"">Regulation of brain cognitive states through auditory, gustatory, and olfactory stimulation with wearable monitoring</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/ad1ac1/meta">EEG-based hierarchical classification of level of demand and modality of auditory and visual sensory processing
</a></li>
  <li><a href="https://www.mdpi.com/2076-3425/14/2/131?utm_campaign=releaseissue_brainsciutm_medium=emailutm_source=releaseissueutm_term=doilink12">Short-Term Effect of Auditory Stimulation on Neural Activities: A Scoping Review of Longitudinal Electroencephalography and Magnetoencephalography Studies
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s13042-023-01797-7">Recognition of odor and pleasantness based on olfactory EEG combined with functional brain network model
</a></li>
  <li><a href="https://www.mdpi.com/2076-3425/13/6/866">Machine Learning-Based Classification to Disentangle EEG Responses to TMS and Auditory Input
</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/24/1/45">Temporal Electroencephalography Traits Dissociating Tactile Information and Cross-Modal Congruence Effects</a></li>
  <li><a href="https://www.mdpi.com/2076-3425/13/5/766">Somatosensory Event-Related Potential as an Electrophysiological Correlate of Endogenous Spatial Tactile Attention: Prospects for Electrotactile Brain-Computer Interface for Sensory Training</a></li>
  <li><a href="https://academic.oup.com/cercor/article-abstract/34/4/bhae161/7651008">Cortical activations associated with spatial remapping of finger touch using EEG Get access Arrow
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1053811923004202">Vicarious touch: Overlapping neural patterns between seeing and feeling touch
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0924224424002838">Recent advances and applications of deep learning, electroencephalography, and modern analysis techniques in screening, evaluation, and mechanistic analysis of taste peptides
</a></li>
  <li><a href="https://pubs.acs.org/doi/abs/10.1021/acs.jafc.3c04611">TastePeptides-EEG: An Ensemble Model for Umami Taste Evaluation Based on Electroencephalogram and Machine Learning</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10394408">Decoding Taste from EEG: Gustatory Evoked Potentials During Wine Tasting
</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-51485-2_44">Study on the Detection of Vertigo Induced by GVS Based on EEG Signal Feature Binary Classification
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10055-023-00795-y">Brain activity during cybersickness: a scoping review
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s00221-023-06690-x">Exploring neurophysiological correlates of visually induced motion sickness using electroencephalography (EEG)
</a></li>
  **Proprioceptive (body awareness):**
The proprioceptive system is located in our muscles and joints. It provides us with a sense of body awareness and detects/controls force and pressure. The proprioceptive system also has an important regulatory role in sensory processing as proprioceptive input can assist in controlling responses to sensory stimuli.

Proprioceptive input can be very calming for those who are easily overwhelmed by sensory stimulation.

Proprioceptive input can be alerting for those who need increased sensory stimulation to facilitate attention and learning.

Many students with autism seek proprioceptive input in order to regulate their emotional and behavioural responses to sensory stimulation.

</details>


<details>
  <summary>Neuroergonomics</summary>
  Researchers in the field of human factors and ergonomics examine both physical and cognitive human abilities and limitations and use this information to design safer, more convenient, and efficient work environments for people to interact with (Dehais and Ayaz, 2019). Neuroergonomics, which was developed as a special field of ergonomics, combines neuroscience and ergonomics to examine the brain and mental behavior of people working in the business environment (Parasuraman, 2003). It is used for the design and evaluation of human–machine systems in various work environments through the mental examination or modeling of workers (Parasuraman, 2003, Parasuraman and Rizzo, 2009). Neuroergonomics includes studies of the brain and behaviors at work and explores the relationship between work-related tasks and the brain to modify work environments to increase performance (James, 2012).

Within the scope of neuroergonomics, one of the primary studies carried out to understand how a task has an effect on a working person is to determine the mental workload. Mental workload is the cognitive demand of a task. Mental workload may be evaluated by recording psychophysiological components (cardiac activity, electrooculogram, respiration or event-related potentials of brain activity signals), task performance (commonly measured with response accuracy and response latency), and self-rating questionnaires [mostly used ones being the NASA-Task Load Index (NASA-TLX) (Hart and Staveland, 1988) and the subjective workload assessment technique (SWAT) (Reid and Nygren, 1988)]. Both the task-related components and subject-related characteristics can be the reason for the increase in mental workload (Galy et al., 2012). In everyday life, increasing mental workload causes overload and eventually decreases the task performance (Borghini et al., 2014).

  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1369847824000706">A neuroergonomics approach to investigate the mental workload of drivers in real driving settings
</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroergonomics/articles/10.3389/fnrgo.2024.1346794/full">Reproducible machine learning research in mental workload classification using EEG
</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/accbed/meta">Using EEG signals to assess workload during memory retrieval in a real-world scenario
</a></li>

</details>


### 🔶 Neuroscientific Research

<details>
  <summary>Functional Connectivity</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.mdpi.com/2306-5354/10/3/372">Connectivity Analysis in EEG Data: A Tutorial Review of the State of the Art and Emerging Trends
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2352914824000327">EEG-based functional connectivity analysis of brain abnormalities: A systematic review study
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0165032723001465">Alterations in EEG functional connectivity in individuals with depression: A systematic review
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1388245723006569">Can we manipulate brain connectivity? A systematic review of cortico-cortical paired associative stimulation effects
</a></li>
  <li><a href="https://www.cell.com/heliyon/fulltext/S2405-8440(24)07308-0">EEG connectivity and network analyses predict outcome in patients with disorders of consciousness – A systematic review and meta-analysis
</a></li>
  <li><a href="https://iopscience.iop.org/article/10.1088/1741-2552/acf734/meta">Analysis of functional connectivity using machine learning and deep learning in different data modalities from individuals with schizophrenia
</a></li>
  <li><a href="https://www.nature.com/articles/s41598-024-59652-w">Classification of mental workload using brain connectivity and machine learning on electroencephalogram data
</a></li>

</details>

<details>
  <summary>Developmental Neuroscience</summary>
  
  
  **Useful Resources:**

  <li><a href="https://www.sciencedirect.com/science/article/pii/S1878929323000063">Maximizing the potential of EEG as a developmental neuroscience tool</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/full/10.1111/desc.13259">How infant-directed actions enhance infants’ attention, learning, and exploration: Evidence from EEG and computational modeling</a></li>
  <li><a href="https://journals.sagepub.com/doi/full/10.1177/08830738231177386">Electroencephalographic (EEG) Biomarkers in Genetic Neurodevelopmental Disorders</a></li>
  <li><a href="https://link.springer.com/article/10.1186/s11689-023-09481-1">The contribution of theta and delta to feedback processing in children with developmental language disorder</a></li>
  <li><a href="https://www.nature.com/articles/s41598-023-47606-7">Application of bi-directional long-short-term memory network in cognitive age prediction based on EEG signals</a></li>

</details>

### 🔶 Education and Sports


<details>
  <summary>Personalized Learning</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1053811923005189">Is neuroimaging ready for the classroom? A systematic review of hyperscanning studies in learning</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10584531">Advancing Real-Time Remote Learning: A Novel Paradigm for Cognitive Enhancement Using EEG and Eye-Tracking Analytics</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10639-022-11372-2">On enhancing students’ cognitive abilities in online learning using brain activity and eye movements</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10601997">Learning Behavior Analysis for Personalized E-Learning using EEG Signals</a></li>
  <li><a href="https://www.mdpi.com/2227-7102/13/9/914">Emotions Matter: A Systematic Review and Meta-Analysis of the Detection and Classification of Students’ Emotions in STEM during Online Learning </a></li>
  <li><a href="https://www.mdpi.com/2073-431X/13/4/96"> The Use of Integrated Multichannel Records in Learning Studies in Higher Education: A Systematic Review of the Last 10 Years </a></li>

</details>


<details>
  <summary>Skill Acquisition and Training</summary>
  
  
  **Useful Resources:** (Frontiers in Neuroscience works alot in this field)
  <li><a href="https://link.springer.com/article/10.1007/s00464-024-11049-6">Classification of subtask types and skill levels in robot-assisted surgery using EEG, eye-tracking, and machine learning</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11701-023-01722-8">Surgical skill level classification model development using EEG and eye-gaze data and machine learning algorithms</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11760-022-02327-8">Assessment of learning a new skill using nonlinear and spectral features of EEG</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1094658/full">Characteristics of EEG power spectra involved in the proficiency of motor learning
</a></li>
  <li><a href="https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2023.1273186/full">A new EEG neurofeedback training approach in sports: the effects function-specific instruction of Mu rhythm and visuomotor skill performance
</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10379685">Advancing Aviation Safety Through Machine Learning and Psychophysiological Data: A Systematic Review</a></li>
  <li><a href="https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2023.1172103/full">EEG-based analysis for pilots’ at-risk cognitive competency identification using RF-CNN algorithm
</a></li>
<li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0957417423021607">An EEG-based cross-subject interpretable CNN for game player expertise level classification</a></li>

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
  <li><a href="https://www.mdpi.com/2075-1729/13/2/365">EEG-Neurofeedback as a Potential Therapeutic Approach for Cognitive Deficits in Patients with Dementia, Multiple Sclerosis, Stroke and Traumatic Brain Injury</a></li>
  <li><a href="https://ddfv.ufv.es/entities/publication/ea103500-999c-4ac4-917a-6d4a46796e68">
Cognitive rehabilitation in a case of traumatic brain injury using EEG-based neurofeedback in comparison to conventional methods.</a></li>
  <li><a href="">depression</a></li>


</details>

### 🔶 Consumer and Lifestyle Technologies

<details>
  <summary>Emotional State Analysis</summary>
  
  
  **Useful Resources:**
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0010482523009150">Emotion recognition in EEG signals using deep learning methods: A review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1566253523005341">Multimodal Emotion Recognition with Deep Learning: Advancements, challenges, and future directions</a></li>
  <li><a href="https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2024.1387089/full">Integrating artificial intelligence to assess emotions in learning environments: a systematic literature review
</a></li>
  <li><a href="https://www.nature.com/articles/s41598-024-61832-7">Insights from EEG analysis of evoked memory recalls using deep learning for emotion charting</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10443946">EEG-Based Multimodal Emotion Recognition: A Machine Learning Perspective</a></li>
  <li><a href="https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2023.1289816/full">Mini review: Challenges in EEG emotion recognition
</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s10462-023-10690-2">Role of machine learning and deep learning techniques in EEG-based BCI emotion recognition system: a review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1389041723000803">A systematic literature review of emotion recognition using EEG signals</a></li>
  <li><a href="https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2023.1126994/full">Deep learning-based EEG emotion recognition: Current trends and future perspectives
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1566253523005067">A review on semi-supervised learning for EEG-based emotion recognition☆</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S036013152300074X">Measuring emotions in education using wearable devices: A systematic review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0360131524001258">Bridging computer and education sciences: A systematic review of automated emotion recognition in online learning environments</a></li>

</details>


</details>

<details>
  <summary>Immersive Gaming and Entertainment</summary>
  
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10064320">Neural Applications Using Immersive Virtual Reality: A Review on EEG Studies</a></li>
  <li><a href=""></a></li>
  <li><a href="https://link.springer.com/referenceworkentry/10.1007/978-3-031-23161-2_176">EEG as an Input for Virtual Reality</a></li>
  <li><a href="https://www.worldscientific.com/doi/abs/10.4015/S1016237224500224">MENTAL WORKLOAD ASSESSMENT OF GAMERS’ EEG WITH MULTI-DOMAIN FEATURE-BASED COGNITIVE MODEL AND ITS VALIDATION</a></li>
  <li><a href="https://www.mdpi.com/2079-9292/13/11/2043">Assessing the Effects of Various Gaming Platforms on Players’ Affective States and Workloads through Electroencephalogram </a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10589391">Analysis Learning Model With Biometric Devices for Business Simulation Games: Brazilian Case Study</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10049421">Virtual Reality Cognitive Gaming Based on Brain Computer Interfacing: A Narrative Review</a></li>
  <li><a href="">Classification of VR-Gaming Difficulty Induced Stress Levels using Physiological (EEG & ECG) Signals and Machine Learning</a></li>
  <li><a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.16873471.v1"></a></li>
  <li><a href="https://www.mdpi.com/1999-5903/15/8/264"> Mapping EEG Alpha Activity: Assessing Concentration Levels during Player Experience in Virtual Reality Video Games </a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-61569-6_5">The Influence of Educational and Entertainment Videos on Children’s Frontal EEG Activity: A Case Study</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-35596-7_26">Research on Brain-Computer Interfaces in the Entertainment Field</a></li>
  <li><a href=""></a></li>
  <li><a href=""></a></li>

</details>


<details>
  <summary>Meditation and Mindfulness</summary>
  
  <li><a href="https://www.frontiersin.org/journals/human-neuroscience/articles/10.3389/fnhum.2023.1033420/full">EEG-based investigation of effects of mindfulness meditation training on state and trait by deep learning and traditional machine learning
</a></li>
  <li><a href="https://academic.oup.com/cercor/article-abstract/34/7/bhae288/7716272">Enhancing specialization of attention-related EEG power and phase synchronism brain patterns by meditation</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2667242123000209">Intermediate effects of mindfulness practice on the brain activity of college students: An EEG study</a></li>
  <li><a href="https://www.cell.com/heliyon/fulltext/S2405-8440(23)07283-3">Long-term practice of intuitive inquiry meditation modulates EEG dynamics during self-schema processing</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-97-1463-6_15">Mindfulness Intervention Affects Cognitive Abilities of Students: A Time–Frequency Analysis Using EEG</a></li>
  <li><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10777293/">Convolutional neural networks for classifying healthy individuals practicing or not practicing meditation according to the EEG data</a></li>

</details>

<details>
  <summary>Smart Home Systems</summary>
  
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-99-7456-6_10">Smart Home</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-42622-3_51">Brain-Computer-Interface (BCI) Based Smart Home Control Using EEG Mental Commands</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s12652-022-04469-6">A hybrid EEG and head motion system for smart home control for disabled people</a></li>
  <li><a href="https://www.frontiersin.org/journals/aging-neuroscience/articles/10.3389/fnagi.2023.1167410/full">Eliciting brain waves of people with cognitive impairment during meditation exercises using portable electroencephalography in a smart-home environment: a pilot study
</a></li>
  <li><a href="https://inass.org/wp-content/uploads/2022/10/2023022828-2.pdf">Design and Implementation of EEG-Based Smart Structure</a></li>


</details>


<details>
  <summary>Wearable Technology</summary>
  
  <li><a href="https://www.frontiersin.org/journals/neuroergonomics/articles/10.3389/fnrgo.2024.1340732/full">Brain-age estimation with a low-cost EEG-headset: effectiveness and implications for large-scale screening and brain optimization
</a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/5/2387">Online Learning for Wearable EEG-Based Emotion Classification </a></li>
  <li><a href="https://www.mdpi.com/1424-8220/23/3/1255">https://www.mdpi.com/2079-6374/13/10/930</a></li>
  <li><a href="https://www.mdpi.com/2079-6374/13/10/930"> Application and Development of EEG Acquisition and Feedback Technology: A Review </a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1386505623000436">Generalizable machine learning for stress monitoring from wearable devices: A systematic literature review</a></li>
  <li><a href="https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2023.1220688/full">Use of wearable devices in the teaching-learning process: a systematic review of the literature
</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S001048252200796X">Wearable electroencephalography and multi-modal mental state classification: A systematic literature review☆</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10025407">Diversity and Suitability of the State-of-the-Art Wearable and Wireless EEG Systems Review</a></li>

</details>

### 🔶 Marketing and User Experience

<details>
  <summary>Human-Computer Interaction (HCI)</summary>
  
  <li><a href="https://www.inderscienceonline.com/doi/abs/10.1504/IJBM.2024.135160">Recent trends and challenges in human computer interaction using automatic emotion recognition: a review</a></li>
  <li><a href="https://www.tandfonline.com/doi/abs/10.1080/10447318.2022.2116530">A Systematic Review of Human–Computer Interaction (HCI) Research in Medical and Other Engineering Fields</a></li>
  <li><a href="https://dl.acm.org/doi/full/10.1145/3582272">A Survey on Measuring Cognitive Workload in Human-Computer Interaction</a></li>
  <li><a href="https://www.mdpi.com/2076-3417/14/1/368"> Human–Computer Interaction Multi-Task Modeling Based on Implicit Intent EEG Decoding </a></li>
  <li><a href="https://dl.acm.org/doi/abs/10.1145/3593226">EEG-Based Brain-Computer Interactions in Immersive Virtual and Augmented Reality: A Systematic Review</a></li>

</details>


<details>
  <summary>Neuromarketing and Advertisement</summary>
  
  <li><a href="https://link.springer.com/article/10.1186/s40708-024-00229-8">A systematic review on EEG-based neuromarketing: recent trends and analyzing techniques</a></li>
  <li><a href="https://journals.sagepub.com/doi/full/10.1177/14707853221112622">A practical review of electroencephalography’s value to consumer research</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S1877050923013972">The use of electroencephalography (EEG) in a study into the effectiveness of advertising communication</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s12144-023-04812-w">Exploring global trends and future directions in advertising research: A focus on consumer behavior</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S0031938424000544">A review on the use of eeg for the investigation of the factors that affect Consumer’s behavior</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/cb.2142">An EEG-based neuro-recommendation system for improving consumer purchase experience</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/abs/pii/S1746809423009023">Neuromarketing and decision-making: Classification of consumer preferences based on changes analysis in the EEG signal of brain regions</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11042-023-17114-x">Multi-channel EEG-based classification of consumer preferences using multitaper spectral analysis and deep learning model</a></li>

</details>


<details>
  <summary>Neuroaesthetics</summary>
  
  <li><a href="https://www.frontiersin.org/journals/neuroergonomics/articles/10.3389/fnrgo.2024.1341790/full">Ecological decoding of visual aesthetic preference with oscillatory electroencephalogram features—A mini-review
</a></li>
  <li><a href="https://dl.acm.org/doi/abs/10.1145/3640824.3640839">Artificial Aesthetics: Bridging Neuroaesthetics and Machine Learning</a></li>
  <li><a href="https://link.springer.com/article/10.1186/s13010-023-00147-3">One hundred years of neurosciences in the arts and humanities, a bibliometric review</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-3-031-33013-1_1">Neuroaesthetics: How We Like What We Like</a></li>
  <li><a href="https://papers.cumincad.org/data/works/att/caadria2024_486.pdf">EMPIRICAL INSIGHTS INTO ARCHITECTURAL AESTHETICS: A NEUROSCIENTIFIC PERSPECTIVE</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S0149763423001665">The Neuroscience of Dance: A Conceptual Framework and Systematic Review</a></li>
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2095263523000912">Contemplative neuroaesthetics and architecture: A sensorimotor exploration</a></li>
  <li><a href="">Exploring Methodological Approaches of Experimental Studies in the Field of Neuroarchitecture: A Systematic Review</a></li>
  <li><a href="https://journals.sagepub.com/doi/abs/10.1177/19375867221133135"></a></li>
  <li><a href="https://journals.sagepub.com/doi/full/10.1177/10892680241260840">Neurodynamics of Relational Aesthetic Engagement in Creative Arts Therapies</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s11571-022-09821-2">Cross-subject aesthetic preference recognition of Chinese dance posture using EEG</a></li>
</details>


<details>
  <summary>User Experience</summary>
  
  <li><a href="https://www.sciencedirect.com/science/article/pii/S2451958824000149">Evaluating chatbot user experience (UX) through electroencephalography measures: A systematic literature review</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10462893">Evaluation of User Interface, User Experience, and Usability in Software Through Electroencephalography (EEG) Signal Detection: A Mapping Review</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10035957">User Experience: A Bibliometric Review of the Literature</a></li>
  <li><a href="https://dl.acm.org/doi/abs/10.1145/3593434.3593452">Measuring User Experience of Adaptive User Interfaces using EEG: A Replication Study</a></li>
  <li><a href="https://link.springer.com/chapter/10.1007/978-981-99-0293-4_53">Who to Blame—User Interface Design or Learning Content? A Neurophysiological UX Assessment of e-learning Process</a></li>
</details>

<details>
  <summary>Workforce Monitoring</summary>

</details>

### 🔶 Military and Security

<details>
  <summary>Biometric Authentication</summary>
  
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10536762">EEG-based Biometric Authentication Using Machine and Deep Learning Approachs : A Review</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10577965">Systematic Review of Brain-Computer Interface-Based User Authentication System: Trends, Challenges, and Directions</a></li>
  <li><a href="https://onlinelibrary.wiley.com/doi/abs/10.1002/spy2.345">EEG-based biometric authentication system using convolutional neural network for military applications</a></li>
  <li><a href="https://link.springer.com/article/10.1186/s40708-023-00198-4">An evaluation of transfer learning models in EEG-based authentication</a></li>
  <li><a href="https://link.springer.com/article/10.1007/s00521-022-07795-0">Biometric identification system using EEG signals</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/10058960">A Review of EEG-Based User Authentication: Trends and Future Research Directions</a></li>
  <li><a href=""></a></li>
  <li><a href=""></a></li>


</details>


<details>
  <summary>General Field</summary>
  
  <li><a href="https://link.springer.com/referenceworkentry/10.1007/978-981-16-5540-1_78?fromPaywallRec=true">Deep Learning Methods for EEG Neural Classification</a></li>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9626707">EEG signal analysis using deep learning: A systematic literature review</a></li>
  <li><a href="file:///home/mahdi/Downloads/s12021-022-09572-9.pdf">How Machine Learning is Powering Neuroimaging to Improve Brain Health</a></li>
  <li><a href="https://theses.hal.science/tel-03602771/">Enabling real-world EEG applications with deep learning</a></li>
  <li><a href=""></a></li>
  <li><a href=""></a></li>
  <li><a href=""></a></li>
  <li><a href="https://link.springer.com/book/10.1007/978-3-030-69717-4">Advanced Machine Learning Technologies and Applications </a></li>
  <li><a href="https://link.springer.com/referencework/10.1007/978-981-16-5540-1">Handbook of Neuroengineering </a></li>


</details>

<!-- CONTRIBUTING -->
## CONTRIBUTING
<li><a href="https://ieeexplore.ieee.org/abstract/document/10176120">A Systematic Review of Electroencephalography Open Datasets and Their Usage With Deep Learning Models</a></li>
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
