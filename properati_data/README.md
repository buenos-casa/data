### Properati Data

|Index | Folder | Description |
|----|---------|------------|
| 1| rent | This folder include the following files: Properati rental listings within Buenos Aires (`properati_census_barrios.csv`), Properati statistics files (`properati_barrios_grouped` and `properati_barrios_grouped_month`) and Properati statistics files in JSON in order to be imported into SQLite. It also includes `combining rent.gqz`, which is the QGIS file used to merge the Properati data with Buenos Aires' locational data (eg. health, humanity, etc) |
|2 | rent_stripped | Properati's rent data geospatially merged with Buenos Aires' datasets |
| 3| sell | This folder include the following files: Properati purchase listings within Buenos Aires (`sell_census_barrios.csv`), Properati statistics files (`properati_sell_grouped` and `properati_sell_grouped_month`) and Properati statistics files in JSON in order to be imported into SQLite. It also includes `combining sell.gqz`, which is the QGIS files used to merge the Properati data with Buenos Aires' locational data (eg. health, humanity, etc) |
| 4 | sell_stripped | Properati's purchase data geospatially merged with Buenos Aires' datasets |




#### Notes:

1. Refer to [Merging Rent Data Notebook](../Merging%20Rent%20Data.ipynb) for how Properati's rental data was cleaned.
2. Refer to [Merging Purchase Data Notebool](../Merging%20Purchase%20Data.ipynb) for how Properati's sale data was cleaned.
3. Used [barrios data](../shape%20files/barrios.csv) from the Baires government [portal](https://data.buenosaires.gob.ar/dataset/barrios)




