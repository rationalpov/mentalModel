# Mental Model: Elementary math of permutations and combinations

## Discipline:Mathematics

### Up Stream Lattice

Basic Arithmetic

### Down Stream Lattice

* premature Optimization


### Peer Lattice:

* Occam's razor
* Analysis from first principle


# Introduction


> Elementary math of permutations and combinations, It's very simple algebra. It was all worked out in the course of about one year between Pascal and Fermat. They worked it out casually in a series of letters.
>
> It's not that hard to learn. What is hard is to get so you use it routinely almost everyday of your life. The Fermat/Pascal system is dramatically consonant with the way that the world works. And it's fundamental truth. So you simply have to have the technique. --Charlie Munger


## How to use this mental Model:

### Combinatorial explosion
Combination and permutations has a feature or a curse, depends on how your look at it.
__Combinatorial explosion__
You have 3 hats, 4 shirts, 5 pants, 4 pair of socks, 2 pair of shoes. How many possible way you could dress up with these ?
Thats 3 * 4 * 5 * 4 * 2 = 480 ways of dressing.
Thats the world we are living in, it is filled with combinatorial explosion. There are only 102 Chemical Elements. But the combination and permutation of these 102 Elements creates every thing of our world.
Combinatorial explosion can be used in two ways.


One way is forward, you use Combinatorial explosion to create many many alternative path.

by doing this way, you can:

* Make your particular combination **unique**
* Make a one way mirror, ie. **encryption**, make it very difficult to reverse engineer and know your original combinational set.


### The other way is invert, try to break down a complex sysstem into its components.

#### Occam's razor 
Understand the Combinatorial explosion by trying to analyses and isolate things back to its elements. It is very difficult to analyse 480 ways of dressing, but
trace it down to 3 hats, 4 shirts, 5 pants, 4 pair of socks, 2 pair of shoes will be much easier.

Thats the attribution of Occam's razor, Among competing hypotheses, the one with the fewest assumptions should be selected, because the one with the fewest assumptions, it is closer to the seed element of combinations.

#### Analysis from First Principles, how Richard Feynman and Elon Musk do analysis

Elon Musk Explained how to think in first principle in this short video

