# prime-set-conjecture
Computational attempt at verifying a number theoretic conjecture of mine

<b>Conjecture</b>

<img src="http://latex.codecogs.com/svg.latex?Let\:\rho(C) = \prod_{c_j \in{C}}{c_j}\:+1" border="0"/>, and F(N) be the set of all prime factors of N. 

<img src="http://latex.codecogs.com/svg.latex?Let\:E_i = E_{i-1} \cup \left\{z: z \in{F}(\rho(C)) \:\forall{C} \in{P}(E_{i-1})\right\} for\:i>1" border="0"/>

where P(E) is the power set of E. Let <img src="http://latex.codecogs.com/svg.latex?E_1 = \{2\}" border="0"/>

If p is a prime number, then <img src="http://latex.codecogs.com/svg.latex?\exists{i} \in\field{N} : p \in{E_i}}" border="0"/>

<b>Goal</b>

Computationally verify this conjecture for as many of the first consecutive prime numbers as possible. 

<b>Results of a first attempt</b>

Within 5 iterations, the conjecture was verified for the first 2595 prime numbers. 

