# MOVIMIENTO ARMÓNICO SIMPLE
**Física III**  
**Ing. Willians Medina**  
*Puerto La Cruz, enero de 2005*

---

## <a id="indice"></a>Índice de Contenido

- [Movimiento de un objeto unido a un resorte](#movimiento-de-un-objeto-unido-a-un-resorte)
- [Partícula en movimiento armónico simple](#particula-en-movimiento-armonico-simple)
  - [Ejercicios](#ejercicios-1)
- [Posición, velocidad y aceleración en función del tiempo](#posicion-velocidad-y-aceleracion-en-funcion-del-tiempo)
  - [Casos según condiciones iniciales](#casos-segun-condiciones-iniciales)
  - [Ejercicios](#ejercicios-2)
- [Elongación máxima, velocidad máxima y aceleración máxima](#elongacion-maxima-velocidad-maxima-y-aceleracion-maxima)
  - [Ejercicios](#ejercicios-3)
- [Relación entre posición, velocidad y aceleración](#relacion-entre-posicion-velocidad-y-aceleracion)
  - [Ejercicios](#ejercicios-4)
- [Problemas que involucran gráficas](#problemas-que-involucran-graficas)
  - [Conocida la ecuación del movimiento](#conocida-la-ecuacion-del-movimiento)
- [El péndulo](#el-pendulo)
  - [Ejercicios](#ejercicios-5)
- [Circuitos LC](#circuitos-lc)
  - [Ejercicios](#ejercicios-6)
- [Energía del oscilador armónico simple](#energia-del-oscilador-armonico-simple)
  - [Ejercicios](#ejercicios-7)

---

## <a id="movimiento-de-un-objeto-unido-a-un-resorte"></a>Movimiento de un objeto unido a un resorte
*(Oscilaciones libres)*

Como un modelo de movimiento armónico simple considere un bloque de masa $m$ unido al extremo de un resorte, con el bloque libre de moverse sobre una superficie horizontal sin fricción. Cuando el resorte no está estirado ni comprimido, el bloque queda en reposo, en la posición llamada posición de equilibrio del sistema, que se identifica como $x = 0$. Se sabe por la experiencia que tal sistema oscila de atrás para adelante si se perturba desde su posición de equilibrio.

Se puede entender cualitativamente el movimiento oscilatorio del bloque al recordar primero que, cuando el bloque se desplaza a una posición $x$, el resorte ejerce sobre el bloque una fuerza que es proporcional a la posición y se conoce por la ley de Hooke:

$$\displaystyle F_s = -kx$$

A $F_s$ se le llama **fuerza restauradora** porque siempre se dirige hacia la posición de equilibrio y, en consecuencia, es opuesta al desplazamiento del bloque desde el equilibrio. Es decir, cuando el bloque se desplaza hacia la derecha de $x = 0$, la posición es positiva y la fuerza restauradora se dirige hacia la izquierda. Cuando el bloque está en $x = 0$, la fuerza en el bloque es cero. Cuando el bloque se desplaza a la izquierda de $x = 0$, la posición es negativa y la fuerza restauradora se dirige hacia la derecha.

Al aplicar la segunda ley de Newton al movimiento del bloque, se obtiene:

$$\displaystyle -k x = m a_x$$

$$\displaystyle a_x = -\frac{k}{m}x$$

Es decir, la aceleración del bloque es proporcional a su posición, y la dirección de la aceleración es opuesta a la dirección del desplazamiento del bloque desde el equilibrio. Se dice que los sistemas que se comportan de esta forma exhiben movimiento armónico simple. Un objeto se mueve con movimiento armónico simple siempre que su aceleración es proporcional a su posición y se dirige en sentido opuesto al desplazamiento desde el equilibrio.

Si el bloque se desplaza a una posición $x = A$ y se libera desde el reposo, su aceleración inicial es $-\frac{kA}{m}$. Cuando el bloque pasa a través de la posición de equilibrio $x = 0$, su aceleración es cero. En este instante, su rapidez es un máximo porque la aceleración cambia de signo. Por lo tanto el bloque continúa viajando hacia la izquierda del equilibrio con una aceleración positiva y al final llega a $x = -A$, momento en el que su aceleración es $+\frac{kA}{m}$ y su rapidez de nuevo es cero. El bloque termina un ciclo completo de su movimiento cuando regresa a la posición original y una vez más pasa por $x = 0$ con rapidez máxima. En consecuencia, el bloque oscila entre los puntos de retorno $x = \pm A$. En ausencia de fricción, este movimiento idealizado continuará por siempre porque la fuerza que ejerce el resorte es conservativa.

[Volver al Índice](#indice)

---

## <a id="particula-en-movimiento-armonico-simple"></a>Partícula en movimiento armónico simple

Por definición, $a = \frac{dv}{dt} = \frac{d^2x}{dt^2}$, por lo que la ecuación del movimiento se expresa como:

$$\displaystyle \frac{d^2x}{dt^2} = -\frac{k}{m}x$$

Si la relación $\frac{k}{m}$ se indica con el símbolo $\omega^2$, en tal caso:

$$\displaystyle \omega^2 = \frac{k}{m}$$

$$\displaystyle \omega = \sqrt{\frac{k}{m}}$$

Y la ecuación se escribe como:

$$\displaystyle \frac{d^2x}{dt^2} = -\omega^2 x$$

La solución general de esta ecuación diferencial de segundo orden es:

$$\displaystyle x(t) = c_1 \cos(\omega t) + c_2 \sin(\omega t)$$

donde $c_1$ y $c_2$ son constantes arbitrarias determinadas por las condiciones iniciales. Preferimos expresar esta solución en términos de una sola función trigonométrica:

$$\displaystyle x(t) = A \cos(\omega t + \phi)$$

Dado que el coseno de un ángulo no puede ser mayor que 1, el factor $A$ corresponde al desplazamiento máximo llamado **amplitud** de las oscilaciones. La masa oscilará continuamente entre las posiciones $x = A$ y $x = -A$.

El tiempo durante el cual se completa un ciclo se llama **periodo** ($T$) del movimiento:

$$\displaystyle T = \frac{2\pi}{\omega}$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$\displaystyle T = \frac{t}{n}$$

La **frecuencia** ($f$) de las oscilaciones es el número de oscilaciones por unidad de tiempo, e igual a la inversa del periodo:

$$\displaystyle f = \frac{1}{T} = \frac{\omega}{2\pi}$$

$$\displaystyle f = \frac{n}{t}$$

Una unidad para la frecuencia es denominada Hertz (Hz), equivalente al número de ciclos por segundo. El término $\omega$ se conoce como frecuencia angular natural del sistema y tiene unidades de rad/s.

### <a id="ejercicios-1"></a>EJERCICIOS

1. Una masa que pesa 4 libras se une a un resorte cuya constante es $16 \text{ lb/pie}$. ¿Cuál es el periodo del movimiento armónico simple?  
   *Respuesta: $T = 0.5539 \text{ s}$*

2. a) ¿Qué masa debes unir a un muelle de constante $k = 37 \text{ N/m}$ para que la frecuencia de oscilación del sistema sea de 1 Hz?  
   b) ¿Y para que sea de 4 Hz?  
   *Respuesta: a) $m = 0.9372 \text{ kg}$; b) $m = 0.0586 \text{ kg}$*

3. La punta de un diapasón efectúa 440 vibraciones completas en $0.500 \text{ s}$. Calcule a) la frecuencia angular y b) el periodo del movimiento.  
   *Respuesta: a) $\omega = 5529.20 \text{ rad/s}$; b) $T = 0.00114 \text{ s}$*

4. Una cuerda de piano produce un "la medio" vibrando primordialmente a 220 Hz.  
   a) Calcule su periodo y frecuencia angular.  
   b) Calcule el periodo y la frecuencia angular de una soprano que canta un "la alto", dos octavas más arriba, que es cuatro veces la frecuencia de la cuerda de piano.  
   *Respuesta: a) $T = 0.00455 \text{ s}, \omega = 1382.30 \text{ rad/s}$; b) $T = 0.00114 \text{ s}, \omega = 5529.20 \text{ rad/s}$*

5. Un oscilador armónico tiene una masa de $0.500 \text{ kg}$ y un resorte ideal con $k = 140 \text{ kg/s}^2$. Calcule: a) el periodo; b) la frecuencia; c) la frecuencia angular.  
   *Respuesta: a) $T = 0.3755 \text{ s}$; b) $f = 2.6631 \text{ Hz}$; c) $\omega = 16.73 \text{ rad/s}$*

6. Si un objeto en una superficie horizontal sin fricción se une a un resorte, se desplaza y después se suelta, oscilará. Si se desplaza $0.120 \text{ m}$ de su posición de equilibrio y se suelta con rapidez inicial cero, después de $0.800 \text{ s}$ su desplazamiento es de $0.120 \text{ m}$ en el lado opuesto, habiendo pasado por la posición de equilibrio una vez. Calcule: a) la amplitud; b) el periodo; c) la frecuencia.  
   *Respuesta: a) $A = 0.120 \text{ m}$; b) $T = 1.600 \text{ s}$; c) $f = 0.625 \text{ Hz}$*

