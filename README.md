# Group #6 Project 2 MIST4610
Chemicals in California 
Tableau Analysis

# Team Members:
1. Alexandra DiClemente, @akd27602
2. Chris Johnson, @cjohns417
3. Mckenna Isenberg, @mckennaisen
4. Kennedy Johnson, @kennedyrjohnson
5. Charlie Matthews, @2004matthews

# Dataset Description:
We have obtained our database from the US Data gov website at https://catalog.data.gov/dataset. 

The California Safe Cosmetics Program (CSCP), under the California Department of Public Health (CDPH), collects data on products sold in California that contain ingredients linked to cancer, birth defects, or reproductive harm. Companies with over $1M in annual sales and operating since 2007 must report products with these chemicals. The data is aimed to help consumers make informed decisions about the products they use or are considering purchasing. Also, regulatory agencies may use this data to analyze trends in company's use of chemicals in cosmetics, monitoring a company's compliance with the Safe Cosmetics Act overtime.

The dataset includes product labels, brands, manufacturers, categories, reported chemical ingredients (with CAS#), the number of chemicals per product, and dates of reporting or reformulation. It aims to inform the public about potentially hazardous cosmetics but may lack full coverage due to underreporting by companies. 

Our database showcases chemicals in cosmetics primarily. It shows the specific product name, company name (Ex- Glover’s medicated Shampoo made by J. Strickland & Co.)
, product category (Ex- Hair Care products), chemical used (Ex- Distillates (coal tar)), and chemical count based on a scale from 0-2 (Ex-2)). Additionally, it provides the initial date imported and most recent dated (Ex-7/1/2009, 7/1/2009).

The data dimensions consists of rows and columns. There are records for individual cosmetic/personal care products, where each row represents a single product or a product formulation. There are multiple columns in the dataset, each containing many attributes of each product.


![Screenshot 2024-11-22 125937](https://github.com/user-attachments/assets/e025501d-ad77-4844-b72c-62051b11aec5)


![Screenshot 2024-11-22 130006](https://github.com/user-attachments/assets/8d6f03ed-ff5a-414b-b7b1-9747371ff9fa)


![Screenshot 2024-11-22 130024](https://github.com/user-attachments/assets/9461c6fd-e7ac-4e7d-b310-d13f229972be)


![Screenshot 2024-11-22 130041](https://github.com/user-attachments/assets/7317de86-832c-4cb4-970a-947a9ac594bc)



# Analysis Question #1:
Which companies have the highest number of products containing carcinogenic ingredients with a rating of at least 1A? 
 - A rating of at least 1A  refers to the classification of carcinogenic ingredients. 1A is considered known to have carcinogenic potential for humans, based on evidence from human studies, meaning there is sufficient data to conclude it causes cancer in people.
 - By filtering products by CAS number, we can see products with carcinogenic ingredients rated 1A or higher.
 - The goal is to rank companies based on the number of products containing carcinogens.

Here we will also analyze the carginogenic chemical distribution across product categories and companies...
 - Certain product categories might contain a higher amount of carcinogenic ingredients, identifying trends in product formulations across different areas of the cosmetic industry.
   
Analyze chemical ingredient counts overtime...
 - Showing the ingredient counts overtime will show whether companies have been increasing/decreasing their use of carcinogenic ingredients in their formulations to attract consumers.
 - We can observe trends in initial reporting dates and chemical dislosure counts over time. 

Importance: 
- Public Health: Identifies areas for improved safety regulations and transparency.
- Economic Impact: Helps consumers make informed purchasing decisions, affecting company sales and trust. 
- Cultural Relevance: Protects groups relying heavily on cosmetics in daily life or traditions. Protects groups that need to use these products everyday for work.
  
# Analysis Question #2:
Which companies have the most products reported with discontinued chemicals?
- This will help identify companies that may be trying to limit certain ingredients from their forumulas or have products that contain chemicals no longer available.
- Capture the products and chemicals that are associated with these discontinued ingredients.
  
Here we can analyze product and chemical discontinuations overtime...
- Track the trend of product and chemical discontinuations overtime to see if there is a an increase or decrease in the use chemicals that have been discontinued.
- This can show if certain years saw a significant discontinuations of chemicals, possibly due to regulatory changes or pressure from consumers in the marketplace.
  
Analyze the correlation between product and chemical discontinuation...
- We can observe the relationship between when products were discontinued and when the chemicals in those products were discontinued.
- Do products tend to be discontinued after the chemicals are phased out?

Importance:
- Public Health and Safety: Identifies companies historically linked to products containing harmful chemicals, even if they are now discontinued. This can inform ongoing regulatory scrutiny and public awareness.
- Regulatory Compliance: Demonstrates whether companies are actively addressing safety concerns and adapting to regulations.
- Consumer Trust: Highlights accountability and the extent to which companies are committed to improving product safety, influencing customer perceptions and loyalty.
- Economic Impact: Companies with numerous discontinued chemicals might face reputational risks, affecting market value and sales.

# Database Manipulations:

# Analysis and Results: 

# Tableau Packaged Workbook:
