# Understanding Cardiovascular Risk Factors and Disease Prevalence
This project focuses on visualizing cardiovascular disease (CVD) data to provide insights into the prevalence, risk factors, and correlations associated with CVD. Through descriptive and exploratory data visualization techniques, the aim is to uncover patterns and trends that may aid in understanding and addressing cardiovascular health issues.
### Cardiovascular disease is the leading cause of death globally, responsible for approximately one-third of all deaths worldwide, according to the World Health Organization (WHO)

#### Risk Factors : [SOURCE](https://www.drugwatch.com/health/cardiovascular-health/)

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/aac50102-8581-4709-9fd2-549fed5409cc)


Understanding Cardiovascular Risk Factors and Disease Prevalence involves a comprehensive examination of the various factors contributing to heart health risks and the prevalence of cardiovascular disease within populations.By exploring the interplay between risk factors such as smoking, hypertension, obesity, and sedentary lifestyles, alongside the prevalence of cardiovascular disease across different demographics. 

The data originates from the Behavioral Risk Factor Surveillance System (BRFSS) in 2021, which is maintained by the World Health Organization (WHO). The data was collected as part of the BRFSS, which is a large-scale survey conducted to monitor health-related behaviors.The data was collected to understand health-related behaviors and risk factors associated with cardiovascular diseases.The dataset was created by LAKSHMAN CHANDRA HALDAR

Height_(cm), Weight_(kg), BMI, Alcohol_Consumption, Fruit_Consumption, Green_Vegetables_Consumption, FriedPotato_Consumption are continuous attributes and remaining attributes like General_Health, Checkup, Exercise, Heart_Disease, Skin_Cancer, Other_Cancer ,Depression, Diabetes, Arthritis, Sex, Smoking_History seems to be categorical attributes. In total there are 11 categorical attributes and 7 continuous attributes. 
Alcohol_Consumption, Fruit_Consumption, Green_Vegetables_Consumption, and FriedPotato_Consumption indicate the frequency of consumption for each individual, measured in times per month.

There are 308854 rows and 19 columns , the size of the dataset is about 30.9 MB

The dataset was found on https://datasetsearch.research.google.com/search?src=0&query=Cardiovascular%20diseases%20risk%20kaggle&docid=L2cvMTFrcXg4NHNreQ%3D%3D and License is [CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/) license. No changes to the original dataset were made before analysis.

### What factors are associated with the occurrence of heart disease among adults? 
Seeks to identify and understand the various factors that may contribute to the development of heart disease in adult populations. Here's a breakdown with these subquestions 

### 1) How does age impact the likelihood of developing heart disease?
### 2) Do individuals who report regular exercise have a lower prevalence of heart disease compared to those who do not exercise?
### 3) Consumption of fruits, green vegetables, and fried potatoes—on the prevalence of heart disease
### 4) How does the distribution of general health status differ between males and females in relation to heart disease prevalence?

**Hypotheses:**

**1) Age and Heart Disease:** There is an increased likelihood of developing heart disease with age due to cumulative exposure to risk factors, physiological changes, and declining cardiovascular health. Younger individuals may have a lower likelihood of developing heart disease compared to older individuals, as they are less likely to have accumulated significant risk factors and may maintain better cardiovascular resilience.

**2) Impact of Exercise:** Regular exercise is expected to correlate with a lower prevalence of heart disease due to its protective effects on cardiovascular health. Conversely, a lack of regular exercise may be associated with a higher prevalence of heart disease, given its links to increased cardiovascular risk factors.

**3) Dietary Habits:** How do dietary habits (consumption of fruits, green vegetables, and fried potatoes) impact the prevalence of heart disease among different age groups? Maintaining a healthy BMI through regular exercise, a balanced diet, and other lifestyle choices contributes to heart health and overall well-being.

### 1. How does age impact the likelihood of developing heart disease?

Age is a critical determinant of heart disease risk, and healthcare professionals often consider age along with other risk factors when assessing an individual's cardiovascular health.People age 65 and older are much more likely than younger people to suffer a heart attack, to have a stroke, or to develop cardiovascular diseases.

