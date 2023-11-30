---
layout: page
title: "DisYBoost: Physician Recommendation Predictions"
description: Classification model built using XGBoost (ML/AI, Decision Trees, XGBoost, Python)
img: assets/img/DisYBoost.png
importance: 2
category: fun
---

In this project, we are tasked with predicting whether or not physicians will will recommend a product from our company (Product X) to treat a particular disease (Disease Y). The datset provided encompasses patient Chart data that physicians have filled out for their patients. I ended up deciding to use an XGBoost based classifier for this task, and ultimately acheived an accuracy of ~85%, which we deemed a good model for this task given the data.

Below you can find some summary slides as well as the notebook including EDA and Model construction/testing. The full problem statement is given below.


<blockquote>
<p>You have been asked to participate in the evaluation of a novel new compound (Product X) being considered for the treatment of "Disease Y". The Medical Affairs team has partnered with leading physicians to complete a detailed chart review of thousands of potential patients. The physicians have documented other relevant treatments and diagnoses each patient has received. Disease Y presents in three types: mild, moderate, and severe. 


Using the data provided, please build a model to predict whether physicians are likely to recommend Product_X for any given patient. Summarize the data and your findings in a PowerPoint (or equivalent) deck of no more than 5 slides. Your target audience is a mixture of medical, marketing, and analytics leaders, with varying levels of data science familiarity. </p>
</blockquote>




<h3>Summary Slides</h3>
<article class="post-content CV clearfix">
        <embed src="DisYBoost.pdf" width="75%" height="800" type="application/pdf" />

</article>






<h1>
    Jupyter Notebook
</h1>

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/DisY_Boost.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/DisY_Boost.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
