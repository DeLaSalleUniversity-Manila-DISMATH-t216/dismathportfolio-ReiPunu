# dismathportfolio-ReiPunu
Rei Carmina R. Punu 11123036
-------------------------------------------------------------------------------------------------------------------------------------
## WEEK 1 FIRST MEETING (JUNE 16, 2016)
</br>
Regarding last week's meeting, the first meeting was short and informative since we are all on our second take of the course. The 
few things we had a recap on the logic used in LOGICIR such as OR, AND, XOR and XNOR and many more. The first topic discussed was 
the Propositions, since I am not good in logic, I found it hard to absorb the its nature. After some time, it dawned on me  that
**Propositions** are  declarative sentences <i>whether true or false</i>. 
</br>
Finally, when our instructor asked me how does conditional logic work, I thought I remembered correctly. I told him that a con-
ditional logic works when the if the first statement is **False** and the second statement is **True**. After hearing the answers
of my coursemates, I got confused on whether my answer is correct. After our instructor explained that a conditional logic is
like a promise or a condition that must be fulfilled for it to be true.
</br>
  Let:</br> *p* be: You get a 100 on the final exam. </br>*q* be: I will give you a 4.0 on your final grade.
</br>
  Putting the above statement into conditional logic, '**If** you get a 100 on the final exam **then** I will give you a 4.0 on your final grade.'</br>
> If P is true then definitely Q is true. The condition is fulfilled therefore it's true.</br>
> If P is false then Q might be true. Though the condition is not fulfilled there are factors which may lead you to 4.0 on your final grade.</br>
>If P is false then Q is false The condition is not fufilled and there's a possibilty that the rest of your grades do not agree with the 4.0 requirement.</br>
>If P is true then Q is false. The condition is fulfilled yet you didn't get a 4.0 on your final grade which is a breach in the condition made.<br>
</br>
  Since, I am familiar with the previous logic statements such as:</br>
- Conjuction/And (p^q),
- Disjunction/Or(pvq),
- Negation/Not(¬p),
- Exclusive Disjunction/XOR(p⊕q),
- Conditional/If..then(p→q),
- Biconditional/If and Only If(p↔q),</br>
 I found the introduction as a review from my previous learnings during my first take of DISMATH. What I found fascinating was the play of words in the statements such as the usage of sufficient in conditional, necessary and sufficient in biconditional, and p whenever q. I was also fascinated with the play of IF AND ONLY IF statements, </br>
- *I have P if only if B* -wherein B is the condition, </br>
- *A if B* -wherein B is the condition and finally,</br>
- *A ony if B* -wherein A is the condition.</br> Also, since during my first take I was rarely in class, I was now introduced to converse(q→p), contrapositive(¬q→¬p) and inverse(¬p→¬q). One of the highlights of the meeeting includes when I remembered the rows needed in a truth table which is:
</br>
**# of Rows=2^n**
</br>
*where N is the number of variables present*
</br>
#Answer to Homework 1</br>

31. f. (p→q) → (q→p)</br>
NO. of Rows=2^2=4</br>
</br>

|      P       |        Q       |       P→Q     |     Q→P       | (P→Q) → (Q→P) |
|    :---:     |      :---:     |    :---:      |    :---:      |     :---:     |
|      T       |        T       |       T       |       T       |        T      |
|      T       |        F       |       F       |       T       |        T      |
|      F       |        T       |       T       |       F       |        F      |
|      F       |        F       |       T       |       T       |        T      |

</br>
35. a. (p→¬q)</br>
NO. of Rows=2^2=4</br>
</br>

|      P       |        Q       |       ¬Q      |     P→¬Q      | 
|    :---:     |      :---:     |    :---:      |    :---:      |    
|      T       |        T       |       F       |       F       |       
|      T       |        F       |       T       |       T       |        
|      F       |        T       |       F       |       T       |      
|      F       |        F       |       T       |       T       |

</br>
35. a. ¬p→(q→r)</br>
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
