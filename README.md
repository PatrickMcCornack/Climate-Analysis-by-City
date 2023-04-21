# Climate-Analysis-by-City
These are the results of the Climate Analysis performed for my capstone project for DATA 424. In this collaborative project we assessed the vulnerability of Boeing Facilities to climate change impacts based on their geographic location using parameters related to climate, electricity prices, and energy resource mixes. The climate analysis component, found here, was narrowed to analyzing temperature trends for simplicity and as that is the component that will have the most influence on energy costs.  

A subset of the charts and summary statistics found here are incorporated into an R Shiny web app that maps Boeing facilities and allows users to dynamically explore the data related to the three facets of our analysis for each facility.

# Files
__climate_analysis.Rmd:__ RMarkdown file containing results of an analysis of temperature regime trends for a user-selected city in the dataset. Defaults to Seattle. 
__climate_analysis.pdf:__ PDF knit from the above RMarkdown file with climate analysis for Seattle. 
__process_data.Rmd:__ Script to preprocess the raw data for a list of selected cities and write the processed datasets to processed_data. These processed datasets are intended to be used in R Shiny web application. 
