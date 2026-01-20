# sleep_data_cdc
Sleep, Stress, and School Engagement: What a National Student Survey Reveals

This study uses the 2023 CDC Youth Risk Behavior Survey (YRBS), Special Adolescent Data Collection (SADC), National Combined dataset.
The YRBS surveys hundreds of thousands of U.S. high school students about health behaviors, mental well-being, and school-related experiences. While the dataset does not include GPA or letter grades in this national file, it does capture several indicators closely linked to academic functioning, such as school attendance disruption and grade-level progression. The dataset has many columns, but I chose to work with a smaller set that best matched the questions I wanted to explore and had enough usable data.

The data (yrbs_2023_sadc_vars.csv) is extacted from main files: 
2023-SADC-SPSS-Input-Program.sps
sadc_2023_national.dat

The file "sps to csv" is the python file to extarct the data into csv using "2023-SADC-SPSS-Input-Program.sps" and "sadc_2023_national.dat"

The file "basic" has the code to analyse the data using matplotlib 

The file "pyecharts" has the code for the PyEcharts graphs and charts
