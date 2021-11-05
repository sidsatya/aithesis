# Estimating the Impact of Artificial Intelligence on Jobs Within the Healthcare Industry.

This repository contains the code + Jupyter Notebooks for my Senior Economics Honors Thesis @ UC Berkeley

# Abstract
The rapid growth of the artificial intelligence field, as well as its ability to impact nearly every economic sector,
underscores the importance of understanding its potential impact on labor. This paper examines how wages and employment levels for jobs in the healthcare industry are affected by artificial intelligence as well as the net effect of two direct impacts of AI through a difference-in-differences approach. The results show that wages and employment for Physicians and Surgeons increased after the introduction of IBM Watson for healthcare applications in 2013 while no significant effect was found for Secretaries and Administrative Assistants in the healthcare industry. Overall, the results suggest that when artificial intelligence augments labor on decision tasks, it has a net positive effect whereas the effect of automating prediction tasks remains ambiguous.

# Relevant Files
1. `THESIS.pdf`: The actual paper itself! 
2. `healthcare_data_regressions.ipynb`: Contains the main data cleaning code as well as code used to output tables and figures used in the paper.  
3. `aipatent_cleaning.ipynb`: Contains data cleaning for OECD data regarding the number of AI-related patents over time.
4. `onet_tasks.ipynb`: Constructs tables regarding the number of tasks that are affected by each AI-related impact for each occupation of interest. 
5. `did_ols_regressions.Rmd`: R notebook containing the Difference-in-Differences and OLS regressions that I ran. 
6. `did_ols_regressions.pdf`: PDF version of the R notebook containing the regressions. 

# Data
Unfortunately, the IPUMS data that I used is too large to include within a git repository. If you are interested in learning more and viewing the data, please contact me at sidsatya@berkeley.edu and I would be happy to provide it. I have included the smaller datasets that I generated in the `data` folder. 
