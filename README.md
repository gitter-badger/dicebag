dicebag
=======

[![Join the chat at https://gitter.im/lodestone/dicebag](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/lodestone/dicebag?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A dice rolling simulation and textual graphing library


This allows me to generate output as follows.

For a DiceSet:

```ruby
 <DiceSet:
   @set: [d8=>7, d10=>5, d12=>2, d8=>8, d6=>1]>

 > ds=DiceSet.new [d^8, d^10, d^12, d^8]
 > ds.graph

 > # OR
 > Dice.roll what: d^6, how_many: 4, keep: 3

```

```
 
 Running 100000 times, taking the top 3, the breakdown of results by value rolled are:
 …………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………………
     3   ( 0.00%)
     4   ( 0.01%)
     5   ( 0.03%)
     6   ( 0.08%)
     7   ( 0.21%) °
     8   ( 0.33%) °
     9   ( 0.69%) °°°
    10   ( 1.02%) °°°°°
    11   ( 1.61%) °°°°°°°°
    12   ( 2.34%) °°°°°°°°°°°
    13   ( 3.25%) °°°°°°°°°°°°°°°°
    14   ( 4.25%) °°°°°°°°°°°°°°°°°°°°°
    15   ( 5.42%) °°°°°°°°°°°°°°°°°°°°°°°°°°°
    16   ( 6.29%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    17   ( 7.41%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    18   ( 8.13%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    19   ( 8.74%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    20   ( 8.91%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    21   ( 8.68%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    22   ( 8.06%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    23   ( 6.98%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°°
    24   ( 5.78%) °°°°°°°°°°°°°°°°°°°°°°°°°°°°
    25   ( 4.41%) °°°°°°°°°°°°°°°°°°°°°°
    26   ( 3.18%) °°°°°°°°°°°°°°°
    27   ( 2.14%) °°°°°°°°°°
    28   ( 1.26%) °°°°°°
    29   ( 0.56%) °°
    30   ( 0.19%)

```

 Similar Anydice function here: [http://anydice.com/program/25a0](http://anydice.com/program/25a0)

