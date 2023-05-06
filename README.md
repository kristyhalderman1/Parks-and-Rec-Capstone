Parks-and-Rec-Capstone Project 

RESEARCH OBJECTIVES 

In preparation for its 2024 Park Asset Management Plan, the City of Missoula Parks and Recreation (MPR) approached The University of Montana College of Business seeking assistance with aggregating, entering, and analyzing National Recreation and Park Association (NRPA) data, identifying sustainability, and diversity, equity, and inclusion (DEI) trends, and building dashboards based on these findings.  MPR was also interested in identifying peer cities from this data, so that it could compare its level of service (LOS) standards to like jurisdictions to better serve the community. 

METHODS 
To find peer cities, I performed a K-means cluster analysis on 2019 5-Year American Community Survey (ACS) Data provided by the U.S. Census Bureau using 10 different ACS variables.  I then narrowed the cluster containing the City of Missoula using only those agencies within the 2022 NRPA Annual Park Metrics Survey dataset in the Intermountain West region, as defined by the United States Geological Survey.  I further analyzed these datasets as well as NRPA-provided DEI and sustainability survey results, the Federal Bank of Chicago’s Peer City Identification Tool (PCIT), and peer city strategic plans to offer a comprehensive report.   

KEY FINDINGS
MPR is most like 15 peer agencies which are: 
•	Medford, OR
•	Montrose, CO 
•	Idaho Falls, ID
•	Alamosa, CO
•	Redmond, OR
•	Bend, OR
•	Sandpoint, ID
•	Pueblo, CO
•	Coeur d’Alene, ID 
•	Post Falls, ID
•	Salt Lake City, UT
•	Spokane, WA
•	Bozeman, MT
•	Farmington, NM
•	Reno, NV

NOTEBOOK DESCRIPTION
•	Census Cluster.ipynb: Main file with all code for full analysis 
•	Parks and Rec Clustering.ipynb: Preliminary analysis using NRPA data
•	Parks and Rec.ipynb: Preliminary analysis using Census data.  Contains code to analyze key words in pdfs 
•	api_keys.py: My Census API key (active API key not pushed) 
•	censusdf.csv: Full list of all US Census cities (29,573 total)  
•	censusdf2.csv: List of all 2022 NRPA jurisdictions in the form City, ST
•	closest_cities.csv: List of top ten peer cities per first Census analysis 
•	closest_cities_lat: Top ten peer cities with latitude and longitude coordinates
•	closest_NRPAcities.csv: Top ten peer cities based on first NRPA analysis
•	cluster0.csv: Final Census analysis cluster of Missoula peer cities 
•	mergedNRPAdata.csv: All 2022 NRPA cities with available Census data
•	nrpa_data2.csv: list of all 2022 NRPA cities in the format: “Missouri City city, Texas”
•	NRPADATAALL2.csv: Full dataset of all available NRPA data (as of 3/1/23)
•	pca_results.csv: results of Principal Component Analysis 
•	pop_df.csv: Preliminary analysis list of all Census cities within a population of 50K-125K
•	summaryall.csv: descriptive statistics of all Census city data (count: 29573)
•	summarycluster.csv: descriptive statistics of cluster0 city data (count: 228)
•	summaryNRPA.csv: descriptive statistics of all NRPA data (count: 375)
