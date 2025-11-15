# Analysis of Public Travel Expenses in Brazil

This project performs an exploratory analysis of public travel expenses by the Brazilian federal government, using data made available by the **Transparency Portal**. The analysis includes data processing, visualization, and report generation to provide meaningful insights.

## Objectives
- Consolidate public travel data and extract insights about expenses.
- Identify spending patterns, trip duration, and travel frequency by public positions.
- Generate visualizations and consolidated reports for better understanding of the results.

## Data Source
The data used in this analysis was obtained from the [Transparency Portal](https://portaldatransparencia.gov.br/), focusing on the fiscal year **2023**.

## Key Features
1. **Data Processing**
   - Conversion of numeric values and handling of missing data.
   - Calculation of total travel expenses for each trip.
   - Date conversions to analyze travel duration and monthly patterns.

2. **Data Consolidation**
   - Grouping data by public position to calculate:
     - Average travel expenses.
     - Average trip duration.
     - Total expenses by position.
     - Most frequent travel destinations.
   - Filtering relevant public positions based on spending thresholds.

3. **Visualization**
   - Generation of bar charts to visualize:
     - Total number of trips by position.
     - Average and total expenses by position.
     - Average trip duration by position.
   - All visualizations are saved as `.png` files for further use.

4. **Report Generation**
   - Consolidated data is saved as an Excel file (`tabela_final.xlsx`) for easy sharing and deeper analysis.

## Project Structure
- `Análise final.ipynb`: Main Jupyter Notebook with all code and comments.
- `2023_Viagem.csv`: Input dataset with travel expenses data.
- `tabela_final.xlsx`: Output Excel file with consolidated results.
- `grafico1.png`, `grafico2.png`, `grafico3.png`, `grafico4.png`: Visualizations of the analysis.

## Libraries Used
- `pandas`: Data manipulation and analysis.
- `matplotlib`: Data visualization.

## How to Run
1. Clone the repository and open the notebook in Google Colab or a local Jupyter environment.
2. Ensure the input file (`2023_Viagem.csv`) is in the same directory.
3. Execute all cells to process the data and generate outputs.
4. View the results in the output Excel file and the saved visualizations.

## Results
The analysis highlights the following:
- Distribution of travel expenses across public positions.
- Insights into average spending and trip durations.
- Identification of frequent destinations by position.

## License
This project is licensed under the MIT License.
