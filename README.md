# Equal Opportunity of Coverage in Fair Regression

We study fair machine learning under predictive uncertainty to enable reliable and trustworthy decision-making. We introduce a new uncertainty-aware fairness notion, Equal Opportunity of Coverage (EOC). Under EOC, each group with the same label is treated equally, not only in terms of equal coverage rates (i.e., equal probability of being included in the prediction result) but also in terms of comparable prediction widths as a measure of uncertainty. 

To enhance EOC, we propose Binned Fair Quantile Regression (BFQR) with several desired properties: It guarantees equal coverage rates for groups with the same labels and marginal coverage rate at a pre-determined level. It also ensures a small prediction interval than CQR. This repository contains the codes for evaluating EOC and our proposed method, BFQR.
