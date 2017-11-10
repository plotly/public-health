 # ⚕ Public health dashboards and tutorials using open data
 
 > Collection of public health dashboards and tutorials, hosted on plot.ly. Plot.ly is free for public data - [create an account](https://plot.ly/organize/). All dashboards were created without coding using plotly's online chart and dashboard creator.
 
 ***
 
 ## Contents
 
- [Crossfilter Overview](#crossfilter-overview)
- [California Measles Outbreak](#california-measles-outbreak)
- [Aid Agencies during Ebola Outbreak](#aid-agencies-during-ebola-outbreak)

## Crossfilter Overview

Crossfilter is a visual analysis technique for multidimensional data. It is used to clarify relationships between dimensions.

To use crossfilter, simply click-and-drag on a chart in one of the linked plot.ly dashboards below. Selected data that shares common rows with other charts will highlight and all other data will fade out. To reset the dashboard, click anywhere on a graph that doesn't have data.

To make crossfilter dashboards in plot.ly, make sure each dashboard chart is made from the same dataset. Once your dashboard is constructed, enable crossfilter under Settings > Filter. Follow one of the tutorials linked below for a full and illustrated guide to this workflow.

## California Measles Outbreak

| Dashboard Metadata               | Link                                                    |
| -------------------------------- | ------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:18123/present           |
| Dataset on plot.ly               | https://plot.ly/~jackp/18114/                           |
| Original dataset                 | [Project Tycho at U. Pittsburgh](http://bit.ly/2zrVG6s) |
| Tutorial to make this dashboard  | [Tutorial](tutorials/measles-dashboard.md)              |

#### Example insights

- You can see a share fall in measles cases after 1968 when the vaccinne was introduced.
- There were smaller outbreaks in 1988 and 1991.
- Weeks in the springtime had more outbreaks than any other season.

![measles-outbreak](https://github.com/plotly/public-health/raw/master/screencasts/california_measles_outbreaks.gif)

## Aid Agencies during Ebola Outbreak

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:18133/present             |
| Dataset on plot.ly               | https://plot.ly/~jackp/18129/                             |
| Original dataset                 | [Humanitarian Data Exchange (HDE)](http://bit.ly/2zq86Mh) |
| Dashboard inspiration            | [Simon B. Johnson](http://bit.ly/2zyztRN)                 |
| Tutorial to make this dashboard  | [Tutorial](tutorials/aid-agencies-dashboard.md)           |

#### Example insights

- Liberia had the most reported cases and most aid December 10, 2013
- Only 11 aid organizations were reported in Sierra Leone
- WHO provided 6 aid activities - Social mobilization, surveillance, coordination, safe burial, psychological support, and logistics
![ebola-aid](https://github.com/plotly/public-health/raw/master/screencasts/ebola_humanitarian_aid.gif)
