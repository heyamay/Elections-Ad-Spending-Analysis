# Elections-Ad-Spending-Analysis

![Indian Political Parties Logo](https://affairscloud.com/assets/uploads/2015/09/Indian-Political-Parties-Logo.jpg)

If you are highly active on Facebook and Instagram, you must have seen ads based on elections by any of the political parties, especially BJP and INC. All the parties in India usually spend a lot of money on election campaigns. I recently collected data from Meta ads about how much money was spent on Instagram and Facebook ads by each political party during the Indian elections 2024 in each state.

## Dataset Overview
The dataset I have collected contains three files:

- The Advertisers Dataset provides insights into which pages (parties or organizations) spend money on election ads and the volume of ads they run.
- The Locations Dataset shows how much money was spent on ads in different locations, indicating where the campaigns were focusing their efforts.
- The Results Dataset provides actual voting data, showing how many people voted in each area and the percentage of voter turnout.

## Few glimpses of EDA:
### 1. Total ad spend by state:
![Total ad spend by state](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/total%20ad%20spend%20by%20state.png)
-  Uttar Pradesh has the highest ad spend, followed by Maharashtra and Odisha, indicating significant political investment in these populous states.
-  States like West Bengal, Tamil Nadu, Andhra Pradesh, and Bihar also exhibit substantial ad expenditures, reflecting their political significance.
-  Lakshadweep, Dadra & Nagar Haveli, Daman & Diu, Andaman & Nicobar Islands, and Arunachal Pradesh show the lowest ad expenditures.
-  The findings suggest that larger and more populous states tend to allocate more funds for advertisements, likely due to their larger voter base and greater political importance.

### 2. Average voter turnout by state:
![Average voter turnout by state](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/average%20voter%20turnout%20by%20state.png)
- Lakshadweep leads with the highest average voter turnout at nearly 80%, followed closely by Tripura and Assam, indicating strong voter engagement in these regions.
- States like Andhra Pradesh, Sikkim, and West Bengal also exhibit high voter participation, with turnouts exceeding 70%.
- Bihar, Uttar Pradesh, and Uttarakhand show the lowest average voter turnout, around 50-55%, highlighting regional disparities in engagement.
- The analysis reveals significant variations in voter participation, with smaller states and union territories often demonstrating higher engagement levels compared to larger states that have higher ad spend.

### 3. Top 5 parties by ad spend:
![Top 5 parties by ad spend](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/top%205%20parties%20by%20ad%20spend.png)
- The Bharatiya Janata Party (BJP) leads with the highest ad spend, accounting for 42.3% of the total expenditure, indicating a strong focus on advertising.
- This is followed by the Ama Chinha Sankha Chinha (Biju Janta Dal, Odisha) party at 24.5% and the Indian National Congress at 23.7%.
- Parties like DMK and BJP Odisha have significantly lower ad spends at 5.19% and 4.27%, respectively
- It indicates that BJP dominates in terms of ad spending on Facebook and Instagram ads, with nearly half of the total expenditure, suggesting a significant investment in advertising compared to other parties.

### 4. Ad spend and voter turnout by parliamentary constituency:
![Ad spend and voter turnout by parliamentary constituency](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/ad%20spend%20and%20voter%20turnout%20by%20parliamentary%20constituency.png)

- Higher ad spending does not necessarily correlate with higher voter turnout, indicating a complex relationship between advertising and engagement.
- Voter turnout seems to cluster between 60% and 80% across most constituencies, regardless of the ad spend amount, which ranges from 0 to 150 million INR.
- The analysis suggests that other factors, beyond ad expenditure, may significantly impact voter turnout, emphasizing the need to explore additional variables affecting electoral engagement.

### 5. Distribution of ad spending:
![Distribution of ad spending](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/distribution%20of%20ad%20spending.png)
- Most constituencies have ad spends clustered around the 50M and 100M INR marks, indicating common spending practices among many regions.
- There are fewer constituencies spending less than 10M INR or more than 150M INR, suggesting a preference for moderate ad budgets.
- The box plot indicates that the median ad spend is approximately 70M INR, with the interquartile range (IQR) spanning from about 30M to 110M INR.
- There are a few outliers, particularly a constituency with an exceptionally high ad spend above 150M INR.
- This distribution suggests that while the majority of ad spends are concentrated within a certain range, there are notable exceptions with significantly higher expenditures.

### 6. Ad spend and voter turnout by election phase
![Ad spend and voter turnout by election phase](https://github.com/heyamay/Elections-Ad-Spending-Analysis/blob/main/ad%20spending%20and%20voter%20turnout%20by%20election%20phase.png)

- There is no consistent trend between ad spend and voter turnout across different election phases
- Election phases 1 and 4 exhibit the highest ad spends, with phase 4 achieving a peak voter turnout of around 70%.
- Despite high ad spend in phase 1, voter turnout is lower at approximately 67%, highlighting that spending alone does not guarantee engagement.
- Phases with moderate ad spend (e.g., 2 and 6) have lower voter turnout, while phase 5 has a notably low turnout despite moderate spending, further emphasizing the lack of correlation between expenditure and electoral participation.

## Conclusion
- The analyses indicate that higher ad spend does not guarantee higher voter turnout, highlighting the complexity of voter engagement.
- Larger and more populous states tend to spend more on advertisements; however, this does not necessarily result in increased voter participation.
- Political parties, especially the BJP, invest heavily in advertising, but the effectiveness of this spending in driving voter turnout remains questionable.
- Voter engagement is influenced by various other factors beyond ad spend, suggesting the need for a multifaceted approach to understanding electoral participation.
