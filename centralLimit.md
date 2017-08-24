# Mental Model:Central Limit Theorem

## Discipline:Mathematics


## Up Stream Lattice :

Law of large numbers

## Down Stream Lattice :

* 80/20 Rule
* principle of locality


# Introduction:

Atoms, the basic element of our world, is very , very small. an atom is about million times smaller than human hair, the unit to measure atom diameter is nanometer, (10 -10 m), the size is about 0.1 to 0.5 nm

Why atom is so **small** ? why can't it be much larger ?

Nobel laureate Erwin Schrödinger in his insightful book [what is life?](https://www.amazon.com/What-Life-Autobiographical-Sketches-Classics/dp/1107604664/ref=sr_1_3?ie=UTF8&qid=1503536862&sr=8-3&keywords=what+is+life) bring up this question.

Erwin argues the law of physics and chemistry, is **statistical** in nature.

> If you fill the lower part of a closed glass vessel with fog (figure below ), consisting of minute droplets, you will find that the upper or boundary of the fog gradually sinks, with a well-defined velocity, determined by the viscosity of the air and the size and the specific gravity of the droplets. But if you look at one of the droplets under the microscope you find that it does not permanently sink with constant velocity, but performs a very irregular movement, the so-called Brownian movement (figure on the right), which corresponds to a regular sinking only on the average. Now these droplets are not atoms, but they are sufficiently small and light to be not entirely insusceptible to the impact of one single molecule of those which hammer their surface in perpetual impacts. They are thus knocked about and can only on the average follow the influence of gravity. This example shows what funny and disorderly experience we should have if our senses were susceptible to the impact of a few molecules only.

![sinking fog](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/1g4b983h.png)

The brownian of the movement

![brownian movement](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/xt67tvy8.png)

Erwin generalized this statement as $$sqrt(n)$$ law,

>The laws of physics and physical chemistry are inaccurate whithin a probably relative error of the order of 1/$$sqrt(n)$$, where n is the number of the molecules that co-operate to bring about the law





The central limit theorem states:

If you draw a fix number of random samples many times from a pool of numbers with **known** standard deviation & mean, The sum of these sample values from each draw will form a bell curve with predictable standard deviation and mean.

__The prediction:__

The mean of the bell curve will be $$ µ * n $$:

The standard deviation of these sum will be $$ µ* \sqrt{n}$$

If you want to use the average;

sample group mean average = true mean µ
**sample standard deviation** = $$\frac{σ}{\sqrt{n}}$$


**Why this is important?**

CLT is in the heart of modern statistics.

One Example will be The Famous Bell Curve;

Why normal distribution( The bell shape curve) is so widely seen and important ?

One Plausible explanation: A lot of things can be think of a black box with many unknown inside component.

The output of the system could think of a sum of a fix number of internal valuables, these valuable usually has range(finite), and the output of the system is a sum of the internal parts, hence we could apply CLT and expect to get a output of a bell curve.



Example. [Diffusion of innovations](https://en.wikipedia.org/wiki/Diffusion_of_innovations)

> Diffusion of innovations is a theory that seeks to explain how, why, and at what rate new ideas and technology spread. Everett Rogers, a professor of communication studies, popularized the theory in his book Diffusion of Innovations; the book was first published in 1962, and is now in its fifth edition (2003).[1] Rogers argues that diffusion is the process by which an innovation is communicated over time among the participants in a social system. The origins of the diffusion of innovations theory are varied and span multiple disciplines.

> Rogers proposes that four main elements influence the spread of a new idea: the innovation itself, communication channels, time, and a social system. This process relies heavily on human capital. The innovation must be widely adopted in order to self-sustain. Within the rate of adoption, there is a point at which an innovation reaches critical mass.

> The categories of adopters are innovators, early adopters, early majority, late majority, and laggards.[2] Diffusion manifests itself in different ways and is highly subject to the type of adopters and innovation-decision process. The criterion for the adopter categorization is innovativeness, defined as the degree to which an individual adopts a new idea.

![diffusion of ideas](https://upload.wikimedia.org/wikipedia/commons/1/11/Diffusion_of_ideas.svg)

**The S-Curve**

Each innovation is a additive system consist of many internal valuables( how it looks, how it markets, how effective it is solve customer's problem) , and each customer( adopters ) is a sampling of this additive system. thus we could apply CLT and expect a bell curve.



Example:

For example, Human height is influenced by genes, enviromental effects, nutritions etc. The final result(Height) can be think of as sumation of all the influencing factors of a complex system. so by the prediction of central limit theory, it is a bell curve .

![human height](http://i.kinja-img.com/gawker-media/image/upload/s--z9tyvHx3--/c_scale,fl_progressive,q_80,w_800/17iprmfy286axjpg.jpg).

**Why this is useful?**

Because if you know the shape of the distribution and standard deviation of the distribution, you can compute a lot of things

Eg. you can reverse look up the probability of a given data point.


**When it does'n apply ?**


* The Central Limit Theorem only applies to the estimated means of a population parameter when sampled **randomly** and **independently**.

**Independent** and **Random** is the key. human beings is subject to social prove and often influence by decision of others. ( It is not nessary to even be the real decision, just the perceived decision of others) in real life, thus often break the independent requirement.

Thats why polling results is often seems less reliable than the cited "99%" confidence level.

* The central limit theorem fails when there is an infinite variance

* The central limit theorem fails when the output is not a summation of its parts. ie not a additive system, but a multiplicative one.

* The internal factor of is of this blackbox not complete independent, and some times has strong correctlation with each other, and there could be possibly has positive/negative feedback into then, which will create extreme outcomes.

* You need to have enough samples (30 is good, and 15 is a stretch minimum)

An Excellent illustration is explained by [Danielle Fong](http://daniellefong.com/2008/01/28/outliers-why-the-central-limit-theorem-is-typically-off/)



# How to use this mental Model:

* Gather following data by statistics,combination/permutations or approximations, or proability theory
* Gather/compute the true mean µ
* you can try to look for this number in large scale public survey etc.
* Gather/compute Group true standard deviation σ
* you can try to look for this number in large scale public survey etc.
* get the sample size

From the data point above, you can calculate the probability of a given sample data point.

the most difficult part of the process is to get base rate true mean and standard deviation. Fortunately, we can quickly get the data point if the problem is yes/no type.

## Central Limit Theorem **Approximation** for Binomial Distribution


If the process has only two outcomes, 1 or 0, true or false, head or tail, it fits the [Bernoulli Distribution](https://en.wikipedia.org/wiki/Bernoulli_distribution) definition, we can use the following approximation:

lets define:

p: % of x = 1

1-p: % of x = 0

then the mean:

mean = p * 1 +(1-p) * 0 = p

variance = p(1-p)^2 + (1-p)(0-p)^2
= p(1-2p+p^2)+P^2-P^3
= p-2p^2+p^3 +p^2 - P^3 = p-p^2 = p(1-p)


lets say we have n numbers

Expected value = n*p
Variance = p(1-p)/n

if we use average:

Average expected Value = p

The approximation is good if n is large enough for given p.

i.e, must pass the following test: given p, i.e, must pass the following test:

Must have : np ≥ 5 and n(1- p) ≥ 5

[CLT for binomial distribution](http://ocw.mit.edu/courses/sloan-school-of-management/15-063-communicating-with-data-summer-2003/lecture-notes/lecture10.pdf)

Variance = $$p*(1-p)$$

then we can apply the special case of [applying CLT when the base pool is Binomial distriubtion](https://www.stat.auckland.ac.nz/~wild/ChanceEnc/Ch07.propCLT.pdf), and quickly caculate the standard deviation.

if we assign value of head = 1, and value of tail = 0, and the probability of getting a head is p, then σ(x):

* check for CLT binomial conditions. n and p should be large enough for np≥5 and n(1−p)≥5

basically, if the signal less than 5, it will not hold.

Predictions

mean: $$n*p$$

variance: $$\frac{p*(1-p)}{n}$$

standard divation: $$\sqrt{\frac{p*(1-p)}{n}}$$



* Compute the sample group mean/sum mean and standard deviation from CLT

* Caution: You can't use one sample group data standard deviation to calculate population standard deviation.
as the CLT only says: sample group average σ' = σ/(n)^0.5

The σ' is the standard deviation of sample group average, not the stand deviation within the samples.


* Use Normdist function of google spreadsheet to find out the probability, if needed.

* Compute the sample group mean/sum mean and standard deviation from CLT

* Use Normdist function of google spreadsheet to find out the probability, if needed.



### Predictions:

* The probability of the true mean of the samples higher or lower than a specified number

* * *

[Example: Coin Toss](https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/Chapter9.pdf)

> Example 9.2 A coin is tossed 100 times. Estimate the probability that the number of heads lies between 40 and 60 (the word “between” in mathematics means inclusive of the endpoints)

the true mean for coin toss is 0.5

and check for binomail clt condition

100*0.5 >=5, so it holds

sd = sqrt(0.5*(1-0.5)/100) = 0.05

number of heads lies between 40 and 60

=normdist(0.6,0.5,0.05,true)-normdist(0.4,0.5,0.05,true)
= 95.4%


___

[Example: Freshmen admittance](https://www.dartmouth.edu/~chance/teaching_aids/books_articles/probability_book/Chapter9.pdf)

> Example 9.3 Dartmouth College would like to have 1050 freshmen. This college
cannot accommodate more than 1060. Assume that each applicant accepts with
probability .6 and that the acceptances can be modeled by Bernoulli trials. If the college accepts 1700, what is the probability that it will have too many acceptances?

Test: np & n(1-p) >= 5, binomial clt holds

mean = 1700*0.6 =
sd = sqrt(0.6(1-0.6)/1700)=0.01188

for admited application =1050, p = 1060/1700=0.6235


=1-normdist(0.6235,0.6,0.01188,true) = 2.39%




___

[Example: Sampling distribution of serum cholesterol][11]

According the National Center for Health Statistics, the distribution of serum cholesterol levels for 20- to 74-year-old males living in the United States has mean 211 mg/dl, and a standard deviation of 46 mg/dl We are planning to collect a sample of 25 individuals and measure their cholesterol levels What is the probability that our sample average will be above 230?


The group µ is 211mg/dl
The group σ is 46 mg/dl

So by CLT, if we run the 25 sample test many times, the sum of these samples will form a bell curve, with the following characteristic

group sum mean: = 25* 211 = 5275
group sum σ = 46 * 25^1/2 = 46*5 = 230
group average: = 211
group average S = 230/25 = 9.2
The group true mean is 211mg/dl The group SD is 46 mg/dl


![Sample Bell Curve][12]

by using Normdist function in google spreadsheet(=normdist(230,211,9.2,true)), we know the probability of group average below 230 is 0.98

Thus the probability of the sample average be above 230 is 1-0.98 = 2%

___

[Example: Slot Machine][13]

> Suppose that we play a slot machine such you can either double your bet or lose your bet. If there is a 45% chance of winning, what is the probability of the Gambler will not lose by playing 100 times ?

* The Group mean of expected payout:

= 45% * 1 + 55% * -1 =-0.1

* The Group standard deviation:

The Group Standard Deviation:

sqr(0.45*(1-(-1))^2+0.55*(-1-(-0.1))^2/100)

= 0.0995

not losing probability=1-normdist(0,-0.1,0.0995,true)= 1-0.84263= 15.7%

We can also use the CLT for binomial distribution:

![CLT of binomial distribution](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/l5xsvj_7.png)

The win rate p=0.45

p=µ=0.45

and the sample σ Standard Deviation: = sqr((1-0.45)*0.45/100) = 0.0497

n= 100

Now we have all the data we need:

sample mean = 0.45
σ(sample) = sqrt(0.45*(1-0.55)/100)= 0.0497
and the break even mark is 0.5

so the probablity of not losing = 1- normdist(0.5,0.45,0.0497,true) = 1-0.843 =15.7%

***

[Example: SUV Recall][13]

The new Endeavor SUV has been recalled because 5% of the cars experience brake failure. The Tahoe dealership has sold 200 of these cars. What is the probability that fewer than 4% of the cars from Tahoe experience brake failure?

You can think of the problem is a casino game too, break failure is a payout of -1, and withouth break failure is a payout of 1

and probability of break failure = 5%

so the mean is = 0.95*1 + 0.05*(-1)= 0.95-0.05= 0.9

and the standard deviation is:

(0.95*0\.01+0.05*3\.61)^(1/2)= 0.435

the 200 sample group mean = 0.9

and group mean standard deviation = (200)^(1/2)* 0.435/200 = 0.031

now we want to know what is the probability of has fewer than 4% of the break failure.

so the value of 4% breakfailure = 1*0\.96+(-1)*0\.04= 0.92

the value of fewer than 4% break failure =1-normdist(0.92,0.9,0.031,true) = 1-0.74 = 26%

if we use the CLT for binomial distrubtion

we can definte:

break failure = 1 no break failure = 0

chance of getting break faiulre (p) = 0.05

mean = 0.05
σ = ((1-0.05)0.05)^0.5=0.2179

and group σ of 200 samples = 0.2179/(200^0.5)= 0.01556

and getting 4% failure rate:

=normdist(0.04,0.05,0.01556,true)

= 0.2602, about 26%

___

[Example: Opinion Polls, explained from popularsocialscience.com ][16]

![house of the cards][17]

Let us say that we want to know whether Candidate Obama or Candidate Underwood will win the next presidential election.

Since there is only two possible outcomes, we could applying CLT for Binomial distriubtion.

Say we do the hard leg work , and conduct a survey of 1000 persons and ask if they prefer the candidate Obama or candidate Underwood . Then We find that in this poll, 54 percent of those we ask will vote for Obama.

Is that safe to use these 1000 voters to proxy what all US voter think?

lets assign value of voter vote for Obama = p;

by using CLT for binomail distribution,


we can know if we do this polling 1000 times, it will form a bell curve and with the following standard deviation

standard deviation = $$\sqrt{\frac{0.54*(1-0.54)}{1000}}$$ = 0.01576


p'+2sd = 0.54+2*0\.0157=0.5714 p'-2sd = 0.054-2*0\.0157 = 0.5086

![Polling Diagram][18]

All we care is: What is will the µ value greater than 0.5? ie. will more than 50% of voter will vote for Obama ?

By CLT, we know that when we do the 1000 people poll, the average of the poll results will form a bell curve around the µ p( The bell curve on the left of the diagram) , and with standard deviation of σ.

now we know the standardviation , which is only 1.576%, even if we miss by 2 standard deviation:

we have the µ = p'- σ = 0.054-2*0.0157 = 0.5086, which is still greater than 0.5
In the worse case scenario( within these 95% chance), the true mean is -2 SD' from the sample mean,

so we can say that the µ lies in region 1 ( The turf where Obama will win is 95% + 2.5% = 97.5%

Couple of things to use this with causion:

* There is a **non-zero** probability of the µ lies in region 2, ( where Obama will lose), and it is not so uncommon as the numbers suggest, because human is not really as independent thinker as one thinks.

___

[Example Salary Survey](https://historiesofcatastrophicdreaming.wordpress.com/quantitative-methods/third-and-final-exam-qm/the-central-limit-theorem/practical-applications-of-the-central-limit-theorem/)


>The mean salary of the 9,000 employees at Holley.com is µ = 26,000 with a standard deviation of σ = 2420. A pollster samples 400 randomly selected employees and finds that the mean salary of the sample is 26 650. Is it likely that the pollster would get these results by chance, or does the discrepancy suggest that the pollster’s results are suspect?

Step of Analysis:

* Gather following data by statistics,combination/permutations or approximations, or proability theory

Group true mean:
µ = 26000

Group standard deviation:
σ = 2420

Compute the sample group mean/sum mean and standard deviation from CLT

the sample group of 400 standard deviation:
σ' = 2420/20 = 121

so the mean salary of the sample is 5σ' away, which is raise a big question mark, so the pollster's result could by a suspect.


___

[Example Hypothesis Testing](http://people.math.gatech.edu/~ecroot/3215/central_limit_apps.pdf)

> Problem. You read in a newspaper that 20% of Georgians smoke, and you
decide to test this hypothesis by doing a poll on 1, 000 randomly selected
Georgians with replacement (if the population you are testing is very large,
then you would not need to test with replacement). Suppose that 205 of
the responses are “smoker”, while 795 are “non-smoker”. Is the claim “20%
of Georgians smoke” unreasonable? (Obviously not, but let’s see what the
math tells us...)

__Step of Analysis:__

* Gather following data by statistics,combination/permutations or approximations, or proability theory

- Group µ

By using binomal case of CLT, the p we want to test is:
p = 0.2 ( 20% of Georgians Smoke)
- Group standard deviation σ
σ = (0.2*0.8)^0.5
* Compute the sample group mean/sum mean and standard deviation from CLT

If the hypothesis is true:

The group mean = p =0.2
standard deviation σ'= σ/(1000)^0.5 = 0.0126



* Use Normdist function of google spreadsheet to find out the probability, if needed.

The polling result is 20.5%, which is wihin p+__σ', we would say it is quite probable.

___
[Example Testing a proportion](http://people.cas.uab.edu/~mpogwizd/ma180-fall-2014/HypothesisTesting.pdf)

> The XSORT method of gender selection is believed to increases the likelihood of birthing a girl.
14 couples used the XSORT method and resulted in the birth of 13 girls and 1 boy. Using a 0.05
significance level, test the claim that the XSORT method increases the birth rate of girls.

Step of analysis:

* Gather following data by statistics,combination/permutations or approximations, or proability theory

- population µ
* lets assume the probability of birthing a girl is 0.5
- population standard deviation σ

* by using binomial CLT, the
σ = 0.5
* Compute the sample group mean/sum mean and standard deviation from CLT

Sample group σ'= σ/14^0.5 =0.133689

and the sample result mean is 0.9286, which is more than 2σ' away from mean.

so the claim is accepted




* Use Normdist function of google spreadsheet to find out the probability, if needed.

___

[Example AP Scores](http://homepages.math.uic.edu/~bpower6/stat101/Sampling%20Distributions.pdf)

> A Teacher has a class of 68 students taking the AP Physics test. Assuming they are typical of the population, the result of whose scores are given, what is the probability the average score will be at least 3?

score | 1 | 2 | 3 | 4 |5
---|---|---|---|---
Probability|21.5%|18.8%|24.7%|21.7%|13.3%

The Base average value = 2.865
The Base group standard deviation = 1.337
So the Expected sample average standard deviation = 1.337 /(68)^0.5=0.1617

So the probability of the score higher than 3 is 20.2%
***

[Example: Is homefield advantage effect true in baseball ?](https://www.lakeheadu.ca/sites/default/files/uploads/77/docs/Anderson_Project.pdf)

>In the 2013 Major League Baseball season, there were 2431 games played, and of those games, 1308 of them were won at home. This indicates that approximately 53.81% of the games played were won at home.

If there is no homefield advantage, the probability of winning at home will be 50:50, 0.5

We can use the same binomial CLT technique we used in the polling sample

the σ=((1-0.5)(0.5))^0.5 = 0.5

and sample average standard deviation = 0.5/(2431)^0.5=0.5/49.3=0.010141

using 1-normdist(0.5381,0.5,0.01014198,true)= 1-0.9999139= 0.008%

so the probability of hypothesis of homefield advantage not exist is 0.008%

**Bonus: Confidence Interval & CLT:**

Confidence Interval is a range, usualy is Sample Mean +- 1.96 standard deviation (95% Interval)

***


[Example Advertisement Campaign](https://www.youtube.com/watch?v=QRwPMzAL0iA&list=PLAKBwakacHbRRw278HMXpCsOOIIcLYGX5&index=4)

If you run two campagin banners fro 1000 impression, and first banner has a 1% conversion rate, and second banner has a 3% conversion rate, whats the probability of second banner better than the first banner?

Recall, conversion is basically 1 or 0, and we can use CLT for binomial distribution to estimate the standard deviation of two banners.

first banner:

mean= 0.01
standard devivation = sqrt(0.01*0.99/1000)=0.00314

second banner:

mean=0.03
standard deviation = sqrt(0.03*0.97/1000)= 0.00539

use 99% confidence interval

first banner:

1% +- 2.58*0.314%= 0.19% ~ 1.81%

second banner:

3% +- 2.58*0.539% = 3% +- 1.39% = 1.61

so the second banner has a probablilty of over 90% better converting than banner 1

[Example A keyword search program ](http://www.utdallas.edu/~mbaron/3341/Practice6.pdf)

> A keyword search program lists the files that contain a given keyword. If it runs
through 200 files, and each file contains the keyword with probability 0.36, independently of
other files, compute the probability that
(a) more than 70 files
(b) less than 70 files
(c) exactly 70 files will be listed.

p=0.36
sd= sqtr(0.36*0.64/200)
= 0.0339

Normdist(0.35,0.36,0.0339,true)=0.384

(a) 1-0.384 = 61.6%

***

[Example Roulette](https://www2.stat.duke.edu/courses/Spring05/sta101.2/lectures/STA101lecture13.pdf)

> You are playing Red and Black in roulette. (A roulette wheel
has 38 pockets; 18 are red, 18 are black, and 2 are green—the house takes
all the money on green). You pick either red or black; if the ball lands in
the color you pick, you win a dollar. Otherwise you lose a dollar.
Suppose you make 100 plays. What is the chance that you lose $10 or
more?

The win rate p: 18/38 = 47.37%

from Binomial CLT, the true mean = p = 0.4737

the 100 sample sum true mean = 0.4737*100 = 47.37
the 100 sample sum standard deviation = sqrt((1-0.4737)*0.4737*100)=4.99

The triky part is to find the target win rate for betting $100 and lose $10 more:


the win rate p for betting $100 and lose $10 more is:

90/100*0.5=0.45

average:

betting 50
lost more than 45

so the final formular is:

normdist(45,47.37,4.99,true)= 31.74%

Using classic CLT to verify:

for betting $1

true mean = 2*0.4737 + (0)*(1-0.4737)=0.9474

true standard deviation = sqrt(0.4737*(2-(0.9474))^2+0.5263*(0-(0.9474))^2)=0.99861

for betting $1 100 times

the group mean = 0.9474* 100 = 94.74

the group standard deviation = sqrt(100)*0.99861 = 9.9861

for loss more than $10

=normdist(90,94.74,9.9861,true)=31.75%

___

[Example Quality Check](http://ocw.mit.edu/courses/sloan-school-of-management/15-063-communicating-with-data-summer-2003/lecture-notes/lecture10.pdf)

> Example: An electrical component is guaranteed by its
suppliers to have 2% defective components. To check a
shipment, you test a random sample of 500 components. If
the supplier’s claim is true, what is the probability of finding 15
or more defective components?

p = 0.02

sd = sqrt(0.02*0.98/500)= 0.006260990337

15 more defect component in 500 component is equal to a rate of 0.03

so the answer is

= 1 - normdist(0.03,0.02,0.00626099,false)

= 5.5%
***


___

[Example Restaurant Tips](http://homepages.math.uic.edu/~bpower6/stat101/Sampling%20Distributions.pdf)

> A waitress earns varying tips with a mean of $10.90 and sd of $5.60. Assume on the weekend she gets 60 tips.

What is the probability she earns $750 or more?

sample sd = 5.6/sqrt(60) = 0.72

required sample mean = 750/60 = 12.5

probability = 1- normdist(12.5,10.9,0.72,true) = 1.3%


___

[Example restaurant manager](http://faculty.lasierra.edu/~jvanderw/classes/m251a07/m251r3a07ans.pdf)

> The Roman Arches is an Italian restaurant. The manager wants to estimate the average amount a customer spends on lunch Monday through Friday. A random sample of 115 customers’ lunch tabs gave a mean of ¯x = $9.74 with a standard deviation s = $2.93.
>
> Find a 95% confidence interval for the average amount spent on lunch by all customers

population sd = 2.93 * sqrt(115)

range = 9.74 +- 1.96 * (31.42)


[Example real life bell shape curve](http://math.stackexchange.com/questions/38825/cool-examples-of-the-central-limit-theorem-in-action)

> by Matt E
Find an old stone step or lintel in front of a doorway (one that is old enough that it has been worn down by generations of people walking over it). If you look at how it is worn down, the wearing down won't be uniform over the surface of the step: rather, it will be in a bell-curve. (People tend to walk through the middle of the doorway.)

> If the door doesn't open all the way, the bell-curve won't be perfect; there will a bias towards the side away from the hinges.



**Bonus: How to Read the Normal Distribution Diagram**

I think I know Normal Distribution Digram, but until I use excel to plot one, I found out actually I don't really understand normal distribtuion digram ! So here is the findings of rediscovering normal distribution diagram.

![Normal Distribution Diagram][19]

what is the x-axis ?

the x-axis is the standard deviation from the mean, ( the 0 in the normal distribution digarm is equal to the mean of the histogram)

what is the y-axis ?

y-axis the the probability of getting this value, in real life terms, y-axis is the frequency in the histogram, noted the probability of getting mean value( the 0 point in x-axis is not 0.5! but about 0.4)

![Normal Distribution Diagram Explained][20]

* * *


***

Further study

[z-test,Z-test is any statistical test for which the distribution of the test statistic under the null hypothesis can be approximated by a normal distribution.](https://en.wikipedia.org/wiki/Z-test)

[Beta distrubtion](https://en.wikipedia.org/wiki/Beta_distribution)
[Poisson distribution](https://en.wikipedia.org/wiki/Poisson_distribution)



More resource:

[Central limit Theorem demostration][21]

[1]: http://www.rationalpov.com/wp-content/uploads/2016/03/E6A2D69A-C356-4900-AABE-46DFEDE096AD.gif
[2]: https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/519d73uu.png
[3]: https://docs.google.com/spreadsheets/d/10LqWsKJhCBxm_281Vt0d2yH8-WYg39OLwXkWY4eLTIg/edit#gid=0
[4]: http://www.rationalpov.com/wp-content/uploads/2016/03/image-1.png
[5]: https://docs.google.com/spreadsheets/d/10LqWsKJhCBxm_281Vt0d2yH8-WYg39OLwXkWY4eLTIg/edit#gid=626723546
[6]: http://www.rationalpov.com/wp-content/uploads/2016/03/image-2.png
[7]: http://www.rationalpov.com/wp-content/uploads/2016/03/Planche_de_Galton.jpg
[8]: http://blog.vctr.me/posts/central-limit-theorem.html
[9]: https://www.stat.auckland.ac.nz/~wild/ChanceEnc/Ch07.propCLT.pdf
[10]: http://www.rationalpov.com/wp-content/uploads/2016/04/gn6xmnvy.png
[11]: http://web.as.uky.edu/statistics/users/pbreheny/580-f10/notes/9.pdf
[12]: https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/bryi_5g3.png
[13]: https://www.ltcconline.net/greenl/courses/201/probdist/clt.htm
[14]: https://upload.wikimedia.org/math/3/1/8/31830fa1f2f922edf6079209a51f8967.png
[15]: http://www.rationalpov.com/wp-content/uploads/2016/03/render-2.png
[16]: http://www.popularsocialscience.com/2013/08/26/can-we-trust-opinion-polls-the-central-limit-theorem-binomial-proportion-confidence-intervals-and-likely-voters/
[17]: http://www.rationalpov.com/wp-content/uploads/2016/04/house-of-cards-season-4-key-art1.jpg
[18]: http://www.rationalpov.com/wp-content/uploads/2016/04/rpov-polling-1.png
[19]: http://www.rationalpov.com/wp-content/uploads/2016/04/Empirical_Rule.png
[20]: http://www.rationalpov.com/wp-content/uploads/2016/04/ji8_ij43.png
[21]: http://onlinestatbook.com/2/sampling_distributions/clt_demo.html
