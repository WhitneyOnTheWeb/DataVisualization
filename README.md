# Data Visualization
## P6: Make Effective Data Visualization
##### Author: Whitney King

### Summary

The dataset chosen for this project was originally wrangled and cleaned for P4: Data Exploration in R, which is located in the [DataExploration_R repository](https://github.com/WhitneyOnTheWeb/DataExploration_R). 

The dataset contains information about and sales numbers for *VGChartz: Top 10,000 Best Selling Video Games Globally*. Expanding on the wrangled and cleaned dataset generated as part of an earlier project made sense, since it allowed me to work with an original dataset without expending a lot of extra time doing it again. 

### Design

One of the most interesting, yet difficult to explore charts from the data exploration was global sales for each game released,faceted by franchise. This returned a whole lot of information, but so many charts that it quickly becomes overwhelming for any reader attempting to glean information from it. When thinking about which findings to detail in an interactive data visualization, this was the one that jumped to the forefront that would be a lot more informative if the user could interactively explore some more.

The design for this data visualization was chosen to be a line graph with scatterplot points. 

The reader will begin the exploration at the 'base of the martini glass' by the visualization showing color-coded franchises together on a scatterplot. From there, they will follow the 'stem of the martini glass' by being guided through an animation that highlights the best selling franchise each year. Finally, for the 'mouth of the martini glass', the reader will be able to pick from a list of video game franchises that will drill down into the sales trends for each franchise year over year, then hover over plot points to get detailed information on each video game.

### Feedback

#### *First Draft*

#### *Revision 1*

#### *Revision 2*

#### *Revision 3 - Final*

### Resources

- **Data Exploration**:  [VGChartz_AnalysisInR.ipynb](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/VGCharts_AnalysisInR.ipynb)
- **Dataset**: VGChartz: Top 10,000 Best Selling Video Games Globally (Cleaned)
- **Data File**:  [vgsales_clean.csv](https://github.com/WhitneyOnTheWeb/DataExploration_R/blob/master/vgsales_clean.csv)
- **Chart Mock Up** [SVG Image](https://github.com/WhitneyOnTheWeb/DataVisualization/blob/master/mockup.svg)

### External Resources

- [*Upgrading D3 from v3 to v4*](https://keithpblog.wordpress.com/2016/07/31/upgrading-d3-from-v3-to-v4/)
- [*Narrative Structures in Data Visualizations to Improve Storytelling*](http://mastersofmedia.hum.uva.nl/blog/2011/05/03/narrative-structures-in-data-visualizations-to-improve-storytelling/)