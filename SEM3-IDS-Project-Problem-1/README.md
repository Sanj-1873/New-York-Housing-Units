# SEM3-IDS-Project
## New York Housing Units
1.	Project ID: The Project ID is a unique numeric identifier assigned to each project by HPD.
2.	Project Name: The Project Name is the name assigned to the project by HPD.
3.	Project Start Date: The Project Start Date is the date of the project loan or agreement closing.
4.	Project Completion Date: The Project Completion Date is the date that the last building in the project was completed. If the project has not yet completed, then the field is blank.
5.	Building ID: The Building ID is a unique numeric identifier assigned to each building by HPD.
6.	Number: The House Number is the street number in the building’s address. E.g., the house number is ‘100’ in ‘100 Gold Street.’
7.	Street: The Street Name is the name of the street in the building’s address. E.g., the street name is ‘Gold Street’ in ‘100 Gold Street.’
8.	Borough: The Borough is the borough where the building is located.
9.	Postcode: Zip code
10.	BBL: The BBL (Borough, Block, and Lot) is a unique identifier for each tax lot in the City.
11.	BIN: The BIN (Building Identification Number) is a unique identifier for each building in the City.
12.	Community Board: The Community Board field indicates the New York City Community District where the building is located.
13.	Council District: The Council District indicates the New York City Council District where the building is located.
14.	Census Tract: The Census Tract indicates the 2010 U.S. Census Tract where the building is located.
15.	NTA - Neighborhood Tabulation Area: The Neighborhood Tabulation Area indicates the New York City Neighborhood Tabulation Area where the building is located.
16.	Latitude: The Latitude and Longitude specify the location of the property on the earth’s surface. The coordinates provided are an estimate of the location based on the street segment and address range.
17.	Longitude: The Latitude and Longitude specify the location of the property on the earth’s surface. The coordinates provided are an estimate of the location based on the street segment and address range.
18.	Latitude (Internal): The Latitude (Internal) and Longitude (Internal) specify the location of the property on the earth’s surface. The coordinates provided are of the internal centroid derived from the tax lot.
19.	Longitude (Internal): The Latitude (Internal) and Longitude (Internal) specify the location of the property on the earth’s surface. The coordinates provided are of the internal centroid derived from the tax lot.
20.	Building Completion Date: The Building Completion Date is the date the building was completed. The field is blank if the building has not completed.
21.	Reporting Construction Type: The Reporting Construction Type field indicates whether the building is categorized as ‘new construction’ or ‘preservation’ in Housing New York statistics. Note that some preservation projects included here may not actually involve construction, because they extend the project’s regulatory restrictions but do not require rehabilitation.
22.	Extended Affordability Only: The Extended Affordability Only field indicates whether the project is considered to be Extended Affordability. An extended affordability project involves no construction, but secures an extended or new regulatory agreement. All extended affordability projects have a ‘reporting construction type’ of ‘preservation.’
23.	Prevailing Wage Status: The Prevailing Wage Status field indicates whether the project is subject to prevailing wage requirements, such as Davis Bacon.
24.	Extremely Low Income Units: Extremely Low Income Units are units with rents that are affordable to households earning 0 to 30% of the area median income (AMI).
25.	Very Low Income Units: Very Low Income Units are units with rents that are affordable to households earning 31 to 50% of the area median income (AMI).
26.	Low Income Units: Low Income Units are units with rents that are affordable to households earning 51 to 80% of the area median income (AMI).
27.	Moderate Income Units: Moderate Income Units are units with rents that are affordable to households earning 81 to 120% of the area median income (AMI).
28.	Middle Income Units: Middle Income Units are units with rents that are affordable to households earning 121 to 165% of the area median income (AMI).
29.	Other Income Units: Other Units are units reserved for building superintendents.
30.	Studio Units: Studio Units are units with 0-bedrooms.
31.	1-BR Units: 1-BR Units are units with 1-bedroom.
32.	2-BR Units: 2-BR Units are units with 2-bedrooms.
33.	3-BR Units: 3-BR Units are units with 3-bedrooms.
34.	4-BR Units: 4-BR Units are units with 4-bedrooms.
35.	5-BR Units: 5-BR Units are units with 5-bedrooms.
36.	6-BR+ Units: 6-BR+ Units are units with 6-bedrooms or more.
37.	Unknown-BR Units: Unknown-BR Units are units with an unknown number of bedrooms.
38.	Counted Rental Units: Counted Rental Units are the units in the building, counted toward the Housing New York plan, where assistance has been provided to landlords in exchange for a requirement for affordable units.
39.	Counted Homeownership Units: Counted Homeownership Units are the units in the building, counted toward the Housing New York Plan, where assistance has been provided directly to homeowners.
40.	All Counted Units: The Counted Units field indicates the total number of affordable units, counted towards the Housing New York plan, that are in the building.
41.	Total Units: The Total Units field indicates the total number of units, affordable and market rate, in each building.
## What we need to do (strike-through when done)
1. ~~Clean Dataset (Current state: Deleted "CONFIDENTIAL" entries, Seperated complete and incomplete entries).~~
2. ~~Plot frequencies for n-BR units per borough.~~ (Make 3D plot?)
3. Find population of boroughs.
4. Plot houses on maps.
  4b. Find relation between proximity to places and BR.
## References
[For mapping houses](https://www.kaggle.com/rossrco/passnyc-socio-economic-needs-index)

[For 3D plots](https://matplotlib.org/3.1.1/gallery/mplot3d/3d_bars.html)
