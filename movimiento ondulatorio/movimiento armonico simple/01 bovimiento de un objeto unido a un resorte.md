# Movimiento Oscilatorio

## Índice

* [1. Movimiento de un objeto unido a un resorte](#sec-1)

* [2. Movimiento armónico simple (Oscilaciones libres)](#sec-2)

* [3. Partícula en movimiento armónico simple](#sec-3)

* [4. Ejercicios (Parte 1)](#sec-4)

* [5. Posición, velocidad y aceleración en función del tiempo](#sec-5)

  * [5.1 Posición de la partícula en función del tiempo](#sec-5-1)

  * [5.2 Rapidez de la partícula en función del tiempo](#sec-5-2)

  * [5.3 Aceleración de la partícula en función del tiempo](#sec-5-3)

  * [5.4 Convenio de signos para la posición inicial y la velocidad inicial](#sec-5-4)

  * [5.5 Amplitud y ángulo de fase en función de las condiciones iniciales](#sec-5-5)

  * [5.6 Casos particulares para el ángulo de fase](#sec-5-6)

  * [5.7 Ajustes en el ángulo de fase (Caso general)](#sec-5-7)

* [6. Ejercicios (Parte 2)](#sec-6)

* [7. Elongación máxima, velocidad máxima y aceleración máxima](#sec-7)

* [8. Ejercicios (Parte 3)](#sec-8)

* [9. Relación entre posición, velocidad y aceleración](#sec-9)

  * [9.1 Relación entre la posición y la aceleración en el M.A.S.](#sec-9-1)

  * [9.2 Relación entre la posición y la velocidad en el M.A.S.](#sec-9-2)

  * [9.3 Relación entre la velocidad y la aceleración en el M.A.S.](#sec-9-3)

* [10. Ejercicios (Parte 4)](#sec-10)

* [11. Problemas que involucran gráficas](#sec-11)

* [12. Conocida la ecuación del movimiento](#sec-12)

## 1. Movimiento de un objeto unido a un resorte \[Volver al Índice\]

Como un modelo de movimiento armónico simple considere un bloque de masa $m$ unido al extremo de un resorte, con el bloque libre de moverse sobre una superficie horizontal sin fricción (figura 1). Cuando el resorte no está estirado ni comprimido, el bloque queda en reposo, en la posición llamada posición de equilibrio del sistema, que se identifica como $x = 0$. Se sabe por la experiencia que tal sistema oscila de atrás para adelante si se perturba desde su posición de equilibrio.

Se puede entender cualitativamente el movimiento oscilatorio del bloque en la figura 1 al recordar primero que, cuando el bloque se desplaza a una posición $x$, el resorte ejerce sobre el bloque una fuerza que es proporcional a la posición y se conoce por la ley de Hooke:

$$
\displaystyle F_{s} = -kx \quad \color{red}{(1)}
$$

A $F_{s}$ se le llama fuerza restauradora porque siempre se dirige hacia la posición de equilibrio y, en consecuencia, es opuesta al desplazamiento del bloque desde el equilibrio. Es decir, cuando el bloque se desplaza hacia la derecha de $x = 0$ en la figura 1a, la posición es positiva y la fuerza restauradora se dirige hacia la izquierda. La figura 1b muestra al bloque en $x = 0$, donde la fuerza en el bloque es cero. Cuando el bloque se desplaza a la izquierda de $x = 0$, como en la figura 1c, la posición es negativa y la fuerza restauradora se dirige hacia la derecha.

## 2. Movimiento armónico simple (Oscilaciones libres) \[Volver al Índice\]

Al aplicar la segunda ley de Newton al movimiento del bloque, con la ecuación $\color{red}{(1)}$ que proporciona la fuerza neta en la dirección $x$, se obtiene

$$
\displaystyle -kx = m a_{x}
$$

$$
\displaystyle a_{x} = -\frac{k}{m}x \quad \color{red}{(2)}
$$

Es decir, la aceleración del bloque es proporcional a su posición, y la dirección de la aceleración es opuesta a la dirección del desplazamiento del bloque desde el equilibrio. Se dice que los sistemas que se comportan de esta forma exhiben movimiento armónico simple. Un objeto se mueve con movimiento armónico simple siempre que su aceleración es proporcional a su posición y se dirige en sentido opuesto al desplazamiento desde el equilibrio.

Si el bloque en la figura 1 se desplaza a una posición $x = A$ y se libera desde el reposo, su aceleración inicial es $-kA/m$. Cuando el bloque pasa a través de la posición de equilibrio $x = 0$, su aceleración es cero. En este instante, su rapidez es un máximo porque la aceleración cambia de signo. Por lo tanto el bloque continúa viajando hacia la izquierda del equilibrio con una aceleración positiva y al final llega a $x = -A$, momento en el que su aceleración es $+kA/m$ y su rapidez de nuevo es cero. El bloque termina un ciclo completo de su movimiento cuando regresa a la posición original y una vez más pasa por $x = 0$ con rapidez máxima. En consecuencia, el bloque oscila entre los puntos de retorno $x = \pm A$. En ausencia de fricción, este movimiento idealizado continuará por siempre porque la fuerza que ejerce el resorte es conservativa. Por lo general, los sistemas reales están sujetos a fricción, así que no oscilan por siempre.

## 3. Partícula en movimiento armónico simple \[Volver al Índice\]

El movimiento descrito en la sección precedente se presenta con tanta frecuencia que se considera el modelo de partícula en movimiento armónico simple para representar tales situaciones. Con el fin de elaborar una representación matemática para este modelo, primero se reconoce que el bloque es una partícula bajo una fuerza neta, como se describe en la ecuación $\color{red}{(1)}$. Por lo general se elegirá $x$ como el eje a lo largo del que se presenta la oscilación; por eso, en esta explicación se eliminará la notación de subíndice $x$. Recuerde que, por definición, $\displaystyle a = \frac{dv}{dt} = \frac{d^{2}x}{dt^{2}}$, y así la ecuación se puede expresar como

$$
\displaystyle \frac{d^{2}x}{dt^{2}} = -\frac{k}{m}x \quad \color{red}{(3)}
$$

Si la relación $k/m$ se indica con el símbolo $\omega^{2}$ (se elige $\omega^{2}$ en lugar de $\omega$ para que la solución que se desarrolle a continuación sea más simple en forma), en tal caso

$$
\displaystyle \omega^{2} = \frac{k}{m} \quad \color{red}{(4)}
$$

y la ecuación $\color{red}{(3)}$ se puede escribir en la forma

$$
\displaystyle \frac{d^{2}x}{dt^{2}} = -\omega^{2}x \quad \color{red}{(5)}
$$

Lo que necesitamos ahora es una solución para la ecuación $\color{red}{(5)}$, es decir, una función $x(t)$ que satisfaga esta ecuación diferencial de segundo orden.

La solución general de la ecuación diferencial es

$$
\displaystyle x(t) = c_{1} \cos(\omega t) + c_{2} \sin(\omega t) \quad \color{red}{(6)}
$$

donde $c_{1}$ y $c_{2}$ son constantes arbitrarias. Se determinan por las condiciones iniciales. Este es, obviamente, un movimiento periódico, por la naturaleza de las funciones seno y coseno. Por comodidad, preferimos expresar esta solución en términos de una sola función trigonométrica como

$$
\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}
$$

Dado que el coseno de un ángulo no puede ser mayor que $1$, el factor $A$ corresponde al desplazamiento máximo llamado amplitud de las oscilaciones. La masa oscilará continuamente entre las posiciones $x = A$ y $x = -A$.

El tiempo durante el cual se completa un ciclo se llama periodo del movimiento

$$
\displaystyle T = \frac{2\pi}{\omega} \quad \color{red}{(8)}
$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$
\displaystyle T = \frac{t}{n} \quad \color{red}{(9)}
$$

La frecuencia de las oscilaciones es el número de oscilaciones por unidad de tiempo, y es igual a la inversa del periodo:

$$
\displaystyle f = \frac{1}{T} \quad \color{red}{(10)}
$$

$$
\displaystyle f = \frac{\omega}{2\pi} \quad \color{red}{(11)}
$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$
\displaystyle f = \frac{n}{t} \quad \color{red}{(12)}
$$

Una unidad para la frecuencia es denominada Hertz (Hz) equivale al número de ciclos por segundo.

Observe que, en ausencia de cualquier efecto externo, la frecuencia depende sólo de las características de la masa y del resorte, y es independiente de las condiciones iniciales y de la gravedad. La frecuencia $\omega$ es un ejemplo de una frecuencia angular, que tiene unidades de radianes por segundo. El término

$$
\displaystyle \omega = \sqrt{\frac{k}{m}} \quad \color{red}{(13)}
$$

se conoce como frecuencia angular natural o simplemente frecuencia natural del sistema.

## 4. Ejercicios (Parte 1) \[Volver al Índice\]

 1. Una masa que pesa $4 \text{ libras}$ se une a un resorte cuya constante es $16 \text{ lb/pie}$. ¿Cuál es el periodo del movimiento armónico simple?

    Respuesta: $\displaystyle T = 0.5539 \text{ s}$

 2. a) ¿Qué masa debes unir a un muelle de constante $k = 37 \text{ N/m}$ para que la frecuencia de oscilación del sistema sea de $1 \text{ Hz}$? b) ¿Y para que sea de $4 \text{ Hz}$?

    Respuesta: a) $\displaystyle m = 0.9372 \text{ kg}$; b) $\displaystyle m = 0.0586 \text{ kg}$

 3. La punta de un diapasón efectúa $440$ vibraciones completas en $0.500 \text{ s}$. Calcule a) la frecuencia angular y b) el periodo del movimiento.

    Respuesta: a) $\displaystyle \omega = 5529.20 \text{ rad/s}$; b) $\displaystyle T = 0.00114 \text{ s}$

 4. Una cuerda de piano produce un "la medio" vibrando primordialmente a $220 \text{ Hz}$. a) Calcule su periodo y frecuencia angular. b) Calcule el periodo y la frecuencia angular de una soprano que canta un "la alto", dos octavas más arriba, que es cuatro veces la frecuencia de la cuerda de piano.

    Respuesta: a) $\displaystyle T = 0.00455 \text{ s}$, $\displaystyle \omega = 1382.30 \text{ rad/s}$; b) $\displaystyle T = 0.00114 \text{ s}$, $\displaystyle \omega = 5529.20 \text{ rad/s}$

 5. Un oscilador armónico tiene una masa de $0.500 \text{ kg}$ y un resorte ideal con $k = 140 \text{ kg/s}^{2}$. Calcule: a) el periodo; b) la frecuencia; c) la frecuencia angular.

    Respuesta: a) $\displaystyle T = 0.3755 \text{ s}$; b) $\displaystyle f = 2.6631 \text{ Hz}$; c) $\displaystyle \omega = 16.73 \text{ rad/s}$

 6. Si un objeto en una superficie horizontal sin fricción se une a un resorte, se desplaza y después se suelta, oscilará. Si se desplaza $0.120 \text{ m}$ de su posición de equilibrio y se suelta con rapidez inicial cero, después de $0.800 \text{ s}$ su desplazamiento es de $0.120 \text{ m}$ en el lado opuesto, habiendo pasado por la posición de equilibrio una vez. Calcule: a) la amplitud; b) el periodo; c) la frecuencia.

    Respuesta: a) $\displaystyle A = 0.120 \text{ m}$; b) $\displaystyle T = 1.600 \text{ s}$; c) $\displaystyle f = 0.625 \text{ Hz}$

 7. Un resorte tiene una longitud de $30 \text{ cm}$. Si se cuelga de él un cuerpo de masa $250 \text{ g}$ y se le hace oscilar verticalmente, emplea $6 \text{ s}$ en realizar $10$ oscilaciones completas. Calcular a) la constante elástica del resorte y b) su longitud cuando dicho cuerpo está colgado de él, en reposo.

    Respuesta: a) $\displaystyle k = 27.42 \text{ N/m}$; b) $\displaystyle L = 38.94 \text{ cm}$

 8. Una pieza de una máquina está en MAS con frecuencia de $5.00 \text{ Hz}$ y amplitud de $1.80 \text{ cm}$. ¿Cuánto tarda la pieza en ir de $x = 0$ a $x = -1.80 \text{ cm}$?

    Respuesta: $\displaystyle t = 0.05 \text{ s}$

 9. Se crea un oscilador armónico usando un bloque de $0.600 \text{ kg}$, que se desliza sobre una superficie sin fricción y un resorte ideal con constante de fuerza desconocida. Se determina que el oscilador tiene un periodo de $0.150 \text{ s}$. Calcule la constante de fuerza del resorte.

    Respuesta: $\displaystyle k = 1052.76 \text{ N/m}$

