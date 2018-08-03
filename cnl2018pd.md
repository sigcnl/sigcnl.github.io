---
layout: plain
---
<style>
a { color: #176B1B; }
#main_content a:hover { color: #30a030; }
</style>
<p align="middle"><img src="cnl2018logo.png" width="250"/></p>
<p class="tabs" align="middle">
<a href="cnl2018.html">Main</a> | <a href="cnl2018speakers.html">Invited Speakers</a>  | <a href="cnl2018info.html">Info for Participants</a> | <a href="cnl2018SM.html">Social Media</a>
</p>
<p align="middle" style="font-size:200%">CNL 2018: Sixth International Workshop on Controlled Natural Language (CNL 2018)</p>
<p align="middle">27-28 August 2018 — Maynooth, Co Kildare (near Dublin), Ireland</p>

### Announced Posters/Demos

##### Leveraging Gherkin Controlled Natural Language for Global Product Information Development

Morgan O'Brien
 
Behavior Driven Development (BDD) has been growing as a development methodology for the last 10+ years and in that time, has matured as a way of designing software based on behaviors expected by customers. In McAfee, we aim to use the BDD process more and are expanding the usefulness of the MT technology in place. Within BDD, the Gherkin Controlled Natural Language (CNL) is a syntax and common terminology set that is used to describe a software or business process. It is directly linked to the test process and automation code for testing.

Given there exists this control on the language to describe our software using BDD and Gherkin, we seek to test if Machine Translation accuracy can reach a production level for publishing without the need for Post Editing and set some next steps to making this reality. Thus, enabling global product in-formation development to happen as part of the Software Development Life Cycle (SDLC).


##### Reasoning with Arithmetic in the Attempto Reasoner RACE
Norbert E. Fuchs

Attempto Controlled English (ACE) offers numbers that are positive and negative integers and positive and negative reals. Furthermore, there are arithmetic expressions built with the help of the operators +, -, *, /, ^ from numbers, variables, proper names and parenthesised subexpressions.

Boolean formulas are built from numbers, arithmetic expressions, proper names and variables with the help of the comparison operators =, \=, >, >=, < and =<. In RACE the copula is can be used as a synonym for the comparison operator =.

When reasoning with arithmetic expressions and formulas one encounters four phenomena that did not previously occur in the Attempto reasoner RACE.
+ While RACE fundamentally relies on syntactic matching of logical atoms, numerical expressions – like those in the formula **100/50 + 8 = 4 + 6** – cannot simply be matched, but must be numerically evaluated before being tested for equality.
+ While previously the order of processing did not matter, the evaluation of expressions–asinAisB+C. CisD-1. Bis2. Dis3.–must be delayed until all constituents have a value.
+ Even after evaluation remain problems of relating formulas, as can be seen in the deduction attempt X=1 \|- X>0.
+ As in standard logic arithmetical contradictions can involve negation, as for instance in A is 1. A is not 1. But there are new forms of contradictions not involving negation, for example A is 1. A is 2. or simply 1=2.

Using simple examples I will show in this demo how these problems can be solved so that RACE can effectively and efficiently reason with numbers, expressions and formulas.
