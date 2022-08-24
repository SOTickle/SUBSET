# SUBSET
Sparse and Dense Changepoint Detection for High-Dimensional Time Series

SUBSET (Sparse and Ubiquitous Binary Segmentation in Efficient Time) is a changepoint detection method designed for the offline, multivariate setting. For full details of the method, and an application to the detection of change in terror levels in various global regions, see "A computationally efficient, high-dimensional multiple changepoint procedure with application to global terrorism incidence", by Tickle, Eckley and Fearnhead, which can be found here: https://rss.onlinelibrary.wiley.com/doi/10.1111/rssa.12695. The mechanism by which multiple changepoints are detected is called Wild Binary Segmentation, more details of which can be found in "Wild Binary Segmentation for multiple change-point detection" by Fryzlewicz, which can be found here: https://projecteuclid.org/journals/annals-of-statistics/volume-42/issue-6/Wild-binary-segmentation-for-multiple-change-point-detection/10.1214/14-AOS1245.full.

The central functions of interest here can be found in main.R, in particular change_main.R and wbs_penaltyfinder.R.
