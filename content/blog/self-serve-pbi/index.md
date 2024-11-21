---
title: "Self-serve in PowerBI"
description: ""
date: 2024-11-21
author: bigarabuza
---
PowerBI reports are a good way to visualize data across your organization. However, if you’re not a PowerBI developer you might find yourself in a bind when a report does not have the exact view you’re looking for. Fortunately, PowerBI offers the capability to personalize visuals to your liking. I walk through two features that you can easily use: 

- [Personalize visuals](#personalize-visuals)
- [Show as table](#show-as-table) 

## Personalize visuals 

As the name suggests, ‘Personalize visuals’ gives you the ability to customize visuals. Some customizations include: 
- Changing the visualization type 
- Swapping out measures and/or columns 
- Adding or removing chart legends and so on. 

It’s a versatile and familiar feature if you have worked with Pivot Tables in Excel or Google Sheets. To use the feature simply click the 'Personalize this visual' ( ![personalize visual icon](img/pbi-personalize-viz-icon.png)  ) icon and customize the visual to your liking as demonstrated below: 

{{< img src="img/pbi-personalize-viz-walkthrough.gif" alt="Personalize the visual walkthrough" >}} 
 
Note: This feature isn’t activated by default and needs to be enabled by your report author as noted [here](https://learn.microsoft.com/en-us/power-bi/create-reports/power-bi-personalize-visuals?tabs=powerbi-desktop#enable-personalization-in-a-report).  

## Show as table 

You can convert a visual of any kind to a tabular format. While visuals are useful to quickly view trends, identify outliers & make slick looking slide decks, there are use cases that would benefit from the raw numbers behind a report. Manual reconciliation of data across systems might call for reporting precise numbers. Users from the accounting department might not trust the report until they see the raw numbers tied to the general ledger.  

To show a visual as a table: 
- Click More options (...)  on the top right section of the visual 
- Click Show as a table 

The table appears below the visual.  

{{< img src="img/pbi-show-table-walkthrough.gif" alt="Show as table walkthrough" >}} 

Note; not all visuals support this ‘Show as a table’ feature. Visual types that are not supported include: Card, KPI, Key influencers, Q&A visual, Smart narrative, Metrics app visual, Paginated report visual, Power Apps for Power BI visual, ArcGIS map for Power BI visual, Power Automate for Power BI visual.  

More details about the feature can be found in [Microsoft’s official documentation](https://learn.microsoft.com/en-us/power-bi/create-reports/end-user-show-data?tabs=powerbi-service#show-the-data-that-creates-a-report-visual).  

These techniques enable you to self-serve without reaching back out to your PowerBI developer. They are simple and straightforward to implement. A more advanced feature is [Analye in Excel](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-analyze-in-excel). This gives you full control over the layout of the underlying data with Excel. A blog post for another day!

