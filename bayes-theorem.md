#
Mental Model: Bayes Theorem

## Discipline: Mathematics

### Up Stream Lattice


[Invert](./discipline_mathematics,invert.md)


### Down Stream Lattice

### Peer Lattice:

[Basic Probability, central limit theorem](discipline_mathematics,basic_probability,_central_.md)

Introductions

> "When my information changes, I alter my conclusions. What do you do, sir?" - John Maynard Keynes

The essence of Bayes's Theorem is, the evidence could have many alternative explanations, and your plausible belief is just one of them.

When you think about it, it means all your belief can be never 100% confirmed, it is merely a plausibility, and this plausibility( probability to be true ) is depends on the evidence.

Through the lens of Baye's themrom, the world is an ever shifting array of probabilities;

[<img src="https://farm6.staticflickr.com/5532/11937781733_bd60ac6a3a_b.jpg" width="1024" height="640" alt="parallel-universe-visiongf-hd-wallpaper-84742" />][1]

Photo by: [Lee Davy][2]

One vivid example can be found in the [Black Swan][3]by Nassim Taleb


> Consider a turkey that is fed everyday. Every single feeding will firm up the bird’s belief that it is the general rule of life to be fed everyday by friendly members of the human race “looking out for its best interests,” as a politician would say. On the afternoon of the Wednesday before Thanksgiving, something unexpected will happen to the turkey. It will incur a revision of belief.

