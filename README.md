# DISMATHportfolio-ReiPunu
-Rei Carmina R. Punu 11123036
-------------------------------------------------------------------------------------------------------------------------------------
## WEEK 1 FIRST MEETING (JUNE 16, 2016)
</br>
Regarding last week's meeting, the first meeting was short and informative since we are all on our second take of the course. The 
few things we had a recap on the logic used in LOGICIR such as OR, AND, XOR and XNOR and many more. The first topic discussed was 
the Propositions, since I am not good in logic, I found it hard to absorb the its nature. After some time, it dawned on me  that
**Propositions** are  declarative sentences <i>whether true or false</i>. </br>
</br>
Finally, when our instructor asked me how does conditional logic work, I thought I remembered correctly. I told him that a con-
ditional logic works when the if the first statement is **False** and the second statement is **True**. After hearing the answers
of my coursemates, I got confused on whether my answer is correct. After our instructor explained that a conditional logic is
like a promise or a condition that must be fulfilled for it to be true.</br>
</br>
  Let:</br> *p* be: You get a 100 on the final exam. </br>*q* be: I will give you a 4.0 on your final grade.
</br></br>
  Putting the above statement into conditional logic, '**If** you get a 100 on the final exam **then** I will give you a 4.0 on your final grade.'</br></br>
1. If P is true then definitely Q is true. The condition is fulfilled therefore it's true.</br>
2. If P is false then Q might be true. Though the condition is not fulfilled there are factors which may lead you to 4.0 on your final grade.</br>
3. If P is false then Q is false The condition is not fufilled and there's a possibilty that the rest of your grades do not agree with the 4.0 requirement.</br>
4. If P is true then Q is false. The condition is fulfilled yet you didn't get a 4.0 on your final grade which is a breach in the condition made.<br>
</br></br>
  Since, I am familiar with the previous logic statements such as:</br></br>
- Conjuction/And (p^q),
- Disjunction/Or(pvq),
- Negation/Not(¬p),
- Exclusive Disjunction/XOR(p⊕q),
- Conditional/If..then(p→q),
- Biconditional/If and Only If(p↔q),</br></br>
 I found the introduction as a review from my previous learnings during my first take of DISMATH. What I found fascinating was the play of words in the statements such as the usage of sufficient in conditional, necessary and sufficient in biconditional, and p whenever q. I was also fascinated with the play of IF AND ONLY IF statements, </br></br>
- *I have P if only if B* -wherein B is the condition, </br>
- *A if B* -wherein B is the condition and finally,</br>
- *A ony if B* -wherein A is the condition.</br></br> Also, since during my first take I was rarely in class, I was now introduced to converse(q→p), contrapositive(¬q→¬p) and inverse(¬p→¬q). One of the highlights of the meeeting includes when I remembered the rows needed in a truth table which is:</br>
</br></br>
**# of Rows=2^n**
</br>
*where N is the number of variables present*</br></br>
-------------------------------------------------------------------------------------------------------------------------------------
</br>
Answer to Homework 1</br>

*31. f. (p→q) → (q→p)</br>
NO. of Rows=2^2=4</br>
</br>

|      P       |        Q       |       P→Q     |     Q→P       | (P→Q) → (Q→P) |
|    :---:     |      :---:     |    :---:      |    :---:      |     :---:     |
|      T       |        T       |       T       |       T       |        T      |
|      T       |        F       |       F       |       T       |        T      |
|      F       |        T       |       T       |       F       |        F      |
|      F       |        F       |       T       |       T       |        T      |

</br>
*35. a. (p→¬q)</br>
NO. of Rows=2^2=4</br>
</br>

|      P       |        Q       |       ¬Q      |     P→¬Q      | 
|    :---:     |      :---:     |    :---:      |    :---:      |    
|      T       |        T       |       F       |       F       |       
|      T       |        F       |       T       |       T       |        
|      F       |        T       |       F       |       T       |      
|      F       |        F       |       T       |       T       |

</br>
*35. a. ¬p→(q→r)</br>
NO. of Rows=2^3=8</br>
</br>

|      P       |      ¬P        |       Q       |     R         |       Q→R     |  ¬P→(Q→R)   |
|    :---:     |      :---:     |    :---:      |    :---:      |    :---:      |    :---:    |   
|      T       |        F       |       T       |       T       |       T       |     T       |        
|      T       |        F       |       F       |       T       |       T       |     T       |         
|      F       |        T       |       T       |       T       |       T       |     T       |        
|      F       |        T       |       F       |       T       |       T       |     T       |
|      T       |        F       |       T       |       F       |       F       |     T       |        
|      T       |        F       |       F       |       F       |       T       |     T       |
|      F       |        T       |       T       |       F       |       F       |     F       |        
|      F       |        T       |       F       |       F       |       T       |     T       |

