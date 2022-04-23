# cAPI

## Motivation

*Concepts as APIs with Programmable Interfaces*

You may ask: isn't it superfluous to add "Programmable Interfaces" to the name? You may further suspect that the author, yours truly, decided first to name this tool "cAPI" and only came up with the phrase denoted by that acronym after-the-fact.

I will not offer clarity as to the latter possible suspicion, but I will answer the former question - posed by myself to myself on your behalf: no.

The reason is: this is a simple tool for recording and communicating concepts (or sets of related concepts).

The idea is to represent a concept as a little application. The source code of your cAPI *is a representation of a concept*  (thus, the commit history of a particular cAPI functions as the history of the evolution of your understanding of some concept). However, sometimes you may want to see the concept differently, or communicate the concept to some other party who prefers consuming information in a medium other than source code.

So, the source code is the *canonical representation of the concept* which can be represented and consumed through a concept's API! Since I don't know how many possible concepts exist in all possible human minds, I have decided that the API itself ought to be programmable so that you, as the concept author, can determine at conceptualization-time the appropriate interface(s) through which your concept is available for consumption.   

# Code Structure <> Concept isomorphism
Funnily enough, since the code is the canonical representation of the concept, a representation of a concept as provided by the app's API (such as a visualization as a set of primitive ideas and relations between them) is a visualization of the code's structure. 

This is a neat consequence of using a typed programming language to record and define a concept, as opposed to many knowledge management applications which provide an API by which data - stored in a database - is added, updated, deleted, and queried based on fully predefined data types. Since you can extend the types of the base `cAPI` library, and since a Concept is stored as source-code itself, it is an interesting way to get a more expressive form of knowledge management and expression.

Having said all of this, I honestly just think it's an easier way to store and explain ideas; regular personal knowledge management apps never seem to deliver all that I've needed. Something is always falling short. 
- Sometimes it's that it takes too long to modify one part. - Sometimes it isn't expressive enough and I have to shoehorn some relationship between information in an awkward way
- Sometimes it is *too* expressive and overwhelming, providing a large finite set of options to accomodate every use case that ends up polluting the experience with unnecessary noise.

With the cAPI approach, lack of expressiveness is easily solved by defining your own types. And the expressiveness will never be too overwhelming for your use case, since you're the one writing the code to express exactly as much as you require. Further, it's way faster to catch a poorly defined relationship that will cause refactors later on when you have a compiler to yell at you when you've violated some type constraints. Finally, it's way faster to write a few lines of code to encapsulate some expression you use often than it is to repeat the same sequence of point-and-click movements every ... single... time...
