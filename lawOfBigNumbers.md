#
Mental Model: Law of big numbers (regression to the mean)

## Discipline: Mathematics

### Introductions

> In probability theory, the law of large numbers (LLN) is a theorem that describes the result of performing the same experiment a large number of times. According to the law, the average of the results obtained from a large number of trials should be close to the expected value, and will tend to become closer as more trials are performed.

> The LLN is important because it "guarantees" stable long-term results for the averages of some random events. For example, while a casino may lose money in a single spin of the roulette wheel, its earnings will tend towards a predictable percentage over a large number of spins.

This single model model supports a global Casino Industry with (160 Billion US Dollar annual revenue)[https://www.statista.com/topics/1053/casinos/)


![law of large numbers](https://upload.wikimedia.org/wikipedia/commons/0/02/Law_of_large_numbers_%28blow_up%29.gif)

#### How to use this mental Model:

Useful to Predict the mean for a large number of trials.

**Conditions:**

* The result must be come out of same thing/same process
* The number of trial should be large. How large a number we should call it large ? The magic number seems to be 30. Over 30 (times) is considered as large.
* The trial must be independent


**Predictions:**

* The average of the large number should close to the true mean of the group.

* The mean for white noise, is 0.

* Many noisy signal can be purified and amplified by summing up and get a average.

___

### Up Stream Lattice
None

### Down Stream Lattice

#### Wisdom of the Crowd

In his [book wisdom of the crowds](https://www.amazon.com/Wisdom-Crowds-James-Surowiecki/dp/0385721706), james highlighted four elements required to form a wise crowd:

Criteria | Description
---|---
Diversity of opinion | Each person should have private information even if it's just an eccentric interpretation of the known facts.
Independence | People's opinions aren't determined by the opinions of those around them.
Decentralization | People are able to specialize and draw on local knowledge.
Aggregation | Some mechanism exists for turning private judgments into a collective decision.


the four elements required to form a wise crowds is also the conditions for law of large numbers to work.

By using the following example we can better illustrates how widsom of the crowds is a special form of the law of large numbers.

___
[Example Noise Cancellation](http://people.math.gatech.edu/~ecroot/3215/central_limit_apps.pdf)

![noise cancellation](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Active_Noise_Reduction.svg/2000px-Active_Noise_Reduction.svg.png)

> Suppose that a man is driving through the desert, and runs out of gas. He
grabs his cellphone to make a call for help, dialing 911, but he is just at
the edge of the broadcast range for his cellphone, and so his call to the 911
dispatcher is somewhat noisy and garbled. Suppose that the 911 dispatcher
has the ability to use several cellphone towers to clean up the signal. Suppose
that there are about 100 towers near to the stranded driver, and suppose that
the signals they each receive at a particular instant in time is given by:

![example formular](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/f3cjc3ug.png)

S is the true signal and Yi is the noise.

From basic signal & information theory, we can assume the Yi noise is independaent and normally distributed, and has a mean 0 and standard deviation of σ.

![average](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/x51fqq9-.png)

At any rate, if we assume that the Yi are all independent normal random variables, then we don’t even need the central limit theorem, because in that case we have that X − S is exactly N(0, σ2/100).

By just summing the signal average from 100 towers, we can perform a noise cancellation and increate the Signal to noise ration by 100 fold !

So the 911 dispatcher can do the noise cancellation by computing the average.

___

lets look at the the first and third criteria for wise crowd to work:

> Each person should have private information even if it's just an eccentric interpretation of the known facts.

> Decentralization | People are able to specialize and draw on local knowledge.

We could think of each person as the cell towers in the example, and his/her opinion can be splitted into two parts:

*Sign* and *Noise*

In other words, for widsom of crowds to work, each person in the crowd must have some sort of signal in it, even though it will come with noise, which would be okay.

By the law of large numbers, the signal will add up and noise will cancel each other, thus the crowd opinion is actually the sum of the crowds intelligence.

The summing process amplifies the signal.

When the trial is no longer independent( ie the result of one trila affected the outcome of another trial), law of large number will fail, so as wisdom of crowds.

This illustrated why wisdom of crowds often faileds in stock market crash etc, because for extreme market movement the individual traders is no longer independent and influence greatly by the market outcome itself, thus break the condition for law of large number.

___

### how to build an effective team

Charles Duhigg mentions how effective team works in his excellent book [Smarter Faster Better: The Secrets of Being Productive in Life and Business](https://www.amazon.com/Smarter-Faster-Better-Productive-Business-ebook/dp/B00Z3FRYB0)

Three criteria:

* One should feel safe to speak up in the team

* team members needs to be have a high social sensitivity

* Every one should have an roughly equal voice

equal voice means equal in terms on the time they speak in a group
The three criteria also can attribute wisdom of the crowds principle, then attribute to law of large numbers. By creating an safe to speak environment, team members can contribute their best guess to problems and the average of them will cancel out the noise and distill the wisdom out.

To do that, the team chemistry should be 'right', means everyone should be honest but not too blunt to hurt others( make the environment not safe to speak)

The team leader is crucial in building an effective team, he/she needs to a facilitatory to control everyones voice and weep out the worse offenders



___

### Democracy

> If the people are not utterly degraded, although individually they may be worse judges than those who have special knowledge, as a body they are as good or better - Aristotel

the underlining principle for democracy also rely on law of large numbers ( known as wisdom of crowds)


___





#### Revert to the mean

___
Examples:

The whole term life insurance industry is based on law of large number, so the larger the subscriber to a policy, the mean life expectacy of the subscriber will be approaching to the group mean, and better the predictability.

Examples:

Warren Buffet talks about how he come up with the [single best measures to value the stock market][1] as a whole.

Single stock and short term market is not predictable, but by using law of large numbers, stock market trends can be predicted to some extend.

> On a macro basis, quantification doesn't have to be complicated at all. Below is a chart, starting almost 80 years ago and really quite fundamental in what it says. The chart shows the market value of all publicly traded securities as a percentage of the country's business--that is, as a percentage of GNP. The ratio has certain limitations in telling you what you need to know. Still, it is probably the best single measure of where valuations stand at any given moment. And as you can see, nearly two years ago the ratio rose to an unprecedented level. That should have been a very strong warning signal.
>
> For investors to gain wealth at a rate that exceeds the growth of U.S. business, the percentage relationship line on the chart must keep going up and up. If GNP is going to grow 5% a year and you want market values to go up 10%, then you need to have the line go straight off the top of the chart. That won't happen.

Later is becomes Buffett indicator:

![Buffet Indicator][2]

source and attribtion:http://www.businessinsider.com/buffett-indicator-better-but-not-great-2015-10




___



[1]: http://archive.fortune.com/magazines/fortune/fortune_archive/2001/12/10/314691/index.htm
[2]: http://static4.businessinsider.com/image/56336b28bd86ef18008c5f4f-907-659/screen%20shot%202015-10-30%20at%209.05.08%20am.png

