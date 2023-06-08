**YouTube Channel Analytics**
This repository contains code for analyzing YouTube channel statistics and visualizing the data using various Python libraries. The code retrieves channel statistics, video details, and comments from specified YouTube channels using the YouTube Data API. It also performs data manipulation, visualization, and generates word clouds to gain insights into the channels and their content.

**Prerequisites**
Before running the code, make sure you have the following:

- Python 3 installed
- Required Python libraries: pandas, numpy, dateutil, isodate, matplotlib, seaborn, nltk, wordcloud, and google-api-python-client
- Additionally, you need to have a Google API key to access the YouTube Data API. Replace the placeholder 'assignedAPIKey' in the code with your actual API key.

**Code Overview**
The code performs the following steps:

- Import required libraries.
- Set up the Google API client using the provided API key.
- Retrieve channel statistics for specified channel IDs.
- Manipulate and clean the data.
- Visualize the data using bar plots, violin plots, and scatter plots.
- Generate word clouds from video titles and comments.

**Usage**
1. Clone the repository:

2. Open the cloned repository in your preferred Python development environment.
3. Replace the 'assignedAPIKey' placeholder in the code with your actual API key.
4. Run the code and observe the generated visualizations and insights.

**Results**
The code generates various visualizations to provide insights into the YouTube channels and their content. These visualizations include:

- Bar plots: Displaying subscriber counts and views for each channel.
- Violin plots: Showing the distribution of views per channel.
- Scatter plots: Analyzing relationships between views, comments, likes, and other variables.
- Word clouds: Visualizing frequently used words in video titles and comments.
- The generated visualizations help understand the popularity and engagement of the channels and identify trends and patterns in the data.
