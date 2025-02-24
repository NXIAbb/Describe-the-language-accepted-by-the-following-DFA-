Download link :https://programming.engineering/product/describe-the-language-accepted-by-the-following-dfa/


# Describe-the-language-accepted-by-the-following-DFA-
Describe the language accepted by the following DFA :
Question 1. (10 points) Describe the language accepted by the following DFA :

0, 1

q1

0, 1

q2

0

start

q0

1

1

0

0

q4

q3

q5

1

0

Question 2. (10 points) Let w be a string over some alphabet Σ. Odd(w) refers to the string obtained by deleting symbols at all even positions of w. Example, if w = a1a2a3. . . . . . an, then odd(w) = a1a3a5……am, where m is n or n − 1 when m is odd or even respectively. For a language L ⊆ Σ∗, define

oddL = {odd(w) | w ∈ L}. Prove that if L is regular, then oddL is regular too.

Question 3. (10 points) Find the minimum-state finite automaton corresponding to the following DFA.

Show in details all the steps of minimization.

1

1

start

q0

0

q1

1

q2

0

q3

q4

1

q5

1

q6

q7

0

0

0

1

0

0

1

0

1

Name :

Roll Number :

Question 4. (10 points) For languages L1 and L2 over Σ, define

Mix(L1, L2) = {w ∈ Σ∗ | w = x1y1x2y2 . . . xkyk, where x1x2 . . . xk ∈ L1 and y1y2 . . . yk ∈ L2, each xi, yi ∈ Σ∗}.

Show that if L1 and L2 are regular then Mix(L1, L2) is also regular.

Question 5. (10 points) Design an NFA to accept the following language,

L = {w | w is ababn or aban where n ≥ 0}.

Question 6. (10 points) Let L be the language containing all strings over the alphabet {0, 1} that satisfy the property that in every string the difference between the number of 0’s and 1’s is less than two (e.g., 00101 will be in the language, while 010001 will not). Is this a regular language? Explain your answer.

Question 7. (10 points) Convert below NFA to its equivalent DFA.

a

b

b

c

a, b, c

a, b, c

a, b, c

cq3

start

q0

a, ϵ

q1

q2

c

Question 8. (10 points) Let L be the language L = {w ∈ {a, b}∗ | w contains an equal number of occur-rences of ab and ba}

Give a regular expression whose language is L.

Design a DFA/NFA/ϵ-NFA to accept L.

Question 9. (10 points) Use the DFA state-minimization procedure to convert this DFA to an equivalent DFA with the minimum possible number of states.

b

q2

a

q4

a

a

start

q1

b

q6

a, b

b

b

a

q3

b

q5

a

Question 10. (10 points) The language L = {uvvrw | u, v, w ∈ {a, b}+ } is regular. Here, vr is the reverse of v. Design a regular expression whose language is L. Convert the regular expression to an equivalent NFA.

Question 11. (10 points) Find out the equivalent regular expressions from the list given and show why they are equivalent :

(a + ba)∗(b + ϵ)

(a∗(ba)∗)∗(b + ϵ) + a∗(b + ϵ) + (ba)∗(b + ϵ)

(a + ba)(a + ba)∗(b + ϵ)

Name : Roll Number :

Question 12. (10 points) Design DFA for the following languages over {0, 1} :

The set of all strings such that every block of five consecutive symbols have at least two 0s.

The set of strings with an equal number of 0s and 1s such that each prefix has at most one more 0 than 1s and at most one more 1 than 0s.

Question 13. (10 points) Given that language L is regular, is the language L1/2 = {x | ∃y such that |x| = |y|, xy ∈ L} regular? If yes, give a formal proof.

Question 14. (10 points) Define L′ as the language consisting of the reverse of the strings in a language L. Give a formal proof that if L is regular, then L′ is regular.

Question 15. (10 points) Let L be the language over the alphabet {0, 1, 2} such that for any string in s ∈ L, s does not have two consecutive identical symbols, i.e. strings of L are any string in {0, 1, 2}∗ such that there is no occurrence of 00, no occurrence of 11, and no occurrence of 22. Design a DFA that accepts L.

Question 16. (10 points) Let Σ and ∆ be two alphabets and let h: Σ∗ → ∆∗. Extend h to be a function

from Σ∗ to ∆∗ as follows:

h(ϵ) = ϵ,

where w ∈ Σ∗, a ∈ Σ.

h(wa) = h(w)h(a)

(Such a function h is called a homomorphism.)

Now, for L ⊆ Σ∗,

h(L) = {h(w) ∈ ∆∗|w ∈ L}.

Also, for L ⊆ ∆∗,

h−1(L) = {w ∈ Σ∗|h(w) ∈ L}.

Prove that if L ⊆ Σ∗ is regular, then so is h(L).

Prove that if L ⊆ ∆∗ is regular, then so is h−1(L).
