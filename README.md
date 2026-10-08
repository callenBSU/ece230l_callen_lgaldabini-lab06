# Number Theory: Addition

In this lab you've learned the basics of number theory as it relates to addition.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

Names: Connor Allen, Logan Galdabini

## Lab Summary
For this lab, we did the boolean algebra to create a 1-bit adders and a 2-bit adder. We built
out KMaps and created equations to successfully implement these adders. We then demonstrated
this on the physical board.

## Lab Questions

### 1 - How might you add more than two bits together?
To add more than two bits together, we would need to chain together multiple adders into a 
ripple adder.

### 2 - What is the importance of the XOR gate in an adder?
XOR gates are useful in adders because it enforces the rule that when two 1's are added it 
results in a 0. AKA 1+1=0, with a carry out of 1. If it's 1+0 or 0+1, the output is gonna
be one, making it useful for adding binary numbers.

### 3 - What is the largest number a two bit adder can handle? What happens when you go over?
The largest number a two bit adder can do is 7. This is because the biggest number that 2 bits
can be is "11", or 3. Adding 2 together, 3+3, is 6. There is also carry in value, making the 
total sum 3+3+1=7. It will overflow if it goes over 7.
