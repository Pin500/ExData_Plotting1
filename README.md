# Exploratory Data Analysis Project: Electric Power Consumption

This project demonstrates an analysis of electric power consumption data collected from a single household over a period of four years. The analysis focuses on creating exploratory plots to examine household energy usage for a two-day period in February 2007. The dataset is available from the UC Irvine Machine Learning Repository.

## Files in This Repository

- **plot1.R**: R script that reads the data and generates `plot1.png`, a histogram of global active power.
- **plot2.R**: R script that reads the data and generates `plot2.png`, a line plot of global active power over time.
- **plot3.R**: R script that reads the data and generates `plot3.png`, a multi-line plot of energy sub-metering data over time.
- **plot4.R**: R script that reads the data and generates `plot4.png`, a series of plots showing global active power, voltage, sub-metering, and global reactive power over time.

- **plot1.png**: Histogram of global active power for the selected date range.
- **plot2.png**: Line plot of global active power over time.
- **plot3.png**: Multi-line plot of energy sub-metering over time.
- **plot4.png**: Series of plots showing various aspects of energy usage over time.

- **CodeBook.md**: Contains detailed descriptions of each variable, transformations applied, and explanations for the plots.

## How to Run the Scripts

1. Clone this repository to your local machine.
2. Make sure the dataset is in the working directory and is named `household_power_consumption.txt`.
3. Run each of the R scripts (`plot1.R`, `plot2.R`, `plot3.R`, `plot4.R`) to generate the corresponding PNG files. Each script reads the data, processes it, and saves a plot to the top-level folder of the repository.

## Data Source

The dataset used in this analysis comes from the UCI Machine Learning Repository and contains measurements of electric power consumption in one household over a four-year period.

- [Electric Power Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)

## License

This project is licensed under the MIT License.
