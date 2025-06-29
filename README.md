# Covid_19-Data-Analysis

This repository contains a Jupyter Notebook for in-depth data analysis and visualization of COVID-19 case and death data. The project demonstrates how to collect, process, analyze, and visualize time-series COVID-19 data, using Python and popular data science libraries.

## Repository Structure

- **COVID_19_Data_Analysis_and_Visualization.ipynb**  
  The main notebook containing the entire workflow, including data loading, cleaning, analysis, and plotting.

## Features

- **Data Collection:**  
  Downloads and reads global COVID-19 time-series data for cases and deaths from public sources.

- **Data Processing:**  
  Cleans and structures the data for analysis, focusing on country/region and date breakdown.

- **Analysis:**  
  - Computes active, recovered, and death cases over time.
  - Aggregates data globally and by region.
  - Calculates trends, peaks, and other relevant epidemiological metrics.

- **Visualization:**  
  - Plots global trends for cases and deaths.
  - Visualizes recoveries and active cases over time.
  - Utilizes matplotlib, seaborn, and pandas plotting features for clear insights.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, geopandas, folium

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn geopandas folium
```

### Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/DharmikT11/Covid_19-Data-Analysis.git
    cd Covid_19-Data-Analysis
    ```

2. Open the notebook in Jupyter:
    ```bash
    jupyter notebook COVID_19_Data_Analysis_and_Visualization.ipynb
    ```

3. Run the notebook cells to perform the analysis and view the results.

## Data Sources

- [Johns Hopkins University CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)
- Other public datasets as referenced inside the notebook

## Example Outputs

The notebook will generate plots like:

- Global trend of COVID-19 cases
- Global trend of deaths and recoveries
- Regional and country-specific analysis

## Author

- [DharmikT11](https://github.com/DharmikT11)

## License

This project is licensed under the MIT License.


