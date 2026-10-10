# Youth Suicide and Unemployment: Exploratory Visualization

A 2019 **CA682 Data Visualization and Management** academic project, exploring country-level youth suicide and unemployment data for ages 15–24 during 2010–2014.

## Analysis and visualizations

The Python notebook uses **pandas** to inspect, filter, reshape, and join country-year data, then **Plotly** to create interactive grouped bars, time-series displays, country comparisons, and choropleth maps.

The project demonstrates an exploratory workflow from data preparation to visual communication. Its figures describe selected records; summed rates in the original plots are not population-weighted global measures or causal estimates.

## Repository contents

| File | Purpose |
| --- | --- |
| [DataVisualAssign.ipynb](DataVisualAssign.ipynb) | Analysis notebook and interactive visualizations |
| `SuicideRate.csv` | Suicide-data snapshot: 27,820 records |
| `UnempRate.csv` | Youth-unemployment snapshot: 219 records |
| `DVM_Assignment_Report.pdf` | Original academic report |

## Data sources

- [Suicide Rates Overview 1985 to 2016](https://www.kaggle.com/datasets/russellyates88/suicide-rates-overview-1985-to-2016), uploaded by `russellyates88`.
- [World Bank Youth Unemployment Rates](https://www.kaggle.com/datasets/sovannt/world-bank-youth-unemployment), uploaded by `sovannt`.

The notebook selects the study period and age group, reshapes unemployment years into rows, joins on country and year, and retains complete joined observations.

## Open the project

With Jupyter installed:

```bash
git clone https://github.com/RazanAlsulieman/DataVisualizationProject.git
cd DataVisualizationProject
jupyter notebook DataVisualAssign.ipynb
```

Keep both CSV files beside the notebook. **Dependencies:** pandas, Plotly, and Jupyter. The original setup records Python 3.7.1 and Anaconda Navigator 1.9.6; individual package versions are not pinned, so execution requires a compatible environment.


