#example #proof

## [[assumption]] 
> two positive Integers $a$ and $b$ if $a^2 < b^2$ , follows $a<b$

## two statements
> **$A: a^2 < b^2$ 
> $B: a<b$

# 1.[[direct-proof]]
## proof:
we assume A
$$a^2<b^2$$
With [[inequality|inequalities]] it is usefull, to reformulate the expression, so one side is negative. We substract $a^2$ on both sides. This produces:
$$ 0<b^2-a^2$$


with [[binommial-factorization]] follows:
$$ 0<(b-a)(b+a)$$
this shows that both $(b-a)$  and $(b+a)$ must be positive. $0<b+a$ follows. With this proporty we can divide with (b+a) without causing problems with inequality. we get$$0<(b-a) => a<b$$


# 2. [[indirect-proof]]
## proof 
we assume $\neg B$ $$b\geq a$$ we can multiply with $a$
$$ a^2 \geq ab$$
as with $b$ 
$$ab \geq b^2$$
this shows that
$$ a^2 \geq ab \geq b^2$$
from which $a^2 \geq b^2$ and also $\neg A$ which proves that $\neg B \implies \neg A$ 

# 3. [[proof-by-contradiction]]
## proof
we assume $\neg B$ and $A$ 
$$ b \geq a \text{ and } b^2<a^2$$
first we muliply $\neg B$ ( $b\geq a$ ) with $a$ and get $$ab\geq a^2$$ together with $A$ ($b^2<a^2$) we get
$$ab\geq a^2 > b^2$$
then we muliply $\neg B$ ( $b\geq a$ ) with $b$ and get $$b^2\geq ba$$
All of this, finnaly stiched together results in:$$ab\geq a^2 > b^2 \geq ba$$
witch implies that $ab>ba$ which is impossible. So we've prooven that $\neg B \land A \equiv \bot$ which proves that $A\implies B$ .