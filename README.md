# data-512-Homework-2

# Objective
In this research, I embarked on a comprehensive exploration of data bias, leveraging Wikipedia articles as our primary dataset. My approach involved collecting data related to Wikipedia articles about a wide range of cities and towns across the United States. These articles were then evaluated for quality using the ORES API. The analysis was multifaceted, encompassing a thorough examination of critical metrics linked to the anticipated article quality. The focus of this investigation extended to identifying states that exhibited the most extensive per capita coverage of articles. The primary aim of this study was to unearth insights into regional patterns of article coverage and the prevalence of top-quality articles within this expansive dataset.

# Sources

1. Csv file us_cities_by_state_SEPT.2023. It contains state, page title and url.- https://en.wikipedia.org/wiki/Category:Lists_of_cities_in_the_United_States_by_state

3. Excel file NST-EST2022-POP. This file contains the list of states and the 2022 population estimates for each state.

4. csv file US States by Region - US Census Bureau. It contains regions (Northeast, Midwest etc.), divisions (New England, Middle Atlantic) and states (Connecticut, Vermont) - https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html
  
5. List of regions in the US (Wikipedia): https://en.wikipedia.org/wiki/List_of_regions_of_the_United_States#Census_Bureau%E2%80%93designated_regions_and_divisions

6. ORES Article Scores (Wiki): https://www.mediawiki.org/wiki/ORES, https://www.mediawiki.org/wiki/API:Info

# Licensing

[Wikimedia Foundations Rest API](https://www.mediawiki.org/wiki/API:REST_API#Terms_and_conditions)

[Creative Commons Liscence](https://creativecommons.org/licenses/by/4.0/)

# Helpful API Documentation

[ORES Wiki](https://www.mediawiki.org/wiki/ORES)

[Wikipedia Content Assesment](https://en.wikipedia.org/wiki/Wikipedia:Content_assessment)

[API info](https://www.mediawiki.org/wiki/API:Info)

# Files (structure)

#### Git specific
1. License
2. Readme.md

#### Data Files
3. NST-EST2022-POP.xlsx
4. US States by region - US Census Bureau.xlsx
5. us_cities_by_state_SEPT.2023.csv

#### Python Notebook 
6. DATA512_HW2_V2.ipynb
#### Output files
7. wikipageinfo.csv
    
# Research Implications

### What did I learn? 
One key insight gleaned from this analysis is that, despite the United States being a technologically advanced nation with a robust economy, there is a noticeable absence of publicly available articles and information about many regions within the country. Instead, there is a distinct inclination toward regions with high population density. This finding prompts further investigation, extending similar analyses to other countries in Europe, Africa, and Asia. It underscores the fact that public data sources like Wikipedia are susceptible to both implicit and explicit biases. In our particular case, the implicit bias is evident in the form of insufficient articles about specific cities and states. Addressing explicit biases, such as those arising from ideological differences, would necessitate more extensive scrutiny.

### What I found... What surprised me? 
As per my examination, South Dakota emerges as the state with the most superior articles published per individual. Notably, South Dakota doesn't belong to New England, the region recognized for generating the highest-quality articles per person. This particular finding took me by surprise. Moreover, South Dakota not only had the largest number of articles per person but also maintained the highest article quality. This is intriguing because, despite their large quantity of articles, they retained their exceptional quality.

### In addition to any reflections you want to share about the process of the assignment? 
The process was quite convoluted and it took me a while to figure out how to troubleshoot while running the ORES API and add error proofing codes to it.

## Answering the questions asked...

### What biases did you expect to find in the data (before you started working with it), and why?
I anticipated that major cities with substantial populations and higher population densities would produce superior articles due to increased contributions from interested individuals. I also had the expectation that larger states, particularly those with thriving economies, would exhibit both a greater quantity and higher quality of articles compared to economically disadvantaged and smaller states.

### What (potential) sources of bias did you discover in the course of your data processing and analysis?
I'm not entirely certain that the tables I generated unveiled any groundbreaking insights regarding bias. However, during an empirical examination of the data, I did come across some potential indications of bias. As I randomly perused various articles, I noticed that it was quite common for cities I had never encountered and which did not appear to have subjectively high-quality Wikipedia pages to receive favorable ratings from the machine learning model. This has led me to suspect that the model may exhibit a bias toward rating articles more positively. Consequently, this bias could result in states or regions with a higher article count also having a greater number of seemingly "high-quality" articles, largely due to false positives.

### What might your results suggest about (English) Wikipedia as a data source?
Even though Wikipedia's data may carry biases, it remains an openly accessible and unrestricted resource teeming with a wealth of information, making it an ideal choice for initiating a foundational analysis. Our examination reveals that Wikipedia is susceptible to implicit knowledge biases that manifest in the absence of information about specific cities or states.

# Results
<img width="901" alt="image" src="https://github.com/ananya-bajaj-DS/data-512-Homework-2/assets/121599846/30117dbb-ce32-4be1-90d5-520ca4088320">

