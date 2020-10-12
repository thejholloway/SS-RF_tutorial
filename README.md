The purpose of this document is to provide guidance about how to implement our **Stochastic spatial random forest (SS-RF) method** for filling missing data in satellite images due to clouds. 

For more details of our method, please see our open access [paper](https://link.springer.com/article/10.1186/s40537-020-00331-8) in the Journal of Big Data. 
If you do use our method **please cite our original paper**. A suggested format is:
Holloway-Brown, J., Helmstedt, K. J., & Mengersen, K. L. (2020). Stochastic spatial random forest (SS-RF) for interpolating probabilities of missing land cover data. Journal of Big Data, 7(1), 55. https://doi.org/10.1186/s40537-020-00331-8 

This document includes the steps to fit our method and produce probabilities of land cover, which we also convert to a binary classification. Before fitting the SS-RF method, I prepare my image data using a process similar to the one outlined in my[previous tutorial](https://github.com/thejholloway/raster2data) about converting a satellite image to a data frame and calculating variables. 
