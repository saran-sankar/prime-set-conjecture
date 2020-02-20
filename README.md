# prime-set-conjecture
Computational attempt at verifying a conjecture related to prime numbers

<b>Conjecture</b>

<img src="http://latex.codecogs.com/svg.latex?Let\:\rho(c) = \prod{c_j}\:+1" border="0"/> where c_j are elements of set c, and F(N) be the set of all prime factors of N. 

<img src="http://latex.codecogs.com/svg.latex?Let\:E_i = E_{i-1} \cup \left\{z: z \in{F}(\rho(c)) \:\forall \mathnormal{c} \in{P}(E_{i-1})\right\} for\:i>1" border="0"/>

where P(E) is the power set of E. Let <img src="http://latex.codecogs.com/svg.latex?E_1 = \{2\}" border="0"/>

If p is a prime number, then <img src="http://latex.codecogs.com/svg.latex?\exists{i} \in\field{N} : p \in{E_i}}" border="0"/>
