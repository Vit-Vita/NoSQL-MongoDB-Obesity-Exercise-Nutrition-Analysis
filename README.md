# Obesity, Exercise and Nutrition in the USA : Data Analysis using NoSQL

Obesity is often referred to as a global epidemic whose prevalence grows in develped and developing countries alike. One of the countries where it is most prevalent is undoubtedly the United States of America. Since 1984, The Behavioral Risk Factor Surveillance System (BRFSS) has conducted health-related telephone surveys on behalf the Center of Disease Control and Prevention to collect state data about U.S. residents regarding their health-related risk behaviors, chronic health conditions, and use of preventive services. Every year, it conducts suverys with over 400'000 adults across the US.

On the basis of their surveys, they have published a dataset found in the "Data Catalog" of Data.gov which includes data on adults' diet, physical activity, and weight status which spans from 2011 to 2023 and make be found at the following link: https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system.

Using this data, we will closely examine the percentage of individuals qualified as obese or overweight in each US State, examine how these percentages changed over time and also possible correlated factors, such as income, ethnicity, nutrition and exercise.

To do so, we will first extract the data, load it into MongoDB then transform it. The transformation phase includes some quality checks such as identifying missing values, duplicates between fields and duplicates within the data and also identifying perpetually empty or unchanging fields which bring nothing to the analysis.

We will then move on to the analysis, by examining the following main questions which will be broken down into smaller sub-questions:

- Which State has the highest percentage of adults who are either obese or overweight?
- Are certain ethnicites more likely to be obese or overweight?
- Is a lower income associated with higher rates of adults being overweight or obese?
- Has there been a decline or increase in obesity from 2011 to 2023?
- Which State has the lowest percentage of adults consuming vegetables or fruits at least once per day?
- What percentage of Americans regularily exercise?