</br>
-------------------------------------------------------------------------------------------------------------------------------
## WEEK 2 (JUNE 21 & 23, 2016)
*TUESDAY MEETING*</br>
-Compound propositions served as the appetizers for us senses. Compound propositions have three kinds namely:</br>
	1. Tautology - always *true*</br>
	2. Contradiction - always *false*</br>
	3. Contingency - *neither* a tautology nor a contradiction</br>
</br>
**note** that when dealing with contradiction, one must use the logical operand *AND* and *OR* when dealing with tautology.</br>
</br>
-*Logical Equivalences* were also taught and proven through the use of truth table. Table is seen below:</br>


|       EQUIVALENCE                                                  |                          Name                    | 
|            :---:                                                   |                   :---:                          |    
|   p ∧ T ≡ p   </br>p ∨ F ≡ p                                       |                        Identity Laws             |       
| p ∨ T ≡ T   </br> p ∧ F ≡ F                                        |                           Domination Laws        |      
|     p ∨ p ≡ p</br>  p ∧ p ≡ p                                      |                          Idempotent Laws         |        
|    ¬(¬p) ≡ p                                                       |                      Double negation law         | 
|  p ∨ q ≡ q ∨ p </br> p ∧ q ≡ q ∧ p                                 |                Commutative laws                  |    
|(p ∨ q) ∨ r ≡ p ∨ (q ∨ r)</br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)            |        Associative laws                          |       
|p ∨ (q ∧ r) ≡ (p ∨ q) ∧ (p ∨ r)</br>p ∧ (q ∨ r) ≡ (p ∧ q) ∨ (p ∧ r) |             Distributive laws                    |        
|  ¬(p ∧ q) ≡ ¬p ∨¬q </br> ¬(p ∨ q) ≡ ¬p ∧¬q                         |         De Morgan’s laws                         |      
| p ∨ (p ∧ q) ≡ p    </br>          p ∧ (p ∨ q) ≡ p                  |                  Absorption laws                 |
|  p ∨¬p ≡ T   </br>  p ∧¬p ≡ F                                      |     Negation Laws                                | 
</br>
Another equivalence used is the **Implication Law**:</br>
|       EQUIVALENCE                                                  |                          Name                    | 
|            :---:                                                   |                   :---:                          |    
|  p → q ≡ ¬p ∨ q                                                    |                    Implication Law               |
</br>
-We are then assigned to read about **nested quantifiers**</br>

</br></br>
*THURSDAY MEETING*</br>
-*Quantifiers* exist when a preposition results with certain truth values. There are two types of quantifiers, *universal and existential* quantifiers. A *universal quantifier* denotes that **P(x) for all values of x in the domain** wherein **∀xP(x)** is symbol. When P(x) is false, the statement is called a *counterexample* of ∀xP(x). The second quantifier, *existential quantifier* indicates that **There exists an elemeneet x in the domain such that P(x)** </br>

-When negating quamtified expressions, the *De Morgan's laws* for quantifiers is used. </br>
|       Negation |    Equivalent     |     NEGATION IS TRUE                   |    NEGATION IS FALSE                             | 
|      :---:     |      :---:        |     :---:                              |                   :---:                          |    
|   ¬∃xP(x)      |  ∀x¬P(x)          | For every x, P(x) is false.            |        There is an x for which P(x) is true.     |
|   ¬∀xP(x)      | ∃x¬P(x)           |  There is an x for which P(x) is true  |             P(x) is true for every x.            |
</br>

