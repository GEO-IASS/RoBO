---
layout: post
title: Visualization
---

# Plots
RoBO offers following plots pre-implemented in it's visualization package.

## Mean
Plots the mean of different runs of a method for a given time point.

{% highlight python %}
x = np.array([[1, 3, 4, 5], [1, 3, 4, 5], [1, 3, 4, 6]])
method_1 = np.array([[1,4,5,2], [3,4,3,6] , [2,5,5,8]])
method_2 = np.array([[8,7,5,9], [7,3,9,1] , [3,2,9,4]])
method_3 = np.array([[10,13,9,11], [9,12,10,10] , [11,14,18,6]])
methods = [method_1, method_2, method_3]
method_names = ['test method 1','test method 2','test method 3']
plot = plot_mean(x,methods,method_names)
plot.show()
{% endhighlight %}

## Median

## Mean and Standard Deviation

## Standard Error of Mean

## Plot Over Time

## Median and Percentiles

-----
