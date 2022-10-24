<h1>Problem Formulation</h1>


The government of Kenya and NGOs like UN and UNICEF need a way to predict movement of the pastrolists in order to organise resource allocation like delivery of vaccines to children and animals. Also, the government could use this information to set up security zones with enough security personnel to help stop the ever growing problem of cattle rustling and loss of lives. Further, red flags can be raised on issues around environmental conservation and climate change in areas where there is a lot of movement. This will help in creating solutions around managing the number of people and animals in a specific area while introducing crops that will slow soil erosion, and afforestation. There are three main approaches that provide informed guesses about future migration trends. These include the following:

<h6>Early Warnings System:</h6>

Uses quantitative and qualitative data to monitor potential drivers and movements of populations in real time to provide short-term estimations in fast-changing contexts (Carammia and Dumont, 2018). These systems establish pre-defined warning thresholds, that when exceeded, trigger specific actions to be taken by designated individuals.

<h6>Forecasting:</h6>

Predicts future migration flows and trends using quantitative modelling methods with a medium and long-term horizon (Bijak, 2011; Disney, 2015). This approach statistically models future migration trends based on quantitative data from the past. This type of modeling needs a significant amount of numerical data related to migration such as policy changes and past inflows and outflows of migrants by location.

<h6>Foresight:</h6>

Uses qualitative scenario methods like “What if… to describe future migration flows and trends. Migration scenarios are qualitative narratives about the future of migration that examine possible structural changes and their consequences for migration (Vezzoli et al., 2017; De Haas et al. 2010).

<h2>Predicting Migration of Pastrolists using Machine Learning</h2>

We will use data from a selected area of 6000 square kilometers in the ASAL(Arid and Semi-Arid Lands) region in Kenya for our model.
More about the ASAL region here.

The objective of this program is to predict migration of pastrolists in this area for future time periods
We will be using Random Forrest Regressor model with our data for this prediction.

<h3>STEPS</h3>

Import the required software libraries.

Access and import the dataset.

Data Analysis and Exploration.

Split the data into test and training data sets.

Train the model on the training data.

Make predictions on the test data.

Evaluate the model’s performance.

Draw conclusions from evaluations.

DATASET
This dataset includes the following features:

<h6>1. Movement -</h6>

This includes "Arrivals" and "Depatures" into the area

<h6>2. Location -</h6>

Location from where people arrived into to our selected area ( Movement = "Arrivals") or to where they left the area for ( Movement = "Departures"). Contains special values "Not Stated".

<h6>3. Community -</h6>

The community of the pastrolists, including "Borana", "Samburu", and "Multi"( This is inclusive of Turkana, Pokot and a few Kalenjin).

<h6>4. Year -</h6>

Year of Movement

<h6>5. Value -</h6>

Number of Pastrolists( They are counted as individuals of all ages in the area of study)
