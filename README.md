# PCA Demo
Using principal component analysis to perdict Leauge of Legends game outcomes from the 1st 10 minutes of gameplay. 

# PCA Notes
Plan:
1. Standardization of features:

<p style="padding-left: 28.5px">
    Mean &#8594; 0 
</p>
<p style="padding-left: 28.5px">
    If the importance of features is independent of the variance of the features, then sd &#8594; 1. 
    Otherwise, leave as is.
    In the case of the LoL dataset, this is true. So we will be fully normalizing these features.
</p>

2. Calculate [scatter or covariance matrix](http://www.statistics4u.com/fundstat_eng/cc_covarmat.html "learn more about these matrices here") of the features

3. 



# References

**Data:**  
https://www.kaggle.com/bobbyscience/league-of-legends-diamond-ranked-games-10-min

**Resources**  
https://stattrek.com/matrix-algebra/covariance-matrix.aspx  
http://www.statistics4u.com/fundstat_eng/cc_covarmat.html    
https://medium.com/@raghavan99o/scatter-matrix-covariance-and-correlation-explained-14921741ca56  
https://towardsdatascience.com/a-one-stop-shop-for-principal-component-analysis-5582fb7e0a9c  
https://builtin.com/data-science/step-step-explanation-principal-component-analysis  
https://medium.com/@raghavan99o/principal-component-analysis-pca-explained-and-implemented-eeab7cb73b72  
https://en.wikipedia.org/wiki/Principal_component_analysis  