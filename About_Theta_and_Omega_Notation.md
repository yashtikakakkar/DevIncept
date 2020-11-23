## What are Asymptotic Notations?

Whenever we write a program, we want it to work efficiently. The efficiency of one program is mostly based off of two parameters: 
1) Space Complexity 
2) Time Complexity

Two different algorithms may work similarly on a small number of input, but might have a drastic change when dealt with large number of inputs. So this understanding of how efficient a program is, is what is known as <b>Asymptotic Analysis</b> and the Notations that help to measure it are called <b>Asymptotic Notations</b>. Therefore, Asymptotic Notations can be defined as <i>"The mathematical notations used to describe the running time of an algorithm when the input tends towards a particular value or a limiting value"</i>.

There are mainly 3 types of Asymptotic Notations:
1) Big O Notation
2) Theta Notation
3) Omega Notation

In this markdown, we'll understand about Theta and Omega notation.

### Theta Notation

- It is used to represent average case time complexity.
- It represents the upper and the lower bound of the running time of an algorithm.
- For a function g(n), Θ(g(n)) is given by the relation:
<pre>
Θ(g(n)) = { f(n): there exist positive constants c1, c2 and n0
            such that 0 ≤ c1g(n) ≤ f(n) ≤ c2g(n) for all n ≥ n0 }
</pre>

### Omega Notation