10. Una masa de $20 \text{ kilogramos}$ se une a un resorte. Si la frecuencia del movimiento armónico simple es $2/\pi \text{ ciclos/s}$, a) ¿cuál es la constante del resorte $k$? b) ¿Cuál es la frecuencia del movimiento armónico simple si la masa original se reemplaza con una masa de $80 \text{ kilogramos}$?

    Respuesta: a) $\displaystyle k = 320 \text{ N/m}$; b) $\displaystyle f = 1/\pi \text{ Hz}$

11. Un cuerpo de masa desconocida se une a un resorte lineal ideal con constante de fuerza de $120 \text{ kg/s}^{2}$. Se observa que vibra a una frecuencia de $6.00 \text{ Hz}$. Calcule: a) el periodo; b) la frecuencia angular; c) la masa del cuerpo.

    Respuesta: a) $\displaystyle T = 0.1667 \text{ s}$; b) $\displaystyle \omega = 37.70 \text{ rad/s}$; c) $\displaystyle m = 0.0844 \text{ kg}$

12. Un cuerpo de $300 \text{ g}$ se encuentra unido al techo a través de un muelle. El peso del cuerpo hace que el muelle se deforme $6 \text{ cm}$. Determinar:

    a) Cuál será la frecuencia angular de oscilación del cuerpo cuando se desplaza de su posición de equilibrio.

    b) Qué ocurriría al variar la masa del cuerpo a $500 \text{ g}$.

    c) Determina para este último caso la frecuencia angular y el periodo.

    Respuesta: a) $\displaystyle \omega = 12.79 \text{ rad/s}$; b) Si se varía la masa del cuerpo, cambia la frecuencia angular; c) $\displaystyle \omega = 9.90 \text{ rad/s}$, $\displaystyle T = 0.6346 \text{ s}$

13. ¡Cuidado con los baches! Un automóvil con una masa de $1300 \text{ kg}$ se construye de modo que su chasis está sostenido mediante cuatro amortiguadores. Cada amortiguador tiene una constante de fuerza de $20000 \text{ N/m}$. Dos personas que viajan en el automóvil tienen una masa combinada de $160 \text{ kg}$. Encuentre la frecuencia de vibración del automóvil después de que pasa sobre un bache en el camino. Suponga que el automóvil se detiene al lado del camino y las dos personas salen del auto. Una de ellas presiona hacia abajo el automóvil y lo libera de modo que oscile en la vertical. ¿La frecuencia de la oscilación es la misma que el valor recién calculado?

    Respuesta: $\displaystyle f = 1.18 \text{ Hz}$. Si las personas se bajan del carro: $\displaystyle f = 1.25 \text{ Hz}$

14. Una silla de $42.5 \text{ kg}$ se sujeta a un resorte y se le permite oscilar. Cuando la silla está vacía, tarda $1.30 \text{ s}$ en efectuar una vibración completa. Cuando una persona se sienta en ella, sin tocar el piso con los pies, la silla tarda $2.54 \text{ s}$ en efectuar un ciclo. Calcule la masa de la persona.

    Respuesta: $\displaystyle m_{p} = 119.74 \text{ kg}$

