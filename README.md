# Project_NPS
by Gigi Jones and Pratixa Shah

## INTRODUCTION: 
This repo contains the collaborative work that analyzes U.S. National Park Service's (NPS) data. Neither one of us has used this data before we started. As such, this research was inductive that we allowed the data to tell us the story as opposed to approaching the data with a set of pre-conceived research questions to restrict our analysis. 

The reader should see the following files in this repo:
  * Gigi's data analysis as a Jupyter Notebook 
  * Pratixa's data analysis as a Jupyter Notebook
  * A pdf of the final presentation called "Project1_National_Parks_Presentation"
  * A folder of Data Resources 
  * This ReadMe file

## DATA RESOURCES:
The data that we used came from multiple sources: 
  NPS Stats database (https://irma.nps.gov/STATS/)
  NPS API (https://www.nps.gov/subjects/developer/index.htm)
  Open Weather API (https://openweathermap.org/api) 


## ANALYTICAL PROCESS:
Over the 1.5 weeks that we obtained, merged, cleaned, analyzed, and presented the data, we quickly needed to strategize over learning what is in our data, what is possible to analyze with our data, and what data can be presented to tell a compelling story to uninformed audience. More specifically, we conducted the following:
  * Requested data from APIs using json package
  * Pulled .csv/.xlsx reports
  * Used pandas to clean and format our data set(s)
  * Created two jupyter notebooks - one for each project member - perform and describe the data exploration and cleanup process
  * In the same jupyter notebooks - we created multiple charts and graphs to visualize our data analysis using Pandas, Matplotlib, and Numpy
  * The the visualizations are saved in the presentation slide deck that has been saved as a pdf.

At the start, we were exploring to understand the data. We learned that the most interesting data was the number of visitations for each national park. As we dug deeper into the data, we realized that we had data that can share the impact of COVID-19 on the parks. While we have two jupyter notebooks, we worked collaboratively and tried to committed updates on this shared GitHub repo. Taken together, our notebooks holds the analysis and visualizations used in the final presentation, which first described the U.S. National Parks and then share the impact of COVID-19.
  
## SUMMARY OF MAJOR FINDINGS:
We had a lot of questions about the data and found the following answers:
**1. How many U.S. National Parks are there?** We wanted the total number of parks and there are a total of 423. However, the data had some missing and odd data (i.e., a national park river that crossed multiple states). We made the cleaning decision to use the data with the most complete data because we could not verify or research on the missing or questionable data. For the most of the data analysis we had a denominator less than 423 parks. *(see both Gigi's and Pratixa's notebooks).*
2. What kinds of parks are there? We were surprised to find out there were a lot. In fact, there are officially 19 designated parks that range from National Park (like the Grand Canyon or Yosemite), National Recreation Area (like Boston Harbor), or National Monument (like the Statue of Liberty or Washington Monument). *(see Gigi's notebook)*
3. Which parks were the most and least visited? We found the top 10 most visted over a ten year period. #1 was the Golden Gate National Recreation Area with over 14.8 million visits. We found teh bottom 10 in the same period. Dead last on the list was Aniakchak National Monument and Preserve in Alaska. Aniakchak only gets an average of 96 visitors a year. *(see Gigi's notebook)*
4. States. *(see Pratixa's notebook)*
5. Regions. *(see Pratixa's notebook)*
6. Outliers 1. *(see Pratixa's notebook)*
7. Outliers 2  *(see Pratixa's notebook)*
8. Weather API.  *(see Pratixa's notebook)*
9. When visitors stay overnight at the parks, how do they like to sleep over? We found that 1 in 4 (or 25.5%) like to stay in a tent site. Almost another quarter (23.4%) likes to stay in the park's lodging. *(see Gigi's notebook)*
10. What was the overall impact of COVID-19 on the visitation numbers from 2019 compared to 2020? We found that there was a drop of more than 90 million visits from 328 million in 2019 to 237 million in 2020. While we expected a decline in visits. We expected that the decline would be much greater, but it appears that shutdown or lock down of the parks was not held for very long. *(see Gigi's notebook)*
11. What was the impact of COVID-19 during the most popular months - the summer (June, July, and August combined)? We also found that park visits dropped between summer 2019 and 2020. We presented this data for the top four popular park types as bar graphs and saw a decline. *(see Gigi's notebook)*
12. Finally, what was the impact of COVID-19 by region and month? We ran the data for all seven regions but presented two - Pacific West and National Capital. Both graphs showed a large gap between 2019 and 2020 indicating the decline of visits. *(see Gigi's notebook)*


## CONCLUSION:


