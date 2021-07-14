# pandas-challenge
HW assignment for Pandas

```python
# Dependencies and Setup
import pandas as pd
import numpy as np

# Raw data file
file_to_load = "HeroesOfPymoli/Resources/purchase_data.csv"

# Read purchasing file and store into pandas data frame
purchase_data = pd.read_csv(file_to_load)

total_players = purchase_data_df["SN"].nunique()
total_players_df = pd.DataFrame({"Number of Total Players": [total_players]})
total_players_df

```

<!-- unique_items = purchase_data_df["Item ID"].nunique()
average_price = purchase_data_df["Price"].mean()
number_of_purchases = purchase_data_df["Purchase ID"].nunique()
total_revenue = purchase_data_df["Price"].sum()
summary_table_df = pd.DataFrame({"Number of Unique Items": [unique_items],
                                 "Average Price": [f"${round(average_price, 2)}"],
                                 "Number of Purchases": [number_of_purchases],
                                 "Total Revenue": [f"${float(total_revenue)}"]})
summary_table_df -->




```
