Mamy
$$
f_{n}(x)=(x^{2n-1}+3)x=x^{2n}+3x,\qquad x\in[0,1].
$$
Zbieżność punktowa

Dla ustalonego $x\in[0,1)$ mamy
$$
x^{2n}\to 0\quad\text{(bo }x^{2n}\le x^{2n}\text{ i }x<1\text{)},
$$
więc
$$
f_{n}(x)=x^{2n}+3x\to 3x.
$$
Natomiast gdy $x=1$, to
$$
f_{n}(1)=1+3=4.
$$
Zatem ciąg punktowo zbiega do funkcji
$$
f(x)=
\begin{cases}
3x,& x\in[0,1),\[1mm]
4,& x=1.
\end{cases}
$$
Zbieżność jednostajna

Dla $x\in[0,1)$ różnica wynosi
$$
|f_{n}(x)-f(x)|=|x^{2n}+3x-3x|=x^{2n}.
$$
Funkcja $x^{2n}$ rośnie wraz ze $x$ na przedziale $[0,1)$, czyli
$$
\sup_{x\in[0,1)}|f_{n}(x)-f(x)|=\lim_{x\to 1^-}x^{2n}=1.
$$
Przy $x=1$ mamy
$$
|f_{n}(1)-f(1)|=|4-4|=0.
$$
Zatem
$$
\sup_{x\in[0,1]}|f_{n}(x)-f(x)|=1\quad\text{dla każdego } n.
$$
W związku z tym zbieżność jednostajna na $[0,1]$ nie zachodzi.

Na dowolnym zbiorze ograniczonym leżącym w przedziale $[0,a]$, gdzie $a<1$, mamy
$$
\sup_{x\in[0,a]}|f_{n}(x)-f(x)|\le a^{2n}\to 0,
$$
czyli zbieżność jednostajna zachodzi na każdym takim przedziale.
Podsumowanie

Punktowo: $f_{n}(x)\to 3x$ dla $x\in[0,1)$ oraz $f_{n}(1)=4$, więc funkcja graniczna wynosi $$ f(x)= \begin{cases} 3x,& x\in[0,1),   4,& x=1. \end{cases} $$
    Jednostajnie: ciąg nie zbiega jednostajnie na $[0,1]$, lecz jednostajnie na każdym przedziale $[0,a]$, gdzie $a<1$.

