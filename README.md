Download Link: https://assignmentchef.com/product/solved-suppose-you-are-given-a-set-p-of-integers-and-another-integer-x
<br>
1. Suppose you are given a set P of integers and another integer x. We wish to use a Θ(n2) algorithm to decide whether there are 3 integers in P and the sum of these three integers equals to x. Show your algorithm and indicate why its complexity is Θ(n2). (You can use pseudo code or by illustration only)

IF-EQUALS-SET(x, P)

for i ← 1 to P.size – 2

for j ← i + 1 to P.size – 1

if P[i] + P[j] + P[P.size] = x

return true

return false