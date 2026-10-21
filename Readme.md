# High-Performance Big Data Analytics Using R

## Overview

This project explores high-performance data processing and analytics using R and the NYC Yellow Taxi trip dataset for January to March 2023.

The notebook demonstrates data preparation, efficient data manipulation, functional programming, vectorized computation, parallel processing, performance benchmarking, and visualization.

## Objectives

- Process large datasets efficiently using `data.table`.
- Clean data, handle missing values, remove duplicates, and filter invalid records.
- Analyze taxi demand, fares, revenue, routes, and payment preferences.
- Compare functional programming approaches with vectorized operations and `data.table`.
- Evaluate sequential and parallel processing using `foreach` and `doParallel`.
- Benchmark execution time and examine memory usage.
- Visualize analytical results using `ggplot2`.

## Technologies Used

- **Language:** R
- **Data processing:** `data.table`, `arrow`
- **Functional programming:** `purrr`
- **Parallel computing:** `foreach`, `doParallel`
- **Benchmarking:** `microbenchmark`
- **Date and time processing:** `lubridate`
- **Visualization:** `ggplot2`

## Dataset

The project uses NYC Taxi and Limousine Commission (TLC) Yellow Taxi trip records for January, February, and March 2023, along with the taxi-zone lookup table.

The notebook downloads the required files automatically when they are not already available locally.

Dataset source: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

## Project Structure

```text
Lab8-R-Analytics/
├── Lab8_Rprog.ipynb
├── README.md
├── .gitignore
└── data/                 # Downloaded locally; not committed
```

## Key Tasks

1. **Data acquisition and preparation:** Download, inspect, clean, and transform taxi trip records.
2. **Transportation analytics:** Examine trip demand, fares, revenue, popular routes, pickup zones, and payment preferences.
3. **Performance comparison:** Compare `apply()`, `rowSums()`, vectorized arithmetic, `lapply()`, `purrr::map()`, `tapply()`, `aggregate()`, and `data.table`.
4. **Parallel computing:** Compare sequential and parallel processing using monthly data partitions.
5. **Performance benchmarking:** Measure execution time and memory footprint.
6. **Data visualization:** Generate charts using `ggplot2`.
7. **Critical analysis:** Evaluate performance, scalability, memory usage, and trade-offs between approaches.

## How to Run

1. Clone or download this repository.
2. Open `Lab8_Rprog.ipynb` in Google Colab or a compatible Jupyter environment with an R kernel.
3. Alternatively, use an R environment that supports Jupyter notebooks.
4. Run the cells sequentially from top to bottom.
5. Allow the notebook to install the required R packages and download the dataset.
6. Review the tables, charts, benchmark results, and analytical observations.

**Requirements:** An R environment, internet access for initial package and dataset downloads, and sufficient RAM for processing large Parquet files. Parallel performance depends on the available CPU resources.

## Expected Outcomes

The analysis produces:

- Summary statistics and cleaned taxi trip records.
- Demand and revenue analyses across time periods and locations.
- Comparisons of programming and aggregation techniques.
- Sequential-versus-parallel execution timings.
- Benchmark and memory-usage summaries.
- Visualizations of trip demand, fares, routes, and payment preferences.

## Conclusion

This project demonstrates how R can be used for large-scale data analysis and how different programming techniques affect execution time and memory consumption. It highlights the practical use of `data.table`, vectorized operations, functional programming, and parallel computing for transportation analytics.

## Author

Ketki Gaikwad  
Computer Engineering  
Vidyalankar Institute of Technology
