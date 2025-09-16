# Internet Usage Dashboard Analysis

## Overview
This project analyzes global internet penetration patterns from 2000 to 2023. It prepares a clean dataset for self-explanatory, interactive Tableau dashboards that investigate factors affecting internet penetration, identify regions with limited connectivity and support a report proposing recommendations to improve internet access.

## Key points
- Loading and combining datasets from multiple sources
- Data cleanup, EDA and feature engineering
- Correlation analysis

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/juchnowicz/internet-usage-dashboard-analysis.git
```

2. Create `/data` and `/models` folders in the cloned repo.


3. Download the datasets and place in the `/data` folder:

[Data sources](https://www.dropbox.com/scl/fo/eopg3mphmfnq25k2cy2dj/ANCmg-Ioa-WJximPzRELjHU?rlkey=mbjjvvp1ygipudw11tjgeiwgp&st=xlnn7nld&dl=0){:target="_blank"}


4. Download the packaged Tableau workbook and place in the `/models` folder:

[Tableau workbook](https://www.dropbox.com/scl/fo/k4tv2qaeye4tjvt78aziz/AOvpEhiZJUjjo5mVjPD6zrM?rlkey=izp05xokg63qrh4ixa5gbjh04&st=q0un9gh9&dl=0){:target:="_blank"}


5. Run the `analyzing_global_internet_patterns_dc_challenge.ipynb` notebook to reproduce the analysis.


6. The output of the analysis is a consolidated data file `internet_data_v5.csv` saved to the `/data` folder. After saving the file, open the `Tracking Internet Access and Disconnected Regions (2000-2023).twbx` workbook and connect the data file if required to view the two analytics dashboards.