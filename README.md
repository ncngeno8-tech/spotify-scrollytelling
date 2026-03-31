1. Rationale for Design Decisions

I chose a scatterplot because it clearly shows the relationship 
between two numerical variables: energy and danceability. These 
variables describe how a song feels in terms of intensity and rhythm.

Color was used to represent genre since it's a categorical variable. 
This makes it easier to compare different groups of songs.

Point size was used to represent popularity so users can quickly see 
whether more popular songs appear in certain areas of the chart.

For interaction, I used hover tooltips so users can view details about 
each song without cluttering the visualization. I also used the legend 
as a filtering tool so users can turn genres on and off.

I considered using bar charts and faceted plots, but those would not 
show the relationship between energy and danceability as effectively. 
The scatterplot provides both clarity and flexibility for exploration.

2. Overview of Development Process

I spent about 8 hours completing this project.

First, I selected a dataset from Kaggle that included Spotify track 
features. Then I explored the dataset and identified energy and 
danceability as the most relevant variables for my question.

Next, I cleaned the data by removing missing values and limiting the 
dataset to the top genres to keep the visualization readable.

After that, I built the interactive visualization using Plotly in R. 
I adjusted the colors, sizes, and hover details to make the chart 
clear and easy to use. I also reduced the dataset size to improve 
performance.

Finally, I created the Quarto website and organized it into sections,
introduction, dataset description, visualization, and 
conclusion.

The most time consuming parts were cleaning the dataset, choosing the 
right variables, and making sure the visualization stayed clear and 
responsive.
