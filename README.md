# Analyzing Company Funding Data

## 1. Installations
This project uses Python version 3 and the following packages:
* numpy
* pandas
* matplotlib.pyplot
* sklearn.linear_model -> Ridge
* sklearn.model_selection -> train_test_split
* sklearn.metrics -> r2_score
* seaborn
* matplotlib.ticker -> FuncFormatter

## 2. Project Motivation
Having a financial industry background, I was interested in investigation start-up funding data.
Equipped with the 2014 Crunchbase data, I posed the following questions relating to US start-ups/companies:

1. Which markets are funded the most when looking at a typical company within that market?

2. What are the most important variables in predicting total funding, aside from the actual funding rounds (because these would arithmetically add up to total funding)?

3. For technology companies that were acquired, how much on average does the acquisition price exceed total funding?

## 3. File Descriptions
* Companies file contains data on which companies were funded, when and for how much.
* Acquisitions file contains data on the companies acquired and how much they were acquired for.
* Categories file contains a mapping of markets used in the Companies file onto broader market categories that I developed in order to a better understanding of funding by industry.
* Inflation data file contains years and appropriate inflation factor to adjust total funding to 2014 dollars.

## 4. How to Interact with this project
Please see the included Jupyter notebook with the project performed step by step.

## 5. Results
1. Which markets are funded the most when looking at a typical company within that market?
*Looked at the distribution of median funding by industry, finding out that technology companies are in the top 10, but far from the #1 spot, which is taken by Science & Engineering & Electronics.*

2. What are the most important variables in predicting total funding, aside from the actual funding rounds (because these would arithmetically add up to total funding)?
*Examined important factors in predicting total funding, learning that the city of the start-up or company plays an important role.*

3. For technology companies that were acquired, how much on average does the acquisition price exceed total funding?
*Obtained an average multiple for the number of times that acquisition price exceeds total funding for tech companies, which is 12 to 31.*

## 6. Licensing, Authors, Acknowledgements, etc.
The data used for this project originally comes from the Crunchbase website - a platform with business information about private and public companies. I personally downloaded the data from Tableau public. The Excel data file indicates that data was extracted from Crunchbase on Dec 2, 2014. From the Excel file, I utilized the 'Companies' and 'Acquisitions' tabs.
