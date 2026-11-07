# MOVIMIENTO DE UN OBJETO UNIDO A UN RESORTE

Como un modelo de movimiento armónico simple considere un bloque de masa $m$ unido al extremo de un resorte, con el bloque libre de moverse sobre una superficie horizontal sin fricción. Cuando el resorte no está estirado ni comprimido, el bloque queda en reposo, en la posición llamada posición de equilibrio del sistema, que se identifica como $x = 0$. Se sabe por la experiencia que tal sistema oscila de atrás para adelante si se perturba desde su posición de equilibrio.

Se puede entender cualitativamente el movimiento oscilatorio del bloque al recordar primero que, cuando el bloque se desplaza a una posición $x$, el resorte ejerce sobre el bloque una fuerza que es proporcional a la posición y se conoce por la ley de Hooke:

$$\displaystyle F_{s} = -k x \quad \color{red}{(1)}$$

A $F_{s}$ se le llama fuerza restauradora porque siempre se dirige hacia la posición de equilibrio y, en consecuencia, es opuesta al desplazamiento del bloque desde el equilibrio. Es decir, cuando el bloque se desplaza hacia la derecha de $x = 0$, la posición es positiva y la fuerza restauradora se dirige hacia la izquierda. En $x = 0$, la fuerza en el bloque es cero. Cuando el bloque se desplaza a la izquierda de $x = 0$, la posición es negativa y la fuerza restauradora se dirige hacia la derecha.

Al aplicar la segunda ley de Newton al movimiento del bloque, con la ecuación $\color{red}{(1)}$ que proporciona la fuerza neta en la dirección $x$, se obtiene:

$$\displaystyle -k x = m a_{x}$$

$$\displaystyle a_{x} = -\frac{k}{m} x \quad \color{red}{(2)}$$

Es decir, la aceleración del bloque es proporcional a su posición, y la dirección de la aceleración es opuesta a la dirección del desplazamiento del bloque desde el equilibrio. Se dice que los sistemas que se comportan de esta forma exhiben movimiento armónico simple. Un objeto se mueve con movimiento armónico simple siempre que su aceleración es proporcional a su posición y se dirige en sentido opuesto al desplazamiento desde el equilibrio.

Si el bloque se desplaza a una posición $x = A$ y se libera desde el reposo, su aceleración inicial es $-\frac{k A}{m}$. Cuando el bloque pasa a través de la posición de equilibrio $x = 0$, su aceleración es cero. En este instante, su rapidez es un máximo porque la aceleración cambia de signo. Por lo tanto el bloque continúa viajando hacia la izquierda del equilibrio con una aceleración positiva y al final llega a $x = -A$, momento en el que su aceleración es $+\frac{k A}{m}$ y su rapidez de nuevo es cero. El bloque termina un ciclo completo de su movimiento cuando regresa a la posición original y una vez más pasa por $x = 0$ con rapidez máxima. En consecuencia, el bloque oscila entre los puntos de retorno $x = \pm A$. En ausencia de fricción, este movimiento idealizado continuará por siempre porque la fuerza que ejerce el resorte es conservativa. Por lo general, los sistemas reales están sujetos a fricción, así que no oscilan por siempre.

---

## Partícula en movimiento armónico simple

El movimiento descrito en la sección precedente se presenta con tanta frecuencia que se considera el modelo de partícula en movimiento armónico simple para representar tales situaciones. Con el fin de elaborar una representación matemática para este modelo, primero se reconoce que el bloque es una partícula bajo una fuerza neta, como se describe en la ecuación $\color{red}{(1)}$. Por lo general se elegirá $x$ como el eje a lo largo del que se presenta la oscilación; por eso, en esta explicación se eliminará la notación de subíndice $x$. Recuerde que, por definición, $\displaystyle a = \frac{d v}{d t} = \frac{d^{2} x}{d t^{2}}$, y así la ecuación se puede expresar como:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\frac{k}{m} x \quad \color{red}{(3)}$$

Si la relación $\displaystyle \frac{k}{m}$ se indica con el símbolo $\omega^{2}$ (se elige $\omega^{2}$ en lugar de $\omega$ para que la solución que se desarrolle a continuación sea más simple en forma), en tal caso:

$$\displaystyle \omega^{2} = \frac{k}{m} \quad \color{red}{(4)}$$

y la ecuación $\color{red}{(3)}$ se puede escribir en la forma:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\omega^{2} x \quad \color{red}{(5)}$$

Lo que necesitamos ahora es una solución para la ecuación $\color{red}{(5)}$, es decir, una función $x(t)$ que satisfaga esta ecuación diferencial de segundo orden.

La solución general de la ecuación diferencial es:

$$\displaystyle x(t) = c_{1} \cos(\omega t) + c_{2} \sin(\omega t) \quad \color{red}{(6)}$$

