# proof
A proof is a series of [[statement|statements]] chained together, each implied by the ladder. One needs to design a proof fitting to the desired outcome. Mostly one is given an [[assumption]], to begin with, and from which to start the reasoning. 

# proof techniques
![[direct-proof]]
![[indirect-proof]]
![[proof-by-contradiction]]

# Prooving equivalence
we can use the definition of a [[Logical-Syntax#Logical equivalence|Logical Equivalence]] as $(A\Rightarrow B)\land (A\Leftarrow B)$, then we use some #proof-pattern to [[proof|prove]] both directions.


$A$ |$B$  | $A\Rightarrow B$ | $\neg A\Rightarrow \neg B$ | $\neg(A\land \neg B)$ 
------------ | ------------  | ------------  | ------------  | ------------
0 | 1 |1 |1|1
1 | 0 |0 |0|0
1 | 1 |1 |1|1
0 | 0 |1 |1|1


# Examples
[[Proof-techniques ex.1]]
