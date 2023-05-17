# Zeros de Funções Reais

Considere a equação:
$$\cot(x)=\frac{x^2-1}{2x}$$
<br/>

Comparação dos métodos aplicados para encontrar a menor raiz positiva.

|              | Bissecção      | Posição Falsa | Ponto Fixo  |      Netwon    |     Secante   |
|    :---:     |    :---:       |    :---:      |   :---:     |     :---:      |      :---:    |
| $\varphi$ ou $f'$   | - - -     |- - -    |$\varphi = \sqrt{2x\cot(x) + 1}$   | $f' = -\csc^2(x)- \frac{x^2+1}{2x^2}$ | - - -    |
| Dados iniciais: $x^{(0)}$ ou $[a,b]$ | $[1,2]$   | $[1,2]$ | $x^{(0)} = 1.2$ | $x^{(0)} = 1.2$ | $x^{(0)} = 1.2$ e $x^{(1)} = 1.4$  |
|Aproximação para a raiz: $\tilde{x}$ | 1.3065      | 1.3065     |   1.3065    | 1.3065       |     1.3065     |
|Valor de $f$ na aproximação: $f(\tilde{x})$| $1.7379\cdot 10^{-6}$ | $-1.1356\cdot 10^{-6}$ |$8.0465\cdot 10^{-6}$| $7.2292\cdot 10^{-6}$| $-9.3929\cdot 10^{-8}$ |
|Número de iterações| 16      | 6     |71   | 3     | 5     |





