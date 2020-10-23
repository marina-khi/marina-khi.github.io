---
layout: default
title: Research
slug: research/
---

## **Job Market Paper**


## Nonparametric comparison of epidemic time trends: the case of COVID-19
*(with Michael Vogt)*

The COVID-19 pandemic is one of the most pressing issues at present. A question which is particularly important for governments and policy makers is the following: Does the virus spread in the same way in different countries? Or are there significant differences in the development of the epidemic? In this paper, we devise new inference methods that allow to detect differences in the development of the COVID-19 epidemic across countries in a statistically rigorous way. In our empirical study, we use the methods to compare the outbreak patterns of the epidemic in a number of European countries.

*Submitted to Journal of Econometrics*

[Paper][3]

[3]:{{ site.url }}/download/epidemic_paper.pdf


## **Publications**

## Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors
*(with Michael Vogt)*

*Journal of the Royal Statistical Society: Series B, Volume 82, Number 1 (2020), 5-37*

{% raw %}
We develop new multiscale methods to test qualitative hypotheses about the function $$m$$ in the non‐parametric regression model $$Y_{t,T}=m(t/T)+\varepsilon_t$$ with time series errors $$\varepsilon_t$$. In time series applications, $$m$$ represents a non‐parametric time trend. Practitioners are often interested in whether the trend $$m$$ has certain shape properties. For example, they would like to know whether $$m$$ is constant or whether it is increasing or decreasing in certain time intervals. Our multiscale methods enable us to test for such shape properties of the trend $$m$$. To perform the methods, we require an estimator of the long‐run error variance $$\sigma^2 = \sum_{l = -\infty}^{\infty} cov(\varepsilon_0, \varepsilon_l)$$. We propose a new difference‐based estimator of $$\sigma^2$$ for the case that $$\{\varepsilon_t\}$$ belongs to the class of auto‐regressive AR($$\infty$$)  processes. In the technical part of the paper, we derive asymptotic theory for the proposed multiscale test and the estimator of the long‐run error variance. The theory is complemented by a simulation study and an empirical application to climate data.

{% endraw %}

[Paper][1] and [Supplement][2]

[1]:{{ site.url }}/download/onetrend_paper.pdf
[2]:{{ site.url }}/download/onetrend_supplement.pdf

## **Working papers**

## Multiscale Testing for Equality of Nonparametric Trend Curves
*(with Michael Vogt)*

The comparison of nonparametric curves is a classic topic in econometrics and statistics. Depending on the specific application, the curves of interest are densities, distribution functions, time trends or regression curves. In this paper, we focus on the comparison of nonparametric trend curves. We develop new multiscale method for testing whether the trend curves are the same across observed time series. Moreover, the test allows us to detect the regions where the trend curves are different. We illustrate our method with an application to daily price returns for a number of US companies.

*Draft is available upon request*

## **Packages**

## Multiscale R package

{% raw %}
This package implements the multiscale analysis proposed in the papers "Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors" and "Nonparametric comparison of epidemic time trends: the case of COVID-19". Specifically, it allows to test qualitative hypotheses (such as shape properties) about the nonparametric time trend $$m$$ in the model $$Y_t = m(t/T) + \varepsilon_t$$ with time series errors $$\varepsilon_t$$ and to compare the nonparametric time trends in the context of epidemic modelling. The package as well as the detailed description of its functionality can be found in <a href="https://github.com/marina-khi/multiscale"> this github repository</a>.
{% endraw %}