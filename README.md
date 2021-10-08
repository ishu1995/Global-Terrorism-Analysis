# Global Terrorsim Analysis
In this activity, we present the analytical results obtained for digging data into Global Terrorism database. The main purpose is to visualize terrorist data and make it available to users in an easy-to-understand way. This document is designed to contain a collection of various analytical and visual interpretations patterns and trends in it. 

<b> Tags: Exploratory Data Analysis, Visualisation, Data Analysis </b> 
#### Co Created by [Ayush Jain](https://github.com/ishu1995), [Sarvesh Kumar](https://github.com/sky309), [Prabhat Dixit](https://github.com/prapcode), and [Harshal Pawar](https://github.com/HarshalPawar88)
<b> Links: </b> [Collab](https://github.com/ishu1995/Global-Terrorism-Analysis/blob/main/CH_%7BFinal_Notebook%7D%7BTeam_Time%7D_%7BGlobal_Terrorism_Analysis%7D_Capstone_Project.ipynb), [Dataset](https://drive.google.com/file/d/1_VJ0L_mX4a1xBYo4Uvz_ND3_-xDW5ebq/view?usp=sharing), [Presentation](https://docs.google.com/presentation/d/19mIPH-6ZdG2zmJsIstJ6-Tz3Z23K7I-2dMFYBfkSnQk/)
## Project Summary: 
Global Terrorism Database is the most comprehensive database of terrorist attacks in the world. This database provides information on the domestic and international terrorist attacks around the world since 1970 and includes more than 180,000 events. The idea of this project is to use the database and provide the most valuable insights about the terrorism and their groups in the world. To achieve our goal we have divided the analysis into three parts Terrorism on World level, Terrorism in India, Attacks and Damage done by the Terrorist groups and their activity trends. 
## Approach towards project:

<h4> o Data Cleaning: </h4> Process of handle inconsistencies in data. In terrorism dataset, there are numerous fields like motives or responsible organizations which are missing either due to information not available or that field was not relevant for that specific event. Fields like summary, claim_mode, claimmode_txt, guncertain, 'nperps' etc. are removed since they are not relevant to the analysis of this project. Fields like weapsubtype2, and weaptype3_txt have more missing values than valid entries. Hence such fields are also removed to reduce complexity.
<h4> o Data Integration: </h4> In this step, conflicts among data are resolved. Different representations of the same data such as multiple subcategories of weapon type (weapsubtype1, weapsubtype2, weapsubtype3) are put together to avoid confusion and duplications. Fields with one-to-one correspondence like country_code and country_txt are mapped to avoid any conflicts. 
<h4> o Data Transformation: </h4> Here data aggregation, generalization, and normalization are performed. Dataset has nkill and nwounds which can be shown as a single attribute by the name of the Damage in the analysis. This technique reduces the total number of attributes in the dataset and hence reducing the variability in the data.
<h4> o Data analysis and visualisation: </h4> We utilise the libraries like Seaborn, Matplotlib to check the trends and generate the useful insights from the final dataset on the World level, Country level. 

## Conclusion
1. Maximum number of attacks are 16903 across the world in the year 2014. 
2. Taliban group has executed the maximum number of attacks i.e 7360 in the last two decades. 
3. Asia is the most affected region by terrorist attacks with Iraq having maximum number of attacks.
4. Bombing/ Explosion are the most preferred attack type and the same did the maximum damage too. 
5. 2016 has seen the maximum number of attacks in India but the maximum number of people were killed in 1992. 
6. In India, J&K has been the most affected state and Srinagar having the highest number of attacks i.e 749
