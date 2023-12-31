# 911diversionprograms
Data normalization: This data was normalized using OpenRefine. 
I removed unnecessary punctuation (including commas at the ends of sentences) and expanded abbreviations when possible and logical (e.g. SUICIDE instead of SUIC). 
I kept certain words abbreviated when they were both understandable by the potential user and resulted in neater formatting (e.g. PSYCH instead of PSYCHIATRIC). 
The dates and time of initial 911 calls and BCRI calls (when applicable) remain in their original, unstandardized formats. Attempts to normalize these variables resulted in unintentional inaccuracies due to OpenRefine’s difficulty in identifying time zones. These variables remain unstandardized to maintain the integrity of the data. 
File naming convention: {city}_{program name}_{years}.xlsx
BHD stands for Behavioral Health Diversion. ARC stands for Alternative Crisis Response.
This naming convention was chosen to allow for easy additions to the data if/when new cities implement similar programs in the future, hopefully making it possible for users to compare the programs’ efficacy across space and time. 
Variables names and definitions: Variable names used are the same as those in the original datasets, but have received standardized capitalization and clarification when necessary. 
The variable ObjectId1 in the Baltimore dataset had no values in the initial dataset and has been removed. Variable ObjectId2 in the Baltimore datset has been renamed to ObjectId. 
Variables for latitude and longitude coordinates in the Seattle and Cincinatti datsets were removed. 
For a full list of variable and definitions used in the dataset, please refer to the Data Dictionary, included in the dataset file. 
Variable definitions are written in the following format: Defintion, potential values (when applicable), type of entry. 
Acronyms used in the dataset entries have also been defined in the Data Dictionary. 
