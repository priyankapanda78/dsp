[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

```
resp = nsfg.ReadFemResp()
pmf = thinkstats2.Pmf(resp.numkdhh,label = 'numkdhh')
thinkplot.Pmf(pmf)
thinkplot.Config(xlabel='Number of children', ylabel='PMF')
biased_pmf = BiasPmf1(pmf, label='observed')
thinkplot.PrePlot(2)
thinkplot.Pmfs([pmf, biased_pmf])
thinkplot.Config(xlabel='Number of children', ylabel='PMF')
print('Actual mean', pmf.Mean())
print('Observed mean', biased_pmf.Mean())
```
