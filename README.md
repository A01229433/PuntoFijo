# PuntoFijo

El método del punto fijo es un método iterativo que permite resolver sistemas de ecuaciones no necesariamente lineales. En particular se puede utilizar para determinar raíces de una función de la forma f(x), siempre y cuando se cumplan los criterios de convergencia.

Dada una ecuación f(x)=0, podemos transformarla, de alguna manera, en otra equivalente del tipo x=g(x) para alguna función g. En este caso se tiene que: a es raíz de f(x)=0 ↔ f(a)=0 ↔ a=g(a) ↔ a es raíz de x=g(x).

Si g es una función continua en [a, b] y g(x) ε[a, b] para todo x ε[a, b], entonces g tiene por lo menos un punto fijo en [a, b]. Si además, g’(x) existe para todo x ε[a, b], y |g’(x)| ≤ K < 1 para todo x ε[a, b], K constante, entonces g tiene un único punto fijo x ε[a, b]. La sucesión {xn}, con n definida, se encuentra mediante la fórmula de iteración:

![uno](http://aprendeenlinea.udea.edu.co/lms/moodle/filter/tex/pix.php/067a948324b522ef2f8be232207cbe98.gif)

El comportamiento de los esquemas de punto fijo puede variar ampliamente desde la divergencia, lenta convergencia, a la rápida convergencia.

La vía más simple (aunque no más general) de caracterizar el comportamiento de la iteración de punto fijo es considerar la derivada de g en la solución x*.

Si x* = g(x*) y |g’(x*)| < 1, entonces el esquema es localmente convergente. Es decir, existe un intervalo conteniendo x* tal que el correspondiente esquema iterativo es convergente si comienza dentro del intervalo.
