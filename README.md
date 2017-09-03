# Generador Señales
Pequeño circuito diseñado en KiCad para generar señales cuadrada y triangular en fase. El circuito consta de cuatro partes:

1. **Un oscilador:** Empleamos el oscilador del circuito integrado CD4046 para generar una señal cuadrada de frecuencia variable. La frecuencia de las señales se puede ajustar mediante un potenciómetro o mediante una tensión externa al circuito.
2. **Un sumador:** para poder modificar el offset de la señal a nuestro gusto proponemos emplear un circuito sumador que utiliza como entrada la alimentación negativa de los amplificadores operacionales.
3. **Un integrador:** Tras dejar el offset de la señal cuadrada en 0V ya está preaparada para pasar por el integrador y convertirse en una señal triangular.
4. **Un divisor de tensión:** un simple instrumento para controlar la amplitud de la señal triangular.

Por comodidad en el montaje, la placa está diseñada para componentes through-hole.
