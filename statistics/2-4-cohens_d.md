[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)
```def WeightDifference(firsts,others):
    mean1 = firsts.totalwgt_lb.mean()
    mean2 = others.totalwgt_lb.mean()
    var1 = firsts.totalwgt_lb.var()
    var2 = others.totalwgt_lb.var()
    n1, n2 = len(firsts),len(others)
    pooled_var = (n1*var1 + n2*var2)/(n1+n2)
    diff = mean1 - mean2
    d = diff / math.sqrt(pooled_var)
    print(d)
    print(mean1)
    print(mean2)```
According to this above result, first babies are lighter than others. And in comparision to pregnancy length, first pregnancy length is longer than others for live babies.
