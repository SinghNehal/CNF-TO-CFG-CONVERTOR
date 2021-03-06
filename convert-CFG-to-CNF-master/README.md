Convert CFG to CNF
==================
> Simple Java application that **convert Context Free Grammar to Chomsky Normal Form** with the knowledge of **Theory Of Computation**.

***



Introduction
============

**Context-Free Grammars (CFG)**, is a powerful method of describing context free languages that possess recursive structure, which makes them useful in a variety of applications. A language is context free if and only if pushdown automaton (PDA) recognizes it. Many useful languages are context-free, **including most programming languages, query languages, and markup languages**.  

However, CFG can be ambiguous or sometimes unambigious generates from the same language. A grammar is called **inherently ambiguous** if there is no equivalent umambiguous grammar to generates it. When working with context-free grammars CFG, it is often convenient to have them in simplified form. One of the simplest and most useful forms is called the **Chomsky normal form**.  

This application attempt to receive CFG as input and transformed into CNF grammar expressing as same language, all the **procedure and steps** are shown in the program. 

***

Getting Started
===============
Infrastructure Setup and Installation
-------------------------------------
2. Go to the cloned repository and change directory to the containing JAR files under out/artifacts/theory_of_computation_jar/.
```sh
$ cd out/artifacts/theory_of_computation_jar
``` 
3. Run the JAR file. 
```sh
$ java -jar theory-of-computation.jar
```
***

Software Resources
------------------
1. Linux Ubuntu 16.04.03 LTS 64-bit 
2. IntelliJ IDEA Ultimate 
3. Java 1.8.0_151 SE Runtime Environment 

