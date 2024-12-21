# SpeechRecognition_Project
Developing a speech recognition model to identify emotions in speech using the RAVDESS and CREMA-D datasets. Combines feature extraction techniques with a dense neural network for accurate emotion classification.

## EXECUTIVE SUMMARY:

- The swift and precise identification of emotions enhances the effectiveness of interpersonal interactions. Leveraging machine learning, we developed a dense neural network model that achieves accuracy comparable to the top quartile of human reviewers. Emotion classification based on audio remains a challenging task. Although statistical analyses of extracted features indicate distinct population means for different emotions, visualizing the distributions reveals significant overlap among all emotions, rendering individual measures minimally predictive.

- Using the RAVDESS and CREMA-D datasets, this study analyzes over 8,000 short audio clips performed by more than 100 actors portraying emotions such as happiness, sadness, fear, disgust, anger, and a neutral state. Both datasets were created by government-funded research teams affiliated with leading universities.

## CONTENTS:
This project consists of the jupyter notebooks and several folders.

[**Part_1-Understanding_audio_data**](SER_Part_1-Understanding_audio_data.ipynb)
- This notebook uses the audio5.yml environment to explore what sound 
 is, how it is stored digitally and how it can be visualized.

 ### DATA:
This project uses two datasets:

**RAVDESS:** The Ryerson Audio-Visual Database of Emotional Speech and Song
- Use citation, academic paper and file download:
  https://zenodo.org/record/1188976


**CREMA_D:** Crowd-sourced Emotional Multimodal Actors Dataset
- Use citation: Cao H, Cooper DG, Keutmann MK, Gur RC, Nenkova A, Verma R.
 CREMA-D: Crowd-sourced Emotional Multimodal Actors Dataset. IEEE Trans Affect
 Comput. 2014 Oct-Dec;5(4):377-390. doi: 10.1109/TAFFC.2014.2336244.
 PMID: 25653738; PMCID: PMC4313618.
- Academic paper: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4313618/
- Data download: https://github.com/CheyneyComputerScience/CREMA-D