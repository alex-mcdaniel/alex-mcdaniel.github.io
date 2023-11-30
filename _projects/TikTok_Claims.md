---
layout: page
title: TikTok Claims Classification
description: Classification model to predict whethe a TikTok video expresses a claim or an opinion (ML/AI, Classification, Python, XGBoost, Random forest)
img: assets/img/tiktok.png
importance: 3
category: fun
---

In this project we are analyzing an artifcial TikTok dataset. The problem background is as follows:

<blockquote>"At TikTok, our mission is to inspire creativity and bring joy. Our employees lead with curiosity and move at the speed of culture. Combined with our company's flat structure, you'll be given dynamic opportunities to make a real impact on a rapidly expanding company, and grow your career.

TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider in a timely manner. 

TikTok is working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently."</blockquote>

In other words, the goal of this project is to develop a predictive model that can determine whether a video contains a claim or offers an opinion. 

 The notebook for this project can be found as a <a href="TikTok_Claim_Classification.html">static webpage here</a>. The related Tableau Story can be found <a href="https://public.tableau.com/app/profile/alex.mcdaniel/viz/TikTokClaimsClassificationbasicEDA/Story1">here</a>. This project was completed as part of the <a href="https://www.coursera.org/professional-certificates/google-advanced-data-analytics">Google Advanced Data Analytics Professional Certificate</a>.




<h2>Summary Slides</h2>

<article class="post-content CV clearfix">
        <embed src="TikTokClaimsClassificationResults.pdf" width="75%" height="800" type="application/pdf" />

</article>



<h1>
    Jupyter Notebook
</h1>

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/TikTok_Claim_Classification.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/DisY_Boost.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
