**Description of variables in the dataset:**

```Pregnancies:``` Number of times pregnant

```Glucose:``` Plasma glucose concentration a 2 hours in an oral glucose tolerance test

```BloodPressure:``` Diastolic blood pressure (mm Hg)

```SkinThickness:```Triceps skin fold thickness (mm)

```Insulin:``` 2-Hour serum insulin (mu U/ml)

```BMI:``` Body mass index (weight in kg/(height in m)²)

```DiabetesPedigreeFunction:``` Diabetes pedigree function

```Age:``` Age (years)

```Outcome:``` Class variable (0 or 1)

**Diabetes-Prediction directory tree**

```
├─ app.py
├─ demo.gif
├─ downloads
│  └─ prediction.csv
├─ LICENSE
├─ models
│  ├─ model.py
│  ├─ my_model.pkl
│  ├─ predict.py
│  └─ transformer.pkl
├─ procfile
├─ README.md
├─ requirements.txt
├─ src
│  └─ diabetes.csv
├─ static
│  └─ css
│     ├─ grid.css
│     ├─ images
│     │  └─ dia.jpeg
│     └─ style.css
├─ templates
│  └─ index.html
└─ uploads
   └─ test.csv

```

```app.py``` : Front and back end portion of the web application

```downloads``` : conatains predcited csv file(based on uploaded file)

```models```  : contains model for prediction

```requirements.txt``` : required library 

```src```  : conatins raw data file 

```static``` : contains static file (css, img) for UI

```templates``` : contains templates for UI

```uploads``` : uploded csv file will store  here  after that it will used for prediction(added test file for sample)


## Installation

* Clone this repository and unzip it.

* create new env with python 3 and activate it .

* Install the required packages using pip install -r requirements.txt

* Execute the command: python app.py

* Open ```http://127.0.0.1:5000/``` in your browser.