Aging can cause changes in the heart and blood vessels. For example, as you get older, your heart can't beat as fast during physical activity or times of stress as it did when you were younger. However, the number of heartbeats per minute (heart rate) at rest does not change significantly with normal aging.

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/bd5eab13-ebe1-47b9-8395-4d7c0e605b8c)

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/8344af32-fe24-4e48-b6a4-268477f632b7)

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/42218ccf-96bb-4af0-84f1-1a257ab31166)

**Analysis**: 

This indicates a clear relationship between age and the likelihood of developing heart disease. As age increases, there is a corresponding increase in the incidence of heart disease. This aligns with the common understanding that advancing age is a significant risk factor for cardiovascular diseases.

The plotted data illustrates the distribution of heart disease across different age categories. It shows a higher occurrence of heart disease in older age groups, particularly among individuals aged 65 and above . This reaffirms the notion that age plays a crucial role in predisposing individuals to heart-related ailments.

Aging leads to physiological changes in the heart and blood vessels, such as decreased heart rate during physical activity or stress. While the resting heart rate remains relatively stable with age, the heart's response to external stimuli diminishes over time.

Additionally, gender may intersect with age to influence cardiovascular risk. Among older adults, hypertension is notably associated with age, female gender, and obesity, indicating a complex interplay of factors contributing to heart disease

### 2.Do individuals who report regular exercise have a lower prevalence of heart disease compared to those who do not exercise?

Regular exercise helps strengthen the heart muscle, improve blood circulation, and enhance the efficiency of the cardiovascular system. It can lower blood pressure, reduce cholesterol levels (both LDL and triglycerides), and improve blood sugar control, all of which contribute to a reduced risk of heart disease.

Physical inactivity is one of the leading risk factors for noncommunicable diseases mortality. People who are insufficiently active have a 20% to 30% increased risk of death compared to people who are sufficiently active. Regular physical activity is proven to help prevent and manage noncommunicable diseases such as heart disease, stroke and diabetes  

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/2d04a308-7fbf-4d81-ae8f-18c7216109c6)

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/78d736a4-8f7d-4424-8195-dcfd4b60c846)

**Analysis**: 

Exercise and Heart Disease Prevalence: The data analysis suggests that individuals who report regular exercise have a lower prevalence of heart disease compared to those who do not exercise. This is evident from the lower counts of heart disease among those who engage in regular exercise, indicating a potential protective effect of physical activity against heart disease.

Regular exercise is known to strengthen the heart muscle, improve blood circulation, and enhance cardiovascular efficiency. It can also help lower blood pressure, reduce LDL cholesterol and triglyceride levels, and improve blood sugar control, all of which contribute to a reduced risk of heart disease.

Physical inactivity is a significant risk factor for noncommunicable diseases mortality. Insufficient physical activity increases the risk of death by 20% to 30% compared to those who are sufficiently active. Regular physical activity has been proven to prevent and manage noncommunicable diseases such as heart disease, stroke, and diabetes, highlighting its crucial role in maintaining overall health .

## 3. Consumption of fruits, green vegetables, and fried potatoes—on the prevalence of heart disease.
### Analysis Insights:

1. **Mean Consumption:**
   - Fruit consumption has a higher mean value compared to green vegetables and fried potatoes.

2. **Minimum Consumption:**
   - All categories have a minimum value of zero, indicating that some people do not consume these items.

3. **Variability:**
   - The standard deviation provides insight into the variability of consumption within each category.

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/7eeafa18-3648-4874-ad0e-e291e931bbd3)
![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/f1d794b2-6c63-496c-8d83-133cdae04077)

**Analysis**: 

To analyze plot for fruit consumption shows that individuals with heart disease tend to have a wider distribution of fruit consumption compared to those without heart disease. Specifically, the median fruit consumption appears slightly higher among individuals without heart disease. However, the spread (interquartile range) of fruit consumption is similar between the two groups. This suggests that while fruit consumption varies widely across both groups, it might have a slightly different central tendency for individuals with and without heart disease.

