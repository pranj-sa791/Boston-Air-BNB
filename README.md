# Boston-Air-BNB

## Contents

## Installation
- For execuiting the Jupyter Notebook you should have Anaconda 4.5.11 and python 3.6.6 installed. 
- The notebook will be  scikit-learn, matplotlib, numpy and pandas libraries. 
- These are available as part of Anaconda installation and don't need any additional installation.

You will need to install sentiment analysis library textblob if not already available.
> conda install -c conda-forge textblob

- Clone the repo: git clone https://github.com/pranj-sa791/Boston-Air-BNB. 
- Run the Jupyter Notebook

## Motivation
Looking at the AirBnB Boston data1 arouse curiosity to see if following questions can be convincingly answered using data analysis.

What are peak seasons?
What are hot locations?
Does number of properties in neighbourhood affect the occupancy?
## Project Structure

```text
AirBNB-Boston/
├── airbnb-boston-report.html
├── README.md
├── src/
|   └── airbnb-boston.ipynb
└── inputs/
    ├── calendar.csv
    ├──	listings.csv
    └── reviews.csv
 ```
- airbnb-boston-report.html ==> Generated report from notebook
- airbnb-boston.ipynb ==> Notebook to investigate Airbnb data for year 2016 in Boston.
- calendar.csv ==> Booking information of houses in Boston.
- listings.csv ==> Information of properties on offer in Boston.
- reviews.csv ==> User reviews for listings

## Results
- September and October show high occupancy while January and February have low occupancy
- The occupancy is around 50% for most of the remaining period.
- Alston, Mission Hill and Leather Hill have high average occupancy
- Mattapan and Roslindale have least occupancy
- Leather District has very less number of listings with high occupancy.
- Highest number of listings are in Jamaica Plain and South End.

Also a blog supports the anaysis for the project:  [Blog](https://medium.com/@pranj.sadawarte/air-bnb-boston-24de390640c0)

## References
1. https://www.kaggle.com/airbnb/boston
1. https://airbnb.com
