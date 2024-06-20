# AI-Agent-for-creating-visualization-using-natural-language

## Introduction

In this analysis, Developed an AI agent using IBM Watsonx AI model integrated with LangChain to extract meaningful insights from a student performance dataset. This integration allows us to interact with the dataset using natural language queries, making data analysis and visualization intuitive and efficient.

## Code Explanation and Concepts

### Data Loading and Inspection

The script begins by loading a dataset (`student-mat.csv`) using Pandas, which contains various attributes of students such as demographics, family background, academic performance, and health.

### Integration with IBM Watsonx and LangChain

The script integrates IBM Watsonx AI model (`WatsonxLLM`) with LangChain, a framework for natural language processing and data manipulation. This integration allows us to interact with the dataset using natural language queries (`agent.invoke()`), enabling automated data analysis and visualization.

### Data Querying and Manipulation

Queries like `"how many rows of data are in this file?"` and `"Give me all the data where student's age is over 18 years old."` demonstrate how we can use natural language to retrieve specific subsets of data based on criteria.

### Visualization Generation

Visualizations such as bar charts, pie charts, box plots, and scatter plots are generated based on the queried data. Matplotlib is used for plotting, and each visualization corresponds to a specific query about the dataset characteristics or relationships between variables.

## Visuals Produced in Terms of Business Analytics

### Gender Distribution Bar Chart

This visual provides a clear breakdown of the number of male and female students. As a business analyst, this helps in understanding the student demographics, enabling targeted marketing strategies or educational program planning tailored to different gender groups.

### Alcohol Consumption Pie Chart by Gender

These visuals show average weekend alcohol consumption categorized by gender. As a business analyst, this provides insights into behavioral patterns that may affect academic performance differently between genders, influencing decisions on health and wellness initiatives.

### Free Time vs. Grades Box Plot

This visual illustrates how different levels of free time correlate with final grades. It helps in identifying if students with more free time perform better academically, guiding decisions on optimizing students' schedules and extracurricular activities.

### Alcohol Consumption vs. Academic Performance Scatter Plots

These plots highlight correlations between alcohol consumption (both daily and weekend) and final grades. As a business analyst, this insight prompts considerations for interventions or policies aimed at mitigating the negative impact of alcohol on student performance.

### Parental Education Influence Scatter Plots

These visuals depict how parental education levels correlate with student grades. They emphasize the importance of parental involvement in education and suggest strategies to support parents in fostering a conducive learning environment at home.

### Internet Access Impact Bar Plot

This bar plot compares final grades of students with and without internet access at home. It underscores the role of digital connectivity in academic performance and supports advocacy for initiatives to improve internet access for all students.

### Absences vs. Academic Performance Scatter Plot

This scatter plot demonstrates the relationship between student absences and final grades. It highlights the negative impact of absenteeism on academic achievement, prompting strategies to improve attendance tracking and student engagement.

## Conclusion

By leveraging these data-driven insights and visualizations, we can make informed decisions to enhance educational strategies, improve student outcomes, and optimize resource allocation effectively. The integration of IBM Watsonx AI with LangChain facilitates streamlined data analysis and visualization, empowering educational institutions to drive positive changes tailored to the needs of their student population.
