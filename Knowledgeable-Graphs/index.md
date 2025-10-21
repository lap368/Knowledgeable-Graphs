@import "/Grounding-Principles/index.md"

@import "/Foss/index.md"

@import "/Internet-Protocol/index.md"

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
