<img src="https://img.shields.io/badge/Domain%20-Computer%20Vision-orange%20.svg" ><img src="https://img.shields.io/badge/Natural%20Language%20Processing-orange.svg">  <img src="https://img.shields.io/badge/Library Used%20-OpenCv-orange%20.svg" ><img src="https://img.shields.io/badge/Pytesseract-orange%20.svg"><img src="https://img.shields.io/badge/Spacy-orange.svg"><img src="https://img.shields.io/badge/Regular%20Expression-orange.svg">  <img src=https://img.shields.io/badge/Built%20using-Python-yellow><img src="https://img.shields.io/badge/-Html5-orange"><img src="https://img.shields.io/badge/JavaScript-blue"><img src="https://img.shields.io/badge/-Bootstrap-blueviolet">  <img src="https://img.shields.io/badge/Using%20-flask-green"> 

# Any Financial Document -- Text & Data Extractor
Named entity extraction from financial documents with OpenCV, Pytesseract, Spacy (OCR + NER)
<hr> </hr>


<p align="center">
  <kbd><img src="https://user-images.githubusercontent.com/26667491/221348114-87651e73-19f7-4d65-9080-0cfda72e0246.gif" height=300' width='600'> </kbd>
</p>


## `Development Stages`

<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348226-dda61630-5d3c-4baa-a3db-ec042ff2be5b.png" height='160' width='700' tag="development_stage.png"/> </kbd>
</p>


## `Training Architecture -(NER Model)`

<p align="center">
   <kbd>
   <img src="https://user-images.githubusercontent.com/26667491/221348294-f6519191-7552-4092-8ca5-2a84557a95aa.png" height='250' width='700' tag="training_architecture.png"/></kbd> </p>


## `Architecture`

<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348355-23e84cda-4b7a-4f37-9663-8c1512820dbd.png" height='250' width='700' tag="architecture.png"/> </kbd></p>
   

## `Text Detection WorkFlow`
                                                                                                                                                
<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348429-f128ca30-0688-4fd6-91e4-a07654a51ffd.png" height='150' width='700' tag="text_detection_worflow.png"/> </kbd> </p>

<h3> Image Preprocessing (Suppressing unwanted distortions, Enhancing important Image Features)</h3>
1. Binarization 
2. Rescaling
3. Dilation
<h3> Image Segmentation (breaking image based on)</h3>
1. Single Character
2. Word
3. Line


## `Labeling - BIO/IOB Tagging Format`
**Most chronophagous task, took around more than 10 good hours per day and some weeks** <br>
**`Learning` -- Collecting good data in Real Life is not a cakewalk**
   
<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348550-adb91438-e257-443c-906f-d9695956bb6c.jpeg" height='300' width='700' tag="card-sample.jpeg"/> </kbd> </p>

<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348653-c0d73580-55dc-4993-9ac6-6538337ead9a.png" height='650' width='400' tag="BIO-Tagging_example.png"/> </kbd>   


## `Bounding Boxes`
<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221348696-89e3df24-d740-455e-b5ed-1176e6fb28bd.png" height='350' width='750' tag="bounding_boxes_on_image"/> </kbd> 

## `Input - Real Time`
**Eyeballing Scanned results of very common and easy input point you can get in Real Time, input can be anything in range of crazy to very crazy**
<p align="center">
   <kbd><img src="https://user-images.githubusercontent.com/26667491/221350617-62eded9c-c792-47dd-b542-27a7fd77c58f.png" height='600' width='1000' tag="real_time_input"/> </kbd>   


## `NER Prediction`
**You are observing NER Prediction on scanned results of above business card** <br>
**Finding organisation and name is still bit difficult , `clearly I have to increase business card data from 3000+ cards to maybe 10000+, in parallel I need to update my approach a bot more to bit more maybe`**
<p align="center">
   <kbd>
    <img src="https://user-images.githubusercontent.com/26667491/221351756-0955c9c2-fd18-41e2-af85-ee73b322f45e.png" height='350' width='1000' tag='box_prediction_real_time_input'/>
      
   <img src="https://user-images.githubusercontent.com/26667491/221350809-ca7fe8bf-1917-4972-adeb-fef5f62e04c8.png" height='350' width='1000' tag="prediction_real_time_input_terminal"/>
   </kbd> </p>


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
    <img src="https://user-images.githubusercontent.com/26667491/221350877-d50374d8-f713-496c-a51e-af58d0f46b96.png" height='300' width='700' tag='ner_usecases'/> 
</p>


### `Improvements:`
1. I am using Spacy NER model, which is a `BERT architecture` i.e. I have to provide more data to this model to see performance improvement
2. I can also improve `Data Preparation Framework`
3. I am using PyTesseract(google) to extract text, it have some limitations like:
4. Image resolution must be atlest `200 dpi` or width & height must be atlest `300 pixels`
  1. Text must not be Rotated or Skewed
  2. Text must not be having some effets applied on it
  3. Text must not be blured
  4. Text must not be cursive handwriting
                                                                                                                                           
### `Refrences`
* [Skew Detection and Correction of Document images using Hough Transform](https://muthu.co/skew-detection-and-correction-of-document-images-using-hough-transform/)
* [Skew Detection and Correction of Devanagari Script Using Hough Transform](https://www.researchgate.net/publication/274142211_Skew_Detection_and_Correction_of_Devanagari_Script_Using_Hough_Transform)

### `What Next`
* [Understanding this](https://dropbox.tech/machine-learning/creating-a-modern-ocr-pipeline-using-computer-vision-and-deep-learning)
