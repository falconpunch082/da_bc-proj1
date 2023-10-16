# da_bc-proj1
Monash Data Analytics Bootcamp Project 1 - Group 3

Project Objective: To determine factors that impacted Indian crop yield
                    from 1997 to 2020.

Group Members:
- Nicholas Dale (falconpunch082)
- Duc Trieu Pham (Lilydales)
- Rajendra Bondili (rajbondili)


# Description for variables in crop_yield.csv:
(This is our main dataset.)

    - Crop: The name of the crop cultivated.

    - Crop_Year: The year in which the crop was grown.

    - Season: The specific cropping season (e.g., Kharif, Rabi, Whole Year).

    - State: The Indian state where the crop was cultivated.

    - Area: The total land area (in hectares) under cultivation for the specific crop.

    - Production: The quantity of crop production (in metric tons).

    - Annual_Rainfall: The annual rainfall received in the crop-growing region (in mm).

    - Fertilizer: The total amount of fertilizer used for the crop (in kilograms).

    - Pesticide: The total amount of pesticide used for the crop (in kilograms).

    - Yield: The calculated crop yield (production per unit area)
    
    
# Temperature vs. Crop Yield
Overall relationship: As temperature increases, crop yield increases.

Details:

- The relationship between temperature and each of the 5 most produced crops (according to main dataset) was analysed.
      
- The 5 crops analysed were rice, maize, moong, urad and groundnut.
    
- For rice, urad and groundnut, there was a statistically significant, moderate and positive correlation between temperature and crop yield. This indicates that for these crops, crop yield tends to increase as temperature increases.
       
- For moong, the positive correlation was even stronger than of the first 3 mentioned. This indicates that moong crop yield is likely to increase as temperature increases. 
       
- However, for maize, the relationship between temperature and crop yield was statistically insignificant.
       
# Rainfall vs. Crop Yield
Overall relationship: As rainfall increases, crop yield increases.

Details:

- The same 5 crops chosen during the temperature analysis were analysed again, this time for rainfall's impacts on crop yield.

- For rice, moong and urad, there was a statistically significant, moderate and positive correlation between rainfall and crop yield. This indicates that for these crops, crop yield tends to increase as rainfall increases.

- For groundnut, the positive correlation was even stronger than the other 3, indicating that groundnut crop yield is likely to increase as rainfall increases.

- For maize, while the relationship between maize crop yield and rainfall is statistically significant, it is also very weak.

       
# Implications
- In terms of temperaure and rainfall, there is an observed increase in crop yield as
they increase. This highlights the importance of temperature and rainfall in growing
plenty of crops for the Indian population, and if possible, for export to other
countries. Technology which regulates these variables so that they remain optimal for
each crop should be developed to maximise crop yield.

# Coordinator of Indian states vs Crop yield
- There is a weak relationship between the coordinator and the yield.
- There are some omissions such as: type of crop, year.
- 9 states show high yield when compared to the majority of the states listed in the graph, which have relatively very low yield.
- Some investigations are needed for the states of Goa, Puducherry, Kerala, West Bengal, Tamil Nadu, Assam, Andhra Pradesh, Karnataka and Telangana to find out the reasons why these states display high crop yield. This could be due to the properties of the crops, the quality of soil, etc.

# Fertilizer vs Crop yield
- There is no statistically significant relationship between the use of fertiliser and yield.
- A strong correlation was found between Fertilizer used and Year.
- There was a significant increase in fertilizer used in Indian.
       