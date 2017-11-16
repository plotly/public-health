TODO

- add gif
- proofread
___

# Google Flu Trends

In this tutorial, we'll create and style multiple individual plots in the Chart Studio, add them to a dashboard, and utilize the crossfilter function to interact and explore these data further.

## Contents

- [Overview](#overview)
- [Data](#1-data)
- [Create a Chart](#2-create-a-chart)
  - [Oklahoma Bar Chart](#21-oklahoma-bar-chart)
  - [New York Bar Chart](#22-new-york-bar-chart)
  - [US Bar Chart](#23-us-bar-chart)
  - [Search Boxplot](#24-search-boxplot)
  - [Search by Region Boxplot](#25-search-region-boxplot)
- [Create a Dashboard](#3-create-a-dashboard)
  - [Add Charts](#31-add-charts)
  - [Style It](#32-style-it)
- [Crossfilter](#4-crossfilter)


## 1. Data

To get started, head to Plotly’s [Chart Studio](https://plot.ly/create/) and add your data. You have the option of typing directly in the grid, uploading your file, or entering a URL of an online dataset. For this tutorial, we'll use a Google Flu Trends dataset from [Google Flu Trends](https://www.google.org/flutrends/about/data/flu/us/data.txt).
Simply, copy the URL (https://plot.ly/~Dreamshot/9040.csv) or open the [dataset](https://plot.ly/~Dreamshot/9040/) and click **Fork & Edit** to begin.

![Fork and Edit](../screencasts/google-flu-trends/oklahoma-bar/fork-and-edit.png)

If you choose the latter, the Chart Studio ought to have opened and you're all set to go. If the former, navigate to the [Chart Studio](https://plot.ly/create/) and click **'Import'**, **'By URL'**, and then paste in the **URL** (https://plot.ly/~Dreamshot/9040.csv).

![Add Data](../screencasts/google-flu-trends/oklahoma-bar/add-data.png)

## 2. Create a Chart

To visualize Google flu trends, we'll create five individual charts: (1) Oklahoma bar chart, (2) New York bar chart, (3) US bar chart, (4) a boxplot to Google searches, and (5) a boxplot of searches by region. In this section we'll look at how to make each of the charts.

### 2.1. Oklahoma Bar Chart

##### 2.1.1. Create
Now that we have the data added to the grid, we can select our chart type. To do so, select *Graph* on the left-hand side, then *Create*. Click *Chart Type*, and **Bar Chart** from the *Business* column.

![Chart Type](../screencasts/google-flu-trends/oklahoma-bar/chart-type.png)

Now, you ought to see the *y* and *x* dropdowns. Select **Oklahoma** and **Date**, respectively.

![Trace Values](../screencasts/google-flu-trends/oklahoma-bar/trace-values.png)

##### 2.1.2. Traces

Set *Fill* to **#00CC96**.

![Trace Styles](../screencasts/google-flu-trends/oklahoma-bar/trace-styles.png)

##### 2.1.3. Layout
Now that we've finished styling the trace, click *Layout* to style the background, fonts, and margins. To complete the former, select *Canvas* and set **#F3F6FA** as both plot and margin color.

![Canvas](../screencasts/google-flu-trends/oklahoma-bar/canvas.png)

Below that, open the *Title and Fonts* box and under *Global Font*, set *Typeface* to **Raleway**, *Font Size* to **12**, and *Color* to **#506784**.

![Global Font](../screencasts/google-flu-trends/oklahoma-bar/global-font.png)

To set the margins, select the *Margins and Padding* box
and enter the values **0, 30, 50, 150, 0**, respectively.

![Margins](../screencasts/google-flu-trends/oklahoma-bar/margins.png)

##### 2.1.4. Axes
To edit the axis titles, grid lines, and tick labels, navigate to the *Axes* tab. First, in the *Titles* remove the *x* title and then set the *y* axis title to **"Google Flu trends search volume index"**.

![Axes Titles](../screencasts/google-flu-trends/oklahoma-bar/axes-titles.png)

Next, open *Range*, click *y* and select **Custom Range**. Set the *Min* to **0** and *Max* to **25880**.

![Custom Range](../screencasts/google-flu-trends/oklahoma-bar/custom-range.png)

##### 2.1.5. Save
Congrats, your chart is complete! Click **Save** on the left-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all) or **Private Link** (visible only to those who you share the link with) and hit **Save**. Since these plots are destined for a dashboard, they can't be set to private.

![Save](../screencasts/google-flu-trends/oklahoma-bar/save.png)

### 2.2. New York Bar Chart

##### 2.2.1. Create
Again, now that we have the data in the grid, we can select our chart type. To do so, select *Graph* on the left-hand side, then *Create*. Click *Chart Type*, and **Bar Chart** from the *Business* column.

![Chart Type](../screencasts/google-flu-trends/ny-bar/chart-type.png)

Now, you ought to see the *y* and *x* dropdowns. Select **New York** and **Date**, respectively.

![Trace Values](../screencasts/google-flu-trends/ny-bar/trace-values.png)

##### 2.2.2. Traces

Set *Fill* to **#09FFFF**.

![Trace Styles](../screencasts/google-flu-trends/ny-bar/trace-styles.png)

##### 2.2.3. Layout
Now that we've finished styling the trace, click *Layout* to style the background, fonts, and margins. To complete the former, select *Canvas* and set **#F3F6FA** as both plot and margin color.

![Canvas](../screencasts/google-flu-trends/ny-bar/canvas.png)

Below that, open the *Title and Fonts* box and under *Global Font*, set *Typeface* to **Raleway**, *Font Size* to **12**, and *Color* to **#506784**.

![Global Font](../screencasts/google-flu-trends/ny-bar/global-font.png)

To set the margins, select the *Margins and Padding* box
and enter the values **0, 30, 50, 150, 0**, respectively.

![Margins](../screencasts/google-flu-trends/ny-bar/margins.png)

##### 2.2.4. Axes
To edit the axis titles, grid lines, and tick labels, navigate to the *Axes* tab. First, in the *Titles* remove the *x* title and then set the *y* axis title to **"Google Flu trends search volume index"**.

![Axes Titles](../screencasts/google-flu-trends/ny-bar/axes-titles.png)

Next, open *Range*, click *y* and select **Custom Range**. Set the *Min* to **0** and *Max* to **13300**.

![Custom Range](../screencasts/google-flu-trends/ny-bar/custom-range.png)

##### 2.2.5. Save
Congrats, your chart is complete! Click **Save** on the left-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all) or **Private Link** (visible only to those who you share the link with) and hit **Save**. Since these plots are destined for a dashboard, they can't be set to private.


![Save](../screencasts/google-flu-trends/ny-bar/save.png)

### 2.3. US Bar Chart

##### 2.3.1. Create
Like the previous bar chart, select *Graph* on the left-hand side, then *Create*. Click *Chart Type*, and **Bar Chart** from the *Business* column.

![Chart Type](../screencasts/google-flu-trends/us-bar/chart-type.png)

Now, you ought to see the *y* and *x* dropdowns. Select **United States** and **Date**, respectively.

![Trace Values](../screencasts/google-flu-trends/us-bar/trace-values.png)

##### 2.3.2. Traces
Set *Fill* to **#119DFF**.

![Trace Styles](../screencasts/google-flu-trends/us-bar/trace-styles.png)

##### 2.3.3. Layout
Now that we've finished styling the trace, click *Layout* to style the background, fonts, and margins. To complete the former, select *Canvas* and set **#F3F6FA** as both plot and margin color.

![Canvas](../screencasts/google-flu-trends/us-bar/canvas.png)

Below that, open the *Title and Fonts* box and under *Global Font*, set *Typeface* to **Raleway**, *Font Size* to **12**, and *Color* to **#506784**.

![Global Font](../screencasts/google-flu-trends/us-bar/global-font.png)

To set the margins, select the *Margins and Padding* box
and enter the values **0, 30, 50, 150, 0**, respectively.

![Margins](../screencasts/google-flu-trends/us-bar/margins.png)

##### 2.3.3. Axes
To edit the axis titles, grid lines, and tick labels, navigate to the *Axes* tab. First, in the *Titles* remove the *x* title and then set the *y* axis title to **"Google Flu trends search volume index"**.

![Axes Titles](../screencasts/google-flu-trends/us-bar/axes-titles.png)

Next, open *Range*, click *y* and select **Custom Range**. Set the *Min* to **0** and *Max* to **25880**.

![Custom Range](../screencasts/google-flu-trends/us-bar/custom-range.png)

##### 2.3.4. Save
Congrats, your chart is complete! Click **Save** on the left-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all) or **Private Link** (visible only to those who you share the link with) and hit **Save**. Since these plots are destined for a dashboard, they can't be set to private.

![Save](../screencasts/google-flu-trends/us-bar/save.png)


### 2.4. Search Boxplot

##### 2.4.1. Create
After loading the data, select *Graph* on the left-hand side, then *Create*. Click *Chart Type*, and select **Box Plot** from the *Statistics* column.

![Chart Type](../screencasts/google-flu-trends/search-box/chart-type.png)

Like previous plots we want to populate the graph with data, thus in the *Values* and select **United States**. Additionally, add a second trace by clicking the blue *+ Trace* button and in the new trace box that appears alter the *Values* dropdown to **Oklahoma**.

![Trace Values](../screencasts/google-flu-trends/search-box/trace-values.png)

##### 2.4.2. Axes
With the traces added you can see that before styling the traces the y axis scale needs to be set. Thus, navigate to *Axes*, open *Range*, *y*, and set **Custom Range**. Additionally, set the *Min* value to **2.652244785695194** and the *Max* to **4.498865575013528**.

![Log Scale](../screencasts/google-flu-trends/search-box/log-scale.png)

Staying in the *Axes* tab, open *Titles* remove the *x* title and then set the *y* axis title to **"Google Flu trends search volume index"**.

![Axes Titles](../screencasts/google-flu-trends/search-box/axes-titles.png)

##### 2.4.3. Layout
Now that we've finished making changes to the axes, click *Layout* to style the background, fonts, and margins. To complete the former, select *Canvas* and set **#F3F6FA** as both plot and margin color.

![Canvas](../screencasts/google-flu-trends/search-box/canvas.png)

Below that, open the *Title and Fonts* box and under *Global Font*, set *Typeface* to **Raleway**, *Font Size* to **12**, and *Color* to **#506784**.

![Global Font](../screencasts/google-flu-trends/search-box/global-font.png)

To set the margins, select the *Margins and Padding* box
and enter the values **0, 30, 50, 150, 0**, respectively.

![Margins](../screencasts/google-flu-trends/search-box/margins.png)

##### 2.4.4. Traces
With the axes and layout set, navigate to the *Traces* tab to style the traces. At the top, select *Individual* and open the first trace. Here, change the *Fill* and *Line Color* to **#222222**, but set the alpha to **50** for the fill and **100** for the line. Immediately below, set the *Whisker Width* to **40%**, *Display Points* dropdown to **All**, and *Jitter* to **30%**. Next, to minimize points and boxes set the *Diameter* to **2**, *Box Width* to **30**, and *Padding* to **30**. Lastly, with regards to trace styling, in *Display in Legend* select **No**. Now, you ought to see a similar styled trace as below.

![Trace Styles](../screencasts/google-flu-trends/search-box/trace-styles.png)

Repeat the process above on the second trace. The only difference, set *Fill* and *Line Color* to **#00CC96**.

![Trace Styles](../screencasts/google-flu-trends/search-box/trace-styles2.png)

##### 2.4.5. Save
Congrats, your chart is complete! Click **Save** on the left-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all) or **Private Link** (visible only to those who you share the link with) and hit **Save**. Since these plots are destined for a dashboard, they can't be set to private.

![Save](../screencasts/google-flu-trends/search-box/save.png)

### 2.5. Search Region Boxplot

##### 2.5.1. Create
After loading the data, select *Graph* on the left-hand side, then *Create*. Click *Chart Type*, and select **Box Plot** from the *Statistics* column.

![Chart Type](../screencasts/google-flu-trends/search-region-box/chart-type.png)

Like previous plots we want to populate the graph with data, thus in the *Values* and select **HHS Region 1**.

![Trace Values](../screencasts/google-flu-trends/search-region-box/trace-values.png)

As we want to add all HHS regions we need to add multiple traces. To do so, click the blue *+ Trace* button and in the new trace box that appears alter the *Values* dropdown to **HHS Region [n]**. Repeat this process until you've added all 10 regions. You ough to something similar to below.

![Trace Values](../screencasts/google-flu-trends/search-region-box/trace-values-all.png)

##### 2.5.2. Traces

Set *Fill* and *Line Color* to **#00009B**, *Whisker Width* to **40%**, *Display Points* to **None**, *Show Statistics* to **Mean + Standard Deviation**, and *Display in Legend* to **No**.

![Trace Styles](../screencasts/google-flu-trends/search-region-box/trace-styles.png)

For the other traces only alter the *Fill* and *Line Color* to **#0041D7**, **#1489E9**, **#4EE2A8**, **#A1D458**, **#FF9300**, **#FF5700**, **#F72600**, **#E00900**, and **#D80000**, respectively.

![All Traces](../screencasts/google-flu-trends/search-region-box/trace-styles-all.png)

##### 2.5.3. Layout
Now that we've finished styling the traces, click *Layout* to style the background, fonts, and margins. To complete the former, select *Canvas* and set **#F3F6FA** as both *Plot* and *Margin Color*.

![Canvas](../screencasts/google-flu-trends/search-region-box/canvas.png)

Below that, open the *Title and Fonts* box and under *Global Font*, set *Typeface* to **Raleway**, *Font Size* to **12**, and *Color* to **#506784**.

![Global Font](../screencasts/google-flu-trends/search-region-box/global-font.png)

To set the margins, select the *Margins and Padding* box
and enter the values **0, 30, 50, 150, 0**, respectively.

![Margins](../screencasts/google-flu-trends/search-region-box/margins.png)

##### 2.5.4. Axes
Next, navigate to the *Axes* tab, open *Titles* remove the *x* title and then set the *y* axis title to **"Google Flu trends search volume index"**.

![Axes Titles](../screencasts/google-flu-trends/search-region-box/axes-titles.png)

Staying in the *Axes* tab, open *Tick Labels*, *x* and set *Font Size* to **10**.

![Tick Labels](../screencasts/google-flu-trends/search-region-box/tick-labels.png)

##### 2.5.5. Save
Congrats, your chart is complete! Click **Save** on the left-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all) or **Private Link** (visible only to those who you share the link with) and hit **Save**. Since these plots are destined for a dashboard, they can't be set to private.

![Save](../screencasts/google-flu-trends/search-region-box/save.png)

## 3. Create a Dashboard

With the charts completed and saved in your [home folder](https://plot.ly/organize/home), we can now create a dashboard by simply adding these charts, adjusting the layout, and styling the dashboard before sharing and interacting. To get started with creating a dashboard, hover over the *+Create* button and select **Dashboard** from the menu. Alternatively, open this [link](https://plot.ly/dashboard/create).

### 3.1. Add Charts
Before adding a chart, we'll add a text box to describe the dashboard and its uses. Simply, click the *Text* button, where a text editor ought to appear. In the text editor, add the text you wish to display in the dashboard.

![Add Text](../screencasts/google-flu-trends/dashboard/add-text.png)

Now to add the Oklahoma bar plot, click *+Plot* in the bottom left corner of the screen. A new box ought to appear with the option to 'Add a Plot'. Click, the *'Your Files'* option and then in the pop-up select the **Oklahoma Bar Plot** we made earlier.

![Add Oklahoma Bar](../screencasts/google-flu-trends/dashboard/add-plot.png)

Repeat this process to add all the charts in the order they were made.

![Add All Plots](../screencasts/google-flu-trends/dashboard/add-plot-all.png)

Now that we have added all the plots to the dashboard, for each plot where it says "Enter a title..." insert plot titles: **Flu Search Volume in Oklahoma**, **Flu Search Volume in New York**, and **Flu Search Volume in United States**, **Flu Search Boxplot** twice, in the same order as we added the plots. Your result ought to look like below.

![Add Plot Titles](../screencasts/google-flu-trends/dashboard/add-plot-title.png)

### 3.2. Style It

Now that we have the structure of our dashboard, we can style it. To do so, navigate to the *settings icon* directly opposite the dashboard title. When hovering you ought to see the option settings from the menu.

![Settings](../screencasts/google-flu-trends/dashboard/settings.png)

After clicking *settings*, a panel ought to appear from the right-hand side of the screen. Here, we have the option of headers, colors, text, layout, and filter. First, in *Headers*, we can set the title, add a logo, and multiple links. For this tutorial, add **Flu Trends** to the *Title* text box. Next, let's add the Google logo. We can do this by simply adding the URL for the logo PNG: **http://diylogodesigns.com/blog/wp-content/uploads/2016/04/new-google-logo-png.png**.

![Header](../screencasts/google-flu-trends/dashboard/header.png)

In the next tab, *Colors*, we can manipulate the background, borders, and text colors. As you can see, the dashboard has already added these by default. That said, for this dashboard we will set *Header Background*, *Page Background*, *Box Background*, *Box Border*, and *Box Header Background* to **#F3F6FA**. Leave *Header Font Color* as-is.

![Colors](../screencasts/google-flu-trends/dashboard/colors.png)

*Text*, the third settings option, allows you to control all things text, including font color, family, and size, as well as header styles and text box styles. Again, like the Colors tab, some values are defined. However, here, we'll set the *Font Family* to **Raleway**. Make the header font larger by selecting **2.2em** in the *Header Font Size* and, additionally, change the *Header Font Weight* to **300**. Lastly, to separate the text box, set the *Text Box Background Color* to **#F3F6FA**.

![Text](../screencasts/google-flu-trends/dashboard/text.png)

In *Layout*, you have the option of setting the page layout as either a dashboard or a report. Here, we'll leave it as the default dashboard setting. The last settings category, *Filter*, provides you with the option to enable or disable the Search Bar or the Crossfilter feature. For this tutorial, leave the *Search Bar* as is but lets enable the *Crossfilter* feature by selecting **enable** (for more information about this feature see the next section).

![Filter](../screencasts/google-flu-trends/dashboard/filter.png)

Congrats, your dashboard is complete! Click **Save** on in the bottom right-hand side of the screen. In the pop-up, enter your filename and select either **Public** (visible to all), or **Private Link** (visible only to those who you share the link with), or **Private** (visible only to you) and hit **Save**. .

![Save](../screencasts/google-flu-trends/dashboard/save.png)

## 4. Crossfilter

Crossfilter is a visual analysis technique for multidimensional data. It is used to clarify relationships between dimensions. As discussed in the previous section, crossfilter functionality is invoked by setting **enable** in Settings > Filter.

To use crossfilter, simply click-and-drag on a chart. Selected data that shares common rows with other charts will highlight and all other data will fade out. To reset the dashboard, click anywhere on a graph that doesn't have data.

![Crossfilter](../screencasts/google-flu-trends.gif)
