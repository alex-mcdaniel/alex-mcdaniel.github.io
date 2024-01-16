---
layout: page
title: Powered Finance - Predicitng Customer Defaults
description: Classification model to predict whether an applicant for a loan is likely to default (ML/AI, Classification, Logistic Regression, Python, XGBoost)
img: assets/img/poweredFinance.png
importance: 5
category: fun
---

In this project we are analyzing a dataset of loan applicants from a fictional consumer lending company to build a model that predicts whether the applicant will default on the loan or not. Summary slides and the notebook are shown below.


<h2>Summary Slides</h2>

<article class="post-content CV clearfix">
        <embed src="../../assets/pdf/PoweredFinance_SummarySlides.pdf" width="75%" height="800" type="application/pdf" />

</article>



<h1>
    Jupyter Notebook
</h1>

{::nomarkdown}
{% assign jupyter_path = "../../assets/jupyter/PoweredFinance_PredictingCustomerDefaults.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/PoweredFinance_PredictingCustomerDefaults.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
