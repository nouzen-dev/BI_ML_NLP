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


