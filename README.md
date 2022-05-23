# deck_of_card
> Example of deck_of_card.


This file will become your README and also the index of your documentation.

## Install

`pip3 install deck_of_card`

## How to use

`Card` is a class that represents a single card in a deck of cards. For examples:

```python
Card(suit=2, rank=11)
```




    Jack of Hearts



```python
c = Card(suit=1, rank=3)
assert str(c) == '3 of Diamonds'

c2 = Card(suit=2, rank=11)
assert str(c2) == 'Jack of Hearts'
```

You can do comparisons of cards, too!

```python
assert c2 > c
```
