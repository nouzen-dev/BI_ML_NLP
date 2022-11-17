# About this project:

This project examined a Kaggle competition text datasets from the USMLE® Step 2 Clinical Skills examination, a medical licensure exam. Patients
belonged to different case groups. 

Their patient notes were manually annotated based on feature text (incomplete) & the goal of the competition is to develop an
automated way of identifying the features within each patient note:
- My motivation was the application of data annotation & named entity recognition (NER). 
- The project started with the identification of top feature text with missing annotation, and ultimately, a holistic view of patient notes with 
annotations, for individual patient & case group.
- I got to apply bag-of-words, performed manual data annotation, followed by devising & performing programmatic data annotation, which in turn allowed 
me to increase the size of training data from 14300 to 33518 rows, & used SpaCy. 
- A challenge I faced was the ideation of programmatic annotation. I took days on trial & error. 

A future improvement is to explore the use of unsupervised machine learning to reduce (missing annotations in the future. 

## Visualizations:
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/feature.JPG" alt="alt text" width="800"/> 
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/trigram.JPG" alt="alt text" width="800"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/case.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/case_2.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/annotate_1.JPG" alt="alt text" width="650"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/3_Data Annotation to SpaCy NER (Medical Patient Note)/images/annotate_2.JPG" alt="alt text" width="650"/>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
<img src = "https://camo.githubusercontent.com/199640f7a13aab5d8079c955d6ad55847a7350581b1e292dd4ba980d41b0dca5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d737061437926636f6c6f723d303941334435266c6f676f3d7370614379266c6f676f436f6c6f723d464646464646266c6162656c3d">