7. Un resorte tiene una longitud de $30 \text{ cm}$. Si se cuelga de él un cuerpo de masa $250 \text{ g}$ y se le hace oscilar verticalmente, emplea 6 s en realizar 10 oscilaciones completas. Calcular a) la constante elástica del resorte y b) su longitud cuando dicho cuerpo está colgado de él, en reposo.  
   *Respuesta: a) $k = 27.42 \text{ N/m}$; b) $L = 38.94 \text{ cm}$*

8. Una pieza de una máquina está en MAS con frecuencia de $5.00 \text{ Hz}$ y amplitud de $1.80 \text{ cm}$. ¿Cuánto tarda la pieza en ir de $x = 0$ a $x = -1.80 \text{ cm}$?  
   *Respuesta: $t = 0.05 \text{ s}$*

9. Se crea un oscilador armónico usando un bloque de $0.600 \text{ kg}$, que se desliza sobre una superficie sin fricción y un resorte ideal con constante de fuerza desconocida. Se determina que el oscilador tiene un periodo de $0.150 \text{ s}$. Calcule la constante de fuerza del resorte.  
   *Respuesta: $k = 1052.76 \text{ N/m}$*

10. Una masa de 20 kilogramos se une a un resorte. Si la frecuencia del movimiento armónico simple es $2/\pi \text{ ciclos/s}$: a) ¿cuál es la constante del resorte $k$? b) ¿Cuál es la frecuencia del movimiento armónico simple si la masa original se reemplaza con una masa de 80 kilogramos?  
    *Respuesta: a) $k = 320 \text{ N/m}$; b) $f = 1/\pi \text{ Hz}$*

11. Un cuerpo de masa desconocida se une a un resorte lineal ideal con constante de fuerza de $120 \text{ kg/s}^2$. Se observa que vibra a una frecuencia de $6.00 \text{ Hz}$. Calcule: a) el periodo; b) la frecuencia angular; c) la masa del cuerpo.  
    *Respuesta: a) $T = 0.1667 \text{ s}$; b) $\omega = 37.70 \text{ rad/s}$; c) $m = 0.0844 \text{ kg}$*

12. Un cuerpo de $300 \text{ g}$ se encuentra unido al techo a través de un muelle. El peso del cuerpo hace que el muelle se deforme $6 \text{ cm}$. Determinar:  
    a) Cuál será la frecuencia angular de oscilación del cuerpo cuando se desplaza de su posición de equilibrio.  
    b) Qué ocurriría al variar la masa del cuerpo a $500 \text{ g}$.  
    c) Determina para este último caso la frecuencia angular y el periodo.  
    *Respuesta: a) $\omega = 12.79 \text{ rad/s}$; b) Al variar la masa cambia la frecuencia angular; c) $\omega = 9.90 \text{ rad/s}, T = 0.6346 \text{ s}$*

13. Un automóvil con una masa de $1300 \text{ kg}$ se construye de modo que su chasis está sostenido mediante cuatro amortiguadores. Cada amortiguador tiene una constante de fuerza de $20000 \text{ N/m}$. Dos personas que viajan en el automóvil tienen una masa combinada de $160 \text{ kg}$. Encuentre la frecuencia de vibración del automóvil después de que pasa sobre un bache en el camino. Suponga que el automóvil se detiene al lado del camino y las dos personas salen del auto. Una de ellas presiona hacia abajo el automóvil y lo libera de modo que oscile en la vertical. ¿La frecuencia de la oscilación es la misma que el valor recién calculado?  
    *Respuesta: $f = 1.18 \text{ Hz}$. Sin las personas: $f = 1.25 \text{ Hz}$*

14. Una silla de $42.5 \text{ kg}$ se sujeta a un resorte y se le permite oscilar. Cuando la silla está vacía, tarda $1.30 \text{ s}$ en efectuar una vibración completa. Cuando una persona se sienta en ella, sin tocar el piso con los pies, la silla tarda $2.54 \text{ s}$ en efectuar un ciclo. Calcule la masa de la persona.  
    *Respuesta: $m_p = 119.74 \text{ kg}$*

15. Un resorte se mantiene vertical apoyado en el suelo. Se coloca un cuerpo de masa $m$ en reposo sobre el resorte y se observa que éste se acorta $6 \text{ cm}$. Si empujamos ligeramente el cuerpo hacia abajo y lo soltamos: a) ¿cuál será la frecuencia de las oscilaciones? b) ¿y si la masa del cuerpo fuese $2m$?  
    *Respuesta: a) $f_1 = 2.04 \text{ Hz}$; b) $f_2 = 1.44 \text{ Hz}$*

