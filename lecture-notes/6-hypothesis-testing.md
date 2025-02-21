---
layout: default
title: I love being rejected!
nav_order: 7
---

# I love being rejected!
## 6. Hypothesis testing

We will be able to answer the most important question of the century- are golden retrievers taller than those strange things called pugs? We will gather evidence to answer this question through a method in statistics called hypothesis testing. A hypothesis is an educated guess or statement about a population or observation. It is often based on previous knowledge or observations (we saw a lot of golden retrievers that were taller than the one pug). In statistics, we determine support for evidence by hypothesis testing. 

{: .key }
In hypothesis testing, we start with two hypotheses: the null hypothesis (H0) and the alternative hypothesis (Ha). The null hypothesis represents the assumption that there is no significant difference or relationship between variables, while the alternative hypothesis suggests that there is a significant difference or relationship. 

In our example of comparing golden retriever and pug height, this means the null hypothesis is that there is no difference in heights between the two breeds. Our alternative hypothesis is that a difference in heights between the two breeds does exist. <br>
<br>
To conduct hypothesis testing, we collect data and analyze it using statistical tests, of which there are many different kinds. The goal is to either reject or fail to reject the null hypothesis, based on the statistical tests that analyze our data. This process helps us draw conclusions and make informed decisions, and perhaps go on to even bigger projects (are golden retrievers also better swimming dogs than pugs?). So, how do we decide when to reject the null hypothesis?. <br>

{: .youtube }
Dig deeper into hypothesis testing with a [Khan Academy video](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/idea-of-significance-tests/v/simple-hypothesis-testing).

We make a decision based on the concept of a probability value, or a p-value. A p-value is a measure that quantifies the likelihood of evidence against the null hypothesis. It tells us the probability (from 0 to 1) of obtaining our result based on the observed data. The statistical field has generally landed on p-values less than 0.05 being “statistically significant”, which means that a p-value of 0.05 provides evidence to reject the null hypothesis. This equates to us saying that we are 95% confident that the null hypothesis should be rejected. It also means that we could be wrong in rejecting the null hypothesis in 5% of scenarios. 

{: .key }
So, a significant p-value provides evidence in favor of our alternative hypothesis, but it doesn’t mean it’s fact. 

We would need to repeat the experiments in different conditions to see if this is true. If we are interested in seeing a difference in golden retriever and pug height differences, we should compare these dogs in New York City, Los Angeles, Tokyo, Cape Town, Buenos Aires, Mumbai, and more cities. Of course we can’t compare pugs and golden retrievers in every city, so we take an incredibly small risk of being wrong by saying pugs are shorter than golden retrievers, but it certainly beats all the time and money it would take to measure and compare all pugs and all golden retrievers in every city since the beginning of time to all eternity. <br>
<br>
Let’s talk more about interpreting a p-value. When interpreting the p-value, we compare it to a predetermined critical threshold, usually set at 0.05 (5%), though this can vary by research field. If the p-value is less than the critical threshold (p < 0.05), we reject the null hypothesis in favor of the alternative hypothesis. This means that the evidence supports the idea of a significant difference or relationship, i.e. golden retrievers and pugs are not the same height. <br>
<br>
On the other hand, if the p-value is greater than or equal to the critical threshold (p ≥ 0.05), we fail to reject the null hypothesis. This indicates that the evidence does not provide support for a significant difference or relationship. However, it's important to note that failing to reject the null hypothesis does not necessarily mean that the null hypothesis is fact; it simply means that we do not have enough evidence to support the alternative hypothesis. Maybe we find that the pugs in New York City are surprisingly big (maybe from all the NYC Style pizza?). We could test the difference again in Tokyo and perhaps we do find a significant difference. <br>
<br>
So, we know p-values need to be smaller than the critical value for a significant result, but how do we get a p-value? Each statistical test generates something called a test statistic that corresponds to a p-value. 

{: .key }
Test statistics play a crucial role in hypothesis testing! A test statistic is a numerical value that summarizes the data and helps us make comparisons. 

The main advantage of the test statistics is that it follows a known distribution so we can make easy probability calculations (as we did for the z-score). Different tests have different formulas (we’ll see some below and in future sections), but the reason to have test statistics is to have a standardized value that we can compare to certain thresholds or critical values and so we can get a p-value. 

{: .youtube }
Understand p-values more with this [Khan Academy video](https://www.khanacademy.org/math/statistics-probability/significance-tests-one-sample/idea-of-significance-tests/v/p-values-and-significance-tests) and
dive into statistical significance meanings more with this [Khan Academy video](https://www.khanacademy.org/math/statistics-probability/significance-tests-confidence-intervals-two-samples/comparing-two-means/v/statistical-significance-experiment).

We’ve been discussing the idea of comparing golden retrievers and pugs for a while now, and to actually do it, we can use a statistical test called a t-test (more on that later). So enough talk, let's do it! 
<br>

PS- You’ve just read a lot of technical terms that leave you confused. You are not alone! Even the experts in statistics and data science have struggled with these concepts. Experts still need to go back and refresh their memories of how hypothesis testing, critical values, and test statistics work together. To help solidify these terms, we will put these into practice with step by step instructions so you can understand the whole process of turning data into evidence that supports or rejects a hypothesis. In the next section, we finally get to compare golden retriever heights with pug heights, and move on from that example! <br>

| [Home](https://benrushscience.github.io/learning-data-science/) | [Next: Comparing two groups](https://benrushscience.github.io/learning-data-science/pages/7-comparing-2-groups.html) |
