# 2020-37-N-HS4-01542
The research was supported by the National Science Centre, Poland, under the research project 
"Exploring social and information networks of Polish management sciences methodology scholars" [grant number 2020/37/N/HS4/01542].

# Dataset descriptions
## citation_sequences_polish.xml
This is a dataset to train citation parser. It was tagged in compliance with AnyStyle way.
AnyStyle's model performed poorly on references in Polish language, as national citing style standards 
(especially in printed books) differ from globally accepted like APA.
Default model (ver. 1.3.6) had an error rate of 68.59 per sequence and 19.43% per tokens. 
Model trained on this dataset achieved 9.95 sequence error and 2.41% tokens error. 
It allowed for the creation of bibliographic dataset to study information and social networks of polish methodology scholars, 
with an accuracy of 93.72% for the unique identifier (author - date - title).

## polish_methodology_scholars_dataset.csv
This file will appear alongside publication. Stay tuned!
This is a dataset to explorw social and information networks of Polish management sciences methodology scholars.
Abstracts were removed for copyright puropses.
