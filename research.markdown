---
layout: default
title: Research
slug: research/
---

## **Publications**

## Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors
*(with Michael Vogt)*

*Journal of the Royal Statistical Society: Series B, Volume 82, Number 1 (2020), 5-37*

{% raw %}
We develop new multiscale methods to test qualitative hypotheses about the function $$m$$ in the nonparametric regression model $$Y_{t,T}=m(t/T)+\varepsilon_t$$ with time series errors $$\varepsilon_t$$. In time series applications, $$m$$ represents a nonparametric time trend. Practitioners are often interested in whether the trend $$m$$ has certain shape properties. For example, they would like to know whether $$m$$ is constant or whether it is increasing or decreasing in certain time intervals. Our multiscale methods enable us to test for such shape properties of the trend $$m$$. To perform the methods, we require an estimator of the long‐run error variance $$\sigma^2 = \sum_{l = -\infty}^{\infty} cov(\varepsilon_0, \varepsilon_l)$$. We propose a new difference‐based estimator of $$\sigma^2$$ for the case that $$\{\varepsilon_t\}$$ belongs to the class of auto‐regressive AR($$\infty$$)  processes. In the technical part of the paper, we derive asymptotic theory for the proposed multiscale test and the estimator of the long‐run error variance. The theory is complemented by a simulation study and an empirical application to climate data.

{% endraw %}

[Paper][1] and [Supplement][2]

[1]:{{ site.url }}/download/Khismatullina_onetrend.pdf
[2]:{{ site.url }}/download/Khismatullina_onetrend_supplement.pdf

## Nonparametric comparison of epidemic time trends: the case of COVID-19
*(with Michael Vogt)*

The COVID-19 pandemic is one of the most pressing issues at present. A question which is particularly important for governments and policy makers is the following: Does the virus spread in the same way in different countries? Or are there significant differences in the development of the epidemic? In this paper, we devise new inference methods that allow to detect differences in the development of the COVID-19 epidemic across countries in a statistically rigorous way. In our empirical study, we use the methods to compare the outbreak patterns of the epidemic in a number of European countries.

*Forthcoming in Journal of Econometrics*

[Paper][3]

[3]:{{ site.url }}/download/Khismatullina_epidemic.pdf

## **Working papers**

## Multiscale Testing for Equality of Nonparametric Trend Curves
*(with Michael Vogt)*

We develop new econometric methods for the comparison of nonparametric time trends. In many applications, practitioners are interested in whether the observed time series all have the same time trend. Moreover, they would often like to know which trends are different and in which time intervals they differ. We design a multiscale test to formally approach these questions. Specifically, we develop a test which allows to make rigorous confidence statements about which time trends are different and where (that is, in which time intervals) they differ. Based on our multiscale test, we further develop a clustering algorithm which allows to cluster the observed time series into groups with the same trend. We derive asymptotic theory for our test and clustering methods. The theory is complemented by a simulation study and two applications to house pricing data and GDP growth data.

[Paper][4]

[4]:{{ site.url }}/download/Khismatullina_multipletrends.pdf

## **Packages**

## Multiscale R package

{% raw %}
This package implements the multiscale analysis proposed in the papers "Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors" and "Nonparametric comparison of epidemic time trends: the case of COVID-19". Specifically, it allows to test qualitative hypotheses (such as shape properties) about the nonparametric time trend $$m$$ in the model $$Y_t = m(t/T) + \varepsilon_t$$ with time series errors $$\varepsilon_t$$ and to compare the nonparametric time trends in the context of epidemic modelling. The package as well as the detailed description of its functionality can be found in <a href="https://github.com/marina-khi/multiscale"> this github repository</a>.
{% endraw %}