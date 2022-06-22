# Game Analysis
Scripts that analyze user retention, A/B testing, visualizations<br>
<b>Rendered notebook:</b><br>
https://nbviewer.org/github/Teshimoz/Game_analysis/blob/6e89b9a17fb31fe1309235d5f1e3944ab0512782/Game_retention_ab.ipynb
<br><br>
<b>Project description:</b><br>
There was a deployment of the new mobile game application version. We want to be sure everything working properly and all users can to migrate to the new one.<br>
Notebook include following steps:
* Create functions to filter data by groups and subgroups
* Explore users behaviour in different groups and subgroups
* Calculate retentions for different groups of `Unique users`
* Check groups or subgroups trends by:
    * plotting graphs and heat maps of retention (in absolute values and normalized)
    * statisctical tests between groups after normalization<br>
    
<br>Used pandas, matplotlib, scipy, statsmodels.
