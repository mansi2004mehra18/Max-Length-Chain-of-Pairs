# Max-Length-Chain-of-Pairs

Max Length Chain of Pairs
You are given n pairs of numbers. In every pair, the first number is always smaller than the second number. A pair (c, d) can come after pair (a, b) if b < c.

Find the longest chain which can be formed from a given set of pairs.

Given Pairs:
(5, 24)
(39, 60)
(5, 28)
(27, 40)
(50, 90)

Answer:
ans = 3


Approach
1️⃣ Sort pairs (based on 2nd numbers)

2️⃣ 1st pair

cpp
Copy
Edit
for (int i = 1; i < n; i++) {  
    if (pairs->start > lastselected->end) {  
        ans++  
        last end update  
    }  
}