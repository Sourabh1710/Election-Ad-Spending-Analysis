# Elections Ad Spending Analysis

## Dataset Overview
I have collected a dataset containing three files:

1. **Advertisers Dataset** - Provides insights into which pages (parties or organizations) spend money on election ads and the volume of ads they run.
2. **Locations Dataset** - Shows how much money was spent on ads in different locations, indicating where the campaigns were focusing their efforts.
3. **Results Dataset** - Provides actual voting data, showing how many people voted in each area and the percentage of voter turnout.

## Elections Ad Spending Analysis with Python

### Importing the Dataset and Necessary Libraries
I started by importing the dataset and the required Python libraries.

The **Results Dataset** has a column named `state`, and the **Locations Dataset** has a column named `location name`. I merged these datasets using these columns to analyze the relationship between ad spending and election results.

### Total Ad Spend by State
The bar graph below shows the total ad spend (in INR) by state.

![Total Ad Spend by State](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Total%20Ad%20Spend%20by%20State.png)

- **Uttar Pradesh** leads significantly with the highest ad spend, followed by **Maharashtra** and **Odisha**.
- Other states with substantial ad expenditures include **West Bengal, Tamil Nadu, Andhra Pradesh, and Bihar**.
- States with the lowest ad spend include **Lakshadweep, Dadra & Nagar Haveli, Daman & Diu, Andaman & Nicobar Islands, and Arunachal Pradesh**.
- Larger and more populous states tend to spend more on ads, likely reflecting their greater political significance and larger voter base.

### Average Voter Turnout by State
The bar graph below shows the average voter turnout by state.

![Average Voter Turnout by State](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Average%20Voter%20Turnout%20by%20State.png)

- **Lakshadweep** has the highest average voter turnout at nearly **80%**, followed by **Tripura and Assam**.
- States like **Andhra Pradesh, Sikkim, and West Bengal** also show high voter engagement with turnouts above **70%**.
- On the lower end, states such as **Bihar, Uttar Pradesh, and Uttarakhand** have the lowest average voter turnout, around **50-55%**.
- This analysis highlights significant regional variations in voter participation.

### Top 5 Parties by Ad Spend
The bar graph below displays the top 5 political parties by ad spend.

![Top 5 Parties by Ad Spend](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Top%205%20Parties%20by%20Ad%20Spend.png)

- **Bharatiya Janata Party (BJP)** has the highest ad spend, accounting for **42.3%** of the total.
- Followed by **Ama Chinha Sankha Chinha** (24.5%) and **Indian National Congress** (23.7%).
- **Ellorum Nammudan** and **BJP Odisha** have significantly lower ad spends at **5.19%** and **4.27%**, respectively.
- This indicates that **BJP dominates in terms of ad spending on Facebook and Instagram ads**, with nearly half of the total expenditure.

### Correlation Between Ad Spend and Voter Turnout
The correlation matrix shows the relationship between ad spend and voter turnout.

- The correlation coefficient is **-0.010688**, indicating a **very weak and slightly negative relationship**.
- This means that increasing ad spend does **not significantly** affect voter turnout.

### Relationship Between Ad Spend and Voter Turnout by Parliamentary Constituency

![Ad Spend vs Voter Turnout by Constituency](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Ad%20Spend%20and%20Voter%20Turnout%20by%20Parliamentary%20Constitutency.png)

- Higher ad spending does **not necessarily correlate** with higher voter turnout.
- Most constituencies show voter turnout clustering between **60% and 80%**, regardless of ad spend.
- This suggests that **other factors besides ad spend** play a significant role in influencing voter turnout.

### Distribution of Ad Spending

![Distribution of Ad Spending](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Distribution%20of%20Ad%20Spend.png)

- The histogram shows that **most constituencies have ad spends around 50M and 100M INR**.
- Fewer constituencies spend **less than 10M INR or more than 150M INR**.
- The **box plot** shows that the median ad spend is **around 70M INR**, with an **interquartile range (IQR) spanning from 30M to 110M INR**.
- There are **a few outliers** with exceptionally high ad spends above **150M INR**.

### Ad Spending and Voter Turnout by Election Phase

![Ad Spend vs Voter Turnout by Election Phase](https://github.com/Sourabh1710/Election-Ad-Spending-Analysis/blob/main/images/Ad%20Spend%20and%20Voter%20Turnout%20by%20Election%20Phase.png)

- **Election phases 1 and 4** had the highest ad spends.
- **Phase 4** saw the highest voter turnout at around **70%**, whereas **Phase 1**, despite high spending, had a lower turnout of **67%**.
- **Phase 5** had notably **low turnout despite moderate spending**.
- This suggests that **ad spend alone does not drive voter turnout**, and **other factors influence voter engagement**.

## Conclusion

- **Higher ad spend does not guarantee higher voter turnout**.
- Larger and more significant states tend to spend more on ads, but this does **not necessarily translate** to higher voter participation.
- **BJP dominates in ad spending**, yet the effectiveness of this spending in increasing voter turnout remains **questionable**.
- Voter engagement is influenced by **multiple factors beyond ad spend**, making it a complex issue.

## Author
Sourabh Sonker 
Data Scientist