[Volver al Índice](#indice)

---

## <a id="posicion-velocidad-y-aceleracion-en-funcion-del-tiempo"></a>Posición, velocidad y aceleración en función del tiempo

### Posición de la partícula
$$\displaystyle x(t) = A \cos(\omega t + \phi)$$

### Rapidez de la partícula
Diferenciando respecto al tiempo:

$$\displaystyle v(t) = \frac{dx}{dt}$$

$$\displaystyle v(t) = -\omega A \sin(\omega t + \phi)$$

### Aceleración de la partícula
$$\displaystyle a(t) = \frac{dv}{dt}$$

$$\displaystyle a(t) = -\omega^2 A \cos(\omega t + \phi)$$

### Convenio de signos para posición y velocidad inicial

- **Movimiento horizontal:**
  - Desplazamiento hacia la derecha (estirando el resorte): $x_0 > 0$.
  - Desplazamiento hacia la izquierda (comprimiendo el resorte): $x_0 < 0$.
  - Velocidad hacia la derecha: $v_0 > 0$; velocidad hacia la izquierda: $v_0 < 0$.
- **Movimiento vertical:**
  - Desplazamiento hacia abajo (estirando el resorte): $x_0 > 0$.
  - Desplazamiento hacia arriba (comprimiendo el resorte): $x_0 < 0$.
  - Velocidad hacia abajo: $v_0 > 0$; velocidad hacia arriba: $v_0 < 0$.

### Amplitud y ángulo de fase en función de condiciones iniciales
Para $t = 0$, $x = x_0$ y $v = v_0$:

$$\displaystyle x(t) = x_0 \cos(\omega t) + \frac{v_0}{\omega} \sin(\omega t)$$

Comparando con $x(t) = A \cos(\omega t + \phi) = A \cos\phi \cos(\omega t) - A \sin\phi \sin(\omega t)$:

$$\displaystyle A \cos\phi = x_0$$

$$\displaystyle -A \sin\phi = \frac{v_0}{\omega}$$

Elevando al cuadrado y sumando:

$$\displaystyle A = \sqrt{x_0^2 + \left(\frac{v_0}{\omega}\right)^2}$$

Dividiendo ambas ecuaciones para obtener la fase:

$$\displaystyle \tan\phi = -\frac{v_0}{\omega x_0}$$

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_0}{\omega x_0}\right)$$

### <a id="casos-segun-condiciones-iniciales"></a>Casos particulares para el ángulo de fase
- Posición inicial $x_0 = A$, Velocidad inicial $v_0 = 0 \Rightarrow \phi = 0$
- Posición inicial $x_0 = -A$, Velocidad inicial $v_0 = 0 \Rightarrow \phi = -\pi$
- Posición inicial $x_0 = 0$, Velocidad inicial $v_0 > 0 \Rightarrow \phi = -\pi/2$
- Posición inicial $x_0 = 0$, Velocidad inicial $v_0 < 0 \Rightarrow \phi = \pi/2$

*Criterio de elección para el ángulo de fase:*
El ángulo de fase debe cumplir que el signo de $\cos\phi$ coincida con el signo de $x_0$ y el signo de $\sin\phi$ coincida con el signo opuesto de $v_0$.

### <a id="ejercicios-2"></a>EJERCICIOS

16. Se hace oscilar verticalmente un cuerpo de masa $80 \text{ g}$ colgado de un muelle de constante elástica $2 \text{ N/m}$. Si la amplitud es de $10 \text{ cm}$, expresé la elongación en función del tiempo.  
    *Respuesta: $x(t) = 10 \cos(5t + \phi_0) \text{ cm}$*

17. La aceleración (en $\text{m/s}^2$) de un MAS es $a = -256 x$. Expresar esta aceleración en función del tiempo sabiendo que la amplitud es de $2.5 \text{ cm}$ y la constante de fase es nula.  
    *Respuesta: $a(t) = -6.4 \cos(16t) \text{ m/s}^2$*

18. Un cuerpo de masa $m = 2 \text{ kg}$ está unido a un muelle horizontal de constante $k = 5 \text{ N/m}$. El muelle se alarga $10 \text{ cm}$ y se suelta en $t = 0$. Hallar:  
    a) La frecuencia, el período, la amplitud y la ecuación del MAS.  
    b) Instantáneo en que pasa por primera vez por la posición de equilibrio.  
    *Respuesta: a) $f = 0.2515 \text{ Hz}, T = 3.98 \text{ s}, A = 0.1 \text{ m}, x(t) = 0.1 \cos(1.58t) \text{ m}$; b) $t = 0.994 \text{ s}$*

19. Una masa que pesa 20 libras alarga a un resorte 6 pulgadas. La masa se libera desde el reposo desde un punto 6 pulgadas abajo del equilibrio.  
    a) Encuentre la posición de la masa en $t = \pi/12, \pi/8, \pi/6, \pi/4, 9\pi/32 \text{ s}$.  
    b) ¿Cuál es la velocidad cuando $t = 3\pi/16 \text{ s}$ y su dirección?  
    c) ¿En qué tiempos pasa por el equilibrio?

20. Una partícula describe un MAS con $f = 10 \text{ Hz}$ y $A = 5 \text{ cm}$. Calcular:  
    a) Elongación y velocidad si para $t=0$, $x = +5 \text{ cm}$.  
    b) La aceleración para $t = 2 \text{ s}$.  
    *Respuesta: a) $x(t) = 0.05 \cos(20\pi t) \text{ m}, v(t) = -\pi \sin(20\pi t) \text{ m/s}$; b) $a(2\text{ s}) = 197.39 \text{ m/s}^2$*

21. Una partícula describe un MAS con $T = 2 \text{ s}$ y $A = 25 \text{ cm}$. Calcular:  
    a) Elongación y velocidad si para $t=0$, $x = +25 \text{ cm}$.  
    b) La aceleración para $t = 3 \text{ s}$.  
    *Respuesta: a) $x(t) = 0.25 \cos(\pi t) \text{ m}, v(t) = -0.25\pi \sin(\pi t) \text{ m/s}$; b) $a(3\text{ s}) = 2.47 \text{ m/s}^2$*

22. Estiramos un resorte $5 \text{ cm}$ y lo dejamos oscilar libremente completando una oscilación cada $0.2 \text{ s}$. Calcular:  
    a) La función de posición respecto al tiempo.  
    b) Velocidad y aceleración a los $15 \text{ s}$.  
    *Respuesta: a) $x(t) = 0.05 \cos(10\pi t) \text{ m}$; b) $v(15\text{ s}) = 0 \text{ m/s}, a(15\text{ s}) = -49.35 \text{ m/s}^2$*

23. Una partícula en MAS tarda $1 \text{ s}$ en ir de un extremo a otro de la trayectoria ($16 \text{ cm}$ de separación). Si inicia en un extremo, determine:  
    a) El periodo. b) La amplitud. c) La posición a los $1.5 \text{ s}$.  
    *Respuesta: a) $T = 2 \text{ s}$; b) $A = 0.08 \text{ m}$; c) $x(1.5\text{ s}) = 0 \text{ m}$*

24. Una masa puntual oscila en el eje OX con $f = 0.5 \text{ Hz}$ y $A = 30 \text{ cm}$. En $t=0$, $x = +30 \text{ cm}$. Determine:  
    a) Funciones de elongación, velocidad y aceleración.  
    b) Posición y velocidad en $t = 2.5 \text{ s}$.  
    c) Aceleración en $t = 3 \text{ s}$.  
    *Respuesta: a) $x(t) = 0.30 \cos(\pi t), v(t) = -0.30\pi \sin(\pi t), a(t) = -0.30\pi^2 \cos(\pi t)$; b) $x(2.5\text{ s}) = 0, v(2.5\text{ s}) = -0.94 \text{ m/s}$; c) $a(3\text{ s}) = +2.96 \text{ m/s}^2$*

25. Una partícula de $10 \text{ kg}$ sujeta a un muelle de $k = 10 \text{ N/m}$ se desplaza $0.5 \text{ m}$ del equilibrio y se suelta desde el reposo. Representar la elongación y la velocidad.  
    *Respuesta: $x(t) = 0.5 \cos(t) \text{ m}, v(t) = -0.5 \sin(t) \text{ m/s}$*

