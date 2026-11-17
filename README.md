# Air Pollution Exposure and Childhood Asthma — Exploratory Data Analysis

### Project Overview

This project explores the relationship between hazardous air pollutant exposure and childhood asthma prevalence across U.S. states and years.

Using Python-based Exploratory Data Analysis (EDA), I examined pollutant exposure patterns, calculated correlations, and developed visualizations to understand whether higher exposure levels tend to coincide with higher childhood asthma prevalence.

The goal was to translate environmental data into meaningful insights that can support further investigation and informed decision-making.

### Objectives

- Explore the relationship between hazardous air pollutant exposure and childhood asthma prevalence.
- Examine pollutant-specific correlations with childhood asthma prevalence.
- Investigate the relationship between pollutant exposure and mortality rates.
- Use statistical analysis and visualizations to communicate findings.
- Identify data limitations and interpret results responsibly.

### Tools & Technologies

- **Python** — Data analysis
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Exploratory analysis

### Dataset Overview

The analysis used a dataset containing **2,448 records and 11 columns**.

Key variables included:

| Variable | Description |
|---|---|
| State | U.S. state |
| Year | Year of observation |
| Pollutant | Hazardous air pollutant |
| Exposure_Value | Recorded pollutant exposure value |
| Deaths | Recorded deaths |
| Population | Population count |
| Crude Rate | Crude mortality rate |
| Child_Asthma_Prevalence | Childhood asthma prevalence (%) |

The dataset covered eight pollutant groups:

1. 1,3-butadiene
2. Acetaldehyde
3. Benzene
4. Carbon tetrachloride
5. Diesel Particulate Matter
6. Ethylene oxide
7. Formaldehyde
8. Napthalene

**Data availability:** Childhood asthma prevalence was available for 1,112 of the 2,448 records. The asthma-focused analysis therefore used these 1,112 complete observations.

### Analytical Approach

**1. Data exploration and preparation**

- Inspected dataset structure, column types, and missing values.
- Identified relevant variables for asthma and mortality analysis.
- Created separate analytical datasets for mortality and childhood asthma.

**2. Correlation analysis**

- Calculated the overall correlation between pollutant exposure and childhood asthma prevalence.
- Examined pollutant-specific correlations.
- Analyzed pollutant exposure against crude mortality rates.

**3. Data visualization**

Created visualizations to communicate the findings, including:

- Correlation heatmaps
- Pollutant-specific correlation bar charts
- Scatter plots
- Regression plots

### Key Findings

**1. Overall relationship with childhood asthma**

The overall Pearson correlation between pollutant exposure and childhood asthma prevalence was approximately **0.12**, indicating a weak positive relationship in the available observations.

**2. Pollutant-specific correlations**

All eight pollutant groups showed positive correlations with childhood asthma prevalence.

| Pollutant | Correlation |
|---|---:|
| 1,3-butadiene | 0.374 |
| Benzene | 0.373 |
| Carbon tetrachloride | 0.366 |
| Napthalene | 0.358 |
| Formaldehyde | 0.338 |
| Diesel Particulate Matter | 0.323 |
| Acetaldehyde | 0.285 |
| Ethylene oxide | 0.104 |

These results describe associations in the analyzed dataset. They do not establish that any particular pollutant causes childhood asthma.

**3. Mortality-focused analysis**

The analysis also examined correlations between pollutant exposure and crude mortality rates.

The pollutant-specific results varied in direction and strength. For example, Formaldehyde showed a positive correlation (0.131), while 1,3-butadiene showed a negative correlation (-0.186).

These descriptive results require further investigation before drawing conclusions.

### Visualizations

The project includes:

- Exposure vs. childhood asthma prevalence correlation heatmap
- Pollutant-specific correlation comparison
- Exposure vs. childhood asthma scatter plot
- Regression visualization showing the overall trend
- Pollutant-specific mortality correlation chart

### Limitations

Several limitations should be considered when interpreting the findings:

- **Missing data:** Childhood asthma prevalence was available for only 1,112 of 2,448 records.
- **Correlation vs. causation:** Correlation does not establish a causal relationship between pollutant exposure and asthma prevalence.
- **Potential confounding factors:** Socioeconomic conditions, healthcare access, indoor exposures, and other environmental factors were not incorporated into this analysis.
- **Aggregated data:** State-level observations may not represent individual exposure or individual health outcomes.
- **Further validation:** Additional analysis is needed to account for repeated observations across states and years and to evaluate the robustness of the findings.

### Practical Implications

The findings can serve as a starting point for further environmental and public health research.

Potential next steps include:

- Investigating state-level and year-over-year patterns.
- Incorporating socioeconomic and healthcare-related variables.
- Exploring more complete asthma prevalence datasets.
- Applying more advanced statistical methods to examine relationships while accounting for additional factors.
- Evaluating whether observed patterns remain consistent across different periods and locations.

### What I Learned

This project strengthened my skills in:

- Exploratory Data Analysis using Python.
- Data cleaning and missing-value assessment.
- Correlation analysis and statistical interpretation.
- Creating meaningful data visualizations.
- Communicating analytical findings to a practitioner audience.
- Recognizing analytical limitations and avoiding unsupported conclusions.

### Project Takeaway

**Good data analysis is not just about identifying patterns; it is about understanding what the evidence supports, recognizing its limitations, and communicating insights responsibly.**

---

*Project Type: Exploratory Data Analysis (EDA) | Environmental & Public Health Analytics | Extern Project 5*
