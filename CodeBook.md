# CodeBook for Electric Power Consumption Project

## Overview

This codebook describes the variables in the dataset used for this analysis and details the transformations applied to create the final tidy dataset and plots. The dataset represents electric power consumption measurements from a household.

## Variables

The following variables are included in the dataset:

- **Date**: Date of measurement in the format `dd/mm/yyyy`.
- **Time**: Time of measurement in the format `hh:mm:ss`.
- **Global_active_power**: Household global minute-averaged active power (in kilowatts).
- **Global_reactive_power**: Household global minute-averaged reactive power (in kilowatts).
- **Voltage**: Minute-averaged voltage (in volts).
- **Global_intensity**: Household global minute-averaged current intensity (in amperes).
- **Sub_metering_1**: Energy sub-metering for the kitchen (in watt-hours).
- **Sub_metering_2**: Energy sub-metering for the laundry room (in watt-hours).
- **Sub_metering_3**: Energy sub-metering for electric water heater and air conditioner (in watt-hours).

## Data Transformations

1. **Date Conversion**: The `Date` and `Time` columns were combined into a single datetime object to facilitate time-series plotting.
2. **Filtering**: Only data from the dates `2007-02-01` and `2007-02-02` was used for this analysis.
3. **Handling Missing Values**: Missing values in the dataset are represented by `?` and were handled by converting them to `NA` during data import.

## Plots

### Plot 1: `plot1.png`
- **Description**: A histogram of `Global_active_power`.
- **Objective**: To show the distribution of global active power for the two-day period.

### Plot 2: `plot2.png`
- **Description**: A line plot of `Global_active_power` over time.
- **Objective**: To observe changes in global active power over the two-day period.

### Plot 3: `plot3.png`
- **Description**: A line plot of `Sub_metering_1`, `Sub_metering_2`, and `Sub_metering_3` over time.
- **Objective**: To compare energy consumption across different sub-metered areas over time.

### Plot 4: `plot4.png`
- **Description**: A multi-panel plot with the following components:
  - Top left: `Global_active_power` over time
  - Top right: `Voltage` over time
  - Bottom left: Energy sub-metering over time
  - Bottom right: `Global_reactive_power` over time
- **Objective**: To provide a comprehensive view of the different aspects of power consumption and voltage for the household over time.

## Notes

- This project uses only base R plotting functions to create the plots.
- Each plot file can be reproduced independently by running the corresponding R script.

## License

This project is licensed under the MIT License.
