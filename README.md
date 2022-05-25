<h2> <align="center">Melanoma Classification Using Deep Convolutional Neural Network with Dermoscopic Images</h1>
<p align="center"><img src="https://thumbs.dreamstime.com/z/ai-artificial-inte…elligence-modern-medical-technology-132056548.jpg" width="500" height="400"></p>


## Host organization:
* <a href="https://github.com/becodeorg"><strong>BeCode</strong></a>(Ghent campus)
<p align="center"><img src="https://becode.org/app/uploads/2021/06/logo-becode.png" alt="Logo" width="200" height="200"></p>
  
## Project Pipeline:
* <a><strong>Pipeline for Deploying Deep Learning(Convolutional Neural Networks)</strong></a>
<p align="center"><img src="https://media.springernature.com/lw685/springer-st…9865-y/MediaObjects/10462_2020_9865_Fig1_HTML.png
" alt="Logo" width="600" height="300"></p>

# Project Overview

- Repository: `Skin Cancer detention`
- Type of Challenge: `Learning`
- Duration: `8 days`
- Deadline: `24/05/2022 4:30` **(code)**`
- Presentation: `25/05/2022 1:30 PM`
- Team challenge : 'Solo project'
- Developer : [`Moshood Owolabi`](https://www.linkedin.com/in/moshood-owolabi)
- Level: `Junior Developer`
- Organization: `Becode  AI Bootcamp`


## Learning objectives

At the end of this challenge, you should :

- Be able to apply a CNN in a real context
- Be able to preprocess data for computer vision
- Be able to evaluate your model (split dataset, confusion matrix, hyper-parameter tuning, etc)
- Be able to visualize your model results and evaluations (properly labeled, titled...)
- Be able to deploy your solution in an simple APP locally or on Heroku

## The Mission

The health care company "skinCare" hires you as a freelance data scientist for a short mission.
Seeing that they pay you an incredible amount of money you accept. Here is the mail you receive:

```text
from: sales.skincare.be@gmail.com
to:   projects@becode.org

Hi,

At skinCare we have more and more demands from companies for a tool that would be able to detect moles that need to be handled by doctors.

Your mission, if you accept it, would be to create an AI that can detect when the mole is dangerous. To be able to use your AI, we want you to create a simple web page where the user could upload a picture of the mole and see the result.

We don't have a web development department in our company, so you will need to handle the UI as well, we don't care about having something amazing on the design side, we just want a proof of concept to show our client that the product has potential. You are free in the technology you want to use.

You will also need to put your application on the internet so we can use it. I guess you know what that means.

You will find attached to this email the data you need.

If you have any questions, feel free to reply to this mail or send a mail to our department at the following email address: sales.skincare.be@gmail.com

Good luck,
skinCare sales team
```
### Input

The dataset provided by the client can be found here: https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000

Possible disease states are "Melanoma", "Melanocytic nevus", "Basal cell carcinoma", "Actinic keratosis / Bowen’s disease (intraepithelial carcinoma)", "Benign keratosis (solar lentigo / seborrheic keratosis / lichen planus-like keratosis)", "Dermatofibroma", and "Vascular lesion". Approximately 10,000 images provided for training, 200 for validation, 1500 for test.

## Model
<p align="center"><img src="asset\model.JPG" alt="Logo" width="400" height="400"></p>

## Result
### Loss/Accuracy vs Epoch
<p align="center"><img src="asset\Loss.JPG" alt="Logo" width="400" height="400"></p>

### Model Accuracy
<p align="center"><img src="asset\Accuracy.JPG" alt="Logo" width="400" height="400"></p>

## Repo Architecture 

```
│   README.md                     : This file
│   asset                         : image
│   Preprocessing.ipynb           : conatins cleaning_data.py. 
|   api.py                        : contains prediction.py.
|   template                      : contains index.html.
|   static                        : contains style.css.
|   api.py                        : Script used to create a Flask App.
|   requirements.txt              : Libraries needed to runs this App.
|   model.h5                      : model generated after running CNN
|___  
|    template
│   | index.html                  : Script used to get users input for the prediction.
|___
|   static
│   │ style.css                   : Script used for styling the App webpage.          
```




## Used Language and Libraries:
Python libraries:
* Jupyter Notebook
* Numpy
* Pandas
* Scikit-image
* Matplotlib
* Scikit-learn
* Keras

GitHub

Heroku

## Installation & Usage
To run execute below commands

      clone the repository. 
      Run Preprocessing : "model will be generated"
      Run api.py.
      Select the image you want to make prediction on.
      Prediction apprear.

#### Importance
Absolutely, under NO circumstance, should one ever screen patients using computer vision software trained with this code (or any home made software for that matter). 