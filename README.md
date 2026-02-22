# RealTime-Stress-XAI-BCI

**Real-Time Cognitive Load and Academic Stress Monitoring using 5-Channel EEG Headset Data with XAI and Machine Learning Models**

[cite_start]Academic stress affects students' cognitive performance and well-being, yet conventional assessment methods rely on subjective self-reports and lack real-time monitoring[cite: 9, 35]. [cite_start]This repository provides an objective, data-driven framework using EEG signals combined with Machine Learning and Explainable AI (XAI) to accurately classify academic stress[cite: 10, 11].

<img width="1048" height="844" alt="image" src="https://github.com/user-attachments/assets/6e58095c-1f86-4313-9768-3d109c0a18fe" />


### 🚀 Key Highlights
* [cite_start]**High Performance**: Achieved a peak accuracy of **98.9%** with CNN and **98.5%** with LSTM models[cite: 17, 471, 509].
* [cite_start]**Computational Efficiency**: **XGBoost** provided an optimal balance of speed (5.8s training) and accuracy (94.1%) for real-time applications[cite: 498, 750, 755].
* [cite_start]**Model Transparency**: Integrated **SHAP** and **LIME** to identify key physiological predictors, such as **Beta and Gamma** frequency bands[cite: 17, 18, 48].
* [cite_start]**Non-Invasive Hardware**: Developed for the portable and cost-effective **Muse 2** EEG headband[cite: 13, 146, 202].

### 🛠️ Technical Methodology
* [cite_start]**Data Acquisition**: EEG data was collected from 37 participants using 4 active dry electrodes (TP9, AF7, AF8, TP10)[cite: 13, 143, 148].
* [cite_start]**Preprocessing Pipeline**: Signals were processed using bandpass filtering (1-50 Hz), Independent Component Analysis (ICA) for artifact removal, and z-score normalization[cite: 14, 252, 273, 281].
* [cite_start]**Feature Extraction**: Power Spectral Density (PSD) and statistical measures were extracted across five frequency bands: Delta, Theta, Alpha, Beta, and Gamma[cite: 15, 231, 232].
* [cite_start]**Insights**: Beta and Gamma bands exhibited higher power post-quiz, indicating increased cognitive load[cite: 223, 248].



### 💻 Web Application
The project features a **Streamlit** web interface that allows users to:

1.  [cite_start]**Visualize**:
2.  <img width="2379" height="1180" alt="image" src="https://github.com/user-attachments/assets/99231d3f-2fa7-488c-9d4d-7abd3d78b707" />

3.  <img width="2007" height="1200" alt="image" src="https://github.com/user-attachments/assets/c4353633-6235-40f1-bf66-1b52047924a8" />

4.  <img width="1491" height="1189" alt="image" src="https://github.com/user-attachments/assets/42a7f083-3301-4d19-851d-87f927bafcb6" />

5.  [cite_start]**Predict**: <img width="1183" height="790" alt="image" src="https://github.com/user-attachments/assets/ed701464-b7b6-460d-b29f-ab21178c5040" />
<img width="1183" height="790" alt="image" src="https://github.com/user-attachments/assets/5f0521bf-0ac2-4c52-bce7-353fb7d34d0f" />

   
7.  [cite_start]**XAI Interpretation**:
8.  <img width="1345" height="337" alt="image" src="https://github.com/user-attachments/assets/f4692613-cf9a-4a0e-a2df-446d863d996d" />


### 🙏 Acknowledgments
The authors would like to express their sincere gratitude to **Dr. [cite_start]Mohammad Rezwanul Huq**, Associate Professor in the Department of Computer Science & Engineering at **East West University**, for his invaluable guidance and supervision throughout this project[cite: 801]. Special thanks are also extended to **Dr. [cite_start]Raihan Ul Islam**, Associate Professor in the Department of Computer Science & Engineering at **East West University**, for generously providing the dataset used in this research[cite: 802].

---
*Developed as part of a research initiative at East West University, Dhaka, Bangladesh.*
