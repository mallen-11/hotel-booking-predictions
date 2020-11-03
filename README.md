# Cancel Less, Live More

This repository contains all of the steps in the analysis of the cancellation of hotel bookings.
This includes a folder containing all the data, a notebook where all the data was cleaned and analyzed, an article, and a presentation. Below, I will go into what you can expect from each of these.

Data

There is a link to the kaggle site in which the date was found. It includes 32 columns and around 120,000 rows. This dataset has everything you need to analyze hotel bookings. There is also an article on the kaggle site which explains each of the columns and their significance.

Notebooks

Our notebook contains the code to clean the data, which is pretty straightforward. We then went into analysis. Our analysis consisted of first seperating the DataFrame into multiple other DataFrames. These new DataFrames were based on whether the booking cancelled or not. This then helped set up our analysis.

Furthermore, we created a few graphs and a heatmap to help us analyze and understand the data so that we could pick which columns we wanted to put into our model.

Once we found the columns we wanted which we name df_new. We then were able to label encode the categorical columns and run a few models. We did a nearest neighbors model, logistic regression, and finally a XGBoost model. Laslty, we ensembled them to see if that helped the accuracy. The XGBoost model performed the best.

Article

This folder contains an article on Linkedin about our entire analysis.

Presentation

This folder contains a presentation over the same material the article contains. 

This analysis is done by Morgan Allen, Edith Magana, Woo Seok Kim, Marisol Mondragon.
