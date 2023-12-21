# Data Visualization Final Project - HeartFit
## A non-technical project exploring the relationship between BMI and Heart Disease

This project explores the relationship between heart disease and BMI using data-driven insights which provide valuable information and acess to an interactive tool.

# 1. Dataset Description
<table>
<thead><tr>
<th>Attribute</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Age</strong></td>
<td>Age of a patient [years]</td>
</tr>
<tr>
<td><strong>Sex</strong></td>
<td>Gender of the patient [M: Male, F: Female]</td>
</tr>
<tr>
<td><strong>ChestPain</strong></td>
<td>Chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]</td>
</tr>
<tr>
<td><strong>RestingBP</strong></td>
<td>Blood pressure in Hg (Normal blood pressure - 120/80 Hg)</td>
</tr>
<tr>
<td><strong>Cholesterol</strong></td>
<td>Serum cholestrol level in blood (Normal cholesterol level below for adults 200mg/dL)</td>
</tr>
<tr>
<td><strong>FastingBS</strong></td>
<td>Fasting Blood Sugar (Normal less than 100mg/dL for non diabetes for diabetes 100-125mg/dL)</td>
</tr>
<tr>
<td><strong>RestingECG</strong></td>
<td>Resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of &gt; 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]</td>
</tr>
<tr>
<td><strong>MaxHR</strong></td>
<td>Maximum heart rate achieved [Numeric value between 60 and 202]</td>
</tr>
<tr>
<td><strong>ExerciseAngina</strong></td>
<td>Exercise-induced angina [Y: Yes, N: No]</td>
</tr>
<tr>
<td><strong>Oldpeak</strong></td>
<td>oldpeak = ST [Numeric value measured in depression]</td>
</tr>
<tr>
<td><strong>ST_Slope</strong></td>
<td>The slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]</td>
</tr>
<tr>
<td><strong>HeartDisease</strong></td>
<td>output class [1: heart disease, 0: Normal]</td>
</tr>
</tbody>
</table>

# 2. Hypothesis
H0: There is no statistical significant difference between BMI categories in experiencing Heart failure.
Ha: There is a statistical significant difference between BMI categories in experiencing Heart failure.

# 3. Exploring Categorical Features
Gender, Chest Pain, Exercise Induced Angina
Count Plot
     
# 4. Exploring Numerical Features
Age, MaxHR, BMI
KDE Plot
Box Plot
     
# 5. Bivarate Visualizations
Swarm Plot
Scatter Plot

# 6. Exploring Additional Variables
Box Plot: Heart Disease, Age, and Sex
Box Plot: Heart Disease, BMI, and Sex

# 7. Correlation Analysis
Spearman Correlation Matrix

# 8. Interactive Dashboards - Jupyter Widgets
i) BMI and Heart Disease - This interactive dashboard creates a dropdown menu where the user can select different BMI categories, and the scatter plot will dynamically update based on the users BMI category selection. 

ii) Weight and Heart Disease - This interactive dashboard creates a slider where the user can select different weights, and the scatterplot will dynamically update based on the users selected weight.

# 9. Conclusion
## Statistical Tests:
1. Chi-square Statistic
2. Mann-Whitney U Statistic

# 10. Recommendations
1. Develop Gender-Tailored Interventions
2. Explore other Gender-Related Factors
3. Explore Additional Variables


