---
layout: page
title: Salifort Motors Employee Retention Predictor
description: Classification model to predict whether an Employee at Salifort Motors is likely to leave (ML/AI, Classification, Python, XGBoost)
img: assets/img/salifort.png
importance: 5
category: fun
---

In this project we are analyzing a dataset from a fictional auto company's HR records to build a model that predicts whether an employee will leave the company. The problem background is as follows:

<blockquote>
<h3>Salifort Motors Employee Retention</h3>


<h4>About the company</h4>
Salifort Motors is a fictional French-based alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles. Salifort’s end-to-end vertical integration model has made it a global leader at the intersection of alternative energy and automobiles.     


<h4>Your business case</h4>
As a data specialist working for Salifort Motors, you have received the results of a recent employee survey. The senior leadership team has tasked you with analyzing the data to come up with ideas for how to increase employee retention. To help with this, they would like you to design a model that predicts whether an employee will leave the company based on their  department, number of projects, average monthly hours, and any other data points you deem helpful. 
"</blockquote>


 The notebook for this project can be found on this page after the slides or as a <a href="Salifort_Motors.html">static webpage here</a>. This project was completed as the Capstone project for the <a href="https://www.coursera.org/professional-certificates/google-advanced-data-analytics">Google Advanced Data Analytics Professional Certificate</a>.




<h2>Summary Slides</h2>

<article class="post-content CV clearfix">
        <embed src="../../assets/pdf/Salifort_Motors.pdf" width="75%" height="800" type="application/pdf" />

</article>



<h1>
    Jupyter Notebook
</h1>

{::nomarkdown}
{% assign jupyter_path = "../../assets/jupyter/Salifort_Motors.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/Salifort_Motors.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