![turkeys](https://upload.wikimedia.org/wikipedia/commons/6/66/Turkeys.jpg)


**Why is this important ?**

Even the best of us is subject to the hardwiring of our lizard brain's [Confirmation bias][4],[Avalilability bias][5] and Base Rate Ignore Bias, and Baye's theorem is a weapon we can use to fight our lizard brain.

Bayes' theorem gives the relationship between the probabilities of A and B, P(A) and P(B), and the conditional probabilities of A given B and B given A, P(A|B) and P(B|A). In its most common form, it is:

![Bayes Theorem][6]

p (A|B) read: probability of A happens given B is true note, P(B) is the overall probability of event B happens

or in another form:

P(A|B) = AND(P(A), P(B)) / P(B)


Whats the relationship of A to B ?

A is the your hypothesis/believes to be tested for now;

B is an evidence approving or disapproving the fact,which you have a math model of A and B.

What do you mean by math model ?

Basically when applying Bayes Theorem, you need to know how many plausible cause can lead to B happening, and its percentage of A accordingly( Invert):

We used the invert technique from up stream lattice, and inver the view from B's angle( What could lead to B happening) .

__False Negative(Sensitive) : When B is not true, what is the chance of A is true.__

__False Positive(Specific): When B is true, what is chance A is not true:__

a good test should be both **sensitive** and **specific**:

If you want to access the strengh of the Belief/hypothesis (A), then you need to also access the strengh of the evidence(B) supporting your hypothese.

**The strengh of the evidence is depends on how many alternate explaination of evidence (B) could have. the fewer the alternate explaintion of evidence, the stronger the evidence.**


![Drug sniffing Dog](https://upload.wikimedia.org/wikipedia/commons/d/d1/Dre_entorpec.jpg)

> The Wikipedia entry on Sensitivity and Specificity [Wik] uses a nice example to illustrate the difference: think of a drug-sniffing dog as a screening test for illicit drugs. If the dog’s nose is highly sensitive to the smell of drugs, then it will detect all the hidden packets of drugs; if it is less sensitive, then it will fail to detect some of the packets. At the same time, the dog should react specifically to drugs, and not, say, jambalaya or doggie biscuits. If the dog is highly specific in its reactions, it will only react to drugs; if it is less specific, then it will react to the occasional care package of yummy home cooking from Mom.


**The lower the base rate of P(A) is happening, you need a very strong P(B) to confirm or disconfirm P(A)**

Strong means both **specific** and **sensitive**;

[Will Kurt](www.countbayesie.com) give an excellent [illustration](https://www.countbayesie.com/blog/2016/3/16/bayesian-reasoning-in-the-twilight-zone) of this:

> One of my absolute favorite episodes of the classic TV show The Twilight Zone is "The Nick of Time". In this episode, a young, newly married couple, Don (played by none other than William Shatner) and Pat are forced to spend time in a small town diner while they wait for car repairs. In the diner they come across a fortune telling machine, the "Mystic Seer," which accepts yes/no question and (for a penny) spits out a card with an answer. The episode quickly establishes that Don is very superstitious. He eagerly asks the Mystic Seer a series of question and soon begins to believe in the supernatural powers of this particular device. Pat remains continuously skeptical even as each assertions of the Seer comes true. Eventually, Pat comes around to believe in the powers of the seer, but unlike her husband finds the possibility that the seer is prophetic terrifying.

![Mystic Seer](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/3jaqrhqq.png)

Why is the difference ?

It is because Pat and Don hold different believes of P(A)

Pat holds a relative high starting P(A) and thus only need a relative weak P(B) to convince him.

Don holds a relative very low starting P(A) and need a very strong P(B) to convince her.

Will Kurt even calculate the the P(A) of Don and Pat by using how many data it takes to convience them,

for Pat, the inital believe is the seer has 1 in 3000 chance of supernatural power.






One more example about strong and specific evidence. lets use the turkey example again:

Turkey's Believe/Hypothesis (A):

> the human race is our friend and will look after our best interest.

Evidence (B)

> Human has fed us every day for 364 days !

From a Turkey prospertive:

From Turkey's propective, The Evidence is "humans feed us everyday".

But the evidence "humans feed us everyday" could have many alternative explanations, thus a weak evidence.

when we examine the Evidence (B)( "Human fed us every day" ), it could have the following alterative explaination

* Alternate explaination A: Human feed us unconditionally because they are our friends, and do so selflessly.

* Alternate explaination B: Human being is feeding us because they want turkey's meat;

The Evidence "Human fed us every day" can't distinguish between two Alternate Explaination.


**How to use this mental Model**:

* Write down your current believe/Hypothesis A

* Write down your evidence B.

* Research/Find Out the Math Model between A and B:

* Find out the base rate of A
* as the lower the base rate of A, you need a stronger B

* Find out the overall possiblity of B is true
* Brain Storm/List out any reasons you can think of to cause event B to happen, and the probability associate with it.
* This usually it is the hardest part and you can also try using combination to list out the possible scenarios.




**Predictions:**

Give the probability of A when B is true;

___

**Example**

In an excellent [real life example by Allen Downey][7]

![House fire?](https://upload.wikimedia.org/wikipedia/commons/9/96/ShadowRidgeRoadFire.JPG)
> I had a chance to practice Bayesian inference in real life today: at 1pm my wife called to tell me that the carbon monoxide (CO) alarm at the house was going off. Immediately two hypotheses came to mind: (1) there is a dangerous amount of CO in my house, (2) it's a false alarm.
>
> It's summer and all the windows are open in the house. The furnace is not running and we don't have a gas stove. And the detector is about 10 years old. This background information makes a false alarm more plausible, so I started with a low prior for (1). Since my wife was on her way out anyway, I suggested she disconnect the detector, turn on a fan, and leave.
>
> After we hung up, I searched for information on CO detectors and false alarms. Apparently, the rate of false alarms is low, at least in once sense: CO detectors are very specific, that is, unlikely to go off because of anything other than CO. Of course the other possibility is that the detector is broken. On balance, this information made me less confident of a false alarm.

So write down your current believe/hypothesis you want to confirm/disconfirm:

> your house is on fire

The we estimate the chance of house on fire

> The FEMA U.S. Fire Administration keeps stats on fires
>
> In 2010 there were 362,100 residential fires in the USA. In total the fires caused $6.65 billion in damages.
>
> According to the Census there are 131 million housing units in the US and 114 million households.
>
> As far as frequency you could figure that 0.317% of households experienced a fire in 2010. Or we could say that 0.276% of housing units had a fire in the year.

Lets be safe and just put the base rate of house catching fire on 2.7%, which is 10 times higher than national average.

We have our Evidence too, the C/O detctor goes off.

Then we Brain Storm/List out any reasons you can think of to cause the C/O detector to goes off

> * A fire broken off
> * The dectector malfunctioned and give false alarm
> * A major street nearby is being paved. Does fresh pavement off-gas anything that would set off a CO detector? At a construction site down the street, they just poured a concrete foundation, and my neighbor is having some masonry done. Does fresh concrete off-gas CO? I vaguely remember that it sequesters oxygen, which turned out to be a problem for one of the Biosphere projects.
> * What about a smoldering fire inside a wall? Could it produce enough CO to set off the detector, but not enough smoke to set off the smoke alarms?

A rough estimatation of fire alarm reliability is the following, by doing some google search:

[Reliability:][8]75% [False Positive Rate:][9] 15%

By a quick look at the possible causes:

The alarm trigged by street paving is quite unlikely, as it should trigger other house's fire alarm too( which is not happening). so just put a guesstimate probability of 0.5%.

And the fire alarm false positive and reliability rate for smoldering fire is similar to flaming fire, so probably we can combine these two plausible causes.

Then use Use Bayes Theorem to plugin in the equation and find out how possible it it.

P(fire|alarm) = P(alarm|fire) *P(fire)/P(alarm) = 0.75*0\.03/(0.75*0\.03 + 0.97*0\.15 + 0.005)

= 0.0225/(0.0225+0.1455+0.005)= 13 %

so the it doesn't seem so bad after all.

Given that said, this just an example for baysian analysis, if the fire alarm goes off, please follow the protocol and do what every baysian should do, leave the house and call the fire department !

___

**Examples**

Concrete example from [5 August 2011 New York Times article by John Allen Paulos][10]:

![3 gold coin](https://upload.wikimedia.org/wikipedia/commons/5/5a/NNC-US-1907-G$20-Saint_Gaudens_(Roman,_high_relief)_%E2%80%93_edge_detail.jpg)

Assume that you’re presented with three coins, two of them fair and the other a counterfeit that always lands heads. If you randomly pick one of the three coins, and flip it 3 times, you observed the chosen coin has landed head 3 times in a row.

Question: what is the probablity of you picked a counterfeit coin ?


What is your A ( Hypothesis )?

A: The coin is counterfeit:

The evidence B is flipping the coin 3 time and it come out as all heads;

We want to know the probabilty of the coint is counterfei, P(C) (P(counterfeit)):

The base rate of probability of the coin is counterfeit is 1 in 3

P(counterfeit) = 0.33

P(C|3H) = P(3H|C) * P(P) / P(3H)

P(3H|C) = 1 P(P) = 0.33 P(3H)= P(3H|NC) + P(3H|NC) + P(3H|C) = 0.5\*0\.5\*0\.5\*0\.33 + 0.5\*0\.5\*0\.5\*0\.33 + 1\*0.33 = 0.4125

P(C| 3H )= 1* 0.33/0.4125 = 0.33/0.4125 = 80%

So after the test, we are 80% confident that the coin is a counter feit.

**Examples**

The chance that a woman will develop breast cancer in her forties is fortunately quite low — about 1.4 percent. But what is the probability if she has a positive mammogram?

Studies show that if a woman does not have cancer, a mammogram will incorrectly claim that she does only about 10 percent of the time. If she does have cancer, on the other hand, they will detect it about 75 percent of the time.

what is the probability of the woman has breast cancer giving positive manmogram ?

We want to know P(BC|MT)

P(MT)= mammogram is true; P(BC) = Breast Cancel is true;

P(BC|MT)= P(MT|BC)*P(BC)/P(MT)

= 0.75 * 0.014/(0.014 * 0\.75+ (1-0.014)*0\.1) = 0.0105 /( 0.0105+0.0986) = 9.6%

So even the memogram is true, the probability of the women got breast cancer is only 9.6 %

Why is that ? it is because the base rate of cancer happening is very low 1.4% , and for P(MT) it could either because of a positive result of a breast cancel or a false positive of a non breast cancer.

[According to this study][11]screening with mammography uss X-ray is not worth the cost;


**Example**

In the Nate Silver's Books [The Signal and the Noice][12]

![911 attack](https://upload.wikimedia.org/wikipedia/commons/a/a0/World_Trade_Center_9-11_Attacks_Illustration_with_Vertical_Impact_Locations.svg)

There is a vivid example of applying Bayes Theorem

> Consider a somber example: the September 11 attacks. Most of us would have assigned almost no probability to terrorists crashing planes into buildings in Manhattan when we woke up that morning. But we recognized that a terror attack was an obvious possibility once the first plane hit the World Trade Center. And we had no doubt we were being attacked once the second tower was hit. Bayes's theorem can replicate this result.

How do we simulated the induction process using Bayes Theorem ?


P(T)= P(Terrorist Attack)

P(P)= P(Planes crashing into Manhattan Building)

and We want to know:

P(T|P)

P(T|P) = P(C|T)* P(T)/P(P)


Lets gathering base rates:

In the previous 25000 days of aviation over Manhattan prior to 9-11, there had been only two such accidencts.

so P(P) = 2/25000 = 0.008%

and P(T) we can assign an arbitary intial rate: like 0.005%

__Before the first plane hits the twin tower, we have:__

P(T) = 0.005%
P(P|T) = 0.00 % , it is all good

__At the moment the first plane crahsed into the twin tower.__

P(T) = 0.005%

P(P|T) = 100 %

P(P) = 0.008% + 0.005%

P(T|P) = 1*0.00005/(0.00005+0.00008) = 38%

so with the new evidence, the probablility of P(T|C) revised to 38%

__at the moment of second plane hits the twin tower:__


P(T) = 38%
P(2P|T) = 100%
P(2P) = 0.008% * 0.008% + 1 * 38%= 0.3800000064

P(T|2P) = P(2P|T)*P(T)/P(2P)

P(2P|T) = 100% P(T) = 38% /P(2C)=38%/(0.008%*0.008% + 38%)= 99.99%

by the time the 2nd plane hits the twin tower, we can almost certain it is a Terrorist Attack.

___
**Example**

A reader from Quora poses a questioin:

> What does it mean when a girl smiles at you every time she sees you ?

![Girls Smile](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/93t5yvtj.png)

Another reader using Bayes’s Theorem replies:

P(like|smile) = P(smile|like)*p(like)/p(smile)

so you need to gather the base rate data;

ie.

How likely A happens( she like someone)
How strong an evidence of B (she smiles at you)

P(smile|like) = Chance She Smiles at you given she likes you P(like) = Chances She likes you P(smile) = Chances she smile when seeing anyone

Lets assume two extreme:

P(smile) = 1, she smile at everyone, by definition, p(smile|like)=1 too.


so

P(like|smile) = 1*P(Like)/1 = P(like)

So she smiling at **YOU** doesn't tell you much.

Remember, **the strengh of evidence is depends on how many alternative explanation it could have**


But...

if She rarely smiles at someone, but smiles everytime she sees someone she likes, then

P(smile|not liked) = 0%. P(smile|like) = 100% P(smile)=P(like)

P(like|smile) = = 1*P(smile)/(0 + P(smile|like))= 100%

In general, to be a true Bayesian, you will gather the background data of how often she smiles at everyone, and how often she smiles at someone she likes etc.

The more often she smiles at everybody, the lower chance she likes you.

___

**Example**:

![ Rainy Day](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/9wtjfuf8.png)

[**Example Rainy Day**](http://stattrek.com/probability/bayes-theorem.aspx)

Marie is getting married tomorrow, at an outdoor ceremony in the desert. In recent years, it has rained only 5 days each year. Unfortunately, the weatherman has predicted rain for tomorrow. When it actually rains, the weatherman correctly forecasts rain 90% of the time. When it doesn't rain, he incorrectly forecasts rain 10% of the time. What is the probability that it will rain on the day of Marie's wedding?

So we want to know:

P(Raining |Forcasted Rain) = P(Forcasted Rain|Raining)*P(Raining)/P(Forcasted Rain)

= 0.9*(5/365)/(0.9*5/365+(360/365)*0.1)= 0.01232/(0.01232+0.09863)= 11.09%

Despite the weatherman's gloomy prediction, there is a good chance that Marie will not get rained on at her wedding.

___

[**Example:**][13]

![blue eggs](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/nmffwrdq.png)
Suppose that a barrel contains many small plastic eggs. Some eggs are painted red and some are painted blue. 40% of the eggs in the bin contain pearls, and 60% contain nothing. 30% of eggs containing pearls are painted blue, and 10% of eggs containing nothing are painted blue. What is the probability that a blue egg contains a pearl?

P( Contain Pearl | Blue ) = P (Blue | Contain Pearl) * P (Contain Pearl)/P(Blue)

P (Blue | Contain Pearl ) = 0.3 P (Contain Pearl) = 0.4

P(Blue) = P(Blue | Contain Pearl) + P(Blue | Not Contain Pearl) = 0.3*0.4 + (1-0.4) * 0.1 = 0.12 + 0.06

So the answer is = 0.12/0.18 = 66.7%

___

[**Example**][14]

Assume you have a room full of men and women. 70% of the people are women and 30% are men. Additionally, we know from polling every person that 40% of the women’s favorite color is green and 75% of the men’s favorite color is green.

Given that a randomly selected person likes green, what is the probability that the person is a female?”

P(Female | Like Green ) = P ( Like Green | Female ) * P(Female)/P( Like Green) = 0.4*0\.7/(0.4*0\.7+ 0.3*0.75)= 55 %

___

[**Example**][15]

The Monty Hall problem according to Wikipedia states:

> Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?

For simplicity let: D1: The Event of Monty Hall opening door 1. D2: The Event of Monty Hall opening door 2. D3: The Event of Monty Hall opening door 3. C1: The Event of finding the car behind door 1. C2: The Event of finding the car behind door 2. C3: The Event of finding the car behind door 3.

The prior probability of Monty Hall finding a car behind any door is obviously p(C#)=1/3, where P(C1)=P(C2)=P(C3)

P(C1|D3) = P(D3|C1)* P(C1)/P(D3) = 0.5 * 1/3 /0.5 = 1/3

P(C2/D3) = P(D3/C2) * P(C2)/P(D3) = 1*1/3/0.5

[![Monty Hall Problem][16]][17]

___

[**Example**][18]

> Joe is a randomly chosen member of a large population in which 3% are heroin users. Joe tests positive for heroin in a drug test that correctly identifies users 95% of the time and correctly identifies nonusers 90% of the time. To determine the probability that Joe uses heroin (= H) given the positive test result (= E), we apply Bayes' Theorem using the values


P(H|E)= P(E|H)* P(H)/P(E) = 0.95 * 0.03/(0.95 * 0.03 + 0.97*0.1) = 22%

___

[**Example**][19]

> Say you wake up with spots all over your face. You rush to the doctor and he says that 90 percent of the people who have smallpox have the symptoms you have. Since smallpox is often fatal, your first inclination may be to panic.

But but applying the rules of Bayes Themrom, you have no fear:

* Brain Storm/List out any reasons/causes you can think of to event B to happen

so you ask your docter , what could cause spots all over your face. ?

The doc replies.

* you have smallpox.
* you have chicken pox.

* Find out/Estimate the probability base rate of A is happening

* small pox, about 0.111 percent (or 0.0011) population has this
* chickenpox, which by estimation is about 10 times as likely, about 10% of the population has this

Also your doc is kind enough to tell you

* 90 percent of people with smallpox have these spots
* 80 percent of people with chickenpox have these spots

so P(smallpox|Spots) = P(Spots|smallPox) * P(smallpox)/p(spots) = 0.9 * 0.001/(0.1*0\.8+0.001*0\.9)= 1.11 %

___

[**Example**][20]

In James V Stone excellent book of Bayes' Rule: A Tutorial Introduction to Bayesian Analysis, he mentions a interesting example:

If you walked into a hardware store and asked:

"Have you got fork handles ? "

You was surprised by the Bayesian Shop Owner whom present you with four candles.

The Phrase "Fork Handles" and "Four Candles " are acoustically almost identical.

Put you into the Bayeisan shop owner's shoes:

* Brain Storm/List out any reasons you can think of to event B(you hear "fork handles") to happen

* The Customer wants four candles
* The Customer Wants fork handles

and since accoustic pattern of Four candles is almost identical of Fork Handles

We assign abitary probablity of

P(Data | Four Candles ) = 0.6
P(Data | Fork Handles ) = 0.7


And from the Bayesian Shop Owner pass experience,

* he was asked about Fork Handles only 10 times
* he was asked about candles 90 times


so P(Four Candles| Data ) = P(Data | Four Candles ) * P(Four Candles) / P(Data)

= 0.6 * 0.9 /(0.6 *0.9 + 0.7 *0.1) = 88%

Example [Nickel or Quarters](https://www.amazon.com/Bayes-Theorem-Examples-Understanding-Applications-ebook/dp/B01HYHT00W/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1475803337&sr=1-2)


> 5 nickels and 3 quarters are put in a bag. Two coins are drawn, one after the other, without being replaced. If the second coin drawn is a quarter, what is the probability that the first coin drawn is a nickel?

~~~
P(F-N) = 5/8

P(S-Q|F-N) = 3/7

P(S-Q) = 3/8 * 2/7 + 5/8* 3/7 = 21/56

P (F-N| S-Q) = P( S-Q| F-N)* P(F-N)/P( S-Q) = 15/21 = 0.714

~~~

Example [Nickel or Quarter. New Information](https://www.amazon.com/Bayes-Theorem-Examples-Understanding-Applications-ebook/dp/B01HYHT00W/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1475803337&sr=1-2)

> We have a bag with 5 nickels and 3 quarters, as in the previous chapters. We pull out 2 coins without replacement and learn from that if the second coin drawn is a quarter, there is a 71.43% chance that the first coin is a nickel. Now we pull a third coin from the bag. Say it is a quarter. What is the probability the first coin is a nickel, given this new information, in addition to our information above ?


P( S-Q & T-Q) = 3/8 * 2/7 * 1/6 + 5/8* 3/7 * 2/6 = (6+30)/336 = 10.71%

P(S-Q & T-Q | F-N ) = 3/7 * 2/6

P ( F-N) = 5/8

P (F-N | S-Q & T-Q) = P(S-Q & T-Q | F-N ) * P ( F-N) / P (S-Q & T-Q)) = 30/336 / (36/336)

= 0.8333


Example [Nickel or Quarter, the third Draws]](https://www.amazon.com/Bayes-Theorem-Examples-Understanding-Applications-ebook/dp/B01HYHT00W/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1475803337&sr=1-2)

> You pull another coin from your bag. If it is a quarter, what is the probability the first coin is a nickel, given all our information? What if the new coin draw is a nickel?





P( F-N & S-Q & T-Q & F-Q) = 5/8* 3/7 * 2/6 * 1/5

P ( S-Q & T-Q & F-Q) = 5/8* 3/7 * 2/6 * 1/5


P (F-N | S-Q & T-Q & F-Q) = P(S-Q & T-Q & F-Q | F-N ) * P ( F-N) / P (S-Q & T-Q & F-Q)) = 100%


___

**Example**

[Games of Chance ][21]

Each of four urns is to be sampled once by the player. The first urn contains one red ball and two white balls, the second one red ball and three white balls, the third one red ball and four white balls, and the fourth one red bell and five white balls. The selection of urns is equally probable.

The player picked a red ball; what is the probability that the secon urn, U2, was selected ?

P(U2|Red) = P(Red|U2)P(U2)/( P(RED|U1)+P(RED|U3)+P(RED|U2)+P(RED|U4)) = 1/4*1/4/(1/4*1/3+1/4*1/4+1/4*1/5+1/4*1/6)= 26.3%

___

**Example**

[Defective Components][21]

Identical components are procured from three vendors for use in the next higher assembly of a production process. forty-five percent of the componente are procured from Vendor 1. 30 percent from Vendor 2, and 25 percent from Vendor 3. The respective percentages of defective: 6, 3, and 2.

What is the probability of a defective component is from vendor 1 ?

P(1|D)=P(D|1)*P(1)/P(D) = 0.06*0\.45/(0.06*0\.45+0.03*0\.3+0.25*0.02)= 65%

___

Example

[Enviromental Protection][21]

Pollution detection devices of the enviromental protection agency of a certain state can detect excessive enounte of pollutente emitted by factories with a probability of 0.90. and probability of 0.20 that factories not exceeding limits will fail the test. The issue is whether to procure devices with a detection probability of 0.99.even though the increased sensitivity will increase the false alarI probability to 0.22, to apprehend more violators of state statutes. It is estimated around 30 percent of the factories in the state emit excessive pollutants.

Is that worth the investment ?

For the existing device:

P(P|F)= P(F|P)*P(P)/P(F)= 0.9*0\.3/(0.9*0\.3+0.7*0\.2)= 0.27/0.41=65.8%

If we buy the new device:

P('P|'F) = 0.99*0\.3/(0.99*0\.3+0.7*0.22) = 0.297/(0.297+0.154) = 65.8%

So, probably we should not invest in the new device:

___

[Example: Interview][22]

The Gallup organization randomly selects an adult American for a survey about credit card usage.

a. What is the probability that the selected subject is a male? b. After selecting a subject, it is later learned that this person was smoking a cigar during the interview. What is the probability that the selected subject is a male?

Our Hypothesis for now:

The interviewee is male:

So let try to find out the base rate of our hypothesis:

by some googling, we find out the [% for Male in US is about 49.2%][23]

So before the new evidence of the interviewee is smoking cigar, the base rate probability of the interviewee is male:

P(M)= 49.2

And the Test/Evidence is this interviewe smoke cigar during interview:

We got our much needed statistic data from [CDC][24]

> Current Cigar Use
>
> Adults:
>
> Percentage of U.S. adults who were current cigar smokers† in 2013:9
>
> 5\.0% of all adults 8.2% of adult males 2.0% of adult females 7.5% of African American adults 6.7% of American Indian/Alaska Native adults 2.1% of Asian American adults 4.0% of Hispanic adults 5.0% of White adults

P(P) = 5% P(C|M) = 8.2% Lets plug all the data into Bayes themorem

P(M|C) = P(C|M)*P(M)/P(P) = 8.2% * 49.2% /5% = 80.6%

The probability of the interviewee is a male revised to 80.6%

***

[Example: Identical Twins][25]

> Elvis Presley had a twin brother who died at birth. What is the probability that Elvis was an identical twin?
>
> To answer this one, you need some background information: According to the Wikipedia article on twins: ``Twins are estimated to be approximately 1.9% of the world population, with monozygotic twins making up 0.2% of the total---and 8% of all twins.''

So what is the hypothesis we are trying to find out the probability ?

Elvis was an identical twin

and the tricky part is, what the new evidence ?

> Elvis Presley had a twin brother

Presumably Elvis is a boy, and twin brother means same sex, and identical twins, by definition, is always has the same sex, but individual twins probably has 50% to 50% change of different sex( I could be wrong)

plug in the datas to Bayes Themrom, we got:

P(IT|Same Sex) = P(Same Sex| IT)* P(IT)/P(S) = 1* 8%/(92% * 50% + 1* 8%) = 14.8%

[Example: Lung Cancer and Smoking][25]

> According to the CDC, ``Compared to nonsmokers, men who smoke are about 23 times more likely to develop lung cancer and women who smoke are about 13 times more likely.'' If you learn that a woman has been diagnosed with lung cancer, and you know nothing else about her, what is the probability that she is a smoker?

The Hyothesis A:

This Woman is a smoker

A':

This Woman is not a smoker

And the Evidence/New Information:

THis Woman has been diagnosed with lung cancer

Lets find out the base rate first:

According to [CDC][26]:

in 2012

> 210,828 people in the United States were diagnosed with lung cancer, including 111,395 men and 99,433 women.

And 2012 the US population is about 314.1 million.

so the base rate for women diagnosed with lung cancer is:

99433/(314100000/2)= 0.06 %

Also from CDC, we can find the estimation of Adults whom is a smoker:

> By Gender
>
> Men are more likely to be current cigarette smokers than women.
>
> Nearly 19 of every 100 adult men (18.8%) Nearly 15 of every 100 adult women (14.8%)

Lets plugin in the equations:

P(S|L) = P(L|S)* P(S)/P(L)

Wait.. We dont know P(L|S) yet .ie. Probability of Smoker got lung cancer:

Fortunately, high school math come into rescue.

lets put P(L|NS) = x ie. the Probability of Women non-smoker got lung cancer:

0.852x + 13(0.148)x = 0.06 %
2.776x = 0.06%
x = 0.0216%

and P(L|S) = 13x = 0.28%

lets plug all the numbers into Bayes Equation

P(S|L) = P(L|S)* P(S)/P(L) = 0.28% * 14.8% /( 0.0216% * 85.2 % + 0.28% * 14.8%) = 0.04144%/(0.0184%+0.04144)=0.04144/0.0598 = 69.3%

***

[Example: Finding the Mole][27]

![Spy](https://upload.wikimedia.org/wikipedia/commons/3/36/Spy.png)
> So: you're the head of MI6. You're pretty sure there's a "mole" in your organization.
>
> You've narrowed it down to five suspects: Alan,Bob, Chris,Dave, and Ed.
>
> You know from previous experience with interrogations that there are five behaviours to be expected in any given session: normal behaviour, nervousness, anger at the accusation, making a mistake in one's story, and a desperate exhausted confession
>
> you know from experience that moles and loyal operatives will exhibit the five behaviours at different rates.

Behavious of loyal Operatives:

Normal:70% Confess:5% Mistake:10% Angry:5% Nervous:10%

Behaviours of moles:

Normal:55% Confess:10% Mistake:10% Angry:10% Nervous:15%

The probability-of-being-the-mole is 0.2 for each person in this case. This is called a uniform prior.

We begin the interrogation sessions.

Session 1:

lets just use one Agent Alan as an example

P(M|N)= P(N|M) * P(M)/P(N) = 55 % * 20 % /(55 % * 20% + 70% * 80%) = 0.11/0.67 = 0.164

| Agent | Prior Probability | Reaction | Revised Probability of being a Mole |
| ----- | -----------------:| -------- | -----------------------------------:|
| Alan | 0\.2 | Normal | 0\.164 |
| Bob | 0\.2 | Normal | 0\.164 |
| Chris | 0\.2 | Confess | 0\.333 |
| Dave | 0\.2 | Normal | 0\.164 |
| Ed | 0\.2 | Normal | 0\.164 |

Session 2

Lets use Ed as example

P(M|C) = P(C|M) * P(M)/P(P) = 0.1*0\.164 /(0.1*0\.164 + 0.05* 0.836)= 0.0164/0.0582= 0.282

| Agent | Prior Probability | Reaction | Revised Probability of being a Mole |
| ----- | -----------------:| -------- | -----------------------------------:|
| Alan | 0\.164 | Normal | 0\.134 |
| Bob | 0\.164 | Mistake | 0\.164 |
| Chris | 0\.333 | Nervous | 0\.429 |
| Dave | 0\.164 | Normal | 0\.134 |
| Ed | 0\.164 | Confess | 0\.282 |

. . .

Session 150

| Agent | Prior Probability | Reaction | Revised Probability of being a Mole |
| ----- | -----------------:| -------- | -----------------------------------:|
| Alan | 0\.0 | Normal | 0 |
| Bob | 0\.0 | Mistake | 0 |
| Chris | 0\.999 | Nervous | 1 |
| Dave | 0\.001 | Normal | 0\.001 |
| Ed | 1 | Confess | 1 |

* * *


[Example: A Bayesian view of Amazon Resellers](http://www.johndcook.com/blog/2011/09/27/bayesian-amazon/)

You want to buy a used book through Amazon, there are two sellers:

Seller A has 90 Positive reviews out of 100, thus a Rating of 90%

Seller B has 2 Positive reviews, thus a Rating of 100%

Which one will you pick ?

The 100% One Right ?

Because we deal with small numbers here, we need to use Beta-Distribution instead of Normal Distribution.

[best explaination of beta distrubtion & Bayesian therom](http://stats.stackexchange.com/questions/47771/what-is-the-intuition-behind-beta-distribution)

The Math behind is somewhat complicated, but you can use this calculator to quickly [judge the numbers](http://www.peakconversion.com/2012/02/ab-split-test-graphical-calculator/):


[Example: A Political Example, From Bayesian Statistics, Peter M. Lee](http://www.amazon.com/Bayesian-Statistics-Introduction-Peter-Lee/dp/1118332571/ref=sr_1_3?ie=UTF8&qid=1463538432&sr=8-3&keywords=Bayesian+Statistics+peter)


>The following example is a simplified version of the situation just before the time of the British national referendum as to whether the United Kingdom should remain part of the European Economic Community which was held in 1975. Suppose that at that date, which was shortly after an election which the Labour Party had won, the proportion of the electorate supporting Labour (L) stood at 52%, while the proportion supporting the Conservatives (C) stood at 48% (it being assumed for simplicity that support for all other parties was negligible, although this was far from being the case). There were many opinion polls taken at the time, so we can take it as known that 55% of Labour supporters and 85% of Conservative voters intended to vote ‘Yes’ (Y) and the remainder intended to vote ‘N o’ (N). Suppose that knowing all this you met someone at the time who said that she intended to vote ‘Yes’, and you were interested in knowing which political party she supported. If this information were all you had available, you could reason as follows:

P(L|Y)=P(Y|L)* P(L)/P(Y)

= 55% * 52% /( 55% * 52% + 48%* 85%)

= 0.286/(0.286+0.408) = 0.286/0.694 = 41.2 %

She has a 41.2% Belongs to Labour Party

***

[Example: Forensic AnalysisFrom Bayesian Statistics, Peter M. Lee](http://www.amazon.com/Bayesian-Statistics-Introduction-Peter-Lee/dp/1118332571/ref=sr_1_3?ie=UTF8&qid=1463538432&sr=8-3&keywords=Bayesian+Statistics+peter)

![blood test](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/eu85w0il.png)

>Suppose a crime has been committed. Blood is found at the scene for which there is no innocent explanation. It is of a type which is present in 1% of the population. The prosecutor may then state:

>‘There is a 1% chance that the defendant would have the crime blood type if he were innocent. Thus, there is a 99% chance that he is guilty’ .

>Alternatively, the defender may state:

>‘This crime occurred in a city of 800,000 people. This blood type would be found in approximately 8000 people. The evidence has provided a probability of l in 8000 that the defendant is guilty and thus has no relevance.’

Which one is correct ? Armed with Baysian thinking, you find out both argument is not correct.

Lets Apply the Baysian Theorem here:

Believe:

The Suspect is Guity:

Evidence:

The Suspect has the same blood type of the crime scene

Basic Data:

Priors:

P(Guity) = 1/800000

P(Equal Blood Type| Guity) = 1

P(Equal Blood Type)= 8000/800000


P(Guilty|Equal Blood Type) = P (Equal Blood Type| Guilty)* P(Guity)/P(Equal Blood Type)
= 1 * 1/800000/(8000/800000)

With the new evidence of the suspect has the same blood type of the crime scene, the Postier Probability of P(Guity) change from 1/800000 to 1/800


> Such a large change in the odds is, in Aitken’s words ‘surely of relevance’ . But, again In Aitken’s words, ‘Of course, it may not be enough to find the suspect guilty’.

___

[Example: HIV screening](http://www.win-vector.com/blog/2009/11/i-dont-think-that-means-what-you-think-it-means-statistics-to-english-translation-part-1-accuracy-measures/)

> A more realistic example, inspired by a discussion of mandatory AIDS testing by Joshua Rosenau [Ros06], is the use of the ELISA screening test to detect HIV-infected blood donations. The ELISA test is designed to be very sensitive: it detects 99.7% of the cases of HIV-infection, which gives a false negative rate of
0.003 . On the other hand, it is not very specific: it has a 1.9% false positive rate1. If you assume that the incidence of HIV-positive individuals in the general population is about 448 out of every 100,000 people [Hig08], then a positive test result is correct only about 19% of the time: one case of true infection out of every five positives. This error rate may be appropriate for screening blood donations, since it is better to discard four perfectly good pints of blood, “just in case”, than to allow a pint of HIV-infected blood into the blood bank. But it is not appropriate to assume that all five of those poor blood donors are HIV-positive, without followup tests to increase the specificity of the screening procedure.

___

[Example: Board Game hint](https://www.farnamstreetblog.com/2012/12/thomas-bayes-and-bayess-theorem/)

> Let’s imagine that you and a friend have spent the afternoon playing your favorite board game, and now, at the end of the game, you are chatting about this and that. Something your friend says leads you to make a friendly wager: that with one roll of the die from the game, you will get a 6

>Straight odds are one in six, a 16 percent probability. But then suppose your friend rolls the die, quickly covers it with her hand, and takes a peek. “I can tell you this much,” she says; “it’s an even number.”

with this new information:

P(6|E) = P(E|6) P(6)/P(E)= 1 * (1/6) /0.5 = 0.33

> While you are considering whether to change your bet, your friend teasingly adds: “And it’s not a 4.”

with this new addition information:

P(6| ~4) = P(~4|6) P(6)/P(~4|E) = 1*0.33/(2/3)
= 0.5

___


[Example: Sports Fans](http://wwwf.imperial.ac.uk/~ayoung/m2s1/WorkedExamples1.pdf)

> While watching a game of Champions League football in
a cafe, you observe someone who is clearly supporting Manchester United in
the game.
What is the probability that they were actually born within 25 miles of
Manchester ? Assume that:
• the probability that a randomly selected person in a typical local bar
environment is born within 25 miles of Manchester is 1/20
and;
• the chance that a person born within 25 miles of Manchester actually
supports United is 7/10;
• the probability that a person not born within 25 miles of Manchester
supports United with probability 1/10;


A: He/She is born within 25 mibles of Manchester
B: He/She is clearly a fan of Manchester

P(A|B)=P(B|A) \* P(A)/P(B) = 0.7 * 0.05/(19/20*1/10+1/20*7/10)= 0.035/(0.095+0.07)=0.035/0.13=26.9%


___

[Example: Food Allergy](https://www.countbayesie.com/blog/2016/1/22/why-you-should-believe-your-friends-claims-about-food-allergies)


> Food allergies are a big deal. Nearly everyone has had to accommodate someone with a food allergy. Sometimes it's switching from making your kid Peanut Butter and Jelly to Sunflower Butter and Jelly, making a gluten-free appetizer for a party, or cooking a separate meal for a guest. While most people try their best to be considerate, I think everyone without a food allergy, myself included, has wondered "but do they really have a food allergy?". Even the Boston Globe published an article, back in October, "Why food allergy fakers need to stop". The value of probability theory is that we can quantify our skepticism and make rational choices from this analysis. In this post we're going to answer the question "How Skeptical Should I be if my friend claims to have a Food Allergy"?

The data:

> The article gives the probability of a food allergy in children as being between 4%-8% and for adults 1%-2%. For our analysis, we'll assume the middle values, but keep in mind that we could be more conservative in our estimates. Now we can write these down as two probabilities:


> The only other piece of data we need is the probability that someone will claim they have a food allergy. We'll use the variable CC for "claims they have an allergy" (or that their kids do). Luckily the article states that both adults and parents of children claim that either they or their children have a food allergy 30% of the time. For the probability that someone will claim they or their child has a food allergy we get:



___

[Beta Distribution](http://stats.stackexchange.com/questions/47771/what-is-the-intuition-behind-beta-distribution)

Normal Distribtion is the heart of frequencist core(Central Limit Theorem), And Normal Distribution Diagram is a probability density diagram, so once the mean and standard deviation is known, we can use inverse lookup the probability of a given x value.


[Beta Distribution](https://www.countbayesie.com/blog/2015/4/4/parameter-estimation-the-pdf-cdf-and-quantile-function) is the Bayestist equavilant of Normal Distribution.

what is beta distribution ?

In plain words, beta distribution is the unknown distribution, probably x distribution would be a better name;


>[The short version is that the Beta distribution can be understood as representing a distribution of probabilities- that is, it represents all the possible values of a probability when we don't know what that probability is. Here is my favorite intuitive explanation of this:
In Practice, Beta Distribution Function is used with Baysian Formular for Binomial Events(1/0):](http://stats.stackexchange.com/questions/47771/what-is-the-intuition-behind-beta-distribution)

The more commonly used beta distribution is beta distribution with likelyhood of binomial distribution.

[![Beta distribution for binomial](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/x_1ohc4x.png)](https://en.wikipedia.org/wiki/Conjugate_prior)


what is α/ß ? α/ß is the parameter we used to model the probability density digram.

in case of Beta Binomial distribution:

α = No. of successful trials,

ß = No. of unsuccessful trials,

If there is no prior knowledge or memory, the prior input of α/ß will be 1/1

![uninformative prior](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/osb-e3su.png)

The resulting probablity density diagram is a straight line. ie no information., means the odds is even for all outcomes.

what if we do have prior knowledge ?

If you have some prior information of success and failed trials, ie memories. then you can use it to model the probability density diagram. After that, you can use it to inverse look up a given x value, just as using the normal distribution diagram.


Beta Density Function


you can also use this [oline Beta Distrubtion Calculator](http://keisan.casio.com/exec/system/1180573226) to plot it yourself



For example, we put a banner ad and want to estimate the conversion rate for user click through the banner.

Conversion is a binomial event, and for the first few clicks, it will swing greatly between 100% and 0%, and thus make it a poor predictor for its actual performance.

But we do know from experience the banner conversion rate is usually between 0.1% and 1%, and the average probably somewhere between 0.5%

we can use 0.5% average to poll a beta distribution diagram and represents the probability distribution

in this case, we can pick

α = 5
ß = 95

the number is arbitary but need to comply the following rules

![formular](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/iiinzemk.png)= 5/(5+95) = 0.5

![probability density function](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/i8-1ukc_.png)

as you can see , the probability distribution is within 0.0% and 1%

the general rule is the higher confidence of prior knowledge, the higher value of α and ß



David Robinson also explained beta distribution very well in this [post](http://varianceexplained.org/statistics/beta_distribution_and_baseball/)


> Anyone who follows baseball is familiar with batting averages- simply the number of times a player gets a base hit divided by the number of times he goes up at bat (so it's just a percentage between 0 and 1). .266 is in general considered an average batting average, while .300 is considered an excellent one.

>Imagine we have a baseball player, and we want to predict what his season-long batting average will be. You might say we can just use his batting average so far- but this will be a very poor measure at the start of a season! If a player goes up to bat once and gets a single, his batting average is briefly 1.000, while if he strikes out or walks, his batting average is 0.000. It doesn't get much better if you go up to bat five or six times- you could get a lucky streak and get an average of 1.000, or an unlucky streak and get an average of 0, neither of which are a remotely good predictor of how you will bat that season.

>Why is your batting average in the first few hits not a good predictor of your eventual batting average? When a player's first at-bat is a strikeout, why does no one predict that he'll never get a hit all season? Because we're going in with prior expectations. We know that in history, most batting averages over a season have hovered between something like .215 and .360, with some extremely rare exceptions on either side. We know that if a player gets a few strikeouts in a row at the start, that might indicate he'll end up a bit worse than average, but we know he probably won't deviate from that range.



___

[Example Quality Control](https://www.statlect.com/probability-distributions/beta-distribution)

> A production plant produces items that have a probability X of being defective. The plant manager does not know X, but from past experience she expects this probability to be equal to $4%$. Furthermore, she quantifies her uncertainty about X by attaching a standard deviation of $2%$ to her $4%$ estimate. After consulting with an expert in statistics, the manager decides to use a Beta distribution to model her uncertainty about X. How should she set the two parameters of the distribution in order to match her priors about the expected value and the standard deviation of X?


using this [alpha beta calculator](https://docs.google.com/spreadsheets/d/10LqWsKJhCBxm_281Vt0d2yH8-WYg39OLwXkWY4eLTIg/edit#gid=346900249)

___

[Example Mystic Seer Fortune telling machine](https://www.countbayesie.com/blog/2016/3/16/bayesian-reasoning-in-the-twilight-zone)

![One Question Per penny](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/dh4b2yze.png)

Going to reuse the example from [Countbayesie.com[https://www.countbayesie.com/blog/2016/3/16/bayesian-reasoning-in-the-twilight-zone]
>newly married couple, Don (played by none other than William Shatner) and Pat are forced to spend time in a small town diner while they wait for car repairs. In the diner they come across a fortune telling machine, the "Mystic Seer," which accepts yes/no question and (for a penny) spits out a card with an answer. The episode quickly establishes that Don is very superstitious. He eagerly asks the Mystic Seer a series of question and soon begins to believe in the supernatural powers of this particular device. Pat remains continuously skeptical even as each assertions of the Seer comes true. Eventually, Pat comes around to believe in the powers of the seer, but unlike her husband finds the possibility that the seer is prophetic terrifying.

Lets assumpt for PAT, the initial believe for P(A):The Mystic Seer truly can predict the future. is 1/1000,000

The Questions is, how many correct answer it takes to convince PAT

Lets put P(B) = P(xC), ie x Correct Answer

P(A|B) = P(B|A)* P(A)/P(B)

P(B|A) = 1
P(A) =1/1000,1000
P(B) = 1/1000,1000 + P(xC)
= 1/1000,1000 + (0.5)^x

P(A|xC) = 1/1000,1000/(1/1000,1000 + (0.5)^x) > 0.5

Quickly plugin in spreadsheet by trial, you can get when x =20, P(A| 20C) =0.5118

___

[Example 3 Dice](https://www.amazon.com/Bayes-Theorem-Examples-Intuitive-Guide-ebook/dp/B01AZXQY1K/ref=sr_1_1?s=digital-text&ie=UTF8&qid=1474595628&sr=1-1&keywords=bayes+theorem+examples)

> Suppose that your friend has 3 dice. One has 4 sides, one has 6 sides, and one has 8 sides. He draws one die at random, rolls it one time without showing you, and reports the result as having rolled a 2. How would you calculate the probability that the die was the 4 sided die ?

P (4S|2) = P(2|4S)P(4S)/P(2) = 1/4*1/3/(1/3*(1/4+1/6+1/8)= 0.4621



[Example 6 dice](https://www.amazon.com/Bayes-Theorem-Examples-Intuitive-Guide-ebook/dp/B01AZXQY1K/ref=sr_1_1?s=digital-text&ie=UTF8&qid=1474595628&sr=1-1&keywords=bayes+theorem+examples)

> For this problem, we will stick with trying to predict the probabilities of dice drawn at random. This time we are going have 6 possible dice, one with 4 sides, one with 6 sides, one with 8 sides, one with 10 sides, one with 12 sides and one with 20 sides. We are going to roll the die 15 times and calculate what the probability for each die that it was the one that was drawn.

supposely for the first roll, your friend told you he rolled a 4; what is the probability the dice is a 4, 6, 8, 10,12,20 dice ?

P(X sided | 4) = p(4| X sided )* P(X sided) /P(4)

the probability of being a 4 sided dice

P(4S|4) = p(4| 4s) p(4s)/p(4) = 1/4 * 1/6 /(1/6(1/4 + 1/6 + 1/8 + 1/10 + 1/12 + 1/20)) = 1/4/ 0.775 = 0.3225

probability of being a 6 sided dice

P(6S|6) = P(4| 6S) p(6S)/P(4) = 1/6 * 1/6/1/6/(1/4 + 1/6 + 1/8 + 1/10 + 1/12 + 1/20)
= 1/6/(0.775) = 0.215

we can make a table out of it


Roll | Rolled Number| 4 Side Dice | 6 Side Dice | 8 Side Dice | 10 Side Dice | 12 Side Dice | 20 Side Dice
---| --- | --- | --- | --- | --- | --- |----
0 | NA | 1/6 | 1/6 | 1/6 | 1/6 | 1/6 | 1/6
1 |4| 0.323 | 0.215 | 0.161 | 0.129 | 0.108 | 0.065

Say on the second roll, we rolled a 3:

the probability of being a 4 sided dice, noted the p(4s) is no longer 1/6, but updated to 0.3225 after the first roll.

P(4S|4) = p(4| 4s) p(4s)/p(4) = 1/4 * 0.3235/(0.323 * 1/4 + 0.215 * 1/6 + 0.161 * 1/8 + 0.129 * 1/10 + 0.108 * 1/12 + 0.065 * 1/20)

= 1/4 * 0.3235/0.1617 = 0.5

.
.

Roll | Rolled Number| 4 Side Dice | 6 Side Dice | 8 Side Dice | 10 Side Dice | 12 Side Dice | 20 Side Dice
---| --- | --- | --- | --- | --- | --- |----
0 | NA | 1/6 | 1/6 | 1/6 | 1/6 | 1/6 | 1/6
1 |4| 0.323 | 0.215 | 0.161 | 0.129 | 0.108 | 0.065
2 |3| 0.5 | 0.22 | 0.12 | 0.08 | 0.06| 0.02

so after 15 rolls,

the probability of the dice is

Roll | Rolled Number| 4 Side Dice | 6 Side Dice | 8 Side Dice | 10 Side Dice | 12 Side Dice | 20 Side Dice
---| --- | --- | --- | --- | --- | --- |----
15 | 2 | 0 | 0 | 0.96 | 0.03 | 0 | 0

https://docs.google.com/spreadsheets/d/1-HbGESzGuTqCO-yx2yuf3WsmNIdlmOdBHPYxjqBi0to/edit#gid=0


___

[Example: Fair Coin](https://www.amazon.com/Bayes-Theorem-Examples-Intuitive-Guide-ebook/dp/B01AZXQY1K/ref=sr_1_1?s=digital-text&ie=UTF8&qid=1474595628&sr=1-1&keywords=bayes+theorem+examples)

> You have a coin that you suspect is not a fair coin. You flip the coin 100 times to determine if it is fair. After 100 flips, what is the probability that the coin comes up heads each of these percentages, 0%, 10%, 20%, 30%, 40%, 50%, 60%, 70%, 80%, 90%, 100%. ?

say the first flip is a head

and we want to calcuale the coin being head of 40% chance:

P( 40% H | H) = P(H| 40%H) * P(40%H)/P(H)

= 40% * 1/11/1/11(0 + 0.1 +0.2 + 0.3 + 0.4 + 0.5 + 0.6 + 0.7 + 0.8 + 0.9 +1) = 0.4 /5.5 = 0.0727

say the first flip is tail

and we want to calcuale the coin being head of 40% chance:

P( 40% H | tail ) = P(tail| 40%H) * P(40%H)/P(tail)

[Example: German Tank Problem](https://www.amazon.com/Bayes-Theorem-Examples-Intuitive-Guide-ebook/dp/B01AZXQY1K/ref=sr_1_1?s=digital-text&ie=UTF8&qid=1474595628&sr=1-1&keywords=bayes+theorem+examples)


>In this problem you are trying to estimate how many tanks have been produced, based off of the serial numbers of captured tanks. Bayes theorem was used in World War 2 by the Allies to do exactly that, and ended up with results that were substantially lower for total number of tanks produced than conventional intelligence estimates (i.e. spies) were reporting. After the war, records indicated that the statistical estimates using Bayes Theorem were also substantially more correct.



>You are analyzing serial numbers pulled off of wrecked or captured tanks. Use those numbers to estimate how many tanks have been produced. You know this about the tank serial numbers They start at 1 They are sequential without gaps You have found these serial numbers, 30, 70, 140, 125.

you split your guess in number of 20 increment, 20, 40 ... 1000


for first captured tank, you found a serial number of 17

say the probability of total number is 100:

P( 100 | s30) = P(s30 | 100) * P(100)/P(s30)

= 1/100 * 1/50/1/50/(1/20+1/40+...1/1000) = 1/100/0.225 = 0.0444

[Example: Drug Test, Take 2](https://www.amazon.com/Bayes-Theorem-Examples-Intuitive-Guide-ebook/dp/B01AZXQY1K/ref=sr_1_1?s=digital-text&ie=UTF8&qid=1474595628&sr=1-1&keywords=bayes+theorem+examples)

> You are testing for a certain drug. You know that .5% of the population uses this drug. You have a test that will a produce 99% true positive results for users, and 98% true negative results for non-users. You randomly test 2 person from the population and get a positive result.
>
> then you ask the two person to take the same test again, and come out with 1 positive and 1 negative, What is the probability that they are actually a user of the drug ?

On the First Test:

P (D|P) = P(P|D)* P(D)/P(P) = 0.99 * 0.005/(0.99*0.005 + 0.02 * 0.995) = 19.9 %

after the second test, for the postive guy.

P (D|P) = P(P|D)* P(D)/P(P), but we update the P(D) to 19.9 %

= 0.99 * 0.199 /(0.99 * 0.199 + 0.02 * 0.801) = 92.4 %

after the second test, for the negative guy.

P (D|N) = P(D|N)* P(D)/P(N), we update the P(D) to 19.9 %

= 0.01 * 0.199 /(0.01 * 0.199 + 0.98*0.801) = 0.25% , so the guy is non drug user is 99.75%

___



Example: [how to find the fake users](https://mp.weixin.qq.com/s/bn3n4jHudxjst5W2yijjWQ)

In big social networking site allows free users registration, bot user or fake user is always an problem,

How can spot them ?

We can use human to manually classify the users and find out the correlation between the results and attributes(which can be done easily by using a simple sql query)

say we decided to use 3 attributes:

A) the users use profile picture or not
B) Friends / days of registration
C) post/days of registration


and by manually 10000 classify users, the data for the 3 features is the following:

P(Fake Users) = 0.11 = P(F)
P(Real Users) = 0.89 = P(R)

A) the users use profile picture or not
P(R|A) = 0.8
P(R| ~A ) = 0.2

P(F|A) = 0.9
P(F|~A) = 0.1

B) Friends / days of registration

P(B> 0.2 | R) = 0.2
P(B<0.05| R) = 0.3
P(0.05<B<=0.2| R) = 0.5

P(B> 0.2 | F) = 0.1
P(B<0.05| F) = 0.8
P(0.05<B<=0.2| F) = 0.1

C) post/days of registration

P(C<0.1 | R) = 0.1
P(0.1=<C<0.8 | R) = 0.7
P(0.8<C | R) = 0.2

P(C<0.1 | F) = 0.7
P(0.1=<C<0.8 | F) = 0.2
P(0.8<C | F) = 0.1

Now we have a new registration comes in and this account didn't use a profile picture, post/days of registration = 0.1 , Friends / days of registration = 0.2, is it a real user or not ?

lets calculate the probability use feature A, use profile picture or not, the user didn't use a real profile picture

P(R|~A) = P(~A|R) * P(R)/P(~A) = 0.2 * 0.89 / (P(A|F) * P(F) + P(A|R)* P(R)) = 0.178 /(0.11 * 0.1 + 0.89* 0.2) = 0.941

P(R) revised to 0.791 from 0.89

using Feature B, Friends / days of registration

P(R| B(0.2)) = P(B(0.2)|P(R)) * P(R) / PB(0.2) = 0.5 * 0.941 / (0.941 * 0.5 + 0.059 * 0.1) = 0.4705 /0.4764 = 0.988

P(R) revised from 0.791 to 0.95 after considering feature B


using feature C, post/days of registration

P(R| C(0.1)) = P(C(0.1) | R) * P(R) /P(C(0.1)) = 0.7 * 0.988 /(0.988 * 0.7 + 0.0112*0.2) = 0.6916 / 0.69384 =

so there is 99.67 % chance this is a real user



___

Example: [Sally Clark](http://faculty.washington.edu/kenrice/BayesIntroClassEpi515.pdf)

![sally clark bayes's theorem reasoning](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/3yijba25.png)

> After the sudden death of two baby sons, Sally Clark (above,
center) was sentenced to life in prison in 1996
> Among other errors, expert witness Prof Roy Meadow (above
right) had wrongly interpreted the small probability of two cot
deaths as a small probability of Clark’s innocence

Kevin from [Bayesian-intelligence.com](http://bayesian-intelligence.com/bwb/2012-03/sally-clark-is-wrongly-convicted-of-murdering-her-children/) provide an analysis of Prof Roy Meadow's faulty analysis

Sally Clark was arrested after her second baby died a few months old, apparently of sudden infant death syndrome (SIDS), exactly as her first child had died a year earlier. According to prosecution testimony (by a pediatrician, Sir Roy Meadow), about 1 in 8543 babies die of SIDS.

The prosecutor argues the probability of two baby deaths happens in the same family by chance alone is very small:

thus Sally Clark is guity because the chance is so small and beyond reasonability doubt.

Sally Clark was arrested after her second baby died a few months old, apparently of sudden infant death syndrome (SIDS), exactly as her first child had died a year earlier. According to prosecution testimony (by a pediatrician, Sir Roy Meadow), about 1 in 8543 babies die of SIDS.

The prosecutor argues the probability of two baby deaths happens in the same family by chance alone is very small:

P = \frac{1}{8542}^2 = 1/72,965,764

thus Sally Clark is guity because the chance is so small and beyond reasonability doubt.


The flaw of this analysis is in two place.

1) Assumption of independent event

To mulitple two chance together the two event needs to be completely independent of each other. But risk factor of SIDS is very likely to be common to all the childens in the family, including home enviroment, tabacco use, genetic , sleeping practices, and of course, physical abuse.

According to [this](http://www.jpeds.com/article/S0022-3476(05)81596-3/abstract) study of The journal of pediatrics, the risk of second childen die of SIDS is 5 times higher.

so the Chance should be much smaller, even before considering everything else

p = 1/8542 * 1/1708 = 1/14,593,152


2) ignore of base rate

Parents murder his/her own child is a rare event.


P(Guilty| 2D) = P(2D| Guity) * P (Guity)/P(2D)

The prior of P(Guity) should estimated.

>A news report suggests there are about 100 cases a year in the United States, estimated from surveys of prison populations. Since there are about 120 million adult women in the United States, and about half of them have children, that yields 1 in 600000 murdering their children in any given year

> The homicide rate in the US is about 4 times higher than that in the UK (judging by this table), so that gives us 1 in 2.4 million

P(Guity | 2D) = 1 * 1/2400000 / (1/2400000 + 1/14593152* ( 1 - 1/2400000)) = 85%

It is a high probability for sure, but not anything close to beyond reasonability doubt

___

___

Example: [Wreckage search of Air France 447](http://projecteuclid.org/euclid.ss/1399645730)

> In the early morning hours of June 1, 2009, during a flight from Rio de Janeiro to Paris, Air France Flight AF 447 disappeared during stormy weather over a remote part of the Atlantic carrying 228 passengers and crew to their deaths. After two years of unsuccessful search, a group of statistician reviewed the search data and using baysian analysis to came up with a probability density diagram of the possible location of the wreckage.

> The probability maps that resulted from this process were used to guide the 2011 search.On April 3, 2011, almost two years after the loss
of the aircraft, the underwater wreckage was located on the ocean bottom some 14,000 feet below the surface

![air france 447](https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/dlymy5xf.png)

The analysis approach for these satistician is to split the location of the wreckage to a Set of N particles( ie. a grid of cells ) and use the past search result to updated the posteriod probabilities.

>The computation of the posterior distribution involves two basic steps, (1) computation of the prior (before search) distribution and (2) computation
of the posterior distribution given the unsuccessful search.


>The prior distribution P on the location of the wreck was taken to be a mixture of three distributions, D1, D2 and D3. The distribution D1 is uniform
within the 40 NM circle( which is computed base on the last periodic GPS signal the plane sent) , and D2 is based on data from crashes that involved loss of control while a plane was at flight altitude. D3 is based on an analysis that drifted dead bodies found on the surface backward in time to possible crash locations.

>On the basis of discussions with analysts at the BEA, we decided on the following subjective weights for these distributions (scenarios), p1 = p2 = 0.35 and p3 = 0.3 so that

> P = p1D1 + p2D2 + p3D3.

___

example: [swine flu](http://www.maths.uq.edu.au/courses/MATH3104/Lectures/goodhill/bayes_solutions.pdf)

> You go to see the doctor about an ingrowing toenail. The doctor selects you at random to have
a blood test for swine flu, which for the purposes of this exercise we will say is currently suspected
to affect 1 in 10,000 people in Australia. The test is 99% accurate, in the sense that the probability
of a false positive is 1%. The probability of a false negative is zero. You test positive. What is the
new probability that you have swine flu?


P(SF|P) = P(P|SF)P(SF)/P(P) = 0.99 * ( 1/10000) /(1/10000)* 0.99 + (1-1/10000) * 0.01) = 0.0099

so not much to worry


> Now imagine that you went to a friend’s wedding in Mexico recently, and (for the purposes of this
exercise) it is know that 1 in 200 people who visited Mexico recently come back with swine flu.
Given the same test result as above, what should your revised estimate be for the probability you
have the disease?

with the new information of 1 in 200 people who visited Mexico recently come back with swine flu, the base rate of P(SF) changed from 10000 to 1/200

P(SF|P) = P(P|SF)P(SF)/P(P) = 0.99 * 1/200 /(1/200) * 0.99 + (1- 1/200) * 0.01) = 0.33

then you really should worried

How can you be sure ? probably take another test, if the 2nd test comeback positive, then


P(SF|P) = P(P|SF)P(SF)/P(P) = 0.99 * 0.33 /(0.33) * 0.99 + (1- 0.33) * 0.01) = 0.98





* [Use R to run Monte Carlo Simulation](https://www.countbayesie.com/blog/2015/3/3/6-amazing-trick-with-monte-carlo-simulations)

[R](https://www.r-project.org/) is **the** tools for statistical computing

A few Basic and useful function


* dbeta gives the density function, and you can visualize by useing

* C(0,1) sort of generic function and use it to descript anything
* sample() function can draw samples mutitple times


[Approximating the Binomial Distribution](https://www.countbayesie.com/blog/2015/3/3/6-amazing-trick-with-monte-carlo-simulations)

runs<-10000

Trial <- function()(
sum(c(0,1),runs,replace=T) > 3
)


~~~
curve(dbeta(x,10,110),col="green",add=TRUE);
~~~

* rbeta generates random deviates,

*


> https://github.com/WinVector/CampaignPlanner/blob/master/server.R

posterior Jeffreys prior 0.5,0.5 smoothing

ptab$observedSuccessRate = (successes+0.5)/(actions+1) # posterior Jeffreys prior 0.5,0.5 smoothing



curve(dbeta(x,10,100), col="green",add=TRUE)
curve(dbeta(x,15,100), col="red", add=TRUE)


~~~
runs <- 1000000
a.samples <- rbeta(runs,10,100)
b.samples <- rbeta(runs,15,100)
mc.p.value <- sum(a.samples > b.samples)/runs
mc.p.value
~~~

* How to use R to plot beta distribution ?

~~~
curve(dbeta(x,10,110),col="green",add=TRUE);
curve(dbeta(x,15,115),col="red",add=TRUE);

~~~


~~~
runs <- 10000000
a.samples <- rbeta(runs,10,100)
b.samples <- rbeta(runs,15,100)
mc.p.value <- sum(a.samples > b.samples)/runs
~~~


* How to use R to do A/B testing ?

~~~
n.trials <- 100000
prior.alpha <- 3
prior.beta <- 7
a.samples <- rbeta(n.trials,36+prior.alpha,114+prior.beta)
b.samples <- rbeta(n.trials,50+prior.alpha,100+prior.beta)
p.b_superior <- sum(b.samples > a.samples)/n.trials
~~~


More Course on R on montecarlo simulation

https://www.udemy.com/r-programming-for-simulation-and-monte-carlo-methods/



**Bonus**

[Bayesian Vesus Frequentist](http://www.win-vector.com/blog/2013/05/bayesian-and-frequentist-approaches-ask-the-right-question/)

The Core Attribution Theory of Baysian is Invert and Math, and the core Attribution Theory of Freqentist is Central Limit Theory, or more commonly, Binary CLT.

The major difference of Baysian VS CLT is [Baysian could have memories of prior similar events](http://conversionxl.com/bayesian-frequentist-ab-testing/), but CLT doesn't.

It also explained very well in this [stackexchange](http://stats.stackexchange.com/questions/58564/help-me-understand-bayesian-prior-and-posterior-distributions) thread
> If the prior is uninformative, the posterior is very much determined by the data (the posterior is data-driven)
If the prior is informative, the posterior is a mixture of the prior and the data


Example:

You went to see the doctor about your high blood pressure problem:

Freqentist Docotor:

>“If I prescribe drugX to all my hypertensive patients, will their blood pressure improve, on average?”

Baesian Doctor:

>“If I prescribe drugX to this patient, the one sitting in my examination room, will the patient’s blood pressure improve?” "






More Resources:

[more examples][28]

[More examples ][29]

[A visual Explaination of Bay's Themrom][30]

[a lecture on baysian](https://vimeo.com/6823148)

[count baesie](https://www.countbayesie.com/blog/2015/4/25/bayesian-ab-testing)



[Think Bayes From Greenteapress][31]

[1]: https://www.flickr.com/photos/chingster23/11937781733 "parallel-universe-visiongf-hd-wallpaper-84742"
[2]: https://www.flickr.com/photos/chingster23/11937781733
[3]: http://www.amazon.com/exec/obidos/ASIN/081297381X/
[4]: https://en.wikipedia.org/wiki/Confirmation_bias
[5]: https://en.wikipedia.org/wiki/Availability_heuristic
[6]: https://upload.wikimedia.org/math/d/3/c/d3c7c452b3d01f5415dd9bf15d2ab822.png
[7]: http://allendowney.blogspot.hk/2015/08/bayes-theorem-in-real-life.html
[8]: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.586.5246&rep=rep1&type=pdf
[9]: http://fire.nist.gov/bfrlpubs/fire89/PDF/f89012.pdf
[10]: http://www.nytimes.com/2011/08/07/books/review/the-theory-that-would-not-die-by-sharon-bertsch-mcgrayne-book-review.html?_r=0
[11]: http://www.cochrane.org/CD001877/BREASTCA_screening-for-breast-cancer-with-mammography
[12]: http://www.amazon.com/The-Signal-Noise-Predictions-Fail-but/dp/0143125087
[13]: http://www.yudkowsky.net/rational/bayes
[14]: http://blog.claymcleod.io/2016/02/02/Bayes-Theorem-for-Computer-Scientists/
[15]: https://www.quora.com/How-do-I-solve-the-Monty-Hall-Problem-using-Bayes-Theorem
[16]: https://dl.dropboxusercontent.com/spa/8a95omz6xkznrmw/k9wgpe73.png
[17]: https://youtu.be/4Lb-6rxZxx0
[18]: http://plato.stanford.edu/entries/bayes-theorem/supplement.html
[19]: https://lloydmelnick.com/2014/01/21/bayes-theorem-part-1-why-bayes-rule-is-the-key-to-good-decision-making-and-success/
[20]: http://www.amazon.com/Bayes-Rule-Tutorial-Introduction-Bayesian/dp/0956372848/ref=sr_1_1?ie=UTF8&qid=1391446909&sr=8-1&keywords=Bayes+rule
[21]: http://www.value-eng.org/knowledge_bank/attachments/Bayes%20Theorem%20in%20Decision%20Making.pdf
[22]: http://faculty.washington.edu/tamre/BayesTheorem.pdf
[23]: http://www.infoplease.com/ipa/A0884102.html
[24]: http://www.cdc.gov/tobacco/data_statistics/fact_sheets/tobacco_industry/cigars/
[25]: http://allendowney.blogspot.hk/2011/10/all-your-bayes-are-belong-to-us.html
[26]: http://www.cdc.gov/cancer/lung/statistics/
[27]: http://users.ecs.soton.ac.uk/jn2/teaching/bayes.pdf
[28]: http://www.rigb.org/christmaslectures08/html/activities/learning-from-probabilities.pdf
[29]: http://www.greenteapress.com/thinkbayes/html/thinkbayes006.html#toc41
[30]: https://www.countbayesie.com/blog/2015/2/18/bayes-theorem-with-lego
[31]: http://www.greenteapress.com/thinkbayes/thinkbayes.pdf