26. Objeto de $200 \text{ g}$ colgado de un muelle de $35 \text{ cm}$ hace que su nueva longitud sea $45 \text{ cm}$.  
    a) Determinar $k$.  
    b) Si se estira hasta $55 \text{ cm}$ y se suelta, determinar las fuerzas sobre el muelle.  
    *Respuesta: a) $k = 19.6 \text{ N/m}$; b) $P = 1.96 \text{ N}, F_t = -1.96 \text{ N}$*

27. Muelle vertical con $k = 400 \text{ N/m}$ oscila con $T = 1 \text{ s}$.  
    a) Masa necesaria.  
    b) Posición a $t = 1.5 \text{ s}$ si se eleva $4 \text{ cm}$ por encima del equilibrio y se suelta.  
    *Respuesta: a) $m = 10.13 \text{ kg}$; b) $x(1.5\text{ s}) = -0.04 \text{ m} = -A$*

28. MAS con $f = 5 \text{ Hz}$ y $A = 8 \text{ mm}$. En $t = 0$ está en el centro de vibración y va en sentido positivo. Expresar elongación, velocidad y aceleración.  
    *Respuesta: $x(t) = 8\times10^{-3} \cos(10\pi t - \pi/2) \text{ m}, v(t) = -8\times10^{-2}\pi \sin(10\pi t - \pi/2) \text{ m/s}, a(t) = -0.8\pi^2 \cos(10\pi t - \pi/2) \text{ m/s}^2$*

29. Bloque de $2.00 \text{ kg}$ con muelle $k = 300 \text{ N/m}$. En $t=0$, $x=0$ y $v = -12.00 \text{ m/s}$. Calcule: a) amplitud, b) ángulo de fase, c) función de posición. d) Repita si $v_0 = -4.00 \text{ m/s}$ y $x_0 = +0.200 \text{ m}$.  
    *Respuesta: a) $A = 0.97 \text{ m}$; b) $\phi = \pi/2 \text{ rad}$; c) $x(t) = 0.97 \cos(12.32t + \pi/2)$; d) $0.380 \text{ m}, 1.02 \text{ rad}, x(t) = 0.380 \cos(12.32t + 1.02)$*

30. Cuerpo en MAS tiene en $t=0$ aceleración nula y $v = -5 \mathbf{i} \text{ m/s}$, con $f = 0.25 \text{ Hz}$. Determine la ecuación de elongación.  
    *Respuesta: $x(t) = \frac{10}{\pi} \cos(0.5\pi t - 3\pi/2) \text{ m}$*

31. MAS con $T = 1.200 \text{ s}$ y $A = 0.600 \text{ m}$. En $t=0$, $x=0$. ¿A qué distancia está del equilibrio a los $t = 0.480 \text{ s}$?  
    *Respuesta: $x = -0.360 \text{ m}$*

32. Partícula tarda $0.50 \text{ s}$ en ir de un extremo al equilibrio (distantes $8.0 \text{ cm}$). En $t=0$, $x = 4.0 \text{ cm}$. Hallar la ecuación del movimiento.  
    *Respuesta: $x(t) = 0.08 \cos(\pi t - \pi/3) \text{ m}$*

33. Fuerza de $400 \text{ N}$ alarga resorte $2 \text{ m}$. Masa de $50 \text{ kg}$ se libera desde equilibrio con $v = 10 \text{ m/s}$ hacia arriba. Encuentre la ecuación del movimiento. Segundo resorte con $k = 20 \text{ N/m}$ paralela con masa de $20 \text{ kg}$ liberada con igual velocidad.  
    a) ¿Cuál masa tiene mayor amplitud? b) ¿Cuál se mueve más rápido en $t = \pi/4$? c) ¿En qué instantes están en la misma posición?

34. Masa de $24 \text{ lb}$ alarga resorte $4 \text{ in}$. Se libera desde el reposo $3 \text{ in}$ arriba de equilibrio. Encuentre la ecuación del movimiento. Repita si se libera desde equilibrio con velocidad descendente de $2 \text{ pie/s}$.

35. Masa de $32 \text{ lb}$ alarga resorte $2 \text{ ft}$. Determine a) amplitud y b) periodo si se libera $1 \text{ ft}$ arriba del equilibrio con velocidad ascendente de $2 \text{ ft/s}$. c) ¿Cuántos ciclos habrá completado a los $4\pi \text{ s}$?  
    *Respuesta: a) $A = 1.1175 \text{ ft}$; b) $T = 1.57 \text{ s}$; c) $n = 8 \text{ ciclos}$*

36. Aguja de coser oscila a $2.5 \text{ Hz}$. En $t=0$, $x = +1.1 \text{ cm}$ y $v = -15.00 \text{ cm/s}$.  
    a) Aceleración en $t=0$.  
    b) Ecuaciones de $x(t), v(t), a(t)$.  
    *Respuesta: a) $a = -2.71 \text{ m/s}^2$; b) $x(t) = 0.0146 \cos(15.71t + 0.7149) \text{ m}, v(t) = -0.23 \sin(15.71t + 0.7149) \text{ m/s}, a(t) = -3.61 \cos(15.71t + 0.7149) \text{ m/s}^2$*

37. Masa de $2 \text{ lb}$ alarga muelle $6 \text{ in}$. En $t=0$ se libera $8 \text{ in}$ debajo de equilibrio con velocidad ascendente de $4/3 \text{ pie/s}$. Determine la ecuación.  
    *Respuesta: $x(t) = 0.6871 \cos(8.02t + 0.2444) \text{ ft}$*

[Volver al Índice](#indice)

---

## <a id="elongacion-maxima-velocidad-maxima-y-aceleracion-maxima"></a>Elongación máxima, velocidad máxima y aceleración máxima

Los valores máximos de la magnitud de la velocidad y aceleración en un MAS son:

$$\displaystyle v_{\max} = \omega A$$

$$\displaystyle a_{\max} = \omega^2 A$$

Relación entre aceleración máxima y velocidad máxima:

$$\displaystyle a_{\max} = \omega v_{\max}$$

### <a id="ejercicios-3"></a>EJERCICIOS

38. Bloque de $200 \text{ g}$ con muelle de $k = 5.00 \text{ N/m}$ se desplaza $5.00 \text{ cm}$ y se libera del reposo.  
    a) Periodo del movimiento.  
    b) Rapidez máxima.  
    c) Aceleración máxima.  
    d) Expresiones en función del tiempo.  
    e) Si se libera con $v_0 = -0.100 \text{ m/s}$, ¿qué cambia?  
    *Respuesta: a) $T = 1.26 \text{ s}$; b) $v_{\max} = 0.25 \text{ m/s}$; c) $a_{\max} = 1.25 \text{ m/s}^2$; d) $x(t) = 0.05 \cos(5t) \text{ m}, v(t) = -0.25 \sin(5t) \text{ m/s}, a(t) = -1.25 \cos(5t) \text{ m/s}^2$; e) $x(t) = 0.0539 \cos(5t + 0.3805) \text{ m}$*