donde $c_{1}$ y $c_{2}$ son constantes arbitrarias. Se determinan por las condiciones iniciales.

Este es, obviamente, un movimiento periódico, por la naturaleza de las funciones seno y coseno. Por comodidad, preferimos expresar esta solución en términos de una sola función trigonométrica como:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}$$

Dado que el coseno de un ángulo no puede ser mayor que $1$, el factor $A$ corresponde al desplazamiento máximo llamado amplitud de las oscilaciones. La masa oscilará continuamente entre las posiciones $x = A$ y $x = -A$.

El tiempo durante el cual se completa un ciclo se llama período del movimiento:

$$\displaystyle T = \frac{2 \pi}{\omega} \quad \color{red}{(8)}$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$\displaystyle T = \frac{t}{n} \quad \color{red}{(9)}$$

La frecuencia de las oscilaciones es el número de oscilaciones por unidad de tiempo, y es igual a la inversa del período:

$$\displaystyle f = \frac{1}{T} \quad \color{red}{(10)}$$

$$\displaystyle f = \frac{\omega}{2 \pi} \quad \color{red}{(11)}$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$\displaystyle f = \frac{n}{t} \quad \color{red}{(12)}$$

Una unidad para la frecuencia es denominada Hertz (Hz) equivale al número de ciclos por segundo.

Observe que, en ausencia de cualquier efecto externo, la frecuencia depende sólo de las características de la masa y del resorte, y es independiente de las condiciones iniciales y de la gravedad. La frecuencia $\omega$ es un ejemplo de una frecuencia angular, que tiene unidades de radianes por segundo. El término:

$$\displaystyle \omega = \sqrt{\frac{k}{m}} \quad \color{red}{(13)}$$

se conoce como frecuencia angular natural o simplemente frecuencia natural del sistema.

---

## Posición, velocidad y aceleración en función del tiempo

### Posición de la partícula en función del tiempo
$$\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}$$

### Rapidez de la partícula en función del tiempo
Podemos obtener la rapidez de una partícula que experimenta un movimiento armónico simple diferenciando la ecuación $\color{red}{(7)}$ respecto del tiempo:

$$\displaystyle v(t) = \frac{d x}{d t}$$

$$\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \quad \color{red}{(14)}$$

### Aceleración de la partícula en función del tiempo
La aceleración de la partícula es:

$$\displaystyle a(t) = \frac{d v}{d t}$$

$$\displaystyle a(t) = -\omega^{2} A \cos(\omega t + \phi) \quad \color{red}{(15)}$$

---

## Convenio de signos para la posición inicial y la velocidad inicial

### Movimiento horizontal
Si el cuerpo se desplaza una posición $x_{0}$ hacia la derecha (estirando el resorte) y se inicia el movimiento, la posición inicial $x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $x_{0}$ hacia la izquierda (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $v_{0}$ hacia la derecha es positiva y hacia la izquierda es negativa.

### Movimiento vertical
Si el cuerpo se desplaza una posición $x_{0}$ hacia abajo (estirando el resorte) y se inicia el movimiento, la posición inicial $x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $x_{0}$ hacia arriba (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $v_{0}$ hacia abajo es positiva y hacia arriba es negativa.

---

## Amplitud y ángulo de fase en función de las condiciones iniciales

Suponga que la posición inicial $x_{0}$ y la velocidad inicial $v_{0}$ de un solo oscilador están dadas, es decir, en $t = 0$, $x = x_{0}$ y $v = v_{0}$. Obtenemos $\displaystyle c_{1} = x_{0}$ y $\displaystyle c_{2} = \frac{v_{0}}{\omega}$. La ecuación $\color{red}{(6)}$ se escribe como:

$$\displaystyle x(t) = x_{0} \cos(\omega t) + \frac{v_{0}}{\omega} \sin(\omega t) \quad \color{red}{(16)}$$

Al desarrollar la ecuación $\color{red}{(7)}$:

$$\displaystyle x(t) = A \cos(\omega t) \cos \phi - A \sin(\omega t) \sin \phi \quad \color{red}{(17)}$$

Comparando las ecuaciones $\color{red}{(16)}$ y $\color{red}{(17)}$, tenemos:

$$\displaystyle A \cos \phi = x_{0} \quad \color{red}{(18)}$$

$$\displaystyle -A \sin \phi = \frac{v_{0}}{\omega} \quad \color{red}{(19)}$$

Elevamos al cuadrado, sumamos cada ecuación y usando la identidad $\displaystyle \cos^{2} \phi + \sin^{2} \phi = 1$, tenemos:

$$\displaystyle x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2} = A^{2} \cos^{2} \phi + A^{2} \sin^{2} \phi = A^{2}$$

Eligiendo la raíz cuadrada positiva para $A$ obtenemos:

$$\displaystyle A = \sqrt{x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2}} \quad \color{red}{(20)}$$

