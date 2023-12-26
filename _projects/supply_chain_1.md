---
layout: page
title: "Supply Chain Analysis & Optimization - pt 1"
description: Analysis of supply chain data (Supply chains, optimization, Python, scipy PuLP)
img: supplyChain.png
importance: 2
category: fun
---

In this project I explore some supply chain logistics network data. I do some basic data viz in Tableau (<a href="https://public.tableau.com/app/profile/alex.mcdaniel/viz/SupplyChainLogistics_17028331172440/Dashboard1">see here</a>) and then calculate the supply chain cost given the warehousing and transport costs of the network and the orders. I then create a very simple linear programming model to optimize the warehouse assignment. This is done using SciPy and PuLP in order to compare the two implementations. Overall the optimization yields a ~25% cost reduction compared to random warehouse assignment.

This was a very simplified analysis that I hope to follow up with a more complicated study that includes more of the complexities provided by the dataset. Here however I mainly wanted to play around with the various interconnected supply chain data tables, practice visualizing supply chain data, and perform basic supply chain optimization tasks.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="warehouse_assignment.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Assignment of orders to each warehouse. The black outline shows the warehouse order capacity. Blue bars indicate random assignments, while the orange bars are the optimal assignment, which reduces costs by ~25%.
</div>





<h1>
    Jupyter Notebook
</h1>

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/SupplyChain_pt1.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/SupplyChain_pt1.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