39. Cuerda de guitarra vibra a $440 \text{ Hz}$ con $A = 3.0 \text{ mm}$ y $\phi = 0$.  
    a) Ecuación de posición. b) $v_{\max}$ y $a_{\max}$. c) Ecuación del tirón (derivada de $a$) y valor máximo.  
    *Respuesta: a) $x(t) = 0.003 \cos(2764.60 t) \text{ m}$; b) $v_{\max} = 8.29 \text{ m/s}, a_{\max} = 22926.06 \text{ m/s}^2$*

40. Masa de $0.50 \text{ kg}$ en resorte de $k = 50 \text{ N/m}$. Desplazada $5.0 \text{ cm}$ y soltada:  
    a) Frecuencia. b) Velocidad al pasar por el equilibrio.  
    *Respuesta: a) $f = 1.59 \text{ Hz}$; b) $v_{\max} = 0.50 \text{ m/s}$*

41. Masa de $0.5 \text{ kg}$ estira resorte $0.2 \text{ cm}$ en reposo. Se estira y suelta. En $t=0$ pasa por el equilibrio a $10 \text{ m/s}$. Determine: a) $\omega$, b) $T$, c) $A$.  
    *Respuesta: a) $\omega = 70.04 \text{ rad/s}$; b) $T = 8.97\times10^{-2} \text{ s}$; c) $A = 0.1428 \text{ m}$*

42. Muelle se alarga $25 \text{ cm}$ con masa de $2.0 \text{ kg}$. Calcular frecuencia y velocidad máxima con $A = 5.0 \text{ cm}$ ($g = 9.8 \text{ m/s}^2$).  
    *Respuesta: $f = 1 \text{ Hz}, v_{\max} = 0.314 \text{ m/s}$*

43. Cuerpo de $20 \text{ g}$ pasa por el origen con $v = 10 \text{ m/s}$. Actúa la fuerza $F = -4x \text{ N}$. Calcular la distancia máxima que alcanza.  
    *Respuesta: $A = 0.707 \text{ m}$*

44. Partícula de $5.0 \text{ g}$ en MAS con $f = 25 \text{ Hz}$ y $A = 8 \text{ cm}$. Calcular: a) Periodo, b) Frecuencia angular, c) Velocidad máxima, d) Constante recuperadora.  
    *Respuesta: a) $T = 1/25 \text{ s}$; b) $\omega = 50\pi \text{ rad/s}$; c) $v_{\max} = 12.566 \text{ m/s}$; d) $k = 123.37 \text{ N/m}$*

45. Objeto oscila con $A = 5 \text{ cm}$ y $f = 3.3 \text{ Hz}$. Determine: a) Periodo, b) Velocidad y aceleración máxima.  
    *Respuesta: a) $T = 0.30 \text{ s}$; b) $v_{\max} = \pm 1.03 \text{ m/s}, a_{\max} = \pm 21.48 \text{ m/s}^2$*

46. Masa efectúa 2 oscilaciones por segundo con $A = 20 \text{ cm}$. Calcular: a) Velocidad máxima, b) Aceleración en los extremos.  
    *Respuesta: a) $v_{\max} = 2.51 \text{ m/s}$; b) $a_{\max} = -31.58 \text{ m/s}^2$*

47. Carga de barco oscila cada $4 \text{ s}$ con $A = 2 \text{ m}$. Calcule: a) Aceleración máxima, b) Posición a $t = 9 \text{ s}$ si parte en el extremo positivo.  
    *Respuesta: a) $a_{\max} = 4.93 \text{ m/s}^2$; b) $x(9\text{ s}) = 0 \text{ m}$*

48. Masa de $300 \text{ g}$ estira muelle $20 \text{ cm}$. Si se tira $5 \text{ cm}$ hacia abajo y se suelta, calcular período y velocidad máxima.  
    *Respuesta: $v_{\max} = \pm 35.3 \text{ cm/s}$*

49. Pistón de coche tiene una carrera de $20 \text{ cm}$ y el motor gira a $800 \text{ rpm}$. Calcular la velocidad máxima.  
    *Respuesta: $v_{\max} = \pm 8.38 \text{ m/s}$*

50. Partícula recorre $8 \text{ cm}$ de extremo a extremo y $a_{\max} = 48 \text{ m/s}^2$. Calcular: a) Frecuencia y periodo, b) Velocidad máxima.  
    *Respuesta: a) $f = 5.51 \text{ Hz}, T = 0.1815 \text{ s}$; b) $v_{\max} = 1.39 \text{ m/s}$*

51. ¿Qué amplitud y período debe tener un MAS para $v_{\max} = 30 \text{ cm/s}$ y $a_{\max} = 12 \text{ m/s}^2$? Expresar elongación.  
    *Respuesta: $x(t) = 0.0075 \cos(40t) \text{ m}$*

52. Máxima fuerza sobre un cuerpo de $50 \text{ g}$ con $f = 25 \text{ Hz}$ y $A = 2 \text{ mm}$.  
    *Respuesta: $F_{\max} = 2.47 \text{ N}$*

53. En un MAS, cuando $x = 0$, $v = 1 \text{ m/s}$, y cuando $x = 5 \text{ cm}$, $v = 0$. ¿Cuál es el período?  
    *Respuesta: $T = 0.3142 \text{ s}$*

54. Dinamómetro con graduación de $0$ a $20 \text{ N}$ en $10 \text{ cm}$. Se hace oscilar cuerpo de $800 \text{ g}$ con $A = 1 \text{ cm}$. Calcular frecuencia y aceleración máxima.  
    *Respuesta: $f = 2.52 \text{ Hz}, a_{\max} = 250 \text{ cm/s}^2$*

[Volver al Índice](#indice)

---

## <a id="relacion-entre-posicion-velocidad-y-aceleracion"></a>Relación entre posición, velocidad y aceleración

### Relación Posición - Aceleración
$$\displaystyle a = -\omega^2 x$$

### Relación Posición - Velocidad
Partiendo de $x(t) = A \cos(\omega t + \phi)$ y $v(t) = -\omega A \sin(\omega t + \phi)$, usando $\cos^2\theta + \sin^2\theta = 1$:

$$\displaystyle \left(\frac{x}{A}\right)^2 + \left(\frac{v}{\omega A}\right)^2 = 1$$

$$\displaystyle v^2 = \omega^2 (A^2 - x^2)$$

$$\displaystyle v = \omega \sqrt{A^2 - x^2}$$

### Relación Velocidad - Aceleración
Sustituyendo $x = -\frac{a}{\omega^2}$ en la ecuación de velocidad:

$$\displaystyle a^2 = \omega^2 (\omega^2 A^2 - v^2)$$

$$\displaystyle a = \omega \sqrt{\omega^2 A^2 - v^2}$$

### <a id="ejercicios-4"></a>EJERCICIOS

55. Objeto de $0.400 \text{ kg}$ en MAS tiene $a_x = -2.70 \text{ m/s}^2$ cuando $x = 0.300 \text{ m}$. ¿Cuánto tarda una oscilación?  
    *Respuesta: $T = 2.09 \text{ s}$*

56. Partícula en MAS con $A = 1 \text{ cm}$ y $f = 8 \text{ Hz}$. Calcular velocidad y aceleración cuando $x = 6 \text{ mm}$.  
    *Respuesta: $v = \pm 40.21 \text{ cm/s}, a = -15.16 \text{ cm/s}^2$*

57. MAS con $A = 4 \text{ cm}$. Cuando $x = \sqrt{7} \text{ cm}$, $v = 6\pi \text{ m/s}$. Calcular la frecuencia y la velocidad al pasar por el equilibrio.  
    *Respuesta: $f = 100 \text{ Hz}, v_{\max} = 25.1 \text{ m/s}$*

58. Cuerpo oscila desde $x = 5 \text{ cm}$ con $T = 0.4 \text{ s}$. Determinar:  
    a) Velocidad en el equilibrio. b) Velocidad y aceleración en $x = 3 \text{ cm}$. c) Aceleración en los extremos. d) Aceleración en $x = -1 \text{ cm}$.  
    *Respuesta: a) $v = \pm 25\pi \text{ cm/s}$; b) $v = \pm 20\pi \text{ cm/s}$; c) $a_{\max} = \pm 125\pi^2 \text{ cm/s}^2$; d) $a = \pm 25\pi^2 \text{ cm/s}^2$*