El ángulo $\phi$ se llama ángulo de fase, y puede determinarse dividiendo la ecuación $\color{red}{(19)}$ entre la ecuación $\color{red}{(18)}$, para obtener:

$$\displaystyle \frac{-A \sin \phi}{A \cos \phi} = \frac{\frac{v_{0}}{\omega}}{x_{0}}$$

$$\displaystyle -\tan \phi = \frac{v_{0}}{\omega x_{0}}$$

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \color{red}{(21)}$$

### Casos particulares para el ángulo de fase
* Posición inicial: $x_{0} = A$, Velocidad inicial: $v_{0} = 0$: $\phi = 0$.
* Posición inicial: $x_{0} = -A$, Velocidad inicial: $v_{0} = 0$: $\phi = -\pi$.
* Posición inicial: $x_{0} = 0$, Velocidad inicial: $v_{0} > 0$: $\phi = -\pi/2$.
* Posición inicial: $x_{0} = 0$, Velocidad inicial: $v_{0} < 0$: $\phi = \pi/2$.

### Ajustes en el ángulo de fase (Caso general)
Si utilizamos la ecuación $\color{red}{(7)}$ como la ecuación del movimiento:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}$$

el ángulo de fase se determina según la ecuación $\color{red}{(21)}$:

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \color{red}{(21)}$$

Sin embargo, es necesario elegir el valor apropiado de $\phi$ dependiendo de los valores (signo) de la rapidez inicial ($v_{0}$) y la posición inicial ($x_{0}$) de la partícula. Entre:

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \text{y} \quad \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) - \pi$$

elegir como ángulo de fase el que cumpla las condiciones:
1. El signo de $\cos \phi$ coincide con el signo de $x_{0}$.
2. El signo de $\sin \phi$ coincide con el signo opuesto de $v_{0}$.

---

## Elongación máxima, velocidad máxima y aceleración máxima

A partir de la ecuación $\color{red}{(14)}$ se ve que, puesto que las funciones seno y coseno oscilan entre $\pm 1$, los valores extremos de la velocidad $v$ son $\pm \omega A$. Del mismo modo, la ecuación $\color{red}{(15)}$ muestra que los valores extremos de la aceleración $a$ son $\pm \omega^{2} A$. En consecuencia, los valores máximos de las magnitudes de la velocidad y la aceleración son:

$$\displaystyle v_{\max} = \omega A \quad \color{red}{(22)}$$

$$\displaystyle a_{\max} = \omega^{2} A \quad \color{red}{(23)}$$

La fase de la velocidad difiere de la fase de la posición en $\pi/2\text{ rad}$, o $90^{\circ}$. Es decir: cuando $x$ es un máximo o un mínimo, la velocidad es cero. Del mismo modo, cuando $x$ es cero, la rapidez es un máximo. Además, la fase de la aceleración difiere de la fase de la posición en $\pi\text{ rad}$, o $180^{\circ}$. Por ejemplo, cuando $x$ es un máximo, $a$ tiene una magnitud máxima en la dirección opuesta.

### Relación entre la aceleración máxima y la velocidad máxima
$$\displaystyle a_{\max} = \omega v_{\max} \quad \color{red}{(24)}$$

---

## Relación entre posición, velocidad y aceleración

### Relación entre la posición y la aceleración en el movimiento armónico simple
Puesto que $\displaystyle x(t) = A \cos(\omega t + \phi)$, podemos expresar la ecuación $\color{red}{(15)}$ en la forma:

$$\displaystyle a = -\omega^{2} x \quad \color{red}{(25)}$$

### Relación entre la posición y la velocidad en el movimiento armónico simple
Posición en función del tiempo:
$$\displaystyle x(t) = A \cos(\omega t + \phi) \quad \color{red}{(7)}$$

Rapidez en función del tiempo:
$$\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \quad \color{red}{(14)}$$

Al despejar $\cos(\omega t + \phi)$ de la ecuación $\color{red}{(7)}$ y $\sin(\omega t + \phi)$ de la ecuación $\color{red}{(14)}$:

$$\displaystyle \cos(\omega t + \phi) = \frac{x(t)}{A}$$

$$\displaystyle \sin(\omega t + \phi) = -\frac{v(t)}{\omega A}$$

Siendo $\cos^{2}(\omega t + \phi) + \sin^{2}(\omega t + \phi) = 1$ se tiene:

$$\displaystyle \left(\frac{x}{A}\right)^{2} + \left(\frac{v}{\omega A}\right)^{2} = 1$$

$$\displaystyle \frac{x^{2}}{A^{2}} + \frac{v^{2}}{\omega^{2} A^{2}} = 1$$

