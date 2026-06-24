# Row-Health-Marketing-Dashboard---Summary

# The goal of this project is to build a dashboard that allows the Row Health team to track the performance of marketing campaign categories launched in 2019, in order to support decision-making around customer signups and brand awareness ahead of quarterly business reviews.

**Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. Their customers can sign up for 4 different plans - bronze, silver, gold, and platinum - each with different premiums and claim coverage rates.

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims. The budget is allocated to drive two primary objectives: 1) to increase the number of customer signups, and 2) to raise awareness of Row Health's brand across the country.

# Data Structure
The dataset consisted of three tables, including information about campaigns, signups, and user demographics, as well as claims filed by customers and related claim information.

<img width="612" alt="image" src="https://github.com/user-attachments/assets/22f0cdbe-1bd0-4108-9106-0eaee8f853d8" />

# Insights Summary
**In order to evaluate campaign performance, we focused on the following key metrics:**
  * **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
  * **Cost per Signup:** The average dollars spend in order to acquire a signup from each campaign.
  * **Click through Rate:** The percent of people who see a campaign and click on the associated link.

## Signup Rate
  * #CoverageMatters drove the most signups (**3,536**) at a **4.76%** signup rate.
  * Categories like Benefit Updates lagged well behind, with only **45** signups and a 0.08% signup rate.
  * Overall signup rates across all campaign was **1.92%**. 
## Cost per Signup
  * Average cost per signup across all campaigns was $3.68.
  * Health For All had a notably low CPC (**$0.10**), which likely contributes to efficient signup costs for that category.
  * Golden Years Security stood out with a much higher CTR relative to other metrics, which is worth a closer look in case it's driving up acquisition cost in that category.
## Click through Rate
  * Health For All had the highest CTR by far at **25.48%**, despite relatively low impressions (**170,559**).
  * Summer Wellness Tips also performed well, with an **18.09%** CTR.
  * Family Coverage Plan had the highest impressions (**1,106,540**) of any category, but its CTR did not stand out by comparison - a gap worth investigating further.

# Recommendations
* **Health For All**: This category shows a strong CTR and low cost per click relative to others, supporting the signup growth objective efficiently. Worth considering for continued or increased investment.
* **Family Coverage Plan**: High impressions but comparatively low engagement suggest this category may be contributing more to brand awareness than to signups. Worth investigating whether this reflects audience type or a campaign issue.
* **Golden Years Security**: The CTR spike here doesn't align with the category's other metrics. Recommend flagging for review before drawing further conclusions.

# Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/app/profile/nicholas.licari/viz/Book1_17780326213190/Dashboard1). This dashboard enables users to filter by plan, campaign type, and state, and focuses on trends and values in marketing metrics, signup metrics, and claim metrics.

<img width="812" alt="rowhealth_dashboard" src="https://github.com/user-attachments/assets/e7f3598e-c72a-4801-8a72-632b5464e3b3" />
