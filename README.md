# Data Visualization
## P6: Make Effective Data Visualization
##### Author: Whitney King
##### Date Updated: 8/23/2017 

### Summary

The dataset chosen for this project was originally wrangled and cleaned for P4: Data Exploration in R, which is located in the [DataExploration_R repository](https://github.com/WhitneyOnTheWeb/DataExploration_R). 

The dataset contains information about and sales numbers for *VGChartz: Top 5,000 Best Selling Video Games Globally*. Expanding on the wrangled and cleaned dataset generated as part of an earlier project made sense, since it allowed me to work with an original dataset without expending a lot of extra time doing it again.

### Design Overview

The design for this data visualization was chosen to be a color-coded graph with scatterplot points, that is accompanied by an overlayed line showing mean sales per title for each company year over year. The datapoints of the scatter plot are jittered and set to .15 transparency to aid in visual ingestion of the density of games released in a certain year that sold around the same number of copies.

The reader will begin the exploration at the 'base of the martini glass' by loading the visualization showing a scatterplot color-coded by console company. There is also a line for each company that shows average sales per game on each console year over year. From there, they will follow the 'stem of the martini glass' by being able to select which series of data are displayed by using the legend, which doubles as selectable buttons. Finally, for the 'mouth of the martini glass', the reader will be able to hover over the individual points of data for each game to see the detailed information about that specific title.

#### Design Decisions

- **Scatterplot**:  Showing the datapoints for every game is a quick and rich way for the reader to see patterns in game sales throughout history. Displaying all datapoints for all series is the base of the martini glass. 
- **Mean Lines**:  This type of plot is a good representation of the console wars, since each major company producting game platforms has released several consoles with games that are in the top 5,000 of all time by global units sold. The reader can see how each company has done with average sales per year, and how they stacked up against other companies selling games. Having the moving average for each mean as the reader moves their mouse in the chart space acts as the stem of the martini glass, and let the user explore average units shipped per game for each console company each year.
- **Legend Buttons**:  Turning the legend into interactive buttons was a good way to let the user filter through the amount of information being displayed in the chart, without crowding the page up with too many elements. This also enables detailed comparisons between console companies, since the reader can select to display as many or as few of the series as they wish.
- **Tooltips**: When coupled with the datapoints of the scatterplot, making tooltips available as part of the exploration allows for the reader to explore the mouth of the martini glass by looking into the information associated with each individual title released.

### Feedback

#### *First Draft (Feedback #1)*

Feedback By:  Stephen V King III

- **What do you notice in the visualization?**

   The parts that stood out were the different colors representing the different console companies, along with the cluster of dots towards the bottom-right of the chart.

- **What questions do you have about the data?**

   No questions come to mind. The chart feels straight-forward and well-labeled.

- **What relationships do you notice?**

   Companies that are no longer selling consoles (Atari and Sega) didn't seem to have to have as many high-selling games as the other companies/platforms.

- **What do you think is the main takeaway from this visualization?**

   Nintendo seems to have the highest selling games, as they have several above the 20 million mark whereas the other companies only have a few.

- **Is there something you don’t understand in the graphic?**

   No.


#### *Revision 1 (Feedback #2)*

Feedback By:  Mike Ihlenfeldt

- **What do you notice in the visualization?**

   Some companies have come and gone, others have been constant forces in the market.

- **What questions do you have about the data?**

   How do the same game franchise sales compare between difference platforms? Ex, Call of Duty on Xbox vs Playstation

- **What relationships do you notice?**

   There seems to be a critical mass of sales that gets hit and depending on the numbers of platforms in the market, that will determine sales. Early on with few platform choices, total sales were higher while with more choices, more of the total sales seem to be lower.

- **What do you think is the main takeaway from this visualization?**

   Explosive growth in video game sales in the last 20 years, between titles, sales and platforms released.

- **Is there something you don’t understand in the graphic?**

   Maybe a way to filter between different platforms by the same company. Show Xbox vs Xbox 360 vs Xbox One sales in the drill downs


#### *Revision 2 (Feedback #3)*

Feedback By:  Bryan Yager

- **What do you notice in the visualization?**

   No response

- **What questions do you have about the data?**

   - How much of the average dropoff per platform is due to shifts from one system to another and how much is due to oversaturation within a given market, such as what happened with Atari near the time that ET The Exterrestrial video game was produced?
   - How much of the average dropoff per platform is due to the wider variety of choices? For instance, PC games beginning in 2006 or five competing manufacturers from 1994 onwards. 

- **What relationships do you notice?**

   - Atari started off with lots of choices, several of which were popular, but their market dried up as titles stopped being produced.
   - Nintendo, on the other hand, seemed to weather a surge in choices between 2008 and 2010 pretty well.
   - Microsoft has had a steady number of titles per year, with lots of below-average titles and a slowly increasing number of breakout hits between 2005 and 2013.

- **What do you think is the main takeaway from this visualization?**
   Average game sales per title for a given platform tend go down as the number of possible choices (in titles and platforms) increase. 

- **Is there something you don’t understand in the graphic?**
   No, but it would be nice to have an aggregate of total game sales for each platform for comparison purposes, to weed out the difference between a glut of titles for a given system and loss of overall market share to other systems.

### Changes Made

After reviewing the feedback, I opted to not make any changes to the chart. The majority of questions about the visualization from the readers pertain to individual platform sales instead of sales by company. I agree that going one step further by breaking out each company by platform would be extremely interesting, however it wasn't the objective of this particular visualization. Looking at this data broken down by company gives a different and somewhat more informative view of who is winning the console wars, as platforms tend to come and go relatively quickly, however companies that release game platforms tend to do so fairly regularly. 

As I build this data visualization, I was making continual improvements based on verbal feedback I was receiveing from the people who would become my readers as to what kind of functionality they would like to see. Much of these improvements can be seen by reviewing the code change history of index.html on GitHub.

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