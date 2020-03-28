[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

>> REPLACE THIS TEXT WITH YOUR RESPONSE
import scipy.stats

mean = 178
std = 7.7

distribution = scipy.stats.norm(loc=mean, scale = std)

low_hight = distribution.cdf(177.8)
high_hight = distribution.cdf(185.4)

diff = high_hight - low_hight
