# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

In this lab we applied the SOP and POS to a truth table (via KMap), as well as verified that it gives us the same outputs when fed into the tester. Following this, we uploaded it to the board to allow us to visually verify the outputs of the table. 

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
They are able to go across edges because of the wrap around effect. The edges of the map are functionally adjacent to each other. 

### Why are the names Sum of Products and Products of Sums?
They are named this way because that is how they are treated. In POS we have sum terms and in SOP we have product terms, and then we sum the product terms together for SOP and create a product of the sum terms in POS. This means we have a product of sum terms, or the POS, and a sum of product terms, or SOP.

### Open the test.v file – how are we able to check that the signals match using XOR?
We are able to check that they match with XOR functions because then we can isolate the instances where the outputs don’t align. If the LEDs for the naive and minterm are both on or both off, for example, then the XOR provides a zero, and we know that they match. If one is off while the other is on, however, then the XOR provides a one and we know that they must have different values to provide that output.
