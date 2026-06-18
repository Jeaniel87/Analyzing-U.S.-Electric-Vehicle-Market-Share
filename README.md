# Analyzing-U.S.-Electric-Vehicle-Market-Share

This project focuses on understanding the growth and distribution of electric vehicles across the United States. The dataset contains vehicle registration counts for multiple fuel types (EV, PHEV, HEV, gasoline, diesel, etc.) by state. 
Our goal is to uncover where EV adoption is happening fastest, how EVs compare to traditional fuels, and what insights can be drawn for policymakers and automakers

**Question to answer**

- What percentage of vehicles in each state are EVs, PHEVs, HEVs, and gasoline?
- Which alternative fuels (biodiesel, ethanol, hydrogen) are significant vs. niche?
- Where should policymakers prioritize EV infrastructure investment based on adoption trends and gaps in support?

**Tools used**
  - Pandas for data cleaning and analysis
  - Matplotlib for data visualization

**Methodology**

1. Data cleaning and standardization
   - Rename the columns for better readability
   - check for duplicate values (No duplicate found)
   - check for missing values (No missing values found)
     
2. Business Metrics
   
   - Calculate the percentage distribution of fuel types per state using aggregation function (groupby)
   - Sort values based on percentage to find the top and bottom states.
   - Use matplotlib for visualization, showing the distribution of fuel types by state 

  3. Key insights

   - What percentage of vehicles in each state are EVs, PHEVs, HEVs, and gasoline?

      - EVs Vehicle in US

     <img width="2368" height="2373" alt="ev_distribution" src="https://github.com/user-attachments/assets/d1597096-2828-4745-ada7-f448c46a4eaf" />

- Electric vehicle adoption in the United States is relatively low, with strong concentration in a few leading states.
  California significantly outperforms all other states with EV adoption  around 3.4%. This indicates strong policy support,  infrastructure(charging stations), and consumer adoption. Other states like the District of Columbia (2.60%), Hawaii(2.37%), and Washington(2.23) are among the top 5 EV adoption. States like Mississippi (0.13%), North Dakota (0.13%), and Wyoming (0.17%) have a very low EV penetration.















   - PHEVs (Plug-in Hybrid Electric) vehicles in the US
 
<img width="2368" height="2373" alt="PHEV_Vehicle_distribution" src="https://github.com/user-attachments/assets/8b464ccd-0fbb-44c7-a5d7-9b1dfc219e3f" />

















  
