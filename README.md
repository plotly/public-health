 # ⚕ Public health dashboards and tutorials using open data
 
 > Collection of public health dashboards and tutorials, hosted on plot.ly. Plot.ly is free for public data - [create an account](https://plot.ly/organize/). All dashboards were created without coding using plotly's online chart and dashboard creator.
 
 ***
 
 ## Contents
 
0. [Crossfilter Overview](#crossfilter-overview)
1. [California Measles Outbreak](#california-measles-outbreak)
2. [Aid Agencies during Ebola Outbreak](#aid-agencies-during-ebola-outbreak)
3. [U.S. Police officer deaths by cause](#us-police-officer-deaths-by-cause)
4. [WHO Infant Mortality Index](#comparing-1990-and-2015-infant-mortality-index)
5. [IHME Global Health Indicators](#ihme-global-health-indicators)
6. [Google Flu Trends](#google-flu-trends)
7. [Ebola Outbreaks 1976-2013](#ebola-outbreaks-1976-2013)
8. [Dashboard Pro Tips](#pro-tips)

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

## Pro Tips

Here are a few Pro Tips when creating crossfilter dashboards on Plot.ly:

1. To enable crossfilter in Plot.ly dashboards, make sure that all graphs in the dashboard are made from the same dataset and that crossfilter is enabled in the Filter tab of Dashboard Settings.

2. Right-click (or Ctrl-click) on the Plot.ly spreadsheet for a menu of data preparation tools including:
 - Convert dates to Plotly date format
  - E.g. **December 10, 2016 -> 12-10-2016**
 - Find... Replace
 - Merge 2 or more columns with a delimiter
  - E.g. **| December | 10 | -> December-10**
 - Merge week of year and year columns into Plotly date format
  - E.g. **| 48 | 2016 | -> 12-28-2016**
 - Convert **state name** to **state abbreviation** (for use in choropleth maps)
  - E.g. **Vermont -> VT**
 - Cumulative sum
 - Sometimes you will still have to prep datasets before plotting using a tool like Google Sheets, Python, or R

3. Raw CSV links on GitHub such as https://gist.githubusercontent.com/omarish/5687264/raw/7e5c814ce6ef33e25d5259c1fe79463c190800d9/mpg.csv can be imported directly into Plot.ly from the the "URL" tab of the Import tool.

4. You can access the dataset behind a dashboard plot by:
 a. Selecting "View Plot" under the cog menu in the upper-right corner of the plot
 b. On the plot page, select the "Sources" tab. "Sources" is a tree view of the data sources that make up a plot. The data sources can be created by the author of the plot or a different Plot.ly user.
 c. In the tree view, the root nodes on the left side are the datasets that make up the plot. Click on them to go to the home page for the dataset.
 
 5. Use the [Plotly modebar](https://help.plot.ly/getting-to-know-the-plotly-modebar/) in the upper-right corner of dashboard plots to change the cursor mode between hover, zoom, and panning states. The modebar can also download a PNG image of plots.
 
 6. Disable default zoom in dashboard plots to prevent users from accidentally zooming as they scroll through your dashboard. You can disabled zoom for your plot under **Axes -> Zoom Interactivity** inside [Chart Studio](https://plot.ly/online-chart-maker/).
 
 7. Minimize the ink-to-data ratio: Make plots minimalistic or they will be overwhelming when combined in a dashboard.
 
![ink-data-ratio](https://static1.squarespace.com/static/56713bf4dc5cb41142f28d1f/t/5671eae2816924fc2265189a/1454121618204/data-ink.gif?format=750w)
(Data-Ink GIF via [Dark Horse](http://www.darkhorseanalytics.com/blog/data-looks-better-naked)