15. Un resorte se mantiene vertical apoyado en el suelo. Se coloca un cuerpo de masa $m$ en reposo sobre el resorte y se observa que éste se acorta $6 \text{ cm}$. Si empujamos ligeramente el cuerpo hacia abajo y lo soltamos, a) ¿cuál será la frecuencia de las oscilaciones? b) ¿y si la masa del cuerpo fuese $2m$?

    Respuesta: a) $\displaystyle f_{1} = 2.04 \text{ Hz}$; b) $\displaystyle f_{2} = 1.44 \text{ Hz}$

## 5. Posición, velocidad y aceleración en función del tiempo \[Volver al Índice\]

### 5.1 Posición de la partícula en función del tiempo \[Volver al Índice\]

$$
\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}
$$

### 5.2 Rapidez de la partícula en función del tiempo \[Volver al Índice\]

Podemos obtener la rapidez de una partícula que experimenta un movimiento armónico simple diferenciando la ecuación $\color{red}{(7)}$ respecto del tiempo:

$$
\displaystyle v(t) = \frac{dx}{dt}
$$

$$
\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \quad \color{red}{(14)}
$$

### 5.3 Aceleración de la partícula en función del tiempo \[Volver al Índice\]

La aceleración de la partícula es

$$
\displaystyle a(t) = \frac{dv}{dt}
$$

$$
\displaystyle a(t) = -\omega^{2}A \cos(\omega t + \phi) \quad \color{red}{(15)}
$$

### 5.4 Convenio de signos para la posición inicial y la velocidad inicial \[Volver al Índice\]

**Movimiento horizontal.**

Si el cuerpo se desplaza una posición $x_{0}$ hacia la derecha (estirando el resorte) y se inicia el movimiento, la posición inicial $x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $x_{0}$ hacia la izquierda (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $v_{0}$ hacia la derecha es positiva y hacia la izquierda es negativa.

**Movimiento vertical.**

Si el cuerpo se desplaza una posición $x_{0}$ hacia abajo (estirando el resorte) y se inicia el movimiento, la posición inicial $x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $x_{0}$ hacia arriba (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $v_{0}$ hacia abajo es positiva y hacia arriba es negativa.

### 5.5 Amplitud y ángulo de fase en función de las condiciones iniciales \[Volver al Índice\]

Suponga que la posición inicial $x_{0}$ y la velocidad inicial $v_{0}$ de un solo oscilador están dadas, es decir, en $t = 0$, $x = x_{0}$ y $v = v_{0}$. Obtenemos $c_{1} = x_{0}$ y $c_{2} = \frac{v_{0}}{\omega}$. La ecuación $\color{red}{(6)}$ se escribe como

$$
\displaystyle x(t) = x_{0} \cos(\omega t) + \frac{v_{0}}{\omega} \sin(\omega t) \quad \color{red}{(16)}
$$

Al desarrollar la ecuación $\color{red}{(7)}$:

$$
\displaystyle x(t) = A \cos(\omega t) \cos \phi - A \sin(\omega t) \sin \phi \quad \color{red}{(17)}
$$

Comparando las ecuaciones $\color{red}{(16)}$ y $\color{red}{(17)}$, tenemos:

$$
\displaystyle A \cos \phi = x_{0} \quad \color{red}{(18)}
$$

$$
\displaystyle -A \sin \phi = \frac{v_{0}}{\omega} \quad \color{red}{(19)}
$$

Elevamos al cuadrado, sumamos cada ecuación y usando la identidad $\cos^{2}\phi + \sin^{2}\phi = 1$, tenemos

$$
\displaystyle x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2} = A^{2} \cos^{2}\phi + A^{2} \sin^{2}\phi = A^{2}
$$

Eligiendo la raíz cuadrada positiva para $A$ obtenemos

$$
\displaystyle A = \sqrt{x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2}} \quad \color{red}{(20)}
$$

El ángulo $\phi$ se llama ángulo de fase, y puede determinarse dividiendo la ecuación $\color{red}{(19)}$ entre la ecuación $\color{red}{(18)}$, para obtener

$$
\displaystyle \frac{-A \sin \phi}{A \cos \phi} = \frac{\frac{v_{0}}{\omega}}{x_{0}}
$$

$$
\displaystyle -\tan \phi = \frac{v_{0}}{\omega x_{0}}
$$

$$
\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \color{red}{(21)}
$$

### 5.6 Casos particulares para el ángulo de fase \[Volver al Índice\]

* Posición inicial: $x_{0} = A$, Velocidad inicial: $v_{0} = 0 \implies \phi = 0$.

* Posición inicial: $x_{0} = -A$, Velocidad inicial: $v_{0} = 0 \implies \phi = -\pi$.

* Posición inicial: $x_{0} = 0$, Velocidad inicial: $v_{0} > 0 \implies \phi = -\pi/2$.

* Posición inicial: $x_{0} = 0$, Velocidad inicial: $v_{0} < 0 \implies \phi = \pi/2$.

### 5.7 Ajustes en el ángulo de fase (Caso general) \[Volver al Índice\]

Si utilizamos la ecuación $\color{red}{(7)}$ como la ecuación del movimiento:

$$
\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}
$$

el ángulo de fase se determina según la ecuación $\color{red}{(21)}$:

$$
\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \color{red}{(21)}
$$

Sin embargo, es necesario elegir el valor apropiado de $\phi$ dependiendo de los valores (signo) de la rapidez inicial ($v_{0}$) y la posición inicial ($x_{0}$) de la partícula.

Entre

$$
\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right)
$$


y

$$
\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) - \pi
$$

elegir como ángulo de fase el que cumpla las condiciones:

* El signo de $\cos \phi$ coincide con el signo de $x_{0}$ y

* El signo de $\sin \phi$ coincide con el signo opuesto de $v_{0}$.

## 6. Ejercicios (Parte 2) \[Volver al Índice\]

**Inicialmente está en el extremo derecho (inferior) de la trayectoria con velocidad nula (**$\phi = 0$**)**

16. Se hace oscilar verticalmente un cuerpo de masa $80 \text{ g}$ que está colgado de un muelle en hélice de constante elástica $2 \text{ N/m}$. Si la amplitud de la oscilación es de $10 \text{ cm}$, ¿cuál será la expresión de su elongación en función del tiempo?

    Respuesta: $\displaystyle x(t) = 10 \cos(5t + \phi_{0})$, $t = [\text{s}]$, $x = [\text{cm}]$

17. La aceleración (en $\text{m/s}^{2}$) de un M.A.S. en función de la elongación (en $\text{m}$) es $a = -256 x$. Expresar esta aceleración en función del tiempo sabiendo que la amplitud de la vibración es de $2.5 \text{ cm}$. Considérese nula la constante de fase.

    Respuesta: $\displaystyle a(t) = -6.4 \cos(16t)$

18. Un cuerpo de masa $m = 2 \text{ kg}$ está unido a un muelle horizontal de constante $k = 5 \text{ N/m}$. El muelle se alarga $10 \text{ cm}$ y se suelta en el instante inicial $t = 0$. Hallar:

    a) La frecuencia, el período y la amplitud del movimiento. Escribir la ecuación del M.A.S.

    b) ¿En qué instante pasa el cuerpo por primera vez por la posición de equilibrio?

    Respuesta: a) $\displaystyle f = 0.2515 \text{ Hz}$, $\displaystyle T = 3.98 \text{ s}$, $\displaystyle A = 0.1 \text{ m}$, $\displaystyle x(t) = 0.1 \cos(1.581t)$, $x = [\text{m}]$, $t = [\text{s}]$; b) $\displaystyle t = 0.994 \text{ s}$

19. Una masa que pesa $20 \text{ libras}$ alarga a un resorte $6 \text{ pulgadas}$. La masa se libera al inicio desde el reposo de un punto $6 \text{ pulgadas}$ abajo de la posición de equilibrio.

    a) Encuentre la posición de la masa en los tiempos $t = \pi/12, \pi/8, \pi/6, \pi/4$ y $9\pi/32 \text{ s}$.

    b) ¿Cuál es la velocidad de la masa cuando $t = 3\pi/16 \text{ s}$? ¿En qué dirección se dirige la masa en este instante?

    c) ¿En qué tiempos la masa pasa por la posición de equilibrio?

