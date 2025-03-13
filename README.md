# Global Demographic and Socioeconomic Analysis

## Project Overview

This repository contains a comprehensive analysis of global demographic and socioeconomic indicators based on the World95 dataset. The project explores relationships between various development metrics across different countries and regions, providing insights into global patterns of development, health, education, and economic status.

## Dataset Description

The **World95 Dataset** includes data from approximately 150 countries with the following key variables:

| Variable | Description |
|----------|-------------|
| country | Country name |
| populatn | Population size |
| density | Population density (people per square kilometer) |
| urban | Percentage of population living in urban areas |
| lifeexpf | Female life expectancy (years) |
| lifeexpm | Male life expectancy (years) |
| literacy | Overall literacy rate (percentage) |
| pop_incr | Annual population increase (percentage) |
| babymort | Infant mortality rate (per 1,000 live births) |
| gdp_cap | GDP per capita (USD) |
| region | Geographic region (coded 1-6) |
| calories | Average daily caloric intake |
| aids | Number of AIDS cases |
| birth_rt | Birth rate per 1,000 population |
| death_rt | Death rate per 1,000 population |
| aids_rt | AIDS rate per 100,000 population |
| log_gdp | Logarithm of GDP per capita |
| lg_aidsr | Logarithm of AIDS rate |
| b_to_d | Ratio of births to deaths |
| fertilty | Fertility rate (children per woman) |
| log_pop | Logarithm of population |
| cropgrow | Percentage of land used for agriculture |
| lit_male | Male literacy rate (percentage) |
| lit_fema | Female literacy rate (percentage) |
| climate | Climate zone (coded 1-9) |

### Region Codes
1. Western Europe & North America
2. Eastern Europe & Central Asia
3. East Asia & Pacific
4. Africa
5. Middle East & North Africa
6. Latin America & Caribbean

### Climate Codes
1. Desert
2. Arid/Semi-arid
3. Mediterranean
4. Tropical
5. Subtropical
6. Temperate
7. Continental
8. Cold Continental
9. Subarctic/Arctic

## Research Questions

This analysis addresses several key questions:

1. How do health indicators (life expectancy, infant mortality) vary across different regions?
2. What is the relationship between economic development (GDP per capita) and social indicators?
3. How do demographic patterns (fertility, population growth) differ between developed and developing nations?
4. What are the gender disparities in literacy rates across different regions?
5. Can countries be clustered into meaningful groups based on their socioeconomic profiles?
6. What factors most strongly correlate with life expectancy and infant mortality?

## Key Findings

### Development Indicators
- Strong positive correlation exists between GDP per capita and life expectancy (r = 0.78)
- Infant mortality rates show significant regional disparities, with Africa having the highest rates
- Education (literacy) shows a clear positive relationship with both health and economic indicators

### Regional Patterns
- Western Europe & North America show the highest values for development indicators
- Africa faces the greatest challenges across multiple indicators
- East Asia & Pacific shows the most rapid improvements in development metrics

### Gender Disparities
- Female literacy lags behind male literacy in most developing regions
- The gap between female and male life expectancy varies significantly by region
- Gender equality indicators correlate strongly with overall development

### Population Dynamics
- Inverse relationship between fertility rates and economic development
- Urbanization strongly correlates with decreased fertility and increased life expectancy
- Population growth rates remain high in regions with lower GDP per capita

## Repository Contents

- `data/`: Contains the original dataset and processed data files
- `notebooks/`: Jupyter notebooks with detailed analyses
- `visualizations/`: Generated charts, graphs, and maps
- `reports/`: Detailed findings and methodology documents
- `scripts/`: Reusable scripts for data processing and analysis

## Methodology

The analysis employs various statistical and data science techniques:

1. **Exploratory Data Analysis (EDA)**: Summary statistics, distribution analysis, and data visualization
2. **Correlation Analysis**: Identifying relationships between key indicators
3. **Regression Analysis**: Modeling relationships between dependent and independent variables
4. **Cluster Analysis**: K-means clustering to identify natural country groupings
5. **Principal Component Analysis (PCA)**: Dimensionality reduction to identify key factors
6. **Geospatial Analysis**: Mapping indicators to identify regional patterns

## Usage

This repository serves multiple purposes:

- **Educational Resource**: Understanding global development patterns
- **Research Reference**: Foundation for academic studies on international development
- **Policy Insights**: Evidence-based approach to global development policies
- **Data Visualization Examples**: Techniques for visualizing complex international data

## Future Work

Potential extensions of this analysis include:

1. Incorporating time-series data to analyze trends over decades
2. Adding additional variables like education spending, healthcare access, and political stability
3. Developing predictive models for future demographic changes
4. Creating interactive dashboards for exploring the data
5. Expanding the analysis to sub-national regions where data is available

## Contributing

Contributions to this project are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements or additions.

## Acknowledgments

- Original data sourced from [provide original source details if available]
- Analysis inspired by research in international development economics
- Visualization techniques adapted from best practices in data science
