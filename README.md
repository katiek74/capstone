# Clinical Trials in the Year of COVID-19

*A look at how the COVID-19 pandemic impacted research in 2020*


## MOTIVATION

I have previous experience working with human research studies in a regulatory and compliance component, so I am familiar with the subject matter. COVID-19 is currently impacting everyone, so this data is timely and significant. My main question was to compare COVID-19 studies versus other studies and see how the COVID-19 pandemic has impacted clinical trials in 2020. 

## DATA
Most data came from http://clinicaltrials.gov and Clinical Trials Transformation Initiative (CTTI) which has created a relational database of the data directly from clinicaltrials.gov (found at http://aact.ctti-clinicaltrials.org)
Our World in Data’s COVID information which uses data from Johns Hopkins Coronavirus Resource Center (http://ourworldindata.org/covid-cases, http://coronavirus.jhu.edu) 

## ANALYTICAL APPROACH
### Issues and Challenges:
Much of the data involved open text fields so there was a lot more data cleaning than expected. There is still a lot that could be done as far as standardizing words and phrases that mean the same thing. 

## TOOLS USED
- 'PostgreSQL' – for uploading the relational database from CTTI, I then fed this into Python
- 'Python/Pandas' - for exploration, cleaning and aggregation of the data
- 'Tableau' - for creating the presentation