20. Una partícula describe un movimiento armónico simple con una frecuencia de $10 \text{ Hz}$ y una amplitud de $5 \text{ cm}$. Calcular:

    a) Las funciones de la elongación y de la velocidad de la partícula si para $t = 0$ está en la posición $x = +5 \text{ cm}$.

    b) La aceleración para $t = 2 \text{ s}$.

    Respuesta: a) $\displaystyle x(t) = 0.05 \cos(20\pi t) \text{ m}$, $\displaystyle v(t) = -\pi \sin(20\pi t) \text{ m/s}$; b) $\displaystyle a(2\text{ s}) = 197.39 \text{ m/s}^{2}$

21. Una partícula describe un movimiento armónico simple con un periodo de $2 \text{ s}$ y una amplitud de $25 \text{ cm}$. Calcular:

    a) Las funciones de la elongación y de la velocidad de la partícula si para $t = 0$ está en la posición $x = +25 \text{ cm}$.

    b) La aceleración para $t = 3 \text{ s}$.

    Respuesta: a) $\displaystyle x(t) = 0.25 \cos(\pi t) \text{ m}$, $\displaystyle v(t) = -0.25\pi \sin(\pi t) \text{ m/s}$; b) $\displaystyle a(3\text{ s}) = 2.47 \text{ m/s}^{2}$

22. Estiramos un resorte $5 \text{ cm}$ y lo dejamos oscilar libremente resultando que completa una oscilación cada $0.2 \text{ s}$. Calcular:

    a) La función que nos permite calcular su posición en función del tiempo.

    b) La velocidad y la aceleración a la que estará sometido el extremo libre a los $15 \text{ s}$ de iniciado el movimiento.

    Respuesta: a) $\displaystyle x(t) = 0.05 \cos(10\pi t)$, $x = [\text{m}]$, $t = [\text{s}]$; b) $\displaystyle v(15\text{ s}) = 0 \text{ m/s}$, $\displaystyle a(15\text{ s}) = -49.35 \text{ m/s}^{2}$

23. Una partícula que se mueve de acuerdo a un movimiento armónico simple tarda $1 \text{ s}$ en llegar de un extremo a otro de su trayectoria. Sabiendo que la distancia que separa ambas posiciones es de $16 \text{ cm}$, y que el movimiento se inicia en un extremo de la trayectoria, determinar:

    a) El periodo del movimiento.

    b) La amplitud máxima de las oscilaciones.

    c) La posición de la partícula a los $1.5 \text{ segundos}$.

    Respuesta: a) $\displaystyle T = 2 \text{ s}$; b) $\displaystyle A = 8 \times 10^{-2} \text{ m}$; c) $\displaystyle x(1.5) = 0$

24. Una masa puntual está sujeta a un resorte elástico y oscila sobre el eje $OX$ con una frecuencia de $0.5 \text{ Hz}$ y una amplitud de $30 \text{ cm}$. Si en el instante inicial su elongación es de $+30 \text{ cm}$, determine:

    a) Las funciones de la elongación, la velocidad y la aceleración.

    b) Su posición y velocidad cuando $t = 2.5 \text{ s}$.

    c) Su aceleración cuando $t = 3 \text{ s}$.

    Respuesta: a) $\displaystyle x(t) = 0.30 \cos(\pi t)$; $\displaystyle v(t) = -0.30\pi \sin(\pi t)$; $\displaystyle a(t) = -0.30\pi^{2} \cos(\pi t)$; b) $\displaystyle x(2.5\text{ s}) = 0$; $\displaystyle v(2.5\text{ s}) = -0.94 \text{ m/s}$; c) $\displaystyle a(3\text{ s}) = +2.96 \text{ m/s}^{2}$

25. Una partícula de $10 \text{ kg}$ de masa está sujeta a un muelle de constante elástica de $10 \text{ N/m}$. En el instante inicial se desplaza $0.5 \text{ m}$ de la posición de equilibrio y se suelta con velocidad nula. Representa la elongación y la velocidad frente al tiempo.

    Respuesta: $\displaystyle x(t) = 0.5 \cos t$, $\displaystyle v(t) = -0.5 \sin t$

26. Se cuelga un objeto de $200 \text{ g}$ de un muelle sujeto al techo de $35 \text{ cm}$ de longitud y su nueva longitud es de $45 \text{ cm}$.

    a) Determinar la constante de elasticidad $k$ del muelle.

    b) Si estiramos el muelle hasta que mida $55 \text{ cm}$ y lo soltamos, determina las fuerzas que actúan sobre el muelle.

    Respuesta: a) $\displaystyle k = 19.6 \text{ N/m}$; b) $\displaystyle P = 1.96 \text{ N}$, $\displaystyle F_{t} = -1.96 \text{ N}$

**Inicialmente está en el extremo izquierdo (superior) de la trayectoria con velocidad nula (**$\phi = -\pi$**)**

27. Tenemos colgado verticalmente un muelle con una constante $k = 400 \text{ N/m}$ y queremos colgarle una masa para que oscile con un periodo de $1 \text{ s}$. Calcular:

    a) La masa que debemos colgarle para conseguir ese periodo.

    b) Su posición para $t = 1.5 \text{ s}$ si, para que empiece a vibrar, levantamos la masa $4 \text{ cm}$ por encima de su posición de equilibrio y contamos el tiempo desde que la soltamos.

    Respuesta: a) $\displaystyle m = 10.13 \text{ kg}$; b) $\displaystyle x(1.5\text{ s}) = -0.04 \text{ m} = -A$

**Inicialmente está en el punto de equilibrio y se desplaza hacia la derecha (abajo) (**$\phi = -\pi/2$**)**

28. Un M.A.S. tiene una frecuencia de $5 \text{ Hz}$ y una amplitud de $8 \text{ mm}$. En el instante $t = 0$, el móvil se encuentra en el centro de la vibración y se desplaza en sentido positivo. Expresar su elongación, su velocidad y su aceleración como funciones del tiempo.

    Respuesta: $\displaystyle x(t) = 8 \times 10^{-3} \cos(10\pi t - \pi/2)$, $x = [\text{m}]$, $t = [\text{s}]$; $\displaystyle v(t) = -8 \times 10^{-2}\pi \sin(10\pi t - \pi/2)$, $v = [\text{m/s}]$, $t = [\text{s}]$; $\displaystyle a(t) = -0.8\pi^{2} \cos(10\pi t - \pi/2)$, $a = [\text{m/s}^{2}]$, $t = [\text{s}]$

**Inicialmente está en el punto de equilibrio y se desplaza hacia la izquierda (arriba) (**$\phi = \pi/2$**)**

29. Un bloque de $2.00 \text{ kg}$, que se desliza sin fricción, se conecta a un resorte ideal con $k = 300 \text{ N/m}$. En $t = 0$, el resorte no está estirado ni comprimido y el bloque se mueve en la dirección negativa a $12.00 \text{ m/s}$. Calcule: a) la amplitud; b) el ángulo de fase; c) Escriba una ecuación para la posición en función del tiempo. d) Repita los incisos a) a c) pero suponga que, en $t = 0$, el bloque tiene una velocidad de $-4.00 \text{ m/s}$, y un desplazamiento de $+0.200 \text{ m}$.

    Respuesta: a) $\displaystyle A = 0.97 \text{ m}$; b) $\displaystyle \pi/2 \text{ rad}$; c) $\displaystyle x(t) = 0.97 \cos(12.32t - 3\pi/2)$; d) $\displaystyle 0.380 \text{ m}$, $\displaystyle 1.02 \text{ rad}$, $\displaystyle x(t) = 0.380 \cos(12.32t + 1.02)$

30. Un cuerpo que se mueve describiendo un movimiento armónico simple a lo largo del eje X presenta, en un instante inicial, una aceleración nula y una velocidad de $-5\vec{i} \text{ m/s}$. La frecuencia del movimiento es $0.25 \text{ Hz}$. Determine la expresión matemática que describe la elongación del muelle en función del tiempo. Justifique su respuesta.

    Respuesta: $\displaystyle x(t) = \frac{10}{\pi} \cos(0.5\pi t - 3\pi/2)$

