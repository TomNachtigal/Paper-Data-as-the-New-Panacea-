# Paper-Data-as-the-New-Panacea-
We share here the data and code for the paper: Bromley, P. Nachtigal, T., & Kijima, R. (Forthcoming). "Data as the New Panacea: Trends in Global Education Reforms, 1970-2018", in the Special Issue of Comparative Education (*to add: editors, title of the special issue*)

# Data: Sample of WERD
For this paper, we use a dataset from the World Education Reform Database, which is an extended of WERD v2 (https://werd.stanford.edu/database), including reforms between the years 1970-2018, and that have reform description. The code below includes the sections of data cleaning and pre-processing to generate the final dataset. Country codes and country names are subject to small edits from v2. We include here the final dataset used for topic modeling (titled "WERD_dataset.csv").

See more details about the structure of WERD V2 in: Bromley, P., Kijima, R., Overbey, L., Furuta, J., Choi, M., Santos, H., Song, J., and Nachtigal, T. 2023b. World Education Reform Database (WERD), Harvard Dataverse, V2. 

# Code:
We provide the code used to produce our findings in the R Markdown file, including key data objects generated throughout the code. Our methodological approach is structural topic modeling, for which we used the STM package (Roberts, Stewart & Tingley, 2019). 
The code includes in-line comments to clarify decisions that have been made throughout to facilitate replication.

The code further utilize Google Translate API to translate non-English reforms in the data, see: Google. (N.D). Cloud Translation - Google Cloud. Retrieved [Date Accessed], from https://cloud.google.com/translate. To run this section of the code, be sure to obtain appropriate API. The dataset included here includes the English version of all reforms included in our analysis.
