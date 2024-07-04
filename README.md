# Combining LLM Efficiency with Human Expertise

This repository contains a comprehensive evaluation of various Large Language Models (LLMs) in the context of figurative language detection. The evaluation is detailed in three primary notebooks: "1 Comparative Evaluation.ipynb", "2 Group Agreement.ipynb", and "3 Consensus Based LLM Prediction Aggregation.ipynb". These notebooks collectively explore the performance, biases, and potential of LLMs in handling subjective natural language processing tasks, leveraging both quantitative and qualitative analyses.

## 1 Comparative Evaluation
### 1.1 Functions & Data
This section includes the necessary functions and data required for the evaluation. It sets up the foundation for the subsequent analyses by loading and preparing the datasets.
### 1.2 Figurative Language Devices (Tables 2-5)
This section presents the evaluation of LLMs on various figurative language devices, including metaphors, hyperboles, homographic puns, and heterographic puns. Each device is analyzed using established datasets, with results presented in Tables 2 to 5.
### 1.3 Comparative Analysis (Tables 6-10, Figure 1)
This section delves into a comparative analysis of LLMs' performance, focusing on:

- **GPT4 vs Golden (Tables 6-9)**: Evaluates the alignment of other LLMs' predictions with GPT-4 and human expert annotations across different figurative language devices.
- **Relative Agreement Discrepancy (RAD) (Figure 1)**: Visualizes the discrepancies in agreement between LLMs and human experts using the RAD metric.
- **K-alpha (Table 10)**: Presents Krippendorff’s Alpha values to measure the consistency of LLMs' predictions relative to human annotations.
### 1.4 Further Analysis of Metaphor Detection Divergence

This section performs a deeper analysis of the divergences observed in metaphor detection. It includes:

- **Deriving Subsets $S_0$, $X$, and $Y$ (Equations 2-4)**: Identifies and categorizes subsets of data where there is disagreement between LLMs and human expert annotations.
- **Deriving Subsets $S_1$, $S_2$, $S_3$, and $S_4$ (Equations 5-8)**: Further categorizes these subsets based on agreement patterns with expert judgments.
- **Qualitative Analysis**: Investigates the root causes of these divergences, providing insights into the complexity of metaphor detection and the potential biases in LLMs.
## 2 Group Aggreement
### 2.1 Functions & Data
This section includes the necessary functions and data required to analyze the group agreement of LLMs. It sets up the foundation by loading and preparing the datasets and functions needed for subsequent analyses.

### 2.2 Standard Deviation of Performance Metrics (Tables 15, 16)
This section presents the standard deviation of various performance metrics for the LLMs. By examining these metrics, we can understand the stability and consistency of the models' predictions. The results are detailed in Tables 15 and 16.

### 2.3 Performance Metrics for Heterographic Pun Detection (Figure 2)
This section evaluates the performance metrics for the heterographic pun detection task. Using box plots, Figure 2 visualizes the precision, recall, and F1 scores of the LLMs, highlighting the biases and strengths of each model.

### 2.4 Intra and Inter-Model Agreement for LLMs (Figure 3)
This section examines the agreement between different models (inter-model) and within the same model (intra-model). Figure 3 provides a heatmap illustrating these agreement scores, helping to assess the consistency and reliability of the LLMs' predictions.
## 3 Consensus-Based LLM Prediction Aggregation

### 3.1 Functions & Data
This section contains the functions and data necessary for implementing the Consensus-Based LLM Prediction Aggregation method. It lays the groundwork by loading and preparing the essential datasets and functions for the subsequent analyses.

### 3.2 Consensus Aggregation (Figures 4, 5)
This section introduces the Consensus-Based LLM Prediction Aggregation (CLPA) method, which aims to enhance the prediction accuracy by leveraging the collective wisdom of multiple LLMs. Figures 4 and 5 illustrate the performance metrics and optimal star ratings achieved through this method.

### 3.3 Co-Annotation (Figure 6)
In this section, we explore the application of the CLPA method in co-annotation tasks. Figure 6 shows the process and results of using CLPA to combine human expertise with LLM efficiency, aiming to streamline the annotation process while maintaining high-quality standards.



