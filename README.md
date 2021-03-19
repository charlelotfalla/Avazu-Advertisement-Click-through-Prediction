
<h3 align="center">Avazu Advertisement Click-through Prediction</h3>

  <p align="center">
    <br />
    <a href="https://github.com/charlelotfalla/Avazu-Advertisement-Click-through-Prediction"><strong>Explore the docs »</strong></a>
  </p>
</p>

<br />

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#data">Data</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The purpose of the project is to evaluate the performance of different algorithms (Decision Trees, Bagged Trees, Random Forests & Gradient Boosting Tree) on prediction advertisement click-through based on Avazu dataset. 

First, a random sample of 100,000 is selected for the original dataset. Basic exploratory data analysis was performed on the variables for the purpose of cleaning and excluding unnecessary and ID variables from the train and test samples. The majority class was also undersampled as there was a huge imbalance between the majority & minority classes.

The four algorithms mentioned above were run on an 80-20 train-test split data. Recall was used to evaluate the performance of the algorithms. A grid search was then used for the hyperparameter tuning for the random forest.

### Data

Source: [Avazu Click-through Rate Prediction Data](https://www.kaggle.com/c/avazu-ctr-prediction/data) <br />
Copyright: Avazu <br />
Data Fields: <br />
id: ad identifier <br />
click: 0/1 for non-click/click <br />
hour: format is YYMMDDHH <br />
C1 -- anonymized categorical variable <br />
banner_pos <br />
site_id <br />
site_domain <br />
site_category <br />
app_id <br />
app_domain <br />
app_category <br />
device_id <br />
device_ip <br />
device_model <br />
device_type <br />
device_conn_type <br />
C14-C21 -- anonymized categorical variables <br />

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.


### Prerequisites

Any python IDE or Code Editor (Spyder, Jupyter Notebook, Sublime text 3, ... etc).


### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/charlelotfalla/Avazu-Advertisement-Click-through-Prediction.git
   ```
2. Install Python packages
   ```sh
   pip install sklearn gzip seaborn random imblearn
   ```
<br />

<!-- CONTACT -->
## Contact

Twitter: [@charle_lotfalla](https://twitter.com/charle_lotfalla)  <br />
Email: charlelotfalla@gmail.com





  


  