59. Cuerpo de $3 \text{ kg}$ oscila a razón de 15 oscilaciones/s. Calcular:  
    a) Constante elástica. b) Fuerza cuando $x = 4 \text{ cm}$.  
    *Respuesta: a) $k = 26647.9 \text{ N/m}$; b) $F = -1065.91 \text{ N}$*

[Volver al Índice](#indice)

---

## <a id="problemas-que-involucran-graficas"></a>Problemas que involucran gráficas

60. En una gráfica de desplazamiento vs tiempo de $x = 0.20 \text{ m}$ a $-0.20 \text{ m}$ completando ciclo a los $2.0 \text{ s}$. Calcule: a) frecuencia, b) amplitud, c) periodo.  
    *Respuesta: a) $f = 0.5 \text{ Hz}$; b) $A = 0.20 \text{ m}$; c) $T = 2.00 \text{ s}$*

61. Evaluar las afirmaciones para un gráfica con $A = 3$, $T = 4\text{ s}$:  
    a) Cada 2 s está en el mismo estado vibracional. (Falso)  
    b) Periodo vale 4 s. (Verdadero)  
    c) Amplitud de 6 m. (Falso)  
    d) Frecuencia de 0.25 Hz. (Verdadero)  
    e) Ecuación es $x(t) = 3\sin(\pi t / 2)$. (Falso)

62. Gráfica sinusoidal que pasa por $x = 5 \text{ m}$ en $t=1 \text{ s}$ y completa ciclo entre $-11$ y $13 \text{ s}$. Determinar $A, T, f, \omega, \phi$.  
    *Respuesta: $A = 5 \text{ m}, T = 12 \text{ s}, f = 0.0833 \text{ Hz}, \omega = 0.5236 \text{ rad/s}, \phi = -0.5236 \text{ rad}$*

63. Determinar las ecuaciones para dos ondas con $A = 4 \text{ cm}$ y desfase entre ambas.  
    *Respuesta: $x_1(t) = 4\cos(0.5\pi t + \pi/2), x_2(t) = 4\cos(0.5\pi t + \pi)$, Desfase: $\pi/2 \text{ rad}$*

64. Cuerpo de $150 \text{ g}$ oscila según una gráfica de $A = 9 \text{ cm}$ y $T = 2 \text{ s}$. Calcular:  
    a) Velocidad inicial. b) Aceleración a $t = 2 \text{ s}$ y $t = 6 \text{ s}$. c) Fuerza a $t = 0.5 \text{ s}$ y $t = 1.5 \text{ s}$.  
    *Respuesta: a) $v_0 = 0.2827 \text{ m/s}$; b) $a(2\text{ s}) = 0, a(6\text{ s}) = 0$; c) $F(0.5\text{ s}) = -0.1332 \text{ N}, F(1.5\text{ s}) = 0.1332 \text{ N}$*

---

### <a id="conocida-la-ecuacion-del-movimiento"></a>Conocida la ecuación del movimiento

65. MAS descrito por $x(t) = 2 \cos(30\pi t)$ ($\text{cm, s}$). Amplitud, frecuencia y periodo.  
    *Respuesta: $A = 2 \text{ cm}, f = 15 \text{ Hz}, T = 1/15 \text{ s}$*

66. Movimiento con $x(t) = 0.5 \sin(0.35\pi t + \pi/4) \text{ m}$. Determinar $v(t)$ y $a(t)$.  
    *Respuesta: $v(t) = 0.175\pi \cos(0.35\pi t + \pi/4) \text{ m/s}, a(t) = -0.06125\pi^2 \sin(0.35\pi t + \pi/4) \text{ m/s}^2$*

67. Calcular $v_{\max}$ y $a_{\max}$ para $x(t) = 5 \cos(4\pi t + \pi/6) \text{ cm}$.  
    *Respuesta: $v_{\max} = \pm 20\pi = 62.83 \text{ cm/s}, a_{\max} = \pm 789.57 \text{ cm/s}^2$*

68. Calcular $a_0$ y $v_0$ para $x(t) = 0.3 \cos(2t + \pi/6) \text{ cm}$.  
    *Respuesta: $a_0 = -5.92 \text{ cm/s}^2, v_0 = -0.3 \text{ cm/s}$*

69. Para $x(t) = 5 \cos(2t + \pi/6) \text{ cm}$. En $t=0$ halle posición, velocidad, aceleración, periodo y amplitud.  
    *Respuesta: $x(0) = 4.33 \text{ cm}, v(0) = -5 \text{ cm/s}, a(0) = -17.32 \text{ cm/s}^2, T = \pi \text{ s}, A = 5 \text{ cm}$*

70. $x(t) = 0.4 \cos(10\pi t - \pi/3) \text{ cm}$. Elongación, velocidad y aceleración a $t = 0 \text{ s}$ y $t = 1/120 \text{ s}$.  
    *Respuesta en $t=0$: $x = 0.2 \text{ cm}, v = 10.88 \text{ cm/s}, a = -197.39 \text{ cm/s}^2$*

71. $x = 4 \cos(10t) \text{ cm}$. Aceleración cuando $x = 3 \text{ cm}$.  
    *Respuesta: $a = -3 \text{ m/s}^2$*

72. $x = 6 \cos(5t + \phi_0) \text{ cm}$. Halle posición y velocidad inicial para $\phi_0 = 0, \pi/3, \pi/2, \pi$.

73. Discutir la diferencia entre $x(t) = A \sin t$ y $x(t) = A \cos t$.

74. Demostrar que $x(t) = 4 \sin(10t) + 3 \cos(10t) \text{ cm}$ representa un MAS calculando la aceleración.  
    *Respuesta: $a(t) = -100 x(t) \Rightarrow a = -\omega^2 x$, es un MAS.*

75. $v(t) = 3.60 \sin(4.71t - \pi/2) \text{ m/s}$. Calcule $T$, $A$ y $a_{\max}$.  
    *Respuesta: $T = 1.3340 \text{ s}, A = 0.7643 \text{ m}, a_{\max} = 16.956 \text{ m/s}^2$*

76. $v(t) = -0.36\pi \sin[\pi(24t + 1)] \text{ m/s}$. Frecuencia, amplitud y elongación.  
    *Respuesta: $f = 12 \text{ Hz}, A = 0.015 \text{ m}, x(t) = 0.015 \cos[\pi(24t + 1)] \text{ m}$*

