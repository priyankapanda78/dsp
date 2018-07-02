[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)
```
sample = np.random.random(1000)
pmf = thinkstats2.Pmf(sample)
thinkplot.Pmf(pmf,linewidth=0.1)
thinkplot.Config(xlabel='randomNumbers',ylabel='PMF')
cdf=thinkstats2.Cdf(sample)
thinkplot.Cdf(cdf)
thinkplot.Config(xlabel='randomNumbers',ylabel='CDF')

PMF plot is not uniform and all the random numbers have same PMF value.
CDF plot is uniform for this sample.
