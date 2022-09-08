# Python-Project-on-Data-Science
## Editing the file

Its a markdown in this repository 

In this project, we will predict if the SpaceX Falcon 9 first stage will land successfully.​
SpaceX advertises Falcon 9 rocket launches on its website, with a cost of sixty-two million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage.​
Therefore, if we can determine if the first stage will land, we can determine the cost of a launch.​
This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.​
​

Part 1: Data Collection using Web Scraping​/ SpaceX API
In this part, web scraping is done using the Python BeautifulSoup package, to collect Falcon 9 historical launch records from a Wikipedia page titled 'List of Falcon 9 and Falcon Heavy launches'​
[https://en.wikipedia.org/wiki/List_of_Falcon\_9\_and_Falcon_Heavy_launches]/ The SpaceX REST API endpoints, or URL starts with; api.spacexdata.com/v4/​

Part 2: Data Wrangling​
In this part, Exploratory Data Analysis (EDA) is performed to find some patterns in the data and eliminate null values as well as remove columns not needed​

Part 3: Exploratory Data Analysis with SQL​
The SpaceX Dataset is loaded into a corresponding table in a Db2 database and SQL queries are executed to better understand the data.​

Part 4: Exploratory Data Analysis with Visualization​
Exploratory data analysis and Feature Engineering are performed using Pandas and Matplotlib.​

Part 5: Data Visualization using Folium​
Interactive visual analytics are performed using the Python Folium package.​

Part 6: Plotly Dashboard​
An interactive dashboard app is created based on the SpaceX dataset, using Python Dash and Plotly packages.​

Part 7: SpaceX Machine Learning Prediction​
Here, data is analyzed, split into training and testing sets, and four supervised models-Logistic Regression, K-Nearest Neighbor, Decision Tree, and Support Vector Machine are trained on the dataset. The accuracy of each of the models is calculated to find the best prediction model.​
