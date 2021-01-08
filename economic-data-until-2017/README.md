# Economic regional dataset until 2017

Data of interpolated GRDP per Capita at Constant Price 2010 
for 34 Provinces and 514 districts in Indonesia 

## Important information 

1. When the Central Bureau of Statistics (BPS) releases the data of GDP/GRDP, usually they will note the last two years data as temporary data (with superscript one star (*)) and very  temporary data (with superscript two star (**)). For example, we have a dataset of GDP from 2000-2017. In this dataset, the data in 2016 will be noted as temporary data (with *) and the data of 2017 will be noted as very temporary data (with **).

2. Indonesia only conducts population surveys every 10 years. Therefore, the population data in the csv files are the projection of population dataset from BPS, that were calculated from GRDP Per Capita at current price and GRDP at Current Price. In the year of 2020, Indonesia conducts population surveys, so there is a possibility that the data will also change if we update the dataset again this year or next year because of the Central Bureau of Statistics (BPS) updating their population data.


## GRDP_PerCapita_Indonesia_Districts_until_2017.csv

|     Column    | data type | decimals |   short description  |                                   long description                                   |
|:-------------:|:---------:|:--------:|:--------------------:|:------------------------------------------------------------------------------------:|
| District_name |   string  |    NA    |   name of district   |                                   name of district                                   |
|    Province   |   string  |    NA    |   name of province   |                                   name of province                                   |
|     Region    |   string  |    NA    | geographical regions |                        seven geographical regions of Indonesia                       |
|      KDJ      |   string  |    NA    |      district ID     |                                      district ID                                     |
|  Regency_City |   string  |    NA    |   type of district   |                    type of district: regency, captial city or city                   |
|       X       |  numeric  |     7    |       longitude      |                                       longitude                                      |
|       Y       |  numeric  |     9    |       latitude       |                                       latitude                                       |
|    POPXXXX    |  numeric  |     1    | population year XXXX |                        Total number for year XXXX (2000-2017)                        |
|    RGDPXXXX   |  numeric  |     0    |    RGDP year XXXX    |      Regional Gross Domestic Product in Billion IDR for year XXXX   (2000-2017)      |
|   RGDPPCXXXX  |  numeric  |     1    |   RGDPPC year XXXX   | Regional Gross Domestic Product per capita in Thousand IDR for year XXXX (2000-2017) |

## GRDP_PerCapita_Indonesia_Provinces_until_2017.csv

| dataset columns | data type | decimals |    short description   |                 long description                |
|:---------------:|:---------:|:--------:|:----------------------:|:-----------------------------------------------:|
|     Province    |   string  |     -    |    name of province    |                 name of province                |
|     	XXXX     |  numeric  |    NA    | data for the year XXXX |  GDP per capita for the  year XXXX (1983-2017) (Thousand IDR) |


