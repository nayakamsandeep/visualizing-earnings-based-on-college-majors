## Visualizing-earnings-based-on-college-majors

This repo contains the data and code for FiveThirtyEight's story on earnings of college majors. All data is from American Community Survey 2010-2012 Public Use Microdata Series. Download data here: [http://www.census.gov/acs/www/data_documentation/pums_data/] Documentation here: [http://www.census.gov/acs/www/data_documentation/pums_documentation/]

majors-list.csv:

    - List of majors with their FOD1P codes and major categories.
    - Major categories are from Carnevale et al, "What's It Worth?: The Economic Value of College Majors." Georgetown University Center on Education and the Workforce, 2011. http://cew.georgetown.edu/whatsitworth

Three main data files:

    - all-ages.csv
    - recent-grads.csv (ages <28)
    - grad-students.csv (ages 25+) All contain basic earnings and labor force information. recent-grads contains more detailed breakdown, including by sex and by the type of job they got. Full headers below. grad-students contains details on graduate school attendees.

Additionally, women-stem.csv contains data for scatter plot in associated DataLab post on women in science/technology jobs. It is a subset of recent-grads.csv. (Small easter egg: Check out my related Shiny app: [https://bencasselman.shinyapps.io/new-test/])

Reference: [https://github.com/fivethirtyeight/data/tree/master/college-majors] 
