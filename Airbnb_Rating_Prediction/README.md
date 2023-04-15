# Airbnb Rating Prediction for Dublin


This project is for evaluating the feasibility of predicting for a listing the individual ratings for **accuracy**, **cleanliness**, **checkin**, **communication**, **location** and **value** and also
the **overall review rating**. Logistic Regression and Random Forest were trained in this project.


## Dataset
The datasets can be downloaded from [Inside Airbnb](http://insideairbnb.com/get-the-data/).  

Two datasets were used in this project. One is `listings.csv`, which includes details of Airbnb listings in Dublin. Another is `reviews.csv`, which contains timestamped comments for each listing.



## Usage

* [Part 1: Data processing]() [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()  
In this part, two csv files will be outputed for part2. One is `listings_clean.csv`, which is the cleaned data from `listings.csv`. Another is `reviews_clean.csv`, which is the cleaned data from `reviews.csv`.

* [Part 2: Training]() [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]()   
In this part, `listings_clean.csv` and `reviews_clean.csv` from Part 1 will be the inputs.

## Result
### 1. Metrics comparison
**1.1 Metrics of Dummy Classifer**  
![image](https://user-images.githubusercontent.com/98553439/232233247-82e1f830-f2c5-4bc4-a19c-34183e46214b.png)

**1.2 Metrics of Logistic Regression**  
![image](https://user-images.githubusercontent.com/98553439/232233263-63ee1ed8-c440-4ce4-9bdb-2ab5805517e0.png)

**1.3 Metrics of Random Forest**  
![image](https://user-images.githubusercontent.com/98553439/232233277-aa74bbc1-8ce0-49cf-84fb-fb69e011591d.png)

### 2. Feature importance  
![image](https://user-images.githubusercontent.com/98553439/232233410-27c2f9ee-a998-45e7-b8c6-812c7bac3dbd.png)