The second plot for green vegetables consumption, we observe a more pronounced difference between individuals with and without heart disease. The plot shows that individuals without heart disease generally have a higher median and a narrower distribution of green vegetables consumption compared to those with heart disease. This suggests a potential association between higher green vegetables consumption and lower prevalence of heart disease.

Lastly, this plot for fried potato consumption indicates a less distinct difference between individuals with and without heart disease. Both groups exhibit a similar spread and central tendency of fried potato consumption. This suggests that fried potato consumption might not strongly differentiate between individuals with and without heart disease based solely on this dietary habit.

### 4.How does the distribution of general health status differ between males and females in relation to heart disease prevalence?

The distribution of general health status between males and females varies significantly in relation to heart disease prevalence. By analyzing a dataset that categorizes individuals based on their general health and heart disease status, we can observe notable patterns.

![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/1f2717ce-88ed-44bb-ba99-b310a0866d79)
![image](https://github.com/SethupathiSubramanis/Cardiovascular-Disease-Analysis/assets/167128435/b522976e-204f-4aec-9230-0de01557308f)


**Analysis**: 

The analysis investigates the relationship between general health status, gender, and heart disease prevalence using a dataset of individuals. By categorizing individuals based on their general health and heart disease status, the study reveals important trends. The initial visualization displays the distribution of general health status among males and females, illustrating the count of individuals in each health category. The subsequent plot examines heart disease prevalence across these health categories and by gender, highlighting potential disparities in heart disease rates. Notably, certain health statuses may correlate with higher heart disease prevalence, and these patterns differ between males and females. This analysis underscores the importance of considering gender-specific health factors when assessing heart disease risk in populations.

This analysis looks at how people's general health and gender relate to their likelihood of having heart disease. The graphs show how many people fall into different health categories and how many of them have heart disease, broken down by gender. The charts reveal that heart disease rates can vary depending on general health status and gender, suggesting certain health conditions might increase the risk of heart disease more for men or women. Understanding these patterns can help tailor health interventions to specific groups and improve prevention efforts.

# Conclusion

In conclusion, the analysis underscores several key findings related to heart disease risk factors. Firstly, advancing age significantly increases the likelihood of developing heart disease, with a notable rise in incidence among individuals aged 65 and older. Secondly, regular exercise demonstrates a protective effect against heart disease, as evidenced by lower prevalence rates among those who engage in physical activity. Thirdly, dietary habits such as green vegetable consumption appear to correlate with lower heart disease prevalence, while the impact of fruit and fried potato consumption is less distinct. Lastly, disparities in heart disease rates between males and females exist across different general health statuses, emphasizing the need for gender-specific considerations in cardiovascular health assessments. These insights emphasize the multifaceted nature of heart disease risk and underscore the importance of lifestyle interventions and targeted health strategies to mitigate cardiovascular health disparities across diverse populations.


Sources : 

https://www.who.int/news-room/fact-sheets/detail/physical-activity#


https://www.nia.nih.gov/health/heart-health/heart-health-and-aging#


**Reflection:**  


The analysis provided offers valuable insights into the multifaceted relationships between age, exercise habits, dietary choices, general health status, and the prevalence of heart disease. These findings underscore the complex interplay of factors that contribute to cardiovascular health.
Looking at age, it's clear that advancing years significantly increase the risk of heart disease, aligning with common medical knowledge. This emphasizes the importance of age-specific cardiovascular care and preventive measures as individuals grow older. The data on exercise highlights the protective effects of regular physical activity, which can strengthen the heart and reduce cardiovascular risk factors.
Dietary habits, such as fruit and vegetable consumption, show intriguing patterns. While green vegetable intake appears beneficial, the impact of fruit consumption on heart disease prevalence seems less straightforward. These insights can guide dietary recommendations for heart health.
Gender differences in general health and heart disease prevalence are also noteworthy, indicating that risk factors and outcomes may vary between males and females. This highlights the importance of tailored approaches to cardiovascular care based on gender-specific considerations.











