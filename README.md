# Generatingfunctionology Cards in LaTeX

Herbert S. Wilf, in his book [Generatingfunctionolgy](http://www.amazon.com/generatingfunctionology-Third-Herbert-S-Wilf/dp/1568812795), uses cards as a great way to teach combinatorics. [cards.tex](cards.tex) is a LaTeX package that allows to create such cards in an easy way.

Here is an example followed by the self-explanatory LaTeX code.

![](Resources/Cards.png)

```latex
% First row
\Card[0.6]{n}{S}{ Picture }      \Deck{n}{S}{2}{ Picture }      \Deck{n}{S}{5}{ \Rabbit }      \Deck{n}{S}{a}{ Picture }

% Second row
\Card{n}{S}{ \Connected[0.7]{3} }      \Card{n}{S}{ \Connected[0.7]{n} }      \Card{n}{S}{\Cycle[0.7]{ undirected}{3} }      \Card{n}{S}{ \Cycle[0.7]{}{n} }
```

## Examples

In this section, using [cards.tex](cards.tex), we produce some cheat sheets of important topics contained in Wilf's book.

### Card Structures

![](Resources/Structures.png)

The LaTeX code to produce this table is contained in [Resources/Card Structures.tex](Resources/Card%20Structures.tex).

### The Main Counting Theorems

![](Resources/TheMainCountingTheorems.png)

The LaTeX code to produce this table is contained in [Resources/The Main Counting Theorems.tex](Resources/The%20Main%20Counting%20Theorems.tex).

### The Exponential Families

![](Resources/TheExponentialFamilies.png)

The LaTeX code to produce this table is contained in [Resources/The Exponential Families.tex](Resources/The%20Exponential%20Families.tex).

