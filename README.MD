# COVID-19 Vaccination Analysis: A Case Study on Latin America

View the full interactive dashboard of the COVID-19 Vaccination Analysis for Latin America on Tableau using the link below:<br>
[Interactive Dashboard](https://public.tableau.com/app/profile/daniel.ribeiro5601/viz/COVID19AnalysisLatinAmerica/Dashboard?publish=yes)


## Table of Contents

- [COVID-19 Vaccination Analysis: A Case Study on Latin America](#covid-19-vaccination-analysis-a-case-study-on-latin-america)
  - [Table of Contents](#table-of-contents)
  - [Project Objective](#project-objective)
  - [Project Structure and Steps](#project-structure-and-steps)
  - [Tools and Techniques Utilized](#tools-and-techniques-utilized)
  - [Specific Results and Outcomes](#specific-results-and-outcomes)
  - [What I Have Learned From This Project](#what-i-have-learned-from-this-project)
  - [Final Thoughts](#final-thoughts)
  - [How to use this repository](#how-to-use-this-repository)

## Project Objective

The project aims to analyze the efficiency of COVID-19 vaccination campaigns in select Latin American countries by examining their impact on COVID-19 deaths and new cases. Using SQL to extract relevant data and Tableau for visualization, we strive to answer key questions about the effectiveness of the vaccines.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## Project Structure and Steps

1. **Identifying Key Questions and Goals**
    - The main question: "Are COVID-19 vaccines effective?"
    - Breaking down this overarching question into smaller, more specific ones:
      - Do COVID-19 vaccines reduce the number of COVID-related deaths?
      - Do they reduce the number of new COVID-19 cases?
      - Do they provide immunity against COVID-19?

2. **Dataset Selection and Filtering**
    - Focused on select Latin American countries: Mexico, Chile, Ecuador, Brazil, Peru, and Argentina.
    - Data extracted from the **World Health Organization (WHO)** database, focusing on two tables:
      - **vaccination_data**: Includes details like the country name, ISO code, and the date the first vaccine was administered.
      - **who_covid_global_data**: Contains daily data on new and cumulative COVID-19 cases and deaths by country and region.
      
3. **Data Preparation**
    - Filter data to include only the selected Latin American countries.
    - Create two new columns to track vaccination progress:
      - **days_since_vaccine**: Displays a countdown to the first vaccine and a count-up thereafter.
      - **vaccination_started**: Indicates whether vaccinations had started (Yes/No).

4. **Calculating Death Rates**
    - Analyzed death rates against population size to determine "Deaths per Million" for each country.
    - This metric was derived by summing all deaths and dividing by the population, then multiplying by one million for clarity.

5. **Building Visualizations**
    - Constructed charts to visualize pre- and post-vaccination death rates to assess the impact of vaccines on mortality.
    - Built a **dashboard in Tableau** to provide a comprehensive overview of the data, displaying trends in COVID-19 cases, deaths, and vaccination rates over time.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## Tools and Techniques Utilized

- **SQL**: For extracting data from the WHO database.
- **Tableau**: For visualizations, including maps, line charts, and dashboards to track trends over time.
- **Data Analysis Techniques**:
  - Time series analysis for tracking daily changes in COVID-19 cases and vaccination progress.
  - Calculations of mortality rates before and after vaccine introduction.
- **Statistical Analysis**: To compare pre- and post-vaccine mortality and case rates.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## Specific Results and Outcomes

**1. Analyzing COVID-19 Mortality Trends**
- Created visualizations to track death rates before and after the start of vaccination campaigns.
- **Results**:
  - A general downward trend in death rates over time, suggesting a potential reduction in COVID-related mortality with increasing vaccination rates.
  - Some countries, like Brazil, showed resilience despite challenges with lockdown policies.

**2. Impact of Vaccination on New COVID-19 Cases**
- Visualized the rate of new cases before and after vaccination campaigns began.
- **Findings**:
  - Initially, an increase in new COVID-19 cases was observed as vaccination campaigns commenced.
  - Following a peak, there was a significant reduction in new cases, indicating the effectiveness of the vaccination campaigns in curbing the spread of the virus.

**3. Country-Specific Patterns**
- **Brazil**: Despite criticisms over relaxed lockdown measures, the country never exceeded a 7% mortality rate, demonstrating a significant effort to manage COVID-19's impact.
- **Other Countries**: Each country displayed unique patterns influenced by local policies and behaviors.

**4. Limitations and Additional Observations**
- While the dashboards show clear trends, the analysis was not fully conclusive about the direct impact of vaccines on mortality and case reduction.
- Other factors like government policies, public health campaigns, and behavioral changes likely played a role in the observed trends.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## What I Have Learned From This Project

- **Data Visualization Skills**: Developed the ability to create clear, comprehensive dashboards in Tableau for visual storytelling.
- **Statistical Insight**: Enhanced my understanding of how to calculate mortality rates and analyze their relationship with vaccination campaigns.
- **Critical Analysis**: Improved my ability to critically assess the data, identify patterns, and draw insights from complex datasets.
- **Storytelling with Data**: Learned how to structure a compelling narrative around vaccination efficiency using both qualitative and quantitative data.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## Final Thoughts

To answer our initial questions:
- **Do COVID-19 vaccines reduce mortality?** The data shows a general downward trend in death rates post-vaccination, but further analysis is needed for conclusive results.
- **Do vaccines reduce new COVID-19 cases?** There was a notable reduction in new cases after an initial spike during vaccination rollouts.
- **Do vaccines provide immunity against COVID-19?** The reduction in cases post-vaccination suggests increased resistance, but definitive conclusions require further exploration.

As Plato once said, "The only thing I know is that I know nothing." Our analysis has not reached definitive conclusions, but it provides a strong foundation for understanding the impacts of COVID-19 vaccination campaigns across different countries. By visualizing and interpreting these data trends, we hope to contribute meaningfully to the ongoing discourse on vaccine efficiency.

[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)

## How to use this repository

1. **Clone the repository** <br>
[https://github.com/realdanizilla/COVID19-LATAM.git](https://github.com/realdanizilla/COVID19-LATAM.git)

2. **Run the Jupyter Notebook**  
- Execute the `.ipynb` notebook to see data preprocessing steps
- Review SQL scripts used for data extraction and analysis from datasets on COVID-19 vaccination and cases.

3. **View Tableau Visualizations**  
Open the Tableau workbook (`.twb`) to see dashboards and visual insights on vaccination impact or access the [publick link](https://public.tableau.com/app/profile/daniel.ribeiro5601/viz/COVID19AnalysisLatinAmerica/Dashboard?publish=yes)

4. **Run Your Analysis**  
Use the provided data and scripts to replicate or further explore trends in COVID-19 vaccination efficiency.


[back to top](#covid-19-vaccination-analysis-a-case-study-on-latin-america)