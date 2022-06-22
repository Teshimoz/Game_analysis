# Game Analysis
Scripts that analyze user retention, A/B testing, visualizations<br>
<b>Rendered notebook:</b><br>
https://nbviewer.org/github/Teshimoz/Game_analysis/blob/4c1c3922934f4d0b02f06039e7ef31194fa11fef/Game_retention_ab.ipynb
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
