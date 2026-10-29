# CodeAlpha Data Visualization: Somalia Agriculture

## Project Overview

This project explores agricultural data for Somalia from 2013 to 2023, focusing on three crops: sorghum, maize (corn), and rice.

Using Python and data visualization libraries, the project examines crop production, yield, and harvested area to identify trends, compare crops, and communicate key findings through charts and written interpretations.

## Project Objectives

- Compare recorded production across the three crops.
- Analyze annual crop production trends from 2013 to 2023.
- Identify the highest and lowest recorded sorghum production.
- Examine crop yield trends over time.
- Explore changes in harvested area for each crop.
- Present agricultural data through clear and informative visualizations.

## Dataset

The dataset was obtained from **FAOSTAT**, the statistical database of the Food and Agriculture Organization of the United Nations (FAO).

- **Country:** Somalia
- **Period:** 2013–2023
- **Crops:** Sorghum, maize (corn), and rice
- **Indicators:** Production, yield, and harvested area

Official source: [FAOSTAT Data Catalog](https://www.fao.org/faostat/en/#data)

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Excel

## Visualizations

The notebook includes five visualizations:

1. **Total Recorded Crop Production** — compares total recorded production across the selected crops.
2. **Annual Crop Production Trends** — examines changes in production over time.
3. **Highest and Lowest Sorghum Production** — highlights the highest and lowest recorded sorghum production values.
4. **Crop Yield Trends** — compares crop yield patterns over the study period.
5. **Harvested Area Trends** — examines changes in the area harvested for each crop.

Each visualization is accompanied by an interpretation to explain the main findings.

## Key Findings

- Sorghum recorded the largest decline in production between 2013 and 2023 among the three crops.
- Maize production also declined over the study period.
- Rice production remained relatively stable between 2013 and 2023.
- Sorghum yield decreased substantially, while rice yield increased.
- Harvested area changed differently across the three crops, showing that production trends should be considered alongside yield and harvested area.

These findings describe the recorded values in the dataset and do not, by themselves, establish the causes of the observed changes.

## Project Files

- `Somalia_Agriculture_Visualization.ipynb` — notebook containing the analysis, charts, and interpretations.
- `Somalia_Agriculture_EDA.xlsx` — Excel dataset used in the analysis.

## How to Run the Project

1. Clone or download this repository.
2. Ensure Python and Jupyter Notebook are installed, or upload the notebook to Google Colab.
3. Install the required libraries:

   ```bash
   pip install pandas matplotlib seaborn openpyxl
   ```

4. Keep the Excel dataset in the same directory as the notebook.
5. Open and run `Somalia_Agriculture_Visualization.ipynb` from beginning to end.

## Conclusion

This project demonstrates how data visualization can help explore agricultural production, yield, and harvested area patterns in Somalia. The charts provide a clearer view of changes over time and support further investigation into agricultural performance.

## Author

**Abdulkadir Ahmed Hussein**

## Acknowledgment

Data source: Food and Agriculture Organization of the United Nations (FAO), through FAOSTAT.
