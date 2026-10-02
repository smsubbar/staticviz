# Manas Subbaraman

## Description
As climate change alters the frequency and severity of extreme weather events, communities across the United States face increasingly complex disaster risks. I am interested in conducting a high-level existing conditions analysis of American communities that face the greatest exposure to natural hazards and social vulnerability.

## Data Sources

### Data Source 1: FEMA National Risk Index Data

URL: (https://www.fema.gov/flood-maps/products-tools/national-risk-index)

Size: 85154 rows, 479 columns

The FEMA National Risk Index (NRI) combines expected annual economic loss, social vulnerability, and community resilience to show which communities are at risk to 18 natural hazards. The data is available at the census tract level.

Based on an initial exploration, the dataset allows for analysis of both overall and individual hazards. It provides aggregate measures of risk across all 18 hazards, while also providing hazard-specific measures of risk, economic and social impacts, vulnerability, and resilience for each hazard.

I have the following ideas on how I would utilize this dataset:
- Top 10 most vulnerable census tracts in the USA and their demographic characteristics
- States with the highest number of vulnerable communities
- Physical vs. Social/Community Resilience
- Categorization based on hazard type


### Data Source 2: American Community Survey 2024 5-Year Estimates

URL: https://data.census.gov/ 

Size: 85395 rows, Number of Columns TBD (depends on which characteristics are used)

The ACS 2024 5-Year Estimates would supplement the NRI data by helping the audience understand who lives in the most vulnerable communities and whether there are common characteristics among populations living in high-risk areas.

At this time, I want to incorporate the following demographic characteristics:
- Age
- Gender
- Employment Status
- Income Level and Poverty Status
- Disability

## Questions 

1. Should I incorporate a time-series element to my project? The FEMA NRI dataset is not suitable for time-series analyses, but I can use older ACS data to track demographic trends over time if necessary.
2. When it comes to hazard-level charts, would you recommend that I narrow the list down to 5 to 10 hazards (ex: wildfire, flood, earthquake, etc.) to make visualizations easier to read? 