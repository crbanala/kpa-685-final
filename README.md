# Key point Analysis: Improvement with better Candidate Extraction



## Index of main Models
------




## Folder Structure
------

- Data Preprocessing
  - Contains code used to process the yelp dataset to "Restaurant reviews and 

- Quality Model
   - Contains code for Quality model

- Matching Model
  - Contains code for Matching model

- Summarization Models
  - Contains code used for generating summaries of reviews with T5,BART and Pegasus models.
  - Pegasus-FineTuned
    - Code for dataset preparation and Pegasus Finetuning on IBM's ArgKP dataset and saving a checkpoint
  - Without Finetuning
    - Code for generating sample summaries from reviews using T5, BART and pegasus on Restaurant and Hotel reviews.


- checkpoints


## Datasets
------

Yelp pre processed 1M - https://drive.google.com/file/d/1jI9-1SubKmqfcdnmv0EAVFMTCIDN_Jyj/view?usp=sharing

Yelp restaurants from 1M - 
https://drive.google.com/file/d/1sj4calRVHF3d_pIRti40EULdV732_2Kc/view?usp=sharing

Yelp hotels from 1M - 
https://drive.google.com/file/d/1-4WFDqdZsWJP17uoTSWjeapzT_mrW1r3/view?usp=sharing


Yelp restaurants business ids - 
https://drive.google.com/file/d/1-HU7aTN2p6KmVOrzcnjOrqJJ9ghY8SwC/view?usp=sharing

Yelp Hotels business ids - 
https://drive.google.com/file/d/1jM-z6_MyWHOgI52WN9_estRpydmYB9ka/view?usp=sharing



Project_PreProcessing.ipynb - 
https://colab.research.google.com/drive/1JCCMY_qLA3JxbOwG1mIUDPyz8_U_d3rg?usp=sharing

Project_keyPointsGeneration.ipynb -
https://colab.research.google.com/drive/1k4kCQTyQDQIPfZPwRTcrmnDpB3Aw0aEh?usp=sharing


## Model Checkpoints
------
Pegasus - ArgKP : https://drive.google.com/drive/folders/1ZiJL0qEvz2kvCWfpNKkF6Ngr1Ev-eFbG?usp=sharing

Roberta-yelp-sentiment : https://drive.google.com/drive/folders/1S_VcYdlT7gX7QSHYaCxg-h7gYI7CLpcg?usp=sharing

Matching - ArgKp : https://drive.google.com/drive/folders/1owcAZoOhV-AxLNpFHt5pdW-wZUzAPYdk?usp=sharing

Quality - Arg30K : https://drive.google.com/drive/folders/1owcAZoOhV-AxLNpFHt5pdW-wZUzAPYdk?usp=sharing
