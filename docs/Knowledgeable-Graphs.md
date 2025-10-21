# **Grounding Principles**
## **Trust is Valuable**
## **Trust is Often Freely Given**
## **Trust, Once Lost, is Hard to Win Back**

# **Open Source/Free Software**
Open source software and free software ("[think of 'free speech,' not 'free beer.'](https://www.gnu.org/philosophy/free-sw.html)'") are two interrelated but diverging philosophies that can both be summed up by a key principle:

#### **Principle: Computers Should Empower and Serve People**
How the two differ is largely a matter of the purpose that this principle serves.

## Open Source vs Free Software
### Open Source
Open Source philosophy emphasizes practicality, aiming first and foremost to provide safe, reliable, and useful software to as many people as possible. Free Software critics of Open Source philosophy [say](https://www.gnu.org/philosophy/open-source-misses-the-point.html) that this approach leads to an overemphasis on the popularity of software and a lack of care when it comes to morality of programs, leaving it in a closer situation to nonfree software than ideal.

### Free Software
Free Software, on the other hand, emphasizes providing "freedoms" to users (leading to a confusing situation where Free Software is not always free in cost; thus, the "'free speech', not 'free beer'" mantra.) The Free Software Foundation defines a program as free software "[if [its] users have the four essential freedoms:](https://www.gnu.org/philosophy/free-sw.en.html)"

#### **0. The freedom to run the program as you wish, for any purpose.**
#### **1. The freedom to study how the program works, and change it so it does your computing as you wish**
* *Access to the source code is a precondition for this.*
#### **2. The freedom to redistribute copies so you can help others.**
#### **3. The freedom to distribute copies of your modified versions to others.**
* *This gives the whole community a chance to benefit from your changes.*

* *Access to the source code is a precondition for this.*

### FOSS - A Compromise
Due to the overall alignment of these two philosophies in practical terms, for many non-tech-geeks, there is not a need to distinguish between them. It is common to simply refer to the two as "FOSS" (Free and Open Source Software) for simplicity and to avoid the morality question that Free Software advocates bring up about their Open Source brethren.

# The Internet Protocol

## Development

### Licklider's Intergalactic Computer Network

[J.C.R. Licklider](https://en.wikipedia.org/wiki/J._C._R._Licklider), a  [was one of the first](https://www.internetsociety.org/internet/history-internet/brief-history-internet/) to describe social interactions and information sharing enabled through networking. He described his concept in a series of memos regarding an "Intergalactic Computer Network", which described "a globally interconnected set of computers through which everyone could quickly access data and programs from any site" (["A Brief History of the Internet"](https://www.internetsociety.org/internet/history-internet/brief-history-internet/#JCRL62)). This concept bears an obvious resemblance to the Internet of today, 

#### Tangent: [[Human]-Computer Symbiosis](https://en.wikipedia.org/wiki/Man–Computer_Symbiosis)
- [ ] TODO: Need to look into this, predates Intergalactic Computer Network by 2 years and fits even more directly in with a lot of my thoughts on Knowledgeable Graphs than the IGCN.



### RFCs
## Principle: You Should Control Your Data
## Charity Within the FOSS Framework
## Charity As PR/PR For Charity
### Vlogbrothers
#### Internet Optimism
#### Complexly
#### Good.Store
### Mozilla
***
# **Graphs**
## Notation Used in This Document
## Basics
### Directed Vs Undirected
### Trees
## Knowledge Graphs
## LLMs as Graphs
### Vectors
### Tokens
#### Token-Phoneme Overlap?
* Phonology as sub-syntax?
***
# **RDF**
## Structure: Subject, Predicate, Object
## RDF as a Graph
***
# **Proposal: Knowledgeable Graphs**
## Principle: Everything Is A Graph (Except for the Things That Aren't)
## Notation Used in This Document
## Most Basic Knowledgeable Graph
### Knowledge
### Knowledge Adding Mechanism
## Approved Knowledgeable Graph
### Approval Mechanism
#### An Approval Mechanism Is A Knowledge Adding Mechanism
***
# **Trust as a Currency**
## Rough Formula for Trust
## Charity As PR/PR For Charity, Redux

***

# Loose Notes
 

Graphs can be one to many (tree), many to many ("cloud", not official, need to find if there is a term), one to one , many to one. Any of those can contain further subdivisions; e.x. a one to one graph may actually go one to many to one. The more "manys" are involved (especially in the first position,) the harder it is to work on them, but the more information can be conveyed by them. RDF allows the same graph to be a tree and a cloud, gaining the computational advantages of a tree representation and the information richness of a cloud representation.

## Trust mechanism for black boxes
Entity 1 (ACME) has a black box for some process; Entity 2 has a knowledgeable agent that allegedly can check it. Entity 1 creates a hashed signature of their black box through some process that means that if you know some numbers a and b, it is easy to calculate c, and it is possible but difficult to verify that c is the next number in the sequence? think this could work maybe, have to think more.
