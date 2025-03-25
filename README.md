# water-quality

# Overview
The pollution readings of 545 water quality monitoring stations in India for the year 2015 are uploaded. specific variables include BOD, pH, temperature, nitrate and coliform concentration of Indian rivers. This is an ongoing project: data for more stations and years will be uploaded on a periodical basis

# Methodology

These readings are text extracted using the CPCB data and pdftools package on R. Code is available on request: please reach out to me on dubeyaaditya84@gmail.com 
Currently I have stacked river systems together for a goven year and added the name of the river for every station that had a river in its name. The readings are only for the year 2015 and represent a snapshot in time of the rivers. In the near future, I will upload panellised data for years all the years from 2007 to 2022 for ALL the Indian rivers.

# List of variables

Table 1 contains the compiled values. Table 22-29 contain uncleaned data, which hasn't been appended to the 'main' cross section yet.
The identifying variables are: Station code, Name, State and River
The reading vars: the max and min values of the following vars:  temperature, dissolved oxygen, pH, conductivity, BOD, Nitrates, Fecal coliform and total coliform. The units are mentioned alongisde the variables and have been directly reported from CPCB repositiory.

important note: following are the permissible limits set by CPCB for the following impurities:

Dissolved oxygen: > 4.0 mg/l
pH range: 6.5-8.5	
BOD: < 3 mg/l
Fecal coliform: < 2500 MPN/100ml
Total coliform< 5000 MPN/100ml

# License and Citation
This work does not claim ownership of the CPCB dataset. If you use this data in your research, please cite: https://cpcbenvis.nic.in/water_quality_data.html#






