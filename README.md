# Phase-1-Project-

Project 1: Aircraft Risk Assessment for Diversification
Team: Jason, Ron, Sakeah

References & Visuals:
Google Word Doc of README: https://docs.google.com/document/d/1Ggye19b9RBZLZY51Rio4g54jbVBWbtUKIRx1xYY7SOc/edit?usp=sharing
Visual Dashboard in Tableau here: https://public.tableau.com/app/profile/sakeah.haggagi/viz/AirplaneProject1/Dashboard1?publish=yes
Presentation Slides Link Here: https://docs.google.com/presentation/d/1V4VpVRh8Jf5wq1p5Q6ZPd1VjM-mjwaV6zzlte8HkKOU/edit#slide=id.g2a356a4ba50_0_17
NTSB Aviation Data Set Here:  https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses


Navigating the project on Github:
Original Dataset: “Aviation_Data.csv” is the original data pulled from the NTSB on Kaggle. 
Data Cleaning: Use the “clean_df.csv” for the most clean and refined dataset.
With refining in mind. The data needed to have as much of the categories condensed as much as possible (ie: Make & Models). 
Jupyter Notebook: All of the most updated code and analysis sits in “central_notebook.ipynb”. 

Business Problem

A company is expanding into new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

Overview and Approach
With the provided data set of the NTSB Aviation Accident Data in the US & Int. We used that information and broke it apart into categories to determine best results with safety and reliability as priority for recommendation. To do this, the approach was carried out by analyzing the fatalities and damaged airplanes across multiple key areas of the dataset. 

However, it's important to note that there are many other factors contribute to aircraft safety and reliability, and further research is needed to fully understand the relationship between when aircraft damages and fatality risk.  


Aircraft Engine Types
We explored the relationship between engine type and accident severity across the five engine types (Reciprocating, Turbo Fan, Turbo Prop, Turbo Jet and Turbo Shaft) totaling ~56K data points. We found that Turbo Shaft and Reciprocating engines were involved in a higher percentage of severe accidents. Turbo Jet and Turbo Fan aircrafts ranked the highest in reliability and safety. For this analysis we looked at planes that were destroyed (% of Airplanes Destroyed = (total destroyed by engine type/ total airplanes) to understand historically how consistent each engine type had accidents. On the other hand, Turbo Prop engines were involved in the least severe accidents, with a lower percentage of fatalities and total damage.

Turbo Fan & Turbo Jet
Turbo Jet analysis was 10.8% of the total destroyed. Across ~2400 accidents there were 330 aircraft models that were not destroyed. Turbo Fan analysis was 8.1% of total destroyed accidents.  

Number Jet Engines w/ Turbo Fan Analysis
While keeping the analysis in place with Turbo Fan Airplanes we then doubled down on how well this airplane selection held up against passenger fatalities. The triple engine aircraft came in as the safest passengers against the aircraft with 1, 2 and 4 engines. The overall safety with the analysis (% of passengers killed = total fatalities/num of engine flights) totaled under 2.5% for triple engine aircrafts was by far the lowest rating vs the others where the next safest was over 3%. At a deeper level with safety top of mind we looked at the percentage of passengers killed during accidents when the planes were destroyed. This was where the triple jet stood out the most, scoring the lowest in percentage of passengers killed using our analysis (% of fatalities by destroyed = total fatalities / number of engine accidents). 


McDonnell Douglas 
In conclusion based on all the analysis discussed, we determined that the Mcdonnell Douglas make fit all the criteria in safety and reliability. There was also proficient amount of accident data to help us determine that the models within the DC 10 series airplanes are the best low risk options for investment in terms of Turbo Fan and Triple Engine by fatalities and airplanes destroyed. 
