### Properati Data

| Index | Data | Description |
| ----- | ----- | ------------ |
| 1 | rent-2015 | Sample data for rented properties that were created in 2015 |
| 2 | rent-combined | Data for rented properties - FULL DATASET |
| 3 | Sell_2015 | Sample data for sold properties that were created in 2015 |
| 4 | combined_sell | Data for properties on sale - FULL DATASET |
| 5 | sell_census | Properties within the city of Buenos Aires that were on sale |
| 6 | properati_barrios_grouped | Properati rent data within Baires grouped by barrios - with basic stats (properati + census + barrios and grouped) |
| 7 | properati_census_barrios | Properati rent data within Baires with each property linked to a barrio - no stats (properati + census + barrios no grouping) |
| 8 | properati_barrios | `properati_barrios_grouped` but in JSON|
| 9 | properati_barrios_grouped_month | Properati rent data within Baires grouped by barrios - with basic stats (properati + census + barrios and grouped by month and year) |
| 10 | properati_barrios_month| `properati_barrios_grouped_month` but in JSON |
| 11 | properati_sell_grouped | Properati sale data within Baires with each property linked to a barrio - with basic stats (properati + census + barrios and grouped)|
| 12 | properati_sell | `properati_sell_grouped` but in JSON |
| 13 | properati_sell_grouped_month | Properati sale data within Baires grouped by barrios - with basic stats (properati + census + barrios and grouped by month and year) |
| 14 | properati_sell_month | `properati_sell_grouped_month` but in JSON |


#### Notes:

1. Refer to [Notebook](../Discover%20Data.ipynb) for how 6 - 9 were created. 
2. Refer to [Notebool](../Merging%20Sell%20Data.ipynb) for how 10 - 14 were created.
3. Used [barrios data](../shape%20files/barrios.csv) from the Baires government [portal](https://data.buenosaires.gob.ar/dataset/barrios)
4. The months and years used to group data in `properati_barrios_grouped_month` are from the `created-on` columns - some properties were created before 2015 but appeared in the 2015 datasets. 



