<img src="https://img.shields.io/badge/Domain%20-Computer%20Vision-orange%20.svg" ><img src="https://img.shields.io/badge/Natural%20Language%20Processing-orange.svg">  <img src="https://img.shields.io/badge/Library Used%20-OpenCv-orange%20.svg" ><img src="https://img.shields.io/badge/Pytesseract-orange%20.svg"><img src="https://img.shields.io/badge/Spacy-orange.svg"><img src="https://img.shields.io/badge/Regular%20Expression-orange.svg">  <img src=https://img.shields.io/badge/Built%20using-Python-yellow><img src="https://img.shields.io/badge/-Html5-orange"><img src="https://img.shields.io/badge/JavaScript-blue"><img src="https://img.shields.io/badge/-Bootstrap-blueviolet">  <img src=https://img.shields.io/badge/Using%20-flask-green> 

# Any Financial Document -- Text & Data Extractor
Named entity extraction from financial documents with OpenCV, Pytesseract, Spacy (OCE + NER)
<hr>

<p align="center">
  <kbd>
  <img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/document.gif" height=250' width='700'/> </kbd> </p>

## `Development Stages`

<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/development_stage.png" height='160' width='700'/> </kbd>
</p>

## `Training Architecture -(NER Model)`

<p align="center">
   <kbd>
   <img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/training_architecture.png" height='250' width='700'/>        </kbd> 
</p>

## `Architecture`

<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/architecture.png" height='250' width='700'/> </kbd>
   
   
## `Labeling - BIO/IOB Tagging Format`
**Most chronophagous task, took around more than 10 good hours per day and some weeks** <br>
**`Learning` -- Collecting good data in Real Life is not a cakewalk **
   
<!---Image number 288.jpeg--->
<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/288.jpeg" height='250' width='700'/> </kbd> </p>

<!---Image number 288.jpeg BIO tagging data--->
<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Financial-Document-Text-Data-Extractor/blob/main/images/BIO-Tagging.png" height='650' width='400'/> </kbd>   

## `Bounding Boxes`
<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Any-Financial-Document-Data-Extractor/blob/main/images/bounding_box_img_288.png" height='350' width='700'/> </kbd>   

## `Input - Real Time`
**Eyeballing Scanned results of very common and I will say very easy input point you can get in Real Time, input can be anything in range of crazy to very crazy**
<p align="center">
   <kbd><img src="https://github.com/MvMukesh/Any-Financial-Document-Data-Extractor/blob/main/images/real_time_input.png" height='600' width='1000'/> </kbd>   

 
## `NER Prediction`
**You are observing NER Prediction on scanned results of above business card** <br>
**Finding organisation and name is still bit difficult , `clearly I have to increase business card data from 350+ cards to maybe 1000+, in parallel I need to update my approach a bot more to bit more maybe`**
<p align="center">
   <kbd>
    <img src="https://github.com/MvMukesh/Any-Financial-Document-Data-Extractor/blob/main/images/prediction-real_time_input.png" height='600' width='1000'/> 
   <img src="https://github.com/MvMukesh/Any-Financial-Document-Data-Extractor/blob/main/images/prediction_real_time_input_terminal.png" height='400' width='1000'/>
   </kbd> 


<hr>
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

<img src="https://img.shields.io/badge/Numpy-orange%20.svg" > <img src="https://img.shields.io/badge/Open%20CV-orange%20.svg" > <img src="https://img.shields.io/badge/Pytesseract-orange%20.svg" >
 

### `Python Libraries used in Natural Language Processing`
<img src="https://img.shields.io/badge/Pandas-orange%20.svg" > <img src="https://img.shields.io/badge/Spacy-orange%20.svg" > <img src="https://img.shields.io/badge/Regular%20Expression-orange%20.svg" > <img src="https://img.shields.io/badge/String-orange%20.svg" >

### `Flow to Extract Entities`
1. Location of Entity
2. Text of Corresponding Entity

### `Some more NER use-cases`
<p align="center">
   <kbd>
    <img src="https://github.com/MvMukesh/Any-Financial-Document-Data-Extractor/blob/main/images/ner_usecases.png" height='300' width='700'/> 







