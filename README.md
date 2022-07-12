# Any Financial Document Text & Data Extractor
Named entity extraction from financial documents with OpenCV, Pytesseract, Spacy (OCE + NER)
<hr>

## `Architecture`

<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/architecture.png" height='250' width='700'/> </kbd>
   
## `Training Architecture`

<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/training_architecture.png" height='250' width='700'/> </kbd>

## `Development Stages`

<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/development_stage.png" height='140' width='700'/> </kbd>
   
## `BIO Tagging`
Most time consuming task, took around more than 10 good hours
   
<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/BIO-Tagging.png"/> </kbd>   

<hr>

### `Problem Statement`
Develop customized Named Entity Recognizer to extract entities from scanned documents images like:
1. Invoice
2. Business Card [my focus] || Extract Entities like: Name, Phone, Email, Organisation and Website link 
3. Shipping Bill etc

### `Technologies used`
 
 1. Compute Vision modules were used to:
    1. scan document
    2. identify location of text
    3. extract text from image

 2. Natural Language Processing used to 
    1. extract entitles from text
    2. text cleaning
    3. parsing entities form text
    
### `Python Libraries used in Computer Vision Module`

1. Numpy
2. OpenCV
3. Pytesseract

### `Python Libraries used in Natural Language Processing`
1. Pandas
2. Spacy
3. Regular Expression
4. String

### `Flow to Extract Entities`
1. Location of Entity
2. Text of Corresponding Entity






