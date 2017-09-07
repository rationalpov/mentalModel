# Discipline Mathematics, Basic Arithmetic

## Discipline:

Mathematics

### Up Stream Lattice

### Down Stream Lattice

Monte Carlo Method

feedback system

break points

backup system/redundancy

### Peer Lattice:

Invert

# Introduction

The first mental model is Simple Arithmetic, it ranked one of the most fundamental mental model according to Charlie Munger.

## How to use this mental Model:

Numbers doesn't make much sense alone, but it is much more useful to model reality and make a prediction out of it.

![math](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/4g2-vbhh.png)

## Simplification 

### Identify **critical path** and slim down the problem to its core.

Claude Shannon gave a [speech](http://www1.ece.neu.edu/~naderi/Claude%20Shannon.html)  about creative thinking( or how to solve a hard problem in general)  to a small group in Bell lab

> The first one that I might speak of is the idea of simplification. Suppose that you are given a problem to solve, I don’t care what kind of a problem - a machine to design, or a physical theory to develop, or a mathematical theorem to prove, or something of that kind - probably a very powerful approach to this is to attempt to eliminate everything from the problem except the essentials; that is, cut it down to size. Almost every problem that you come across is befuddled with all kinds of extraneous data of one sort or another; and if you can bring this problem down into the main issues, you can see more clearly what you’re trying to do and perhaps find a solution. Now, in so doing, you may have stripped away the problem that you’re after. You may have simplified it to a point that it doesn’t even resemble the problem that you started with; but very often if you can solve this simple problem, you can add refinements to the solution of this until you get back to the solution of the one you started with.



### Identify what kind of distribution it is, is it normal or powerlaw distributed ?

* What do you mean by distribution ?

Distribution is how the numbers scatter, it appears visually when make a histogram out the data

From Brian Christian and Tom Griffiths's [Algorithms to Live By: The Computer Science of Human Decisions](https://www.amazon.com/Algorithms-Live-Computer-Science-Decisions/dp/1627790365/ref=sr_1_sc_1?ie=UTF8&qid=1503015103&sr=8-1-spell&keywords=alogorimthm+to+live+by),


> In the broadest sense, there are two types of things in the world: things that tend toward (or cluster around) some kind of “natural” value, and things that don’t. 

> Human life spans are clearly in the former category. They roughly follow what’s termed a “normal” distribution— also known as the “Gaussian” distribution, after the German mathematician Carl Friedrich Gauss, and informally called the “bell curve” for its characteristic shape. This shape does a good job of characterizing human life spans; the average life span for men in the United States, for instance, is centered at about 76 years, and the probabilities fall off fairly sharply to either side. Normal distributions tend to have a single appropriate scale: a one-digit life span is considered tragic, a three-digit one extraordinary. Many other things in the natural world are normally distributed as well, from human height, weight, and blood pressure to the noontime temperature in a city and the diameter of fruits in an orchard.

Why is that ? it could because a normal distribution is a sign telling you the underlining system is an additive one, the system consist of many components and the result is the sum of the individual parts, so it is like taking a sum of the individual parts and central limit theory applies.

> There are a number of things in the world that don’t look normally distributed, however— not by a long shot. The average population of a town in the United States, for instance, is 8,226. But if you were to make a graph of the number of

> towns by population, you wouldn’t see anything remotely like a bell curve. There would be way more towns smaller than 8,226 than larger. At the same time, the larger ones would be way bigger than the average. This kind of pattern typifies what are called “power-law distributions.” These are also known as “scale-free distributions” because they characterize quantities that can plausibly range over many scales: a town can have tens, hundreds, thousands, tens of thousands, hundreds of thousands, or millions of residents, so we can’t pin down a single value for how big a “normal” town should be. The power-law distribution characterizes a host of phenomena in everyday life that have the same basic quality as town populations: most things below the mean, and a few enormous ones above it. Movie box-office grosses, which can range from four to ten figures, are another example. Most movies don’t make much money at all, but the occasional Titanic makes … well, titanic amounts. In fact, money in general is a domain full of power laws. Power-law distributions characterize both people’s wealth and people’s incomes. The mean income in America, for instance, is $ 55,688— but because income is roughly power-law distributed, we know, again, that many more people will be below this mean than above it, while those who are above might be practically off the charts. So it is: two-thirds of the US population make less than the mean income, but the top 1% make almost ten times the mean. And the top 1% of the 1% make ten times more than that.

powerlaw distribution is a sign of the underlying system is multiplicative one, and grows exponentially.


#### Prediction rules for normal distributed things.

if less than average, predict the average.

eg. if you meet a young man and need to predict how long he will live, give out the average life span of the city.

if more than average, average + some more 



#### Prediction rules for power law distributed things.

Multiple the quantity observed by some constant factor, if you don't know any thing about it, it happens to be 2, 


### Is it a **multiplicative** Or **Additive** System

The best explanation of multiplicative & additive system in [farnamstreetblog](https://www.farnamstreetblog.com/2016/08/mental-model-multiplicative-systems/)

The concept of multiplicative and additive is very powerful and govern many aspect of our lives:

Why market is so powerful and almost work like magic ?

Because it is a additive system, and offers matching between N number of buyer and M number of sellers. The combination between buyer and sellers exploded with number of buyer and seller increase.


Daron Acemoglu and James A. Robinson in their book Why Nations Fail examines the factors could be responsible for determinting countries success and failure,

they argues the factor such as geographic, climate, culture, religion, policitcal leader are either insufficient or defective in explaining it.

Acemoglu and Robinson's major argument is economic prosperity depends above all is whether the economic and political system is inclusive or extractive

inclusive system, is a additive one, and extractive system, is an multiplicative one.



### How will it scale to 100 or 1000 times ?

When things or system scales, it often change to a completely different thing.



### Conditions:

None


## Example

Why Giants were sitting down, and why large animal has a different shape than small one

From [power, sex, suicide, mitochondria and the meaning of life]

> Different organs and tissues respond differently to an increase in body size. A good example is bone. Like muscle, the strength of bone depends on the cross-sectional area, but unlike muscle the bone is metabolically almost inert. Both factors influence scaling. Imagine a 6o-foot giant— ten times taller, ten times wider, and ten times thicker than an ordinary man. This is an example from Haldane again, who cites the giants Pope and Pagan from The Pilgrim’s Progress— one of the few references that dates his essay, as I doubt that many science writers today would turn to Bunyan for an everyday analogy. Because bone strength depends on cross-sectional area, the giants’ bones are 100 times the strength of ours, but the weight they must bear is 1000 times greater. Each square inch of giant bone must withstand ten times the weight of our own. Because the human thigh bone breaks under about ten times the human weight, Pope and Pagan would break their thighs every time they took a step. Haldane supposes this is why they were sitting down in his illustration.

> The scaling of bone strength to weight explains why large, heavy animals need to be a different shape to smaller, lighter ones. Such a relationship was first described by Galileo in his Dialogues Concerning Two New Sciences, a delightful title that could hardly be matched these days. Galileo observed that the bones of larger animals grew more quickly in breadth than in length, compared with the slender bones of small animals. Sir Julian Huxley put Galileo’s ideas on a firm mathematical footing in the 1930s. For a bone to retain the same strength relative to weight, its cross-sectional area must change at the same rate as body weight. Let’s restrain ourselves to doubling the dimensions of our giant. His volume, and therefore weight, increases eightfold (23). To support this extra weight, his bones must grow eightfold in cross-sectional area. However, bones have length as well as cross-sectional area. If their cross-section is raised eightfold, and their length doubled, the skeleton is now sixteen (or 24) times heavier. In other words, the skeleton takes up a greater proportion of body mass. Theoretically, the scaling exponent is 4/ 3, or 1.33, although in reality it is less than this (about 1.08) because bone strength is not constant. Nonetheless, as Galileo realized in 1637, bone mass imposes an insurmountable limit on the size of any animal that must support its own weight— the point at which bone mass catches up with total mass. Whales can surpass the size limit of terrestrial animals because they are supported by the density of water.