31. Un objeto está en movimiento armónico simple con periodo de $1.200 \text{ s}$ y amplitud de $0.600 \text{ m}$. En $t = 0$, el objeto está en $x = 0$. ¿A qué distancia está de la posición de equilibrio cuando $t = 0.480 \text{ s}$?

    Respuesta: $\displaystyle x = -0.360 \text{ m}$

**Inicialmente no está en el extremo de la trayectoria ni tiene velocidad inicial nula**

32. Una partícula vibra de tal modo que tarda $0.50 \text{ s}$ en ir desde un extremo a la posición de equilibrio, distantes entre sí $8.0 \text{ cm}$. Si para $t = 0$ la elongación de la partícula es $4.0 \text{ cm}$, hallar la ecuación que define este movimiento.

    Respuesta: $\displaystyle x(t) = 0.08 \cos(\pi t - \pi/3) \text{ m}$

33. **Ejercicio 6.** Una fuerza de $400 \text{ newtons}$ alarga un resorte $2 \text{ metros}$. Una masa de $50 \text{ kilogramos}$ se une al extremo del resorte y se libera inicialmente desde la posición de equilibrio con una velocidad hacia arriba de $10 \text{ m/s}$. Encuentre la ecuación del movimiento.

    **Ejercicio 7.** Otro resorte cuya constante es $20 \text{ N/m}$ se suspende del mismo soporte, pero paralelo al sistema resorte-masa del problema 6. Al segundo resorte se le coloca una masa de $20 \text{ kilogramos}$, y ambas masas se liberan al inicio desde la posición de equilibrio con una velocidad ascendente de $10 \text{ m/s}$.

    a) ¿Cuál masa exhibe la mayor amplitud de movimiento?

    b) ¿Cuál masa se mueve más rápido en $t = \pi/4 \text{ s}$?

    c) ¿En qué instantes las dos masas están en la misma posición? ¿Dónde están las masas en estos instantes? ¿En qué directions se están moviendo las masas?

34. **Ejercicio 3.** Una masa que pesa $24 \text{ libras}$, unida al extremo de un resorte, alarga a éste $4 \text{ pulgadas}$. Al inicio, la masa se libera desde el reposo en un punto $3 \text{ pulgadas}$ arriba de la posición de equilibrio. Encuentre la ecuación del movimiento.

    **Ejercicio 4.** Determine la ecuación del movimiento si la masa del problema 3 al inicio se libera desde la posición de equilibrio con una velocidad descendente de $2 \text{ pie/s}$.

35. Una masa que pesa $32 \text{ libras}$ alarga un resorte $2 \text{ pies}$. Determine la a) amplitud y b) el periodo del movimiento si la masa se libera inicialmente desde un punto situado $1 \text{ pie}$ arriba de la posición de equilibrio con una velocidad ascendente de $2 \text{ pies/s}$. c) ¿Cuántos ciclos habrá completado la masa al final de $4\pi \text{ segundos}$?

    Respuesta: a) $\displaystyle A = 1.1175 \text{ ft}$; b) $\displaystyle T = 1.57 \text{ s}$; c) $\displaystyle n = 8 \text{ ciclos}$

36. La punta de la aguja de una máquina de coser se mueve en MAS sobre el eje $x$ con una frecuencia de $2.5 \text{ Hz}$. En $t = 0$, sus componentes de posición y velocidad son $+1.1 \text{ cm}$ y $-15.00 \text{ cm/s}$.

    a) Calcule la componente de aceleración de la aguja en $t = 0$.

    b) Escriba ecuaciones para las componentes de posición, velocidad y aceleración de la punta en función del tiempo.

    Respuesta: a) $\displaystyle a_{z} = -2.71 \text{ m/s}^{2}$; b) $\displaystyle x(t) = 0.0146 \cos(15.71t + 0.7149)$, $x = [\text{m}]$, $t = [\text{s}]$; $\displaystyle v(t) = -0.23 \sin(15.71t + 0.7149)$, $v = [\text{m/s}]$, $t = [\text{s}]$; $\displaystyle a(t) = -3.61 \cos(15.71t + 0.7149)$, $a = [\text{m/s}^{2}]$, $t = [\text{s}]$

37. Una masa que pesa $2 \text{ lb}$ alarga un resorte $6 \text{ pulgadas}$. En $t = 0$ se libera la masa desde un punto que está $8 \text{ pulgadas}$ debajo de la posición de equilibrio con una velocidad ascendente de $4/3 \text{ pie/s}$. Determine la ecuación de movimiento.

    Respuesta: $\displaystyle x(t) = 0.6871 \cos(8.02t + 0.2444)$, $x = [\text{ft}]$, $t = [\text{s}]$

## 7. Elongación máxima, velocidad máxima y aceleración máxima \[Volver al Índice\]

A partir de la ecuación $\color{red}{(14)}$ se ve que, puesto que las funciones seno y coseno oscilan entre $\pm 1$, los valores extremos de la velocidad $v$ son $\pm \omega A$. Del mismo modo, la ecuación $\color{red}{(15)}$ muestra que los valores extremos de la aceleración $a$ son $\pm \omega^{2} A$. En consecuencia, los valores máximos de las magnitudes de la velocidad y la aceleración son

$$
\displaystyle v_{\max} = \omega A \quad \color{red}{(22)}
$$

$$
\displaystyle a_{\max} = \omega^{2}A \quad \color{red}{(23)}
$$

La figura 2a grafica la posición con el tiempo para un valor arbitrario de la constante de fase. En las figuras 2b y 2c se ilustran las curvas asociadas velocidad-tiempo y aceleración-tiempo. Las cuales muestran que la fase de la velocidad difiere de la fase de la posición en $\pi/2 \text{ rad}$, o $90^{\circ}$. Es decir: cuando $x$ es un máximo o un mínimo, la velocidad es cero. Del mismo modo, cuando $x$ es cero, la rapidez es un máximo. Además, note que la fase de la aceleración difiere de la fase de la posición en $\pi \text{ radianes}$, o $180^{\circ}$. Por ejemplo, cuando $x$ es un máximo, $a$ tiene una magnitud máxima en la dirección opuesta.

**Relación entre la aceleración máxima y la velocidad máxima.**

$$
\displaystyle a_{\max} = \omega v_{\max} \quad \color{red}{(24)}
$$

## 8. Ejercicios (Parte 3) \[Volver al Índice\]

38. Un sistema bloque-resorte. Un bloque de $200 \text{ g}$ conectado a un resorte ligero tiene una constante de fuerza de $5.00 \text{ N/m}$ y es libre de oscilar sobre una superficie horizontal sin fricción. El bloque se desplaza $5.00 \text{ cm}$ desde el equilibrio y se libera del reposo.

    a) Hallar el periodo de su movimiento.

    b) Determine la rapidez máxima del bloque.

    c) ¿Cuál es la aceleración máxima del bloque?

    d) Exprese la posición, velocidad y aceleración como funciones del tiempo.

    e) ¿Y si el bloque se libera desde la misma posición inicial, $x_{0} = 5.00 \text{ cm}$, pero con una velocidad inicial de $v_{0} = -0.100 \text{ m/s}$? ¿Qué partes de la solución cambian y cuáles son las nuevas respuestas para estas?

    Respuesta: a) $\displaystyle T = 1.26 \text{ s}$; b) $\displaystyle v_{\max} = 0.25 \text{ m/s}$; c) $\displaystyle a_{\max} = 1.25 \text{ m/s}^{2}$; d) $\displaystyle x(t) = 0.05 \cos(5t)$, $x(t) = [\text{m}]$, $t = [\text{s}]$; $\displaystyle v(t) = -0.25 \sin(5t)$, $v(t) = [\text{m/s}]$, $t = [\text{s}]$; $\displaystyle a(t) = -1.25 \cos(5t)$, $a(t) = [\text{m/s}^{2}]$, $t = [\text{s}]$; e) a) $\displaystyle T = 1.26 \text{ s}$; d) $\displaystyle x(t) = 0.0539 \cos(5t + 0.3805)$, $x(t) = [\text{m}]$, $t = [\text{s}]$; $\displaystyle v(t) = -0.2695 \sin(5t + 0.3805)$, $v(t) = [\text{m/s}]$, $t = [\text{s}]$; $\displaystyle a(t) = -1.3475 \cos(5t + 0.3805)$, $a(t) = [\text{m/s}^{2}]$, $t = [\text{s}]$

