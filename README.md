# PuntoFijo

El método del punto fijo es un método iterativo que permite resolver sistemas de ecuaciones no necesariamente lineales. En particular se puede utilizar para determinar raíces de una función de la forma f(x), siempre y cuando se cumplan los criterios de convergencia.

Dada una ecuación f(x)=0, podemos transformarla, de alguna manera, en otra equivalente del tipo x=g(x) para alguna función g. En este caso se tiene que: a es raíz de f(x)=0 ↔ f(a)=0 ↔ a=g(a) ↔ a es raíz de x=g(x).

1. Se ubica la raíz de f(x) analizando la gráfica.

2. Se despeja de manera: x=g(x).

3. Obtenemos de x=g(x) su derivada g'(x).

4. Resolviendo la desigualdad -1 ≤ g'(x),  g'(x)≤ 1 obtenemos el rango de valores en los cuales esta el punto fijo llamado R.

5. Con R buscamos la raíz en g(x), es decir g(R)=R haciendo iteración de las operaciones.
