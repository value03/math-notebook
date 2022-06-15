#proof 
We need to prove this equality ![[complement rules raw1]]
we prove the first rule, the second one can be prooven analogiously. we write $A^c, B^c$ because the [[absolute complement]] if calculated from the same $M$. 
#  [[direct-proof]]:
![[de morgan proof rules raw1]]
We reformulate the definition of the left side into the right ride. with the definition of
[[contains|containment]] $A \subseteq B \Leftrightarrow \text{for all }x \in A \text{, } x\in B$, this means that $$\Rightarrow (A\cup B)^c \subseteq A^c\cap B^c$$ and $$\Rightarrow A^c\cap B^c  \subseteq  (A\cup B)^c$$
which is the definition of [[set equality]]: $$\Rightarrow A^c\cap B^c  =  (A\cup B)^c$$ $\Box$ 

