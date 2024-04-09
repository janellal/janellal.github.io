---
title: HW 8 Visualization
tags: [Technology, Blogging]
style: fill
color: secondary
description: This is a blog post of Homework 8.
---

<div class="middle">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="Dataset" %}
</div>

<div class="middle">
{% include elements/button.html link="https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv" text="Analysis" %}
</div>

## Analysis for Bar Graph  
The graph I created was a bar graph with data representing the number of buildings that a Congress district acquired for each year. This is helpful to know to keep track of how many buildings are in each Congress district and the purpose of the building. On the side of the graph, it has a description key that lets people know the building's purpose and we can see how many of those buildings are in each district.

<vegachart schema-url="{{ site.baseurl }}/assets/json/viz1.json" style="width: 100%"></vegachart>

## Analysis for Scatter Plot
The graph I created for the second data visualization was a scatter plot that represents the year a building was acquired and the year it was constructed. It was interesting to see that most buildings were constructed the same year as acquisition, however, there were some outliers that waited after they acquired the building to construct on it. This graph is helpful to show the age of the buildings.

<vegachart schema-url="{{ site.baseurl }}/assets/json/viz2.json" style="width: 100%"></vegachart>