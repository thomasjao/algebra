### 求 $_{n}C_{r}$ 之最大值
$$_{n}C_{r}=\frac{n(n-1)(n-2)\dotsm(n-r+1)}{r!}=\frac{n}{1}\cdot\frac{n-1}{2}\dotsm\frac{n-2}{3}\dotsm\frac{n-r+1}{r} \tag{1}$$

在 (1) 中，當 $r$ 之數值逐漸增加時，等號右邊分數之個數亦隨之增加，此諸分數之數值，最初為 $n$，往後因分母之數值漸增，分子之數值漸減，故各個分數之數值亦漸減，若最後一個分數之數值較 1 為大，則 $_{n}C_{r}$ 之數值仍必繼續增加，僅增加之倍數逐漸減低而已。在最後一個分數之值減低至 1 或小於 1 時，$_{n}C_{r}$ 之數值愈小，當 $r=n$ 時，$_{n}C_{R}$ 即等於 1，故 $_{n}C_{r}$ 值之變動，其始是卜尸一人漸增大瓪至一定限度以後，即又逐漸減少。故在其變動過程中必有一最大值，但 $_{n}C_{r}$ 之值何時為最大？析明於下：

欲使 $_{n}C_{r}$ 之值最大，(1) 式最後之一個分數之數值，應不小於 1，即應 $\dfrac{n-r+1}{r}\geq 1$，$n-r+1\geq r$

即 $\dfrac{n+1}{2}\geq 1$