# Number Theory: Subtraction

## Names

1. Tassen Raihan Trima
2. Nusaiba Arefin

## Summary

In this lab, we learned how binary subtraction and number complements work using logic gates. We built a half subtractor using XOR for the difference and NOT and AND for the borrow. We also used full adders to implement one's complement addition with an end-around carry and created a two's complement converter by inverting the bits and adding one.

## Lab Questions

### 1 - Explain the differences between our Half Adder from last lab and the Half Subtractor from this lab.

The half adder adds two binary bits and produces a sum and carry. The half subtractor subtracts B from A and produces a difference and borrow. Both use XOR to calculate the output bit, but the half adder uses AND to calculate carry, while the half subtractor uses NOT and AND to calculate borrow.

### 2 - What about the end around carry of One’s Complement makes it hard to use and implement?

The end-around carry makes one's complement addition harder to implement because if there is a carry out of the most significant bit, it must be added back to the least significant bit. This makes the circuit more complicated.

### 3 - What is the edge case and problem with Two’s Complement number representation?

The edge case occurs with the most negative number, which cannot be converted to its positive equivalent using the same number of bits because the positive value is outside the representable range.