-*Rules of inference* were introduced to validate whether arguments were correct with the absence of truth tables.</br>
</br>
|Rule of Inference           |Tautology                     |Name                  |
|:---:                       |:---:                         |:---:                 |
|p</br>p → q</br>∴ q         | (p ∧ (p → q)) → q            |Modus ponens          |
|¬q</br>p → q</br>∴ ¬p       |(¬q ∧ (p → q))→¬p             |Modus tollens         |
|p → q</br>q → r</br>∴ p → r |((p → q) ∧ (q → r)) → (p → r) |Hypothetical syllogism|
|p ∨ q</br>¬p</br>∴ q        |((p ∨ q)∧¬p) → q              |Disjunctive syllogism |
|p</br>∴ p ∨ q               |p → (p ∨ q)                   |Addition              |
|p ∧ q</br>∴ p               |(p ∧ q) → p                   |Simplification        |
|p</br>q</br>∴ p ∧ q         |((p) ∧ (q)) → (p ∧ q)         |Conjunction           |
|p ∨ q</br>¬p ∨ r</br>∴ q ∨ r|((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r)|Resolution            |
</br></br>

*ANSWER TO QUESTIONS*</br>
Truth Table of Absorption:</br>
p ∨ (p ∧ q) ≡ p <br>
*ANSWER:*</br>
|P    |Q    |P^Q  |Pv(P^Q)|
|:---:|:---:|:---:|:---:  |
|T    |T    |T    |      T|
|T    |F    |F    |T      |
|F    |T    |F    |F      |
|F    |F    |F    |F      |

</br>

Example for Dinjunctive Syllogism </br>
*ANSWER:* Meer is cute or cuddly. Meer is not cute. Therefore, Meer is cuddly.</br>
*EXERCISES FOR 1.3*</br>

15. Determine whether (¬q ∧ (p → q))→¬p is a tautology.</br>

  | p     | q     | ¬p    | p → q | (¬p ∧ (p → q))| (¬p ∧ (p → q)) → ¬p |
  | :---: | :---: | :---: | :---: | :---:         | :---:               |
  | T     | T     | F     | T     | F             | T                   |
  | T     | F     | F     | F     | F             | T                   |
  | F     | T     | T     | T     | T             | T                   |
  | F     | F     | T     | T     | T             | T                   |
  
17. Show that ¬(p ↔ q) and p ↔¬q are logically equivalent.

  | p     | q     | p ↔ q |¬(p ↔q)| ¬q    | p ↔ ¬q |
  | :---: | :---: | :---: | :---: | :---: | :---:  |
  | T     | T     | T     | F     | F     | F      |
  | T     | F     | F     | T     | T     | T      |
  | F     | T     | F     | T     | F     | T      |
  | F     | F     | T     | F     | T     | F      |
  </br>
  *Special Exercise:*</br>

  | (p ∧ (p → q)) → q          | Logical Equivalence              |
  | :---:                      | :---:                            |
  | p ∧ (¬p V q)) → q          | Implication Equivalence          |
  | (p ∧ ¬p) V (p ∧ q) → q     | Distribution Law                 |
  | F V (p ∧ q) → q            | Negation Law                     |
  | (F V p) ∧ (F V q) → q      | Distribution Law                 |
  | (p ∧ q) → q                | Identity Law                     |
  | ¬(p ∧ q) V q               | Implication Equivalence          |
  | ¬p V (¬q V q)              | De Morgan's</br>Associative Law  |
  | ¬p V T ≡ T                 | Domination Law                   |
</br>
*EXERCISES FOR 1.4*</br>
5. Let P(x) be the statement “x spends more than five hours every weekday in class,” where the domain for x consists of all students. Express each of these quantifications in English.</br>
c) ∃x ¬P(x)</br>
*ANSWER:* There exist a student in class who doesn't spend 5 hours in class.</br>
9. Let P(x) be the statement “x can speak Russian” and let Q(x) be the statement “x knows the computer language C++.” Express each of these sentences in terms of P(x), Q(x), quantifiers, and logical connectives. The domain for quantifiers consists of all students at your school.</br>
b)There is a student at your school who can speak Russian but who doesn’t know C++.</br.
*ANSWER:* ∃x(P(x) ∧ ¬Q(x))</br>
11. Let P(x) be the statement “x = x2.” If the domain consists of the integers, what are these truth values?</br>
e. ∃xP(x)</br>
*ANSWER:*TRUE</br>
15. Determine the truth value of each of these statements if the domain for all variables consists of all integers.</br>
e. ∃n(n*n = 2) </br>
*ANSWER:*FALSE</br>
17. Suppose that the domain of the propositional function P(x) consists of the integers 0, 1, 2, 3, and 4. Write out each of these propositions using disjunctions, conjunctions, and negations.</br>
e. ¬∃xP(x) </br>
*ANSWER:*¬(P (0) ∨ P(1) ∨ P(2) ∨ P(3) ∨ P(4)) f) ¬(P (0) ∧ P(1) ∧ P(2) ∧ P(3) ∧ P(4))</br>
Disjunction & Negation</br>

*EXERCISES FOR 1.5*</br>
3. Let Q(x, y) be the statement “x has sent an e-mail message to y,” where the domain for both x and y consists of all students in your class. Express each of these quantifications in English.
b. b) ∃x∀yQ(x, y)
*ANSWER:* There exist a student who sent a message to the whole class.</br>

