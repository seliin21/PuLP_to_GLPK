# PuLP_to_GLPK

A problem written in PuLP. This problem was written with GLPK solver via "linprog".

"""
Joanne wants to buy x oranges and y peaches from the store. She must buy at 
least 5 oranges and the number of oranges must be less than twice the number 
of peaches. An orange weighs 150 grams and a peach weighs 100 grams. Joanne 
can carry not more than 3.6 kg of fruits home.

a) Write 3 inequalities to represent the information given above. b) Plot the 
inequalities on the Cartesian grid and show the region that satisfies all the 
inequalities. Label the region S. c) Oranges cost 0.70 and peaches cost 0.90 each. 
Find the maximum that Joanne can spend buying the fruits.

x oranges 150 0.7 y peaches 100 0.9 5 oranges x <= 2y

limit 3.6kg

x150 + y100 <= 3.6kg

5xo <=2yp a) at least 5 oranges: xo ≥ 5 oranges less than twice of peaches: xo < 2y 
not more than 3.6 kg: 150xo + 100yp ≤ 3600 ⇒ 3x + 2y ≤ 72

"""


