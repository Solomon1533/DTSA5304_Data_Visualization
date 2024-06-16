Project Title: Global YouTube Statistics 2023
https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023
for this project I have used the modified dataset. https://raw.githubusercontent.com/Solomon1533/Test1/main/Test1.csv
The modified data set covers only the developed countries instead of the global data. 

Here is the link to the google drive file in case the code fails to open. https://colab.research.google.com/drive/1wLUO7Elp3ucWuTuSF2fgzVvMo1ryH4Zl?usp=sharing

Make sure you run all tha packages before you trying to run the code. 

Introduction:

Interesting Data on YouTube Channels

I've been exploring a dataset on Kaggle called "Global YouTube Statistics 2023" 
Global YouTube Statistics 2023 (kaggle.com)
This dataset provides insights into the most subscribed YouTube channels. Since the full dataset covered a wide range of countries, I narrowed my focus to include channels from developed economies like Australia, Canada, Finland, France, Germany, Italy, Japan, Netherlands, Spain, Sweden, UK, and USA.

2. Analyzing Connections

Within this specific dataset, several attributes caught my attention. These include:

Demographics: Population and unemployment rate

Content: Video categories and viewership

Channel Performance: Number of subscribers and content categories

By analyzing the relationships between these data points, I hope to uncover interesting trends and answer questions. 

Through this analysis, I aim to identify correlations between various factors. This could help explain, for example, why the categories are related to the unemployment rate etc...


3. Objectives:

Data search and Preprocessing:

Collect and preprocess the provided dataset, ensuring data quality and consistency. Data cleaned. Handle missing data and format inconsistencies. Prepare the dataset for analysis.

Exploratory Data Analysis (EDA):

I have conducted EDA to gain a comprehensive understanding of the dataset. Explore data distribution, mean avarage of different dataset, and variations.
Visualize relationships and correlations between variables.

A link have provided in Google drive and GitHub. 

4. A summary of the key elements of your design and accompanying justification

It is important to consider various measures that provide insights into the effectiveness, usability, and impact of the visualization. These measures are important to make informed decision to anyone seeing the visualization and to understand the presented data. Some of the key measures are: 
Accuracy: The correctness of the information presented in the visualization.
Insight depth: The depth of understanding presented in the visualization. 
Use Cases: What is the measures and the alignment of the visualization with specific needs.
Clarity and simplicity: How easily someone can understand the visualization.
Is it clear, simple visuals which enhance communication and refuse reduce cognitive load?

The boxplot, ordered by median subscriber count, gives you a visual overview of how the subscriber counts are distributed within each category, and highlights any channels that stand out from the crowd. Outliers can be interesting to investigate. They might indicate exceptionally popular channels within a less popular category, or they might suggest potential errors in dataset.

5. A discussion of your final evaluation approach, including the procedure, people recruited, and results. Note that, due to the difficulty of recruiting experts, you can use colleagues, friends, classmates, or family to evaluate your designs if experts or others from your target population are unavailable. 

First, I make sure to the best of my knowledge accuracy and representation. The visualization should accurately represent that underlying data and its trends. I ensue that the visual elements such as bars, lines or points correspond faithfully to the actual data points. I make sure I check for any inaccuracies in the visualization. 
Another one is clarity and understandability. A successful visualization should be easy to understand by the intended audience. It should have clear labels and must be intuitive.

6. A synthesis of your findings, including what elements of your approach worked well and what elements you would refine in future iterations.
The choropleth map I've created aims to show the average number of subscribers by country. It uses color intensity to represent the magnitude of the average subscriber count in each country. However, there are a few ways this could potentially be improved or represented differently, depending on what we want to emphasize. The best way to represent our data depends on the specific questions we're trying to answer and the audience we're communicating to. Question to ponder: 
•	What is the key message we want to convey? Is it simply the ranking of countries by subscribers, or are we trying to show regional patterns or correlations with other factors?
•	Who is your audience? A general audience might prefer a simple and visually appealing map, while a more technical audience might appreciate additional data layers or a different type of chart.

Possible Interpretations & Improvements
If the plot is simply showing population and views by country without any normalization or additional context, it might not be very informative. 
Population Bias: Countries with larger populations will naturally have more views, even if their viewership per capita is lower. This could make the visualization misleading.
Lack of Comparison: Without a way to compare viewership relative to population or other factors, it's hard to draw meaningful conclusions.

For future Iteration, we all need to remember that visualization is an interactive process. Feedback is important and a number of elements need to be considered such as data preparation, visual design and choice of visualization. 


