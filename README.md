# Data Visualization
## P6: Make Effective Data Visualization
##### Author: Whitney King

### Summary

The dataset chosen for this project was originally wrangled and cleaned for P4: Data Exploration in R, which is located in the [DataExploration_R repository](https://github.com/WhitneyOnTheWeb/DataExploration_R). 

The dataset contains information about and sales numbers for *VGChartz: Top 5,000 Best Selling Video Games Globally*. Expanding on the wrangled and cleaned dataset generated as part of an earlier project made sense, since it allowed me to work with an original dataset without expending a lot of extra time doing it again.

### Design

The design for this data visualization was chosen to be a line graph with scatterplot points, that is accompanied by an overlayed line showing mean sales per title for each company year over year. 

The reader will begin the exploration at the 'base of the martini glass' by loading the visualization showing a scatterplot color-coded by console company. There is also a line for each company that shows average sales per game on each console year over year. From there, they will follow the 'stem of the martini glass' by being able to select which series of data are displayed. Finally, for the 'mouth of the martini glass', the reader will be able to hover over the individual points of data for each game to see the detailed information about that specific title.

This visualization is a good representation of the console wars, since each company has produced several consoles with games that are in the top 5,000 of all time by global units sold. The reader can see how each company has done with average sales per year, and how they stacked up against other companies selling games.

### Feedback

#### *First Draft (Feedback #1)*

#### *Revision 1 (Feedback #2)*

#### *Revision 2 (Feedback #3)*


### Resources

- **Data Exploration**:  [VGChartz_AnalysisInR.ipynb](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/VGCharts_AnalysisInR.ipynb)
- **Dataset**: VGChartz: Top 5,000 Best Selling Video Games Globally (Cleaned)
- **Data File**:  [vgsales_clean.csv](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/vgsales_clean.csv)
- **Chart Mock Up**: [SVG Image](https://github.com/WhitneyOnTheWeb/DataVisualization/blob/master/mockup.svg)

### External Resources

- [Moving Average Lines](https://bl.ocks.org/larsenmtl/e3b8b7c2ca4787f77d78f58d41c3da91)
- [d3-tip](https://github.com/Caged/d3-tip)
- [*Upgrading D3 from v3 to v4*](https://keithpblog.wordpress.com/2016/07/31/upgrading-d3-from-v3-to-v4/)
- [*Narrative Structures in Data Visualizations to Improve Storytelling*](http://mastersofmedia.hum.uva.nl/blog/2011/05/03/narrative-structures-in-data-visualizations-to-improve-storytelling/)