39. Una cuerda de guitarra vibra con una frecuencia de $440 \text{ Hz}$. Un punto en su centro se mueve en M.A.S con amplitud de $3.0 \text{ mm}$ y ángulo de fase cero. a) Escriba una ecuación para la posición del centro de la cuerda en función del tiempo. b) ¿Qué magnitud máxima tienen: la velocidad y la aceleración del centro de la cuerda? c) La derivada de la aceleración respecto al tiempo es una cantidad llamada tirón. Escriba una ecuación para el tirón del centro de la cuerda en función del tiempo, y calcule el valor máximo de la magnitud del tirón.

    Respuesta: a) $\displaystyle x(t) = 0.003 \cos(2764.60 t)$; b) $\displaystyle v_{\max} = 8.29 \text{ m/s}$, $\displaystyle a_{\max} = 22926.06 \text{ m/s}^{2}$

40. Una masa de $0.50 \text{ kg}$ cuelga de un resorte de $k = 50 \text{ N/m}$. Si la desplazamos $5.0 \text{ cm}$ y la soltamos, calcular: a) La frecuencia b) La velocidad que tiene cuando pasa por la posición de equilibrio.

    Respuesta: a) $\displaystyle f = 1.59 \text{ s}^{-1}$; b) $\displaystyle v_{\max} = 0.50 \text{ m/s}$

41. Una masa $m = 0.5 \text{ kg}$ está suspendida de un resorte que se estiró $0.2 \text{ cm}$ bajo la influencia del peso de esta masa. Ahora se tira de la masa hacia abajo y se suelta. En el tiempo $t = 0$, se observa que la masa pasa por su posición de equilibrio estático con una velocidad de $10 \text{ m/s}$. Despreciando toda fricción, determine a) la frecuencia natural, b) el periodo y c) la amplitud del movimiento resultante.

    Respuesta: a) $\displaystyle \omega = 70.04 \text{ rad/s}$; b) $\displaystyle T = 8.97 \times 10^{-2} \text{ s}$; c) $\displaystyle A = 0.1428 \text{ m}$

42. Un muelle se alarga $25 \text{ cm}$ al colgar de él una masa de $2.0 \text{ kg}$. Calcular la frecuencia y la velocidad máxima de oscilación de la masa sabiendo que la amplitud del movimiento es de $5.0 \text{ cm}$. Dato: $g = 9.8 \text{ m/s}^{2}$.

    Respuesta: $\displaystyle f = 1 \text{ Hz}$, $\displaystyle v_{\max} = 0.314 \text{ m/s}$

43. Un cuerpo de masa $20 \text{ g}$, que se mueve sobre el eje OX, pasa por el origen de coordenadas con una velocidad de $10 \text{ m/s}$. Sobre él actúa una fuerza $F = -4x \text{ N}$, siendo $x$ la abscisa del cuerpo en $\text{m}$. Calcular hasta qué distancia del origen llegará.

    Respuesta: $\displaystyle A = 0.707 \text{ m}$

44. Una partícula de $5.0 \text{ g}$ se mueve con M.A.S. Si su frecuencia es de $25 \text{ Hz}$ y su amplitud $8 \text{ cm}$, calcular:

    a) Su periodo.

    b) La frecuencia angular.

    c) Su velocidad máxima.

    d) La constante recuperadora.

    Respuesta: a) $\displaystyle T = 1/25 \text{ s}$; b) $\displaystyle \omega = 50\pi$; c) $\displaystyle v_{\max} = 12.566 \text{ m/s}$; d) $\displaystyle k = 123.37 \text{ N/m}$

45. Un objeto está unido a un muelle horizontal sin rozamiento que oscila con una amplitud de $5 \text{ cm}$ y una frecuencia de $3.3 \text{ Hz}$. Determine:

    a) El periodo del movimiento.

    b) La velocidad máxima y la aceleración máxima.

    Respuesta: a) $\displaystyle T = 0.30 \text{ s}$; b) $\displaystyle v_{\max} = \pm 1.03 \text{ m/s}$; $\displaystyle a_{\max} = \pm 21.48 \text{ m/s}^{2}$

46. Un móvil realiza un movimiento armónico simple en el extremo de un muelle que hace dos oscilaciones por segundo, siendo la amplitud del movimiento $20 \text{ cm}$. Calcular:

    a) La velocidad máxima que llega a alcanzar la masa que oscila.

    b) La aceleración de la masa al pasar por el extremo del movimiento vibratorio armónico.

    Respuesta: a) $\displaystyle v_{\max} = 2.51 \text{ m/s}$; b) $\displaystyle a_{\max} = -31.58 \text{ m/s}^{2}$

47. Al descargar una carga de un barco mediante una grúa, oscila haciendo un vaivén cada $4 \text{ segundos}$ con una amplitud de $2 \text{ m}$. Si se mueve con un M.A.S. Calcule:

    a) La aceleración máxima que alcanza.

    b) Si para $t = 0$ está en el extremo positivo de la oscilación, su posición para $t = 9 \text{ s}$.

    Respuesta: a) $\displaystyle a_{\max} = 4.93 \text{ m/s}^{2}$; b) $\displaystyle x(9\text{ s}) = 0 \text{ m}$

48. Al suspender un cuerpo de masa $300 \text{ g}$ del extremo de un muelle que está colgado verticalmente, éste se alarga $20 \text{ cm}$. Si se tira del cuerpo $5 \text{ cm}$ hacia abajo y se suelta, comienza a oscilar. Calcular el período del movimiento. ¿Cuál será la máxima velocidad que alcanzará?

    Respuesta: $\displaystyle v_{\max} = \pm 35.3 \text{ cm/s}$

49. El pistón del cilindro de un coche tiene una carrera (distancia desde abajo hasta arriba del movimiento) de $20 \text{ cm}$ y el motor gira a $800 \text{ rpm}$. Calcular la velocidad máxima que alcanza.

    Respuesta: $\displaystyle v_{\max} = \pm 8.38 \text{ m/s}$

50. Una partícula recorre $8 \text{ cm}$ de extremo a extremo en un movimiento armónico simple y su aceleración máxima es de $48 \text{ m/s}^{2}$. Calcular:

    a) La frecuencia y el periodo del movimiento

    b) La velocidad máxima de la partícula.

    Respuesta: a) $\displaystyle f = 5.51 \text{ Hz}$, $\displaystyle T = 0.1815 \text{ s}$; b) $\displaystyle v_{\max} = 1.39 \text{ m/s}$

51. ¿Qué amplitud y qué período debe tener un M.A.S. para que la velocidad máxima sea de $30 \text{ cm/s}$ y la aceleración máxima de $12 \text{ m/s}^{2}$? Expresar la elongación de ese movimiento en función del tiempo.

    Respuesta: $\displaystyle x(t) = 0.0075 \cos(40t)$, $x = [\text{m}]$, $t = [\text{s}]$

52. ¿Cuál es la máxima fuerza que actúa sobre un cuerpo de masa $50 \text{ g}$ cuando vibra con una frecuencia de $25 \text{ Hz}$ y una amplitud de $2 \text{ mm}$?

    Respuesta: $\displaystyle F_{\max} = 2.47 \text{ N}$

53. En un M.A.S., cuando la elongación es nula, la velocidad es de $1 \text{ m/s}$ y, en el instante en que la elongación es de $5 \text{ cm}$, la velocidad es nula. ¿Cuál es el período del movimiento?

    Respuesta: $\displaystyle T = 0.3142 \text{ s}$

