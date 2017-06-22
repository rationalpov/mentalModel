#
Mental Model: Backup System


### Discipline: Engineering

### Up Stream Lattice

* [Break Points][1]

### Down Stream Lattice

### Peer Lattice:

* [Margin of Safety][2]

## Introductions

What is a Backup System ?

From [Reliability Engineering for Electronic Design](https://www.amazon.com/gp/product/0824775716),

> Websters defines redundancy as needless repetition. In reliability engineering, however, redundancy is defined as the existence of **more than one means for accomplishing a given task**. Thus **all** of these means must fail before there is a system failure.

A Backup System is turning a Multiplicative System with a single break point into an additive system with two or more break points.

![computer backup power supplies](https://upload.wikimedia.org/wikipedia/commons/5/54/PC-Netzteil_%28redundant%29.jpg)

When the primary system break point fails, the input can flow through the backup system to the output.

If the primary system is a **simple** one, backup system is less useful, and can backfire, because added a needless path from input to output increases system complexity.

But if the primary system is a very **complex** one, and very hard to understand/predict/control it, backup system will provide great values there.

You can see Backup system it in Biological system more than any other discipline.

Samuel Arbesman explains in his book [Overcomplicated: Technology at the Limits of Comprehension](https://www.amazon.com/dp/1591847761/)

He argues Physics system is a simple one, but biology is much more complex system. mother nature doesn't care about individuals, only the species. thus individuals becomes the backup of his/her species.


>[B]iological systems are generally more complicated than those in physics. In physics, the components are often identical—think of a system of nothing but gas particles, for example, or a single monolithic material, like a diamond. Beyond that, the types of interactions can often be uniform throughout an entire system, such as satellites orbiting a planet.


> In biology, there are a huge number of types of components, such as the diversity of proteins in a cell or the distinct types of tissues within a single creature; when studying, say, the mating behaviour of blue whales, marine biologists may have to consider everything from their DNA to the temperature of the oceans. Not only is each component in a biological system distinctive, but it is also a lot harder to disentangle from the whole. For example, you can look at the nucleus of an amoeba and try to understand it on its own, but you generally need the rest of the organism to have a sense of how the nucleus fits into the operation of the amoeba, how it provides the core genetic information involved in the many functions of the entire cell.

Your body is one of the best example of redundancy.

The author of Black Swan and antifragile , NASSIM TALEB argues;

> she(Mother nature) likes redundancies. Look at the human body. We have two eyes, two lungs, two kidneys, even two brains (with the possible exception of company executives) - and each has more capacity than is needed ordinarily. So redundan­cy equals insurance, and the apparent inefficiencies are associated with the costs of maintain­ing these spare parts and the energy needed to keep them around in spite of their idleness.


## How to use this mental Model:

* Analyze the primary system:

* Is the primary system a multiplicative one or additive one ?
If the system if additive, by definition it doesn't need a backup system.

* if the primary system is a simple or complex one ?
**If the system is a simple one, other means of increasing reliability could be more effective( margin of safety )**

* Designing Backup System.

if the primary system is a complex and multiplicative one, adding backup system could greatly improve reliability:

* the backup system path need to be independent of the primary


### Conditions:

* The primary system is a complex & multiplicative system
* The backup system need to be independent of the primary path


### Predictions:

* when applied correctly, backup system will increase system reliability in expense of added cost and complexity.


### Examples:

[Fly by wire system](https://en.wikipedia.org/wiki/Fly-by-wire)

> Aircraft systems may be quadruplexed (four independent channels) to prevent loss of signals in the case of failure of one or even two channels. High performance aircraft that have fly-by-wire controls (also called CCVs or Control-Configured Vehicles) may be deliberately designed to have low or even negative stability in some flight regimes—the rapid-reacting CCV controls compensating for the lack of natural stability

> Some aircraft, the Panavia Tornado for example, retain a very basic hydro-mechanical backup system for limited flight control capability on losing electrical power; in the case of the Tornado this allows rudimentary control of the stabilators only for pitch and roll axis movements.[citation needed]


![fly by wire planes](https://upload.wikimedia.org/wikipedia/commons/a/a8/Avro_Arrow_rollout.jpg)






[1]: http://www.rationalpov.com/mental-model-engineeringbreak-point/
[2]: http://www.rationalpov.com/mental-model-engineering-margin-of-safety/
