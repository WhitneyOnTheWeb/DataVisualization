# Data Visualization
## P6: Make Effective Data Visualization
##### Author: Whitney King
##### Date Updated: 8/23/2017 

### Summary

The dataset chosen for this project was originally wrangled and cleaned for P4: Data Exploration in R, which is located in the [DataExploration_R repository](https://github.com/WhitneyOnTheWeb/DataExploration_R). 

The dataset contains information about and sales numbers for *VGChartz: Top 5,000 Best Selling Video Games Globally*. Expanding on the wrangled and cleaned dataset generated as part of an earlier project made sense, since it allowed me to work with an original dataset without expending a lot of extra time doing it again.

### Design

The design for this data visualization was chosen to be a line graph with scatterplot points, that is accompanied by an overlayed line showing mean sales per title for each company year over year. 

The reader will begin the exploration at the 'base of the martini glass' by loading the visualization showing a scatterplot color-coded by console company. There is also a line for each company that shows average sales per game on each console year over year. From there, they will follow the 'stem of the martini glass' by being able to select which series of data are displayed. Finally, for the 'mouth of the martini glass', the reader will be able to hover over the individual points of data for each game to see the detailed information about that specific title.

This visualization is a good representation of the console wars, since each company has produced several consoles with games that are in the top 5,000 of all time by global units sold. The reader can see how each company has done with average sales per year, and how they stacked up against other companies selling games.

### Feedback

#### *First Draft (Feedback #1)*

Feedback By:  Stephen V King III

- **What do you notice in the visualization?**

 - The parts that stood out were the different colors representing the different console companies, along with the cluster of dots towards the bottom-right of the chart.

- **What questions do you have about the data?**

 - No questions come to mind. The chart feels straight-forward and well-labeled.

- **What relationships do you notice?**

 - Companies that are no longer selling consoles (Atari and Sega) didn't seem to have to have as many high-selling games as the other companies/platforms.

- **What do you think is the main takeaway from this visualization?**

 - Nintendo seems to have the highest selling games, as they have several above the 20 million mark whereas the other companies only have a few.

- **Is there something you don’t understand in the graphic?**

 - No.


#### *Revision 1 (Feedback #2)*

Feedback By:  Mike Ihlenfeldt

- **What do you notice in the visualization?**

 - Some companies have come and gone, others have been constant forces in the market.

- **What questions do you have about the data?**

 - How do the same game franchise sales compare between difference platforms? Ex, Call of Duty on Xbox vs Playstation

- **What relationships do you notice?**

 - There seems to be a critical mass of sales that gets hit and depending on the numbers of platforms in the market, that will determine sales. Early on with few platform choices, total sales were higher while with more choices, more of the total sales seem to be lower.

- **What do you think is the main takeaway from this visualization?**

 - Explosive growth in video game sales in the last 20 years, between titles, sales and platforms released.

- **Is there something you don’t understand in the graphic?**

 - Maybe a way to filter between different platforms by the same company. Show Xbox vs Xbox 360 vs Xbox One sales in the drill downs


#### *Revision 2 (Feedback #3)*

Feedback By:  

- **What do you notice in the visualization?**

- **What questions do you have about the data?**

- **What relationships do you notice?**

- **What do you think is the main takeaway from this visualization?**

- **Is there something you don’t understand in the graphic?**


### Resources

- **Data Exploration**:  [VGChartz_AnalysisInR.ipynb](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/VGCharts_AnalysisInR.ipynb)
- **Dataset**: VGChartz: Top 5,000 Best Selling Video Games Globally (Cleaned)
- **Data File**:  [vgsales_clean.csv](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/vgsales_clean.csv)
- **Chart Mock Up**: [SVG Image](https://github.com/WhitneyOnTheWeb/DataVisualization/blob/master/mockup.svg)
- **External HTML**: [WhitneyOnTheWeb](http://whitneyontheweb.com/data_vis/index.html)

### External Resources

- [Moving Average Lines](https://bl.ocks.org/larsenmtl/e3b8b7c2ca4787f77d78f58d41c3da91)
- [Jitter Scatterplot](http://bl.ocks.org/mkaz/3816112)
- [d3-tip](https://github.com/Caged/d3-tip)
- [*Upgrading D3 from v3 to v4*](https://keithpblog.wordpress.com/2016/07/31/upgrading-d3-from-v3-to-v4/)
- [*Narrative Structures in Data Visualizations to Improve Storytelling*](http://mastersofmedia.hum.uva.nl/blog/2011/05/03/narrative-structures-in-data-visualizations-to-improve-storytelling/)