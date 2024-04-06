## 5-Year Post-Implementation Analysis of the Affordable Care Act (2010) in the United States: Insights and Trends
### Introduction:
The Affordable Care Act (ACA) of 2010, also known as Obamacare, aimed to increase access to healthcare and reduce the number of uninsured individuals in the United States. 

![gavel_steth](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/de0baacd-406a-43eb-bc41-e75de6272400)

### Project Overview:
This analysis delves into the effects of the ACA over a 5-year period following its implementation, focusing on key metrics such as health coverage, Medicaid expansion, and employer-provided insurance. It examines its impact on health insurance coverage in the United States and seeks to understand trends in health coverage, including changes in the number of insured individuals, shifts in Medicaid enrolment, and variations in uninsured rates across different states.

### Data Source:
The health insurance coverage data was compiled from the US Department of Health and Human Services and the US Census Bureau. This dataset provides health insurance coverage data for each state and the nation as a whole, including variables such as the uninsured rates before and after Obamacare, estimates of individuals covered by employer and marketplace healthcare plans, and enrollment in Medicare and Medicaid programs.

### Tool:
Microsoft PowerBi

### Data Cleaning and Preparation:
1. **Remove Duplicates:** Ensured each record is unique and accurate by eliminating duplicate entries from the dataset. 
2. **Removed Bottom Row:** Excluded the row containing the total for the entire country as it does not represent individual states.
3. **Changed Data Types:** Adjusted data types to align with their respective values, converting decimals to whole numbers where appropriate for consistency and clarity.
4. **Replace Null Values:** Replaced missing values in text fields with "NA" and numerical fields with "0" to standardize the dataset and facilitate analysis.
5. **Created New Column:** Introduced a new column to replace the Medicaid Enrollment Change column. This was done to categorize and sort the instances where there were blank cells identified in the Medicaid Enrollment column for the year 2013. This column enables a more complete and accurate analysis of the data points.

![applied_steps](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/e3ef21e5-c1fb-4ec2-be4a-c48899e9b229)

### Descriptive and Exploratory Data Analysis:
Combination of descriptive and exploratory analyses to understand past trends and identify potential causal relationships between policy changes and health insurance outcomes. As well as to answer key questions such as:
How has the Affordable Care Act changed the rate of citizens with health insurance coverage?
Which states observed the greatest decline in their uninsured rate? 
Did those states expand Medicaid program coverage?

### Key Findings:

#### 🌟Increase in Health Coverage:
- Over the five years following the implementation of the ACA, approximately 20 million more individuals gained health coverage nationwide.
- By 2016, Medicare covered 56 million people, while Medicaid covered 76 million.

#### 🌟 Decline in Uninsured Rates:
- Nevada experienced the greatest decline in uninsured individuals from 2010 to 2015, with a decrease of 10.30%. Other states with significant reductions included Oregon, California, and Kentucky.

![biggest_decline](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/fdc7dad9-bdec-4816-8cf3-7b8bb9a54102)


#### 🌟 Impact of Medicaid Expansion:
- Thirty-two states expanded their Medicaid programs to cover individuals with household incomes below a certain level.
- Between 2013 and 2016, an additional 17 million people enrolled in Medicaid.
- The data suggests that Medicaid expansion played a significant role in reducing uninsured rates, with 90% of the top ten states witnessing the largest declines in uninsured rates having expanded Medicaid. Notably, Florida was the only exception among these states.

![medicaid_expansion](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/f2c39751-68e8-4f7d-82cc-c4b76a4a17ae)


#### 🌟 Employer Health Insurance Coverage:
- California led in employer-provided health insurance coverage, with approximately 20 million individuals covered.
- Texas, New York, and Florida followed with 14 million, 11 million, and 9 million individuals covered, respectively.

![highest_employer_coverage](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/b0d9547c-3bbe-4a95-b6e5-11f8a57daf37)

### Conclusion:
The ACA's impact on healthcare coverage and access has been profound, with millions of Americans gaining insurance coverage over the five years following its implementation. Medicaid expansion emerged as a significant contributor to reducing uninsured rates, highlighting the importance of policy decisions in improving healthcare accessibility. Moving forward, continued analysis and assessment of healthcare policies will be crucial in ensuring equitable access to healthcare for all individuals across the United States.

### Final Dashboard:

![aca_dashnoard2](https://github.com/Melrowze/5-Year-Post-Implementation-Analysis-of-the-Affordable-Care-Act-/assets/44920093/651965ad-7702-4530-a00e-16b999a13823)

Thank you for taking the time to explore this project. Your interest and attention are truly appreciated. Should you have any insights or recommendations, I am eager to engage and exchange ideas. Don't hesitate to reach out to me via meldeezyne@gmail or follow me on [Medium](https://medium.com/@meldeezyne). I'm excited to have a conversation and hear your perspectives.



