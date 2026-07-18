$$
1 + R_n = \prod\limits_{i=1}^n (1 + fr_i)
$$

$$
f \in (0,1], \ \ r_i \in (-\infty, 1]
$$

$$
1+R_n = \prod\limits_{i=1}^n (1 + fr_i) \Rightarrow \ln(1+R_n) = \ln\left(\prod\limits_{i=1}^n (1 + fr_i)\right) = \sum\limits_{i=1}^n (1+fr_i) \Rightarrow
$$

$$
1+R_n=e^{\displaystyle \sum\limits_{i=1}^n (1+fr_i)} \Rightarrow R_n = e^{\displaystyle \sum\limits_{i=1}^n (1+fr_i)} - 1
$$

$$
G(f) = \max_f \left(\sum\limits_{i=1}^n \ln(1+fr_i)\right)
$$

$$
\dfrac{dG(f)}{df} = 0 \Rightarrow \dfrac{d}{df}\ln(1+fr_i) = \dfrac{r_i}{1+fr_i} \Rightarrow G'(f)=\sum\limits_{i=1}^n \dfrac{r_i}{1+fr_i}
$$

$$
\sum\limits_{i=1}^n \dfrac{r_i}{1+f^*r_i} = 0
$$

$$
f^* = \argmax_f \dfrac{1}{n}\sum\limits_{i=1}^n\ln(1+fr_i)
$$

$$
r_g^*=\dfrac{1}{n}\sum\limits_{i=1}^n \ln(1+f^*r_i)
$$
