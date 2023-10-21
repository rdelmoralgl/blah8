# BLAH8 - Comparative Analysis of State-of-the-Art Generative LLMs for Labeling Clinical Notes in Spanish

## Project description
This project aims to evaluate and compare various state-of-the-art generative Large Language Models (LLMs) in the Named Entity Recognition (NER) task within a zero-shot setting, employing publicly available gold-standard annotated datasets in the biomedical domain and the Spanish language. Different prompt strategies will be designed and tested, and the results will be evaluated and compared across different corpora.

## Motivation
Manual extraction of relevant information from EHRs is a very expensive task, both in resources and time. Most high-performing clinical NER methodologies require some form of predefined lexical data. Given the emerging relevance of Generative LLMs, it is very attractive to explore the capabilities of these models in performing biomedical NER tasks, especially since they have demonstrated promising capabilities in various tasks in zero-shot settings (i.e., without utilizing annotated corpora).

Biomedical NLP tasks often face challenges due to language-specific nuances. Spanish, being one of the most spoken languages globally, holds a vast amount of unstructured biomedical data that is yet to be fully utilized. By focusing on Spanish, this project aims to bridge the gap in technologies available for extracting relevant information from text in this language.

## Realistic goals for the period of the hackathon
1. Identify at least three state-of-the-art generative models for comparative analysis. While we have already shortlisted some models for evaluation (GPT-4, Llama 2, Falcon, Beluga, Bloom), we recognize the rapidly evolving landscape in this field and so we intend to keep the list of models open-ended. 

2. Design at least three prompt variations in accordance with each model and the entities to be labeled. This point aims to explore the synergy between different prompting strategies and model architectures 

3. Assess the performance of the selected models and prompt variations on a Spanish biomedical NER dataset, to provide an insight into each model's efficacy and real-world applicability in biomedical labeling tasks. We will employ the evaluation metrics of Precision, Recall, and F1 Score.

## An explanation of how the hackathon environment would contribute to realization of the project
The hackathon environment fosters a collaborative and rapid problem-solving culture, promoting cross-functional teamwork and innovative solutions. This setting is ideal for nurturing the multidisciplinary approach needed for this project, while also providing a platform for immediate feedback and improvements.

## A plan for evaluating the work
The success of our project will be substantiated with a comprehensive table summarizing the performance of each evaluated model along with relevant statistics reflecting their peculiarities. Metrics of Precision, Recall, and F1 Score will be computed to provide a clear comparative analysis. 

We plan to use a subset of around 100 clinical notes from the DisTEMIST/MedProcNER/SympTEMIST corpus, which is also a subset of the SPACCC dataset annotated with mentions of diseases, medical procedures, and symptoms. This dataset has been previously utilized in popular shared-tasks with documented results, establishing a baseline for our task.

Additionally, an in-depth analysis will be conducted to identify and discuss the most challenging cases each Language Model encountered during labeling tasks

## Bibliography
* Hu, Yan, Iqra Ameer, Xu Zuo, Xueqing Peng, Yujia Zhou, Zehan Li, Yiming Li, Jianfu Li, Xiaoqian Jiang, and Hua Xu. “Zero-Shot Clinical Entity Recognition Using ChatGPT.” arXiv, May 15, 2023. https://doi.org/10.48550/arXiv.2303.16416.
* Lima-López, Salvador, Eulàlia Farré-Maduell, Luis Gascó, Anastasios Nentidis, Anastasia Krithara, Georgios Katsimpras, Georgios Paliouras, and Martin Krallinger. “Overview of MedProcNER Task on Medical Procedure Detection and Entity Linking at BioASQ 2023.” In Working Notes of CLEF 2023 - Conference and Labs of the Evaluation Forum. Thessaloniki, Greece: CEUR Workshop Proceedings, 2023. https://ceur-ws.org/Vol-3497/paper-002.pdf.
* López, Salvador Lima, Luis Gascó Sánchez, Eulalia Farré, Laura Vigil Gimenez, and Martin Krallinger. “SympTEMIST Corpus: Gold Standard Annotations for Clinical Symptoms, Signs and Findings Information Extraction.” Zenodo, August 8, 2023. https://doi.org/10.5281/zenodo.8223654.
* Miranda-Escalada, Antonio, Luis Gasco, Salvador Lima-López, Eulàlia Farré-Maduell, Darryl Estrada, Anastasios Nentidis, Anastasia Krithara, Georgios Katsimpras, Georgios Paliouras, and Martin Krallinger. “Overview of DisTEMIST at BioASQ: Automatic Detection and Normalization of Diseases from Clinical Texts: Results, Methods, Evaluation and Multilingual Resources.” In Working Notes of Conference and Labs of the Evaluation (CLEF) Forum. CEUR Workshop Proceedings, 2022. https://ceur-ws.org/Vol-3180/paper-11.pdf.
* Wang, Jiaqi, Enze Shi, Sigang Yu, Zihao Wu, Chong Ma, Haixing Dai, Qiushi Yang, et al. “Prompt Engineering for Healthcare: Methodologies and Applications.” arXiv, April 28, 2023. https://doi.org/10.48550/arXiv.2304.14670.
