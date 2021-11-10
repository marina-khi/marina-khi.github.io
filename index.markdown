---

layout: home
title: "Home"
profile_picture:
  src: /assets/img/profile_pic.jpg
  alt: Profile photo
---


## Welcome!

I am an Assistant Professor of Econometrics at Erasmus University Rotterdam. I have obtained my PhD in Economics in August 2021 at the University of Bonn. I am interested in Econometrics and Statistics, specifically in Nonparametric Statistics and Time Series Analysis. I am also interested in economic applications for statistical methods.

**E-mail:** khismatullina [at] ese.eur.nl



## Research


<p style="line-height:150%"><b> Nonparametric comparison of epidemic time trends: the case of COVID-19<br/>
<em>(with Michael Vogt, forthcoming in Journal of Econometrics)</em></b></p>

*[Paper][4]*

The COVID-19 pandemic is one of the most pressing issues at present. A question which is particularly important for governments and policy makers is the following: Does the virus spread in the same way in different countries? Or are there significant differences in the development of the epidemic? In this paper, we devise new inference methods that allow to detect differences in the development of the COVID-19 epidemic across countries in a statistically rigorous way. In our empirical study, we use the methods to compare the outbreak patterns of the epidemic in a number of European countries.


[4]:{{ site.url }}/download/Khismatullina_epidemic.pdf

<p style="line-height:150%"><b> Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors<br/>
<em>(with Michael Vogt, published in Journal of the Royal Statistical Society: Series B, Volume 82, Number 1 (2020), 5-37)</em>
</b>
</p>

*[Paper][5] and [Supplement][6]*

{% raw %}
We develop new multiscale methods to test qualitative hypotheses about the function $$m$$ in the nonparametric regression model $$Y_{t,T}=m(t/T)+\varepsilon_t$$ with time series errors $$\varepsilon_t$$. In time series applications, $$m$$ represents a nonparametric time trend. Practitioners are often interested in whether the trend $$m$$ has certain shape properties. For example, they would like to know whether $$m$$ is constant or whether it is increasing or decreasing in certain time intervals. Our multiscale methods enable us to test for such shape properties of the trend $$m$$. To perform the methods, we require an estimator of the long‐run error variance $$\sigma^2 = \sum_{l = -\infty}^{\infty} cov(\varepsilon_0, \varepsilon_l)$$. We propose a new difference‐based estimator of $$\sigma^2$$ for the case that $$\{\varepsilon_t\}$$ belongs to the class of auto‐regressive AR($$\infty$$)  processes. In the technical part of the paper, we derive asymptotic theory for the proposed multiscale test and the estimator of the long‐run error variance. The theory is complemented by a simulation study and an empirical application to climate data.

{% endraw %}

[5]:{{ site.url }}/download/Khismatullina_onetrend.pdf
[6]:{{ site.url }}/download/Khismatullina_onetrend_supplement.pdf

<p style="line-height:150%"><b> Multiscale Testing for Equality of Nonparametric Trend Curves<br/>
<em>(with Michael Vogt, working paper)</em></b></p>

*Draft is available upon request*

The comparison of nonparametric curves is a classic topic in econometrics and statistics. Depending on the specific application, the curves of interest are densities, distribution functions, time trends or regression curves. In this paper, we focus on the comparison of nonparametric trend curves. We develop new multiscale method for testing whether the trend curves are the same across observed time series. Moreover, the test allows us to detect the regions where the trend curves are different. We illustrate our method with an application to daily price returns for a number of US companies.

**Multiscale R package**

{% raw %}
This package implements the multiscale analysis proposed in the papers "Multiscale Inference and Long-Run Variance Estimation in Nonparametric Regression with Time Series Errors" and "Nonparametric comparison of epidemic time trends: the case of COVID-19". Specifically, it allows to test qualitative hypotheses (such as shape properties) about the nonparametric time trend $$m$$ in the model $$Y_t = m(t/T) + \varepsilon_t$$ with time series errors $$\varepsilon_t$$ and to compare the nonparametric time trends in the context of epidemic modelling. The package as well as the detailed description of its functionality can be found in <a href="https://github.com/marina-khi/multiscale"> this github repository</a>.
{% endraw %}