54. La escala de un dinamómetro está graduada en N. Desde la división $0 \text{ N}$ hasta la de $20 \text{ N}$ hay una distancia de $10 \text{ cm}$. Hacemos oscilar, con una amplitud de $1 \text{ cm}$, a un cuerpo de masa $800 \text{ g}$ suspendido del muelle del dinamómetro. Calcular la frecuencia de las oscilaciones y su aceleración máxima.

    Respuesta: $\displaystyle f = 2.52 \text{ Hz}$, $\displaystyle a_{\max} = 250 \text{ cm/s}^{2}$

## 9. Relación entre posición, velocidad y aceleración \[Volver al Índice\]

### 9.1 Relación entre la posición y la aceleración en el M.A.S. \[Volver al Índice\]

Puesto que $x(t) = A \cos(\omega t + \phi)$, podemos expresar la ecuación $\color{red}{(15)}$ en la forma

$$
\displaystyle a = -\omega^{2}x \quad \color{red}{(25)}
$$

### 9.2 Relación entre la posición y la velocidad en el M.A.S. \[Volver al Índice\]

Posición en función del tiempo:

$$
\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}
$$

Rapidez en función del tiempo:

$$
\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \quad \color{red}{(14)}
$$

Al despejar $\cos(\omega t + \phi)$ de la ecuación $\color{red}{(7)}$ y $\sin(\omega t + \phi)$ de la ecuación $\color{red}{(14)}$:

$$
\displaystyle \cos(\omega t + \phi) = \frac{x(t)}{A}
$$

$$
\displaystyle \sin(\omega t + \phi) = -\frac{v(t)}{\omega A}
$$

Siendo $\cos^{2}(\omega t + \phi) + \sin^{2}(\omega t + \phi) = 1$, se tiene:

$$
\displaystyle \left(\frac{x}{A}\right)^{2} + \left(\frac{v}{\omega A}\right)^{2} = 1
$$

$$
\displaystyle \frac{x^{2}}{A^{2}} + \frac{v^{2}}{\omega^{2}A^{2}} = 1
$$

$$
\displaystyle \frac{v^{2}}{\omega^{2}A^{2}} = 1 - \frac{x^{2}}{A^{2}}
$$

$$
\displaystyle \frac{v^{2}}{\omega^{2}A^{2}} = \frac{A^{2} - x^{2}}{A^{2}}
$$

$$
\displaystyle \frac{v^{2}}{\omega^{2}} = A^{2} - x^{2}
$$

$$
\displaystyle v^{2} = \omega^{2}(A^{2} - x^{2})
$$

$$
\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \quad \color{red}{(26)}
$$

### 9.3 Relación entre la velocidad y la aceleración en el M.A.S. \[Volver al Índice\]

Rapidez de la partícula:

$$
\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \quad \color{red}{(26)}
$$

Aceleración de la partícula:

$$
\displaystyle a = -\omega^{2}x \quad \color{red}{(25)}
$$

De la ecuación $\color{red}{(25)}$:

$$
\displaystyle x = -\frac{a}{\omega^{2}}
$$

Al sustituir en la ecuación $\color{red}{(26)}$:

$$
\displaystyle v = \omega \sqrt{A^{2} - \left(-\frac{a}{\omega^{2}}\right)^{2}}
$$

$$
\displaystyle v = \omega \sqrt{A^{2} - \frac{a^{2}}{\omega^{4}}}
$$

$$
\displaystyle v^{2} = \omega^{2} \left(A^{2} - \frac{a^{2}}{\omega^{4}}\right)
$$

$$
\displaystyle v^{2} = \omega^{2}A^{2} - \frac{a^{2}}{\omega^{2}}
$$

$$
\displaystyle \frac{a^{2}}{\omega^{2}} = \omega^{2}A^{2} - v^{2}
$$

$$
\displaystyle a^{2} = \omega^{2}(\omega^{2}A^{2} - v^{2})
$$

$$
\displaystyle a = \omega \sqrt{\omega^{2}A^{2} - v^{2}} \quad \color{red}{(27)}
$$

## 10. Ejercicios (Parte 4) \[Volver al Índice\]

55. Un objeto de $0.400 \text{ kg}$ en MAS tiene $a_{x} = -2.70 \text{ m/s}^{2}$ cuando $x = 0.300 \text{ m}$. ¿Cuánto tarda una oscilación?

    Respuesta: $\displaystyle T = 2.09 \text{ s}$

56. Una partícula se desplaza con M.A.S. de amplitud $1 \text{ cm}$ y frecuencia $8 \text{ Hz}$. Calcular su velocidad y su aceleración en el instante en que tiene una elongación de $6 \text{ mm}$.

    Respuesta: $\displaystyle v = \pm 40.21 \text{ cm/s}$, $\displaystyle a = -15.16 \text{ cm/s}^{2}$

57. En un M.A.S. de amplitud $4 \text{ cm}$, en el instante en que la elongación es $\sqrt{7} \text{ cm}$, la velocidad es de $6\pi \text{ m/s}$. Calcular la frecuencia del movimiento. ¿Cuál será la velocidad del móvil al pasar por la posición de equilibrio?

    Respuesta: $\displaystyle f = 100 \text{ Hz}$, $\displaystyle v_{\max} = 25.1 \text{ m/s}$

58. Un cuerpo está unido a un muelle horizontal. Comienza a oscilar desde uno de los extremos situados a $5 \text{ cm}$ de su posición de equilibrio, con un periodo de $0.4 \text{ s}$. Determinar:

    a) La velocidad al pasar por la posición de equilibrio.

    b) La velocidad y la aceleración al pasar por $x = 3 \text{ cm}$.

    c) La aceleración en los extremos de la trayectoria.

    d) La aceleración en $x = -1 \text{ cm}$.

    Respuesta: a) $\displaystyle v = \pm 25\pi \text{ cm/s}$; b) $\displaystyle v = \pm 20\pi \text{ cm/s}$; c) $\displaystyle a_{\max} = \pm 125\pi^{2} \text{ cm/s}^{2}$; d) $\displaystyle \pm 25\pi^{2} \text{ cm/s}^{2}$

59. Sabiendo que un cuerpo de masa $3 \text{ kg}$ oscila unido a un muelle a razón de $15$ oscilaciones cada segundo, calcular:

    a) La constante elástica del muelle.

    b) El valor de la fuerza cuando la elongación es de $4 \text{ cm}$.

    Respuesta: a) $\displaystyle k = 26647.9 \text{ N/m}$; b) $\displaystyle F = -1065.91 \text{ N}$

## 11. Problemas que involucran gráficas \[Volver al Índice\]

60. En la figura se muestra el desplazamiento en función del tiempo. Calcule: a) la frecuencia; b) la amplitud y c) el periodo.

    Respuesta: a) $\displaystyle f = 0.5 \text{ Hz}$; b) $\displaystyle A = 0.20 \text{ m}$; c) $\displaystyle T = 2.00 \text{ s}$

61. Un cuerpo se mueve según un movimiento armónico simple según la gráfica de la figura.

    A la vista de ella, di si son verdaderas o falsas las siguientes afirmaciones:

    a) Cada dos segundos el cuerpo está en el mismo estado vibracional.

    b) El periodo del movimiento vale $4 \text{ segundos}$.

    c) El movimiento tiene una amplitud de $6 \text{ m}$.

    d) La frecuencia del movimiento es de $0.25 \text{ Hz}$.

    e) La ecuación del movimiento es $x(t) = 3 \sin(\pi/2 \cdot t) \text{ cm}$.

    Respuesta: a) Falso; b) Verdadero; c) Falso; d) Verdadero; e) Falso.

62. La siguiente gráfica representa la elongación en función del tiempo de un cuerpo que se comporta según un movimiento armónico simple:

    Determinar la amplitud máxima, el periodo, la frecuencia, la frecuencia angular y la fase inicial del movimiento.

    Respuesta: $\displaystyle A = 5 \text{ m}$, $\displaystyle T = 12 \text{ s}$, $\displaystyle f = 0.0833 \text{ Hz}$, $\displaystyle \omega = 0.5236 \text{ rad/s}$, $\displaystyle \phi = -0.5236 \text{ rad}$

