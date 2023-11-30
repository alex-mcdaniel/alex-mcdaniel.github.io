---
layout: page
title: "DisYBoost: Physician Recommendation Predictions"
description: Classification model built using XGBoost (ML/AI, Decision Trees, XGBoost, Python)
img: assets/img/DisYBoost.png
importance: 2
category: fun
---



<article class="post-content CV clearfix">
        <embed src="../assets/pdf/DisYBoost.pdf" width="100%" height="800" type="application/pdf" />

</article>


{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/DisY_Boost.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/DisY_Boost.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
    {% jupyter_notebook jupyter_path %}
{% else %}
    <p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}