[Volver al Índice](#indice)

---

## <a id="el-pendulo"></a>El péndulo

Un péndulo simple consta de una masa $m$ suspendida de una cuerda ligera de longitud $L$. La fuerza tangencial restauradora es:

$$\displaystyle F_t = -m g \sin\theta = m \frac{d^2s}{dt^2}$$

Como $s = L\theta$:

$$\displaystyle \frac{d^2\theta}{dt^2} = -\frac{g}{L} \sin\theta$$

Para ángulos pequeños ($\theta < 10^\circ \Rightarrow \sin\theta \approx \theta$ en rad):

$$\displaystyle \frac{d^2\theta}{dt^2} = -\frac{g}{L}\theta$$

La solución angular es:

$$\displaystyle \theta(t) = \theta_{\max} \cos(\omega t + \phi)$$

Frecuencia angular y período del péndulo:

$$\displaystyle \omega = \sqrt{\frac{g}{L}}$$

$$\displaystyle T = \frac{2\pi}{\omega} = 2\pi \sqrt{\frac{L}{g}}$$

### <a id="ejercicios-5"></a>EJERCICIOS

77. Longitud de péndulo para oscilar a $2 \text{ Hz}$.  
    *Respuesta: $L = 0.06 \text{ m}$*

78. Péndulo realiza 5 oscilaciones en $10 \text{ s}$. Calcule $L$ ($g = 9.81 \text{ m/s}^2$).  
    *Respuesta: $L = 0.99 \text{ m}$*

79. Explique cómo determinar experimentalmente $g$ mediante un péndulo y un cronómetro.

80. Longitud de un péndulo de $T = 2 \text{ s}$ en la Tierra ($9.8 \text{ m/s}^2$) y en la Luna ($1.6 \text{ m/s}^2$).  
    *Respuesta: $L_{\text{Tierra}} = 0.993 \text{ m}, L_{\text{Luna}} = 0.162 \text{ m}$*

81. Amplitud de oscilación de un péndulo de $70 \text{ cm}$ si el ángulo máximo es $6^\circ$.  
    *Respuesta: $A = 0.0728\pi \text{ m}$*

82. Gravedad de un planeta donde péndulo de $10 \text{ cm}$ tarda $0.634 \text{ s}$ en oscilar.  
    *Respuesta: $g = 9.8 \text{ m/s}^2$*

83. Niño en columpio de $A = 0.5 \text{ m}$ va y vuelve 5 veces en $10 \text{ s}$.  
    a) Frecuencia. b) Función de velocidad y $v_{\max}$.  
    *Respuesta: a) $f = 0.5 \text{ Hz}$; b) $v(t) = 0.5\pi \cos(\pi t) \text{ m/s}, v_{\max} = \pm 1.57 \text{ m/s}$*

84. Columpio de $L = 3.0 \text{ m}$ con $A = 0.5 \text{ m}$.  
    a) Periodo. b) Función de velocidad.  
    *Respuesta: a) $T = 3.47 \text{ s}$; b) $v(t) = 0.904 \cos(1.808t) \text{ m/s}$*

85. Péndulo de $224 \text{ cm}$.  
    a) Periodo. b) Si el recorrido total es $20 \text{ cm}$, halle posición a $t = 4.5 \text{ s}$.  
    *Respuesta: a) $T = 3.00 \text{ s}$; b) $x(4.5\text{ s}) = -0.1 \text{ m}$*

86. Relación entre los periodos de un péndulo en la Tierra y en la Luna ($g_L = g_T / 6$).  
    *Respuesta: $\frac{T_T}{T_L} = \frac{1}{\sqrt{6}}$*

[Volver al Índice](#indice)

---

## <a id="circuitos-lc"></a>Circuitos LC

En un circuito LC sin resistencia, la ley de voltajes de Kirchhoff establece:

$$\displaystyle V_L + V_C = 0$$

Como $V_L = L \frac{dI}{dt}$ y $V_C = \frac{Q}{C}$, con $I = \frac{dQ}{dt} \Rightarrow \frac{dI}{dt} = \frac{d^2Q}{dt^2}$:

$$\displaystyle L \frac{d^2Q}{dt^2} + \frac{1}{C}Q = 0$$

Dividiendo entre $L$:

$$\displaystyle \frac{d^2Q}{dt^2} + \frac{1}{LC}Q = 0$$

Definiendo la frecuencia angular natural $\omega = \frac{1}{\sqrt{LC}}$:

$$\displaystyle \frac{d^2Q}{dt^2} + \omega^2 Q = 0$$

Ecuación diferencial equivalente al oscilador armónico simple, cuya solución es:

$$\displaystyle Q(t) = Q_{\max} \cos(\omega t + \phi)$$

Corriente en función del tiempo:

$$\displaystyle I(t) = \frac{dQ}{dt} = -Q_{\max} \omega \sin(\omega t + \phi)$$

$$\displaystyle I_{\max} = Q_{\max} \omega$$

Voltaje en el capacitor e inductor:

$$\displaystyle V_C(t) = \frac{Q_{\max}}{C} \cos(\omega t + \phi)$$

$$\displaystyle V_L(t) = -\frac{Q_{\max}}{C} \cos(\omega t + \phi)$$

### <a id="ejercicios-6"></a>EJERCICIOS

87. Circuito con $V = 12.0 \text{ V}, L = 2.81 \text{ mH}, C = 9.00 \text{ pF}$.  
    a) Frecuencia de oscilación. b) Carga y corriente máximas.  
    *Respuesta: a) $f = 10^6 \text{ Hz}$; b) $Q_{\max} = 1.08\times10^{-10} \text{ C}, I_{\max} = 6.79\times10^{-4} \text{ A}$*

88. Capacitor de $1.00 \ \mu\text{F}$ cargado a $40.0 \text{ V}$ se descarga en inductor de $10.0 \text{ mH}$. Corriente máxima.  
    *Respuesta: $I_{\max} = 0.400 \text{ A}$*

89. Circuito LC con $L = 20.0 \text{ mH}, C = 0.500 \ \mu\text{F}$. Si $I_{\max} = 0.100 \text{ A}$, determine el voltaje máximo en el capacitor.  
    *Respuesta: $V_{\max} = 20.0 \text{ V}$*

90. Inductancia de $1.05 \ \mu\text{H}$. Capacitancia requerida para sintonizar a $6.30 \text{ MHz}$.  
    *Respuesta: $C = 608 \text{ pF}$*

91. Circuito con $L = 3.30 \text{ H}, C = 840 \text{ pF}, Q_0 = 105 \ \mu\text{C}$. En $t = 2.00 \text{ ms}$ halle: a) energía en el capacitor, b) energía en el inductor, c) energía total.  
    *Respuesta: a) $6.03 \text{ J}$; b) $0.529 \text{ J}$; c) $6.56 \text{ J}$*

