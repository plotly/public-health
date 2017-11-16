 # ⚕ Public health dashboards and tutorials using open data
 
 > Collection of public health dashboards and tutorials, hosted on plot.ly. Plot.ly is free for public data - [create an account](https://plot.ly/organize/). All dashboards were created without coding using plotly's online chart and dashboard creator.
 
 ***
 
 ## Contents
 
- [Crossfilter Overview](#crossfilter-overview)
- [California Measles Outbreak](#california-measles-outbreak)
- [Aid Agencies during Ebola Outbreak](#aid-agencies-during-ebola-outbreak)
- [U.S. Police officer deaths by cause](#us-police-officer-deaths-by-cause)
- [IHME Global Health Indicators](#ihme-global-health-indicators)
- [Google Flu Trends](#google-flu-trends)
- [Ebola Outbreaks 1976-2013](#ebola-outbreaks-1976-2013)

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
| Plotly.js charts in dashboard    | 3d scatter chart, 2d scatter chart, box plot            |

#### Example observations

- You can see a share fall in measles cases after 1968 when the vaccinne was introduced.
- There were smaller outbreaks in 1988 and 1991.
- Weeks in the springtime had more outbreaks than any other season.

![measles-outbreak-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/california_measles_outbreaks.gif)

## Aid Agencies during Ebola Outbreak

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:18133/present             |
| Dataset on plot.ly               | https://plot.ly/~jackp/18129/                             |
| Original dataset                 | [Humanitarian Data Exchange (HDE)](http://bit.ly/2zq86Mh) |
| Dashboard inspiration            | [Simon B. Johnson](http://bit.ly/2zyztRN)                 |
| Tutorial to make this dashboard  | [Tutorial](tutorials/aid-agency-dashboard.md)             |
| Plotly.js charts in dashboard    | Mapbox-gl scatter plot, pie charts, bar chart             |

#### Example observations

- Liberia had the most reported cases and most aid December 10, 2013
- Only 11 aid organizations were reported in Sierra Leone
- WHO provided 6 aid activities - Social mobilization, surveillance, coordination, safe burial, psychological support, and logistics

![ebola-aid-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/ebola_humanitarian_aid.gif)

## U.S. Police officer deaths by cause

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:18052/present             |
| Dataset on plot.ly               | https://plot.ly/~public.health/17/                        |
| Original dataset                 | [FiveThirtyEight](http://bit.ly/237YWtv)                  |
| Dashboard inspiration            | [FiveThirtyEight](http://53eig.ht/2AsMFqG)                |
| Tutorial to make this dashboard  | [Tutorial](tutorials/police-report-deaths.md)             |
| Plotly.js charts in dashboard    | Pie chart, scatter plot, choropleth map                   |

#### Example observations

- After gunfire, the 2nd highest cause of death for on-duty police officers in Alaska is aircraft incidents
- 14 states have reported on-duty police officer cause of death as "struck by train"
- Wyoming has the lowest police officer death rate by gunfire

![police-officer-deaths-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/on_duty_policy_deaths.png)

## Comparing 1990 and 2015 Infant Mortality Index

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:18103/present             |
| Dataset on plot.ly               | https://plot.ly/~jackp/18100                              |
| Original dataset                 | [World Bank](http://bit.ly/2i2SBjs)                       |
| Dashboard inspiration            | [World Bank](http://bit.ly/2i2SBjs)                       |
| Tutorial to make this dashboard  | [Tutorial](tutorials/infant-mortality-index.md)           |
| Plotly.js charts in dashboard    | Choropleth maps, scatter plot                             |

#### Example observations

- IMI improved in every country except Dominca between 1990 and 2005

![infant-mortality-index-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/infant_mortality_index.png)

## IHME Global Health Indicators

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/Dreamshot:8925/present          |
| Dataset on plot.ly               | https://plot.ly/~Dreamshot/8914/                          |
| Original dataset                 | [IHME Viz Hub](https://vizhub.healthdata.org/gbd-compare/)|
| Dashboard inspiration            | [IHME Viz Hub](https://vizhub.healthdata.org/gbd-compare/)|
| Tutorial to make this dashboard  | [Tutorial](tutorials/ihme-dashboard.md)                   |
| Plotly.js charts in dashboard    | Choropleth maps, bubble charts                            |

#### Example observations

- This dashboard is mainly to show crossfilter with a variety of map projections.

![IHME-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/IHME_crossfilter_gif.gif)

## Google Flu Trends

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/Dreamshot:9045/present          |
| Dataset on plot.ly               | https://plot.ly/~Dreamshot/9040/                          |
| Original dataset                 | [US Google Flu Trends CSV](http://bit.ly/2yEtQQU)         |
| Dashboard inspiration            | [Flu Trends Public Data Explorer](http://bit.ly/2AGrm56)  |
| Tutorial to make this dashboard  | [Tutorial](tutorials/google-flu-trends.md)                |
| Plotly.js charts in dashboard    | Time series, histograms, box plots                        |

#### Example observations

- This dashboard is mainly to show crossfilter of distribution plots (box plots and histograms) together with time series.

![google-flu-trends-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/Google_Flu_Trends.png)

## Ebola Outbreaks 1976-2013

| Dashboard Metadata               | Link                                                      |
| -------------------------------- | --------------------------------------------------------- |
| Link to dashboard                | https://plot.ly/dashboard/jackp:17876/present             |
| Dataset on plot.ly               | https://plot.ly/~public.health/8                          |
| Original dataset                 | [Nature: Science Direct](http://go.nature.com/2zKJN9u)    |
| Dashboard inspiration            | [Nature: Science Direct](http://go.nature.com/2zKJN9u)    |
| Tutorial to make this dashboard  | [Tutorial](tutorials/ebola-outbreaks.md)                  |
| Plotly.js charts in dashboard    | Time series, D3 map with hover text, SVG table            |

#### Example observations

- This dashboard is mainly to show using crossfilter with tables.

![ebola-outbreak-dashboard](https://github.com/plotly/public-health/raw/master/screencasts/ebola_outbreak.png)
