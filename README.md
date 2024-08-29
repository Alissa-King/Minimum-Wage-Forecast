# Oregon Minimum Wage Analysis and Projection

This project analyzes historical minimum wage data for Oregon and provides projections for future minimum wage rates using different methodologies. It includes data visualization and statistical analysis to better understand the relationship between minimum wage increases and changes in the Consumer Price Index (CPI).

## Features

- Historical data analysis of Oregon's minimum wage (2016-2024)
- CPI data analysis (2010-2022)
- Minimum wage projections using two methods:
  - Linear regression trend analysis
  - CPI-indexed projections
- Visualization of historical data and future projections
- Comparison of annual minimum wage increases vs CPI increases
- Confidence interval calculation for trend projections

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Alissa-King/oregon-minimum-wage-analysis.git
   ```
2. Install the required packages:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

## Usage

Run the main script:

```
python oregon_minimum_wage_analysis.py
```

This will generate several visualizations and output statistical information to the console.

## Output

The script generates the following visualizations:

1. `minimum_wage_projections.png`: Historical data and projections (2016-2030)
2. `minimum_wage_vs_cpi.png`: Comparison of minimum wage vs CPI (2016-2022)
3. `annual_increases.png`: Annual increases in minimum wage vs CPI
4. `projection_comparison.png`: Comparison of different projection methods (2025-2030)
5. `trend_projection_confidence_interval.png`: Trend projection with 95% confidence interval

## Data Sources

- Minimum wage data: Based on Oregon's official minimum wage schedule
- CPI data: Estimated based on publicly available information

## Limitations

- The CPI data used in this analysis is estimated and may not reflect the exact figures used by Oregon's Bureau of Labor and Industries.
- Projections are based on historical trends and may not account for unforeseen economic changes or policy adjustments.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](https://github.com/yourusername/oregon-minimum-wage-analysis/issues) if you want to contribute.

## License

This project is licensed under the MIT License.