63. Determina las ecuaciones de las gráficas de la figura. Determina también el desfase entre ambos movimientos.

    Respuesta: $\displaystyle x_{1}(t) = 4 \cos(0.5\pi t + \pi/2)$; $\displaystyle x_{2}(t) = 4 \cos(0.5\pi t + \pi)$; desfase: $\displaystyle \pi/2 \text{ rad}$

64. La gráfica de la figura corresponde a un cuerpo de $150 \text{ g}$ de masa que realiza un movimiento armónico simple (M.A.S).

    Se pide calcular:

    a) La velocidad inicial del cuerpo.

    b) La aceleración en los instantes $t = 2 \text{ s}$ y $t = 6 \text{ s}$.

    c) El valor y sentido que tendrá la fuerza que actúa sobre el cuerpo en los instantes $t = 0.5 \text{ s}$ y $t = 1.5 \text{ s}$.

    Respuesta: a) $\displaystyle v_{0} = 0.2827 \text{ m/s}$; b) $\displaystyle a(2\text{ s}) = 0$, $\displaystyle a(6\text{ s}) = 0$; c) $\displaystyle F(0.5\text{ s}) = -0.1332 \text{ N}$, $\displaystyle F(1.5\text{ s}) = 0.1332 \text{ N}$

## 12. Conocida la ecuación del movimiento \[Volver al Índice\]

65. La ecuación de un M.A.S. es $x(t) = 2 \cos(30\pi t)$, en la que $x$ es la elongación en $\text{cm}$ y $t$ en $\text{s}$. ¿Cuáles son la amplitud, la frecuencia y el período de este movimiento?

    Respuesta: $\displaystyle A = 2 \text{ cm}$, $\displaystyle f = 15 \text{ Hz}$, $\displaystyle T = 1/15 \text{ s}$

66. Sabiendo que un movimiento armónico simple tiene por ecuación:

    $$
    \displaystyle x(t) = 0.5 \sin(0.35\pi t + \pi/4) \text{ (m)}
    $$

    Determinar la ecuación y la gráfica de la velocidad y de la aceleración.

    Respuesta: $\displaystyle v(t) = 0.175\pi \cos(0.35\pi t + \pi/4) \text{ m/s}$, $\displaystyle a(t) = -0.06125\pi^{2} \sin(0.35\pi t + \pi/4) \text{ m/s}^{2}$

67. Calcular la velocidad y aceleración máximas del M.A.S. cuya ecuación es

    $$
    \displaystyle x(t) = 5 \cos(4\pi t + \pi/6)
    $$

    en la que $x$ es la elongación en $\text{cm}$ y $t$ el tiempo en $\text{s}$.

    Respuesta: $\displaystyle v_{\max} = \pm 20\pi = 62.83 \text{ cm/s}$, $\displaystyle a_{\max} = \pm 789.57 \text{ cm/s}^{2}$

68. Calcular la aceleración y la velocidad en el instante inicial para un muelle cuyo movimiento viene descrito por la función: $x(t) = 0.3 \cos(2t + \pi/6) \text{ (cm)}$.

    Respuesta: $\displaystyle a_{0} = -5.92 \text{ cm/s}^{2}$; $\displaystyle v_{0} = -1.63 \text{ cm/s}$

69. Una partícula oscila con un movimiento armónico simple de tal forma que su desplazamiento varía de acuerdo con la expresión $x(t) = 5 \cos(2t + \pi/6)$, donde $x$ está en $\text{cm}$ y $t$ en $\text{s}$. En $t = 0$ encuentre a) desplazamiento, b) velocidad, c) aceleración. d) Determinar el periodo y la amplitud del movimiento.

    Respuesta: a) $\displaystyle x(t) = 5 \cos(2t + \pi/6)$; b) $\displaystyle v(t) = -10 \sin(2t + \pi/6)$; c) $\displaystyle a(t) = -20 \cos(2t + \pi/6)$; En $t = 0$, $\displaystyle x = 4.33 \text{ cm}$, $\displaystyle v = -5 \text{ cm/s}$, $\displaystyle a = -17.32 \text{ cm/s}^{2}$; d) $\displaystyle T = \pi \text{ s}$, $\displaystyle A = 5 \text{ cm}$

70. En un M.A.S. la elongación en $\text{cm}$ es $x(t) = 0.4 \cos(10\pi t - \pi/3)$, siendo $t$ el tiempo en $\text{s}$. Calcular la elongación, velocidad y aceleración del móvil en los instantes $t = 0 \text{ s}$ y $t = 1/120 \text{ s}$.

    Respuesta: En $t = 0 \text{ s}$: $\displaystyle x = 0.2 \text{ cm}$, $\displaystyle v = 10.88 \text{ cm/s}$, $\displaystyle a = -197.39 \text{ cm/s}^{2}$

71. La elongación en $\text{cm}$ de un M.A.S. es $x = 4 \cos(10t)$, donde $t$ es el tiempo en $\text{s}$. Calcular la aceleración en el instante en que la elongación es de $3 \text{ cm}$.

    Respuesta: $\displaystyle a = -3 \text{ m/s}^{2}$

72. La ecuación de un M.A.S. es $x = 6 \cos(5t + \phi_{0})$, en la que $x$ es la elongación en $\text{cm}$ y $t$ el tiempo en $\text{s}$. Determinar la posición y velocidad del móvil en el instante $t = 0 \text{ s}$ si:

    a) $\phi_{0} = 0$; b) $\phi_{0} = \pi/3 \text{ rad}$; c) $\phi_{0} = \pi/2 \text{ rad}$; d) $\phi_{0} = \pi \text{ rad}$; e) Representar gráficamente las funciones del tiempo $x(t)$, $v(t)$ y $a(t)$ en cada uno de los incisos a) - d).

    Respuesta: a) $6 \text{ cm}$, $0 \text{ cm/s}$; b) $3 \text{ cm}$, $-25.98 \text{ cm/s}$; c) $0 \text{ cm}$, $-30 \text{ cm/s}$; d) $-6 \text{ cm}$, $0 \text{ cm/s}$

73. Discutir las diferencias entre los M.A.S. que tienen las siguientes ecuaciones de elongación: a) $x(t) = A \sin t$; b) $x(t) = A \cos t$.

74. La abscisa de un móvil en función del tiempo en $\text{s}$ es la función:

    $$
    \displaystyle x(t) = 4 \sin(10t) + 3 \cos(10t) \text{ (cm)}
    $$

    Expresar su aceleración en función del tiempo y demostrar que se trata de un M.A.S.

    Respuesta: $\displaystyle a(t) = -400 \sin(10t) - 300 \cos(10t)$, $a = [\text{cm/s}^{2}]$, $t = [\text{s}]$. Se trata de un M.A.S porque $\displaystyle a = -\omega^{2}x$

75. La velocidad de una masa de $0.500 \text{ kg}$ está dada en función del tiempo por

    $$
    \displaystyle v(t) = 3.60 \sin(4.71t - \pi/2) \text{ (m/s)}
    $$

    Calcule a) el periodo, b) la amplitud y c) la aceleración máxima de la masa.

    Respuesta: a) $\displaystyle T = 1.3340 \text{ s}$; b) $\displaystyle A = 0.7643 \text{ m}$; c) $\displaystyle a_{\max} = 16.956 \text{ m/s}^{2}$

76. La velocidad en $\text{m/s}$ de un M.A.S. es $v(t) = -0.36\pi \sin[\pi(24t + 1)]$, donde $t$ es el tiempo en $\text{s}$. ¿Cuáles son la frecuencia y la amplitud de ese movimiento? Escribir la expresión de su elongación en función del tiempo.

    Respuesta: $\displaystyle f = 12 \text{ Hz}$, $\displaystyle A = 0.015 \text{ m}$, $\displaystyle x(t) = 0.015 \cos[\pi(24t + 1)]$