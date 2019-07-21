# GEEreport
Generate a report of important stats for GEEs

# Usage 

`parseSummary.GEEpack(geeglm_model,odsig=4,logit=FALSE)`
`odsig`: number of significant figures
`logit`: if true, reports Odds ratios and marginal H and modified marginal R^2 (zhang,2000), ignores shapiro-wilks

| | Coef |	95& CI	|Pr(W) |
|--- | --- | --- | --- |
(Intercept) |	0.74030 |(0.3485 - 1.132) |	6.118273e-03
Secretor|	-1.36800	|(-0.6422 - -2.095) | 4.328510e-07
log(DPP) |0.09137 |	(0.06535 - 0.1174) | 5.294142e-01

| stat | value |
|---|---|
Number of observations|	47.0000000
Number of Clusters|	6.0000000
Marginal R^2	|0.4525000
Degrees of Freedom	|44.0000000
Shapiro-Wilks P	|0.5327019

