### Properati Data

| Index | Data | Description |
| ----- | ----- | ------------ |
| 1 | rent-2015 | Sample data for rented properties that were created in 2015 |
| 2 | rent-combined | Data for rented properties - FULL DATASET |
| 3 | properati_barrios_grouped | Properati data within Baires grouped by barrios - with basic stats (properati + census + barrios and grouped) |
| 4 | properati_census_barrios | Properati data within Baires with each property linked to a barrio - no stats (properati + census + barrios no grouping) |
| 5 | properati_barrios | `properati_barrios_grouped` but in JSON|
| 6 | properati_barrios_grouped_month | Properati data within Baires grouped by barrios - with basic stats (properati + census + barrios and grouped by month and year) |
| 7 | properati_barrios_month| `properati_barrios_grouped_month` but in JSON |

#### Notes:

1. Refer to [Notebook](../Discover%20Data.ipynb) for how 3 - 7 were created. 
2. Used [barrios data](../shape%20files/barrios.csv) from the Baires government [portal](https://data.buenosaires.gob.ar/dataset/barrios)
3. The months and years used to group data in `properati_barrios_grouped_month` are from the `created-on` columns - some properties were created before 2015 but appeared in the 2015 datasets. 



