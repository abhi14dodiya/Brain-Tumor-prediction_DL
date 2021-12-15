# Brain-Tumor-prediction_DL
Brain tumor prediction using deep learning 

This is a sample project of brain tumor prediction using deep learning where we are predicting brain tumor from given dataset.
sample and model link: https://drive.google.com/drive/folders/1OyRCHp2nzk-gsDQff5E9K82dRZVYjXFO?usp=sharing
model: https://drive.google.com/file/d/1E_D6oTFPKs74oEcDbgCjos8BtYdzx3S0/view?usp=sharing

## Aproach 
-First we imported all necessary library from tensoreflow and keras <br>
-Then we call our dataset and distribute in train,test and val folder (a<br>ll contain sub folder yes and no ) <br>
-After distribution we generate data from image data generator<br><br>
-Then we we made model and feed to model <br><br>
-Test on test data.<br>

## Transfer leraning
-using transfer learning we can get more accuracy and better result.<br>
-Here we got less result in our scratch model so we call Mobilenet(Transfer learning model) and got accuracy around 97%<br>
-Mobilenet is model which is trained over million images and it has  got weights on each layer by million images. now what we do is we just remove first and last layer and our own layer in it according to our perpouse.<br>

## how to run this file  
- Clone the project <br>
- download dependancies like tensoreflow,keras,sklearn etc  in python/ cmd prompt using -- pip install <name of library> <br>
- Run in conda or python IDE<br>