$$\displaystyle \frac{v^{2}}{\omega^{2} A^{2}} = 1 - \frac{x^{2}}{A^{2}}$$

$$\displaystyle \frac{v^{2}}{\omega^{2} A^{2}} = \frac{A^{2} - x^{2}}{A^{2}}$$

$$\displaystyle \frac{v^{2}}{\omega^{2}} = A^{2} - x^{2}$$

$$\displaystyle v^{2} = \omega^{2}(A^{2} - x^{2})$$

$$\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \quad \color{red}{(26)}$$

### Relación entre la velocidad y la aceleración en el movimiento armónico simple
Rapidez de la partícula:
$$\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \quad \color{red}{(27)}$$

Aceleración de la partícula:
$$\displaystyle a = -\omega^{2} x \quad \color{red}{(25)}$$

De la ecuación $\color{red}{(25)}$:
$$\displaystyle x = -\frac{a}{\omega^{2}}$$

Al sustituir en la ecuación $\color{red}{(27)}$:

$$\displaystyle v = \omega \sqrt{A^{2} - \left(-\frac{a}{\omega^{2}}\right)^{2}}$$

$$\displaystyle v = \omega \sqrt{A^{2} - \frac{a^{2}}{\omega^{4}}}$$

$$\displaystyle v^{2} = \omega^{2}\left(A^{2} - \frac{a^{2}}{\omega^{4}}\right)$$

$$\displaystyle v^{2} = \omega^{2} A^{2} - \frac{a^{2}}{\omega^{2}}$$

$$\displaystyle \frac{a^{2}}{\omega^{2}} = \omega^{2} A^{2} - v^{2}$$

$$\displaystyle a^{2} = \omega^{2}(\omega^{2} A^{2} - v^{2})$$

$$\displaystyle a = \omega \sqrt{\omega^{2} A^{2} - v^{2}} \quad \color{red}{(28)}$$

---

## RESPUESTAS DE LOS EJERCICIOS 1 AL 15

* **EJERCICIO 1.** Respuesta: $\displaystyle T = 0.5539\text{ s}$
* **EJERCICIO 2.** Respuesta: a) $\displaystyle m = 0.9372\text{ kg}$; b) $\displaystyle m = 0.0586\text{ kg}$
* **EJERCICIO 3.** Respuesta: a) $\displaystyle \omega = 5529.20\text{ rad/s}$ (o $\displaystyle f = 880\text{ Hz}$); b) $\displaystyle T = 0.00114\text{ s}$
* **EJERCICIO 4.** Respuesta: a) $\displaystyle T = 0.00455\text{ s}$, $\displaystyle \omega = 1382.30\text{ rad/s}$; b) $\displaystyle T = 0.00114\text{ s}$, $\displaystyle \omega = 5529.20\text{ rad/s}$
* **EJERCICIO 5.** Respuesta: a) $\displaystyle T = 0.3755\text{ s}$; b) $\displaystyle f = 2.6631\text{ Hz}$; c) $\displaystyle \omega = 16.73\text{ rad/s}$
* **EJERCICIO 6.** Respuesta: a) $\displaystyle A = 0.120\text{ m}$; b) $\displaystyle T = 1.600\text{ s}$; c) $\displaystyle f = 0.625\text{ Hz}$
* **EJERCICIO 7.** Respuesta: a) $\displaystyle k = 27.42\text{ N/m}$; b) $\displaystyle L = 38.94\text{ cm}$
* **EJERCICIO 8.** Respuesta: $\displaystyle t = 0.05\text{ s}$
* **EJERCICIO 9.** Respuesta: $\displaystyle k = 1052.76\text{ N/m}$
* **EJERCICIO 10.** Respuesta: a) $\displaystyle k = 320\text{ N/m}$; b) $\displaystyle f = \frac{1}{\pi}\text{ Hz}$
* **EJERCICIO 11.** Respuesta: a) $\displaystyle T = 0.1667\text{ s}$; b) $\displaystyle \omega = 37.70\text{ rad/s}$; c) $\displaystyle m = 0.0844\text{ kg}$
* **EJERCICIO 12.** Respuesta: a) $\displaystyle \omega = 12.79\text{ rad/s}$; b) Si se varía la masa del cuerpo, cambia la frecuencia angular; c) $\displaystyle \omega = 9.90\text{ rad/s}$, $\displaystyle T = 0.6346\text{ s}$
* **EJERCICIO 13.** Respuesta: $\displaystyle f = 1.18\text{ Hz}$, $\displaystyle f = 1.25\text{ Hz}$
* **EJERCICIO 14.** Respuesta: $\displaystyle m_{p} = 119.74\text{ kg}$
* **EJERCICIO 15.** Respuesta: a) $\displaystyle f_{1} = 2.04\text{ Hz}$; b) $\displaystyle f_{2} = 1.44\text{ Hz}$