[Volver al Índice](#indice)

---

## <a id="energia-del-oscilador-armonico-simple"></a>Energía del oscilador armónico simple

### Energía Cinética
$$\displaystyle K = \frac{1}{2}m v^2 = \frac{1}{2}m \omega^2 A^2 \sin^2(\omega t + \phi)$$

### Energía Potencial Elástica
$$\displaystyle U = \frac{1}{2}k x^2 = \frac{1}{2}k A^2 \cos^2(\omega t + \phi)$$

### Energía Mecánica Total
Como $m\omega^2 = k$:

$$\displaystyle E = K + U = \frac{1}{2}k A^2 [\sin^2(\omega t + \phi) + \cos^2(\omega t + \phi)]$$

$$\displaystyle E = \frac{1}{2}k A^2$$

La energía mecánica total es constante y proporcional al cuadrado de la amplitud.

### <a id="ejercicios-7"></a>EJERCICIOS

92. Masa $m = 500 \text{ g}$ unida a muelle $k = 200 \text{ N/m}$. Desplazada $2 \text{ cm}$ y lanzada con $v = 100 \text{ cm/s}$ a la izquierda.  
    a) Período. b) Ecuación del MAS. c) Velocidad y energías cuando $x = -3 \text{ cm}$ hacia la derecha.  
    *Respuesta: a) $T = \pi/10 \text{ s}$; b) $x(t) = 5.38 \cos(20t + 1.1903) \text{ cm}$; c) $v = 0.894 \text{ m/s}, E_c = 0.2 \text{ J}, E_p = 0.09 \text{ J}, E = 0.29 \text{ J}$*

93. Muelle con $k = 48 \text{ N/m}$ y $m = 0.75 \text{ kg}$, estirado $0.2 \text{ m}$.  
    a) Periodo. b) Ecuación de MAS. c) Tiempos donde $x = -0.1 \text{ m}$. d) Velocidad y energías en ese punto.  
    *Respuesta: a) $T = \pi/4 \text{ s}$; b) $x(t) = 0.2 \cos(8t) \text{ m}$; d) $v = -1.39 \text{ m/s}, E_c = 0.72 \text{ J}, E_p = 0.24 \text{ J}, E = 0.96 \text{ J}$*

94. Masa de $100 \text{ g}$ desplazada $2 \text{ cm}$ a la derecha y soltada con $f = 4 \text{ s}^{-1}$. Determine $x(t), v(t), T, a_{\max}, F_{\max}, k, K, U, E$ en el equilibrio.  
    *Respuesta: a) $x(t) = 0.02 \cos(8\pi t) \text{ m}, v(t) = -0.02\pi \sin(8\pi t) \text{ m/s}$; b) $T = 0.25 \text{ s}, a_{\max} = \pm 12.63 \text{ m/s}^2, F_{\max} = \pm 1.26 \text{ N}$*

95. Masa de $10 \text{ g}$ con $f = 4 \text{ Hz}, A = 6 \text{ mm}$ y $x_0 = A$. Ecuaciones, $T, a_{\max}, F_{\max}$ y energías.  
    *Respuesta: $x(t) = 0.006 \cos(8\pi t) \text{ m}, T = 0.25 \text{ s}, a_{\max} = 3.80 \text{ m/s}^2$*

96. Masa de $10 \text{ g}$ con $f = 4 \text{ Hz}, A = 6 \text{ mm}$ y $x_0 = 0$.  
    *Respuesta: $x(t) = 0.006 \cos(8\pi t - \pi/2) \text{ m}, k = 6.3 \text{ N/m}, E_c = 1.13\times10^{-4} \text{ J}$*

97. Muelle $k = 0.4 \text{ N/m}, m = 25 \text{ g}$. En $t=0$, $x_0 = 5 \text{ cm}, v_0 = -20\sqrt{3} \text{ cm/s}$.  
    a) Período. b) Ecuaciones. c) Paso por $x=0$. d) Energías en $x = -5 \text{ cm}$.  
    *Respuesta: a) $T = 1.5708 \text{ s}$; b) $x(t) = 0.1 \cos(4t + \pi/3) \text{ m}$; d) $E_p = 5\times10^{-4} \text{ J}, E_c = 1.5\times10^{-3} \text{ J}, E = 2\times10^{-3} \text{ J}$*

98. Masa $m = 200 \text{ g}, \omega = 100 \text{ rad/s}$. En $t=0$, $x_0 = -0.5\sqrt{3} \text{ cm}, v_0 = 50 \text{ cm/s}$. Ecuación del MAS, $k$ y $E$.  
    *Respuesta: a) $x(t) = 0.01 \cos(100t - 5\pi/6) \text{ m}$; b) $k = 2000 \text{ N/m}, E = 0.1 \text{ J}$*

99. Masa de $200 \text{ g}, \omega = 8.00 \text{ rad/s}$. En $t=0$, $x_0 = 4.0 \text{ cm}, v_0 = -20 \text{ cm/s}$. Amplitud, fase inicial, $k$ y $E$.  
    *Respuesta: a) $A = 0.0472 \text{ m}, \phi = 0.5586 \text{ rad}$; b) $k = 12.8 \text{ N/m}, E = 0.0142 \text{ J}$*

100. Masa de $300 \text{ g}, k = 43.2 \text{ N/m}, A = 20 \text{ cm}$. En $t=0$, $x = 10 \text{ cm}$ hacia la izquierda.  
     a) Ecuaciones. b) Instantes de paso por el origen. c) Energías.  
     *Respuesta: a) $x(t) = 0.20 \cos(12t + \pi/3) \text{ m}, v(t) = -2.4 \sin(12t + \pi/3) \text{ m/s}$; c) $E_M = 0.864 \text{ J}$*

101. Objeto de $30 \text{ g}, f = 5 \text{ Hz}, A = 10 \text{ cm}$. En $t=0$, $x_0 = A/2$. Ecuaciones, periodo, $a_{\max}, F_{\max}, k$ y energías en máxima elongación.

102. Cuerpo de $200 \text{ g}$ oscila según $x(t) = 0.1 \cos(25t)$ (SI).  
     a) Frecuencia. b) Constante recuperadora. c) Energías a $t = 0.5 \text{ s}$. d) Conclusión de posición.  
     *Respuesta: a) $f = 3.98 \text{ Hz}$; b) $k = 125 \text{ N/m}$; c) $E_c = 2.75\times10^{-3} \text{ J}, E_p = 0.6225 \text{ J}$; d) Está cerca de un extremo.*

103. Masa $100 \text{ g}, x(t) = A \sin(\omega t + 3\pi/5)$. Realiza 3 ciclos en $6 \text{ s}$. En $t=0$, $x = +3 \text{ cm}$.  
     a) $\omega$ y $A$. b) Posición, velocidad y aceleración a $t = 0.4 \text{ s}$. c) $k$ y energías en $t = 0.4 \text{ s}$.  
     *Respuesta: a) $\omega = \pi \text{ rad/s}, A = 0.031 \text{ m}$; b) $x(0.4) = 0, v(0.4) = -0.097 \text{ m/s}$; c) $k = 0.986 \text{ N/m}, E_c = 4.70\times10^{-4} \text{ J}$*

104. Oscilador 1: $m_1 = 40 \text{ g}, T_1 = 2 \text{ s}$. Oscilador 2 con muelle idéntico.  
     a) $m_2$ para que $f_2 = 2 f_1$.  
     b) Energía potencial máxima si $A = 10 \text{ cm}$.  
     c) Velocidad máxima de cada masa.  
     *Respuesta: a) $m_2 = 0.010 \text{ kg} = 10 \text{ g}$*

105. Determinar la relación $E_c / E_p$ cuando la posición es $x = A/3$.  
     *Respuesta: $\frac{E_c}{E_p} = 8$*

[Volver al Índice](#indice)