![[youtube link]((https://www.youtube.com/watch?v=NV3sBlRgzTI)](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/eekhqava.png)

> "I think it's also important to reason from first principles rather than by analogy so the normal way that we conduct our lives is we we we reason by analogy it's we're doing this because it's like something else that was done"

> "(first principle) is kind of a physics way of looking at the world and what that really means is you kind of boil things down to the most fundamental truths and and say okay what do we sure is true or sure as possible is true and then reason up from there that takes a lot more mental energy"

In fact, Richard feynman thought the most valuable piece of 20th century physic, is this one piece of information, the root element.

> If, in some cataclysm, all of scientific knowledge were to be destroyed, and only one sentence passed on to the next generations of creatures, what statement would contain the most information in the fewest words? I believe it is the atomic hypothesis (or the atomic fact, or whatever you wish to call it) that all things are made of atoms—little particles that move around in perpetual motion, attracting each other when they are a little distance apart, but repelling upon being squeezed into one another. - Richard Feynman



___

Example: [Premature optimization](https://www.edge.org/response-detail/27063)

business  is facing  Nth degree of combination or even permuations, if he or she pick the right combination, and optimize accordingly , it will reach a state of optimal profits, or optimal fitness, or in another term, sucess.

But success is also come with a curse, by optimizing towards success, you cut off all other combinations and thus risk of ommiting a much bigger success.

In computer science, its termed the hill climbing problem


![hill climbing](https://upload.wikimedia.org/wikipedia/commons/d/d5/Hill_Climbing_with_Simulated_Annealing.gif)


___

Example [Amazon Tax and AWS](https://stratechery.com/2016/the-amazon-tax/)

In his excellement book The everything store, Brad Stone mentioned how Amazon CEO, Jeff Bezos solve this one critical problem :

> various teams in the company were all served by one monolithic technical team that had to authorize and spin up resources for every project. 

> At the same time, Bezos became enamored with a book called Creation, by Steve Grand, the developer of a 1990s video game called Creatures that allowed players to guide and nurture a seemingly intelligent organism on their computer screens. Grand wrote that his approach to creating intelligent life was to focus on designing simple computational building blocks, called primitives, and then sit back and watch surprising behaviors emerge.

> The book…helped to crystallize the debate over the problems with the company’s own infrastructure. If Amazon wanted to stimulate creativity among its developers, it shouldn’t try to guess what kind of services they might want; such guesses would be based on patterns of the past. Instead, it should be creating primitives — the building blocks of computing — and then getting out of the way. In other words, it needed to break its infrastructure down into the smallest, simplest atomic components and allow developers to freely access them with as much flexibility as possible.

Bezos use the idea of basic combination to resolve this problem. Amazon should not try to build a super efficient monolithic techinical team, but instead build multiple primitives services, which is an atomic building block and can be used by all members of the company, and even outsiders, as a service.

by offering as a service to the public, it lollapaloozaed another mental model, benefit of scales from Economics. 







### Combination, Permutations and Cartesian Products:

#### One group case

When the order doesn't matter, it is combinations;

When the order does matter, it is permutations

**Permutatation is the easier one to Explain:**

**The Basic methodology to calculate Permutation is you just mutiple the avaliable choice together**.

If each time you choose from different groups, thats the easiest, you just multple the avalible choices together

for scenario of Permutations choose from same group of choices:

There are two types of Permutations;

* One Allows Repetition, (Like the Combination Lock on your suitcase)

![Combination Lock](https://c2.staticflickr.com/4/3800/12351110484_1718e441ac_b.jpg)

you got to pick 3 numbers from 0 - 9, and you can pick the same number.

When allows repetitions, we dont take aways the choices, so we just multiply the number of choice all toghether

<img src="http://www.sciweavers.org/tex2img.php?eq=%20N%5E%7Br%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt=" N^{r} " width="22" height="17" />

* One Doesn't Allow Repetitions.

When doesn't allows repetitions, after we choose one , next time there will be one less to choose from:

So First time you will got 0-9 to choose from, after choosen said number 9, next time you can only choose 0-8.

then the computations will be (N)(N-1)(N-2)...

So the Formular for Combinations without Repetions is:

**N!**

**Combinations**

**The Basic methodology to calculate Permutation first, then calculate how many ways it can arrange the order, then reduce it to combination**

There are also two types of Combinations:

* One Doesn't Allows Repetition

Example: Lottery, you pick 7 numbers, the order of this 7 numbers doesn't matter, but you can't pick the same number twice.

we can simplify it as Permutations, then reduce it to combinations

say we want to know the possibilities of picking R balls out of a Pool of N, then

The Permutations = N!/(N-R)!, and remember, how many permutations does R balls has ? R!

the R balls could have a permutations of R! iteself, which we dont quite care and all the same to us now, so reduced the choice by R! number of times,

so Combinations without repetion = Permutations without repetitions / R!

* One Allows repetition

Combinations allows repetition, actually it is the hardest to explain but we can flatten the problem and change it to linear

Say we can pick 2 scoops out of a 4 ice cream favors,

GreenTea, Charcolate, Vanilla, Mango

Question, why the answer is not 4*4 = 16 ? because order doesn't matter, if order does matter, you are right but [Green Tea, Charcolate] and [Charcolate green tea] is exact the same when we dont consider order

we can transform the question and think how to program a robot to do it

1 means pass 0 get the soop

Green Tea, Vanilar, chocolate, Coffee

and the robot arm is poniting at the green tea now, you need to programm it to walk to the coffee.

so there will be always 3 pass moves, and 2 get the scoop moves

so it looks like this

00111 10101 01101 * * * lets do another transformation, label each position from 1 to 5, imaging it is 5 balls

12345 and 0 means take 1 ball out of this 5 balls, how many permutations can i have ? take 2 balls out of these 5 balls, no repetition allowed, and orders doesn't matter.

so it will be (5)!/(5-2)!/2!

we have a formula for that

5!/3!*2! = 10 Combinations.


#### Mutiple Groups

In real life, you often need to calculate how many combination/permuations for mutiple groups of choice, thats called **Cartesian Products**:

Eg.

Say you need to create a password consist only two digits.

Say first digit you need to pick one number from group 0-9

Second digit pick one Alphabet from A-Z

How many Combination will you have ?

The Solution, split this into two steps

* Calculate the avaliable combination choice from each group
* In this exmample, first group you got 10 choice( Using the Combination allows repetition formular, 10!/(10-1)!/1! = 10, second you got 26 choice (26!/(26-1)!/1!)
* Second step, you need to calculate how many **permutations** when combining these two groups.
Why **Permutations** ? because these two group is different, so order do matter in step 2, so by using Permuation formular, you got 10*26= 260

**How to use this mental Model**:




### Conditions:

input must be discrete number


### Predictions and:
tocalculate number choices from combination/permutations of factors


### Procedures to use this mental model:

* Always calculate Permutations First

* Identify if repetition allowed

* If repetition allowed, use N^r to calculate base permutation
* If repetition is not allowed, used N! to calculate base permutation

* If need combiniation results, revise the number up or down, if needed.

couple scenarios:

* If results is combination, scale the number down by divide the base permutation by r!

* If there is multiple group combination, multiple the base permuations.


### Examples:



You forgot about passcode on your 3 digit combination lock of your suitcase, you think probably you can try one code for 5 sec, then how many times does it take to unlock your suitecase ?

First of all, you will notice the Name of **combination** lock is wrong, it should be **permutation** lock actually. Because the Passcode order sequence does matter:

and the code allows repetition, so the use the formular N^r

and N = 10, r = 3

so you got 1000 permuation of code to try, and each try takes 5 secs, so approximately it will take 5000 secs, and thats about One and Half Hours, so actually it is not that bad.

**Examples:**

A New Pizza Shop can allow you to create pizzas of your own choice by choosing Crust, Topping and Cheese, How Many Difference type Pizza can you make ?

4 types of toppings - pepperoni, sausage, ham, bacon

3 types of crust -thin, regular, thick

5 types of cheese - American, cheddar, Swiss, blue cheeze, Home Made.

Answer:

This is combination with group scenario:

So first we calculate the number of avaliable choice for each group:

Topping: 4C1 = 4 Crust: 3C1=3 Cheese:5C1=5

And calculate the permulation of 3 groups, thats 4x3x5= 60 different combinations

**Example:**

A 4 person task force is to be formed from 4 men and 3 women who work in Company G's HR dept. If there are to be 2 men and 2 women, how many different task forcers can be formed? A)14 B)18 C)35 D)56 E)144

Answer:

This is combination with group scenario:

So first we calculate the number of avaliable choice for each group, as the order of the candidate within the group doesn't matter, we use combination without repetition.

Men: 4C2=6 Women: 3C2= 3

mutiple two number of choice together, you got 18, so you should chooice B

Another excellent choice for this is [Quora][1]]

**Example:**

Case 1 : You have a date with your girlfriend. And, you want a perfect combination of shirt and pant. Suppose, you have 2 shirts (White and Blue) and 2 pants (Black and Brown). So, how many combinations do you have?

This is a Grouped Combinations and you calculate how many possible combinations from each groups

shirts = 2C1 = 2!/1!= 2 pants = 2C1 = 2

so the possible combinations = 2 x 2 = 4

**Example:**

![How many ways you can personalize wendy's hamburger][2]

[Walkinginmathland][3] give an interesting application for combinations and how Wendy's marketing department got it wrong.:

> The bag my food was in (picture above) had the following phrase: "We figured out that there are 256 ways to personalize a Wendy's hamburger. Luckily someone was paying attention in math class."

is that correct ? Hint: Wendys hamburger has 9 different topping to choose from at the time.

so it is a combinations doesn't allow repetion problem. The trick is, you can pick 0-9 topping from all the avaliable toppings.

9C0 = 1 9C1 = 9 9C2 = 36 9C3 = 84 9C4 = 126 9C5 = 126 9C6 = 84 9C7 = 36 9C8 = 9 9C9 = 1

Total: 512 ways to personalize a Wendy's hamburger

**Example**

[StackOverflow][4] has a permutation & combinations interview problem:

> Imagine an urn filled with balls, two-thirds of which are of one color and one-third of which are of another. One individual has drawn 5 balls from the urn and found that 4 are red and 1 is white. Another individual has drawn 20 balls and found that 12 are red and 8 are white. Which of the two individuals should feel more confident that the urn contains two-thirds red balls and one-third white balls, rather than vice-versa? What odds should each individual give?
>

**[Example](http://www.mathwarehouse.com/probability/combination.php)**

> Over the weekend, your family is going on vacation, and your mom is letting you bring your favorite video game console as well as five of your games. How many ways can you choose the five games if you have 12 games in all?


>12C5 = (12)!/(5!×(12-5)!)=(12)!/(5!×(7)!)
(12×11×10×9×8×7!) /(5!×7!) = 792

**[Example](https://www.cs.sfu.ca/~ggbaker/zju/math/perm-comb-more.html)**

> Example: How many ways are there to permute the letters of the word HAPPY?

* Note there are two Ps, so it is sort of permutation/combination hybrid

let follow the steps:

1. Is repetition allowed ?

No, so use N! formula, 5!=120

2. reduce to combination.
Since PP and PP is the same thing, so reduce to

120/2! = 60

**[Example single deck or double deck](https://www.cs.sfu.ca/~ggbaker/zju/math/perm-comb-more.html)**

> in a card game with a single deck (no jokers), how many way to order the deck ? and how many for two decks shuffled together ?

single deck

> 1. Is repetition allowed ?

No, so use N! formula, 52!=8.06582E+67

2. combination? no. so 8.06582E+67 is the final anwser

double deck

1. is repetion allowed ?

No. so use N1 formular, 104! =1.0299E+166

2. Combination, reduce to combination

there are two decks and there are 52 pair cards is identical.

so questions is, how many permutations can 52 different pairs of card have ?

permutation of a pairs of card:

=2! = 2

52 independent groups of cards permutation, it is a daisy chain, need to multiple the possible permutations together;

= 2^52

so total = 2.28684E+150

___

**[Example](https://www.cs.sfu.ca/~ggbaker/zju/math/perm-comb-more.html)**

> How many ways to order the letters of MISSISSIPPI?
>

1. is repetition allowed ? No

11! = 39916800

2. reduce to combination

there are 4S, 2P and 4 I

the permutation of each will be 4!, 2!, 4!

= 11!/(4!*2!*4!)

**[Example. Too many gifts](https://www.cs.sfu.ca/~ggbaker/zju/math/perm-comb-more.html)

>Your mother-in-law buys 1000 small gifts to give to relatives for Christmas, for reasons you don't understand. Each of the 1000 things is different, because she spends too much time shopping. There are 25 relatives to give gifts to. How many ways are there to distribute the gifts?
Note: the question allows the possibility of one person getting 1000 things, and everyone else getting nothing. There's no fairness in this family

for 1 gift:

you can give the gift to any of the 25 relatives, so choices:

= 25

for 2 gift:

you can give the gift to any of the 25 relatives, so choices:

= 25

so you can transform the question into this form:

you got to pick 25 relative to give gift too, and pick 1000 times. repetition allowed( since there is no fairness in the family)

25^1000 = 8.7×101397

> In the above scenario, how many ways can the gifts be distributed so each person gets 40 items?


[1]: https://www.quora.com/What-is-the-practical-real-life-use-of-permutation-and-combination
[2]: https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/jf-2if5l.png
[3]: http://walkinginmathland.weebly.com/teaching-math-blog/wendy
[4]: http://stackoverflow.com/questions/447384/permutation-combinations-interview
___
#
Example How to transit from book store to a technology company
Brad Stone in his excellnent book [The everything Store: Jeff Bezos and the age of Amazon](https://www.amazon.com/Everything-Store-Jeff-Bezos-Amazon-ebook/dp/B00BWQW73E) mentions Jeff Bezo was struggling to fullfill his vision of turning amazon to a technology company rather than retailer.
He tried many things and argurblly failed. A9 Search, Street view ( of amazon version ). but one vision he had was to break computer infrastrutre into what he called primitives( computing, communication, payment, storagage ), and he believed amazon just need to implement these primitives and make it avaliable, cheap, then it will exploded into amazing things.

Thus the invention of Amazon Elastic Cloud and Simple Storage ( S3 )


___

**[Example binomial distrion](https://www3.nd.edu/~rwilliam/stats1/x13.pdf)**

> For example, many experiments share the common element that their outcomes can be classified
into one of two events, e.g. a coin can come up heads or tails; a child can be male or female; a
person can die or not die; a person can be employed or unemployed. These outcomes are often
labeled as “success” or “failure.” Note that there is no connotation of “goodness” here - for
example, when looking at births, the statistician might label the birth of a boy as a “success” and
the birth of a girl as a “failure,” but the parents wouldn’t necessarily see things that way. The
usual notation is
p = probability of success,
q = probability of failure = 1 - p.
Note that p + q = 1. In statistical terms, A Bernoulli trial is each repetition of an experiment
involving only 2 outcomes.
We are often interested in the result of independent, repeated bernoulli trials, i.e. the number of
successes in repeated trials.
1. independent - the result of one trial does not affect the result of another trial.
2. repeated - conditions are the same for each trial, i.e. p and q remain constant
across trials. Hayes refers to this as a stationary process. If p and q can change
from trial to trial,the process is nonstationary. The term identically distributed is also often used.

> A binomial distribution gives us the probabilities associated with independent, repeated
Bernoulli trials. In a binomial distribution the probabilities of interest are those of receiving
a certain number of successes, r, in n independent trials each having only two possible
outcomes and the same probability, p, of success. So, for example, using a binomial
distribution, we can determine the probability of getting 4 heads in 10 coin tosses.

How can you calculate that ? by using permutations and combinations

Supposedly we want to find out the probability of getting 4 heads out of 10 coin tosses


one way of 4 head and 6 tail is like this( order matters)

HHHHTTTTTT

to get this result, the probability is:

P(H)*P(H)*P(H)*P(H)*P(T)*P(T)*P(T)*P(T)*P(T)*P(T)

but other than HHHHTTTTTT, there are many other permutations

HTHHHTTTTT will work, so as HHTHHTTTTT

but when you look closer since there is only two possible outcomes, we can generalise the problem a bit.

let p = probability of getting Heads, and q = probability of getting tails

q = 1-p

all the sequence with 4H and 6 tails will be like:

p^4q^6

when we have a fair coin(p = 0.5), the probability of getting one sequence of 4 Heads and 6 tails is:

1/0.5^4*(1-0.5)^6 =

































**[Example Elections](https://www3.nd.edu/~rwilliam/stats1/x13.pdf)**

> EXAMPLE. In each of 4 races, the Democrats have a 60% chance of winning. Assuming that
the races are independent of each other, what is the probability that:
a. The Democrats will win 0 races, 1 race, 2 races, 3 races, or all 4 races?
b. The Democrats will win at least 1 race
c. The Democrats will win a majority of the races


