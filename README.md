# EcMOdel

#### Our goal is to develop a machine learning prediction algorithm for neurological injury in pediatric cardiac patients.

The biggest risk factor for Pediatric EcMo patients is stroke.  We have built a framework to statistically assess actionable events leading to stroke and improve neurological outcomes.  

## Abstract
Brain injury is a significant source of morbidity and mortality for pediatric patients treated with Extracorporeal Membrane Oxygenation (ECMO). Our objective was to utilize neural networks to predict radiographic evidence of brain injury in pediatric ECMO-supported patients and identify specific variables that can be explored for future research. Data from 174 ECMO-supported patients were collected up to 24 h prior to, and for the duration of, the ECMO course. Thirty-five variables were collected, including physiological data, markers of end-organ perfusion, acid-base homeostasis, vasoactive infusions, markers of coagulation, and ECMO-machine factors. The primary outcome was the presence of radiologic evidence of moderate to severe brain injury as established by brain CT or MRI. This information was analyzed by a neural network, and results were compared to a logistic regression model as well as clinician judgement. The neural network model was able to predict brain injury with an Area Under the Curve (AUC) of 0.76, 73% sensitivity, and 80% specificity. Logistic regression had 62% sensitivity and 61% specificity. Clinician judgment had 39% sensitivity and 69% specificity. Sequential feature group masking demonstrated a relatively greater contribution of physiological data and minor contribution of coagulation factors to the model's performance. These findings lay the foundation for further areas of research directions.

# Overview Diagram

How to use

Software Workflow Diagram

File structure diagram

Define paths, variable names, etc

Installation options:

We provide two options for installing : Docker or directly from Github.

Installing from Github

git clone https://github.com/NCBI-Hackathons/<this software>.git
Edit the configuration files as below
sh server/<this software>.sh to test
Add cron job as required (to execute .sh script)
Configuration

Examples here

Testing

We tested four different tools with . They can be found in server/tools/ .

Additional Functionality

## Full paper
Shah N, Farhat A, Tweed J, Wang Z, Lee J, McBeth R, Skinner M, Tian F, Thiagarajan R, Raman L. Neural Networks to Predict Radiographic Brain Injury in Pediatric Patients Treated with Extracorporeal Membrane Oxygenation. Journal of Clinical Medicine. 2020; 9(9):2718. https://doi.org/10.3390/jcm9092718

