<div style="font-family: 'Times New Roman', Times, serif; font-size: 12pt; line-height: 1.6; text-align: justify;">

<a id="inicio"></a>

<div style="text-align: center;">

# PROBLEMAS PROPUESTOS DE FÍSICA III
### OSCILACIONES Y ONDAS PARA ESTUDIANTES DE INGENIERÍA, CIENCIA Y TECNOLOGÍA
## MOVIMIENTO ARMÓNICO SIMPLE

**Física III. Ing. Willians Medina**  
*Puerto La Cruz, enero de 2005*

---

</div>

<a id="indice"></a>

## Contenido

* [Movimiento de un objeto unido a un resorte](#seccion-1)
* [Partícula en movimiento armónico simple](#seccion-2)
  * [EJERCICIOS](#ejercicios-1)
* [Posición, velocidad y aceleración en función del tiempo](#seccion-3)
  * [Posición de la partícula en función del tiempo](#subseccion-3-1)
  * [Rapidez de la partícula en función del tiempo](#subseccion-3-2)
  * [Aceleración de la partícula en función del tiempo](#subseccion-3-3)
  * [Convenio de signos para la posición inicial y la velocidad inicial](#subseccion-3-4)
  * [Amplitud y ángulo de fase en función de las condiciones iniciales](#subseccion-3-5)
  * [Casos particulares para el ángulo de fase](#subseccion-3-6)
  * [Ajustes en el ángulo de fase (Caso general)](#subseccion-3-7)
  * [EJERCICIOS](#ejercicios-2)
    * [Inicialmente está en el extremo derecho (inferior) de la trayectoria con velocidad nula ($\phi=0$)](#caso-1)
    * [Inicialmente está en el extremo izquierdo (superior) de la trayectoria con velocidad nula ($\phi=-\pi$)](#caso-2)
    * [Inicialmente está en el punto de equilibrio y se desplaza hacia la derecha (abajo) ($\phi=-\pi/2$)](#caso-3)
    * [Inicialmente está en el punto de equilibrio y se desplaza hacia la izquierda (arriba) ($\phi=\pi/2$)](#caso-4)
    * [Inicialmente no está en el extremo de la trayectoria ni tiene velocidad inicial nula](#caso-5)
* [Elongación máxima, velocidad máxima y aceleración máxima](#seccion-4)
  * [Relación entre la aceleración máxima y la velocidad máxima](#subseccion-4-1)
  * [EJERCICIOS](#ejercicios-3)
* [Relación entre posición, velocidad y aceleración](#seccion-5)
  * [Relación entre la posición y la aceleración en el movimiento armónico simple](#subseccion-5-1)
  * [Relación entre la posición y la velocidad en el movimiento armónico simple](#subseccion-5-2)
  * [Relación entre la velocidad y la aceleración en el movimiento armónico simple](#subseccion-5-3)
  * [EJERCICIOS](#ejercicios-4)
* [Problemas que involucran gráficas](#seccion-6)
  * [Conocida la ecuación del movimiento](#subseccion-6-1)
* [El péndulo](#seccion-7)
  * [EJERCICIOS](#ejercicios-5)
* [Circuitos LC](#seccion-8)
  * [EJERCICIOS](#ejercicios-6)
* [Energía del oscilador armónico simple](#seccion-9)
  * [EJERCICIOS](#ejercicios-7)

---

<a id="seccion-1"></a>
### Movimiento de un objeto unido a un resorte [↑](#indice)

Como un modelo de movimiento armónico simple considere un bloque de masa $\displaystyle m$ unido al extremo de un resorte, con el bloque libre de moverse sobre una superficie horizontal sin fricción. Cuando el resorte no está estirado ni comprimido, el bloque queda en reposo, en la posición llamada posición de equilibrio del sistema, que se identifica como $\displaystyle x=0$. Se sabe por la experiencia que tal sistema oscila de atrás para adelante si se perturba desde su posición de equilibrio.

Se puede entender cualitativamente el movimiento oscilatorio del bloque al recordar primero que, cuando el bloque se desplaza a una posición $\displaystyle x$, el resorte ejerce sobre el bloque una fuerza que es proporcional a la posición y se conoce por la ley de Hooke:

$$\displaystyle F_{s} = -k x \tag{\color{red}{1}}$$

A $\displaystyle F_{s}$ se le llama fuerza restauradora porque siempre se dirige hacia la posición de equilibrio y, en consecuencia, es opuesta al desplazamiento del bloque desde el equilibrio. Es decir, cuando el bloque se desplaza hacia la derecha de $\displaystyle x=0$, la posición es positiva y la fuerza restauradora se dirige hacia la izquierda. Cuando el bloque está en $\displaystyle x=0$, la fuerza en el bloque es cero. Cuando el bloque se desplaza a la izquierda de $\displaystyle x=0$, la posición es negativa y la fuerza restauradora se dirige hacia la derecha.

Al aplicar la segunda ley de Newton al movimiento del bloque, con la ecuación $\displaystyle \tag{\color{red}{1}}$ que proporciona la fuerza neta en la dirección $\displaystyle x$, se obtiene:

$$\displaystyle -k x = m a_{x}$$

$$\displaystyle a_{x} = -\frac{k}{m}x \tag{\color{red}{2}}$$

Es decir, la aceleración del bloque es proporcional a su posición, y la dirección de la aceleración es opuesta a la dirección del desplazamiento del bloque desde el equilibrio. Se dice que los sistemas que se comportan de esta forma exhiben movimiento armónico simple. Un objeto se mueve con movimiento armónico simple siempre que su aceleración es proporcional a su posición y se dirige en sentido opuesto al desplazamiento desde el equilibrio.

Si el bloque se desplaza a una posición $\displaystyle x=A$ y se libera desde el reposo, su aceleración inicial es $\displaystyle -k A / m$. Cuando el bloque pasa a través de la posición de equilibrio $\displaystyle x=0$, su aceleración es cero. En este instante, su rapidez es un máximo porque la aceleración cambia de signo. Por lo tanto el bloque continúa viajando hacia la izquierda del equilibrio con una aceleración positiva y al final llega a $\displaystyle x=-A$, momento en el que su aceleración es $\displaystyle +k A / m$ y su rapidez de nuevo es cero. El bloque termina un ciclo completo de su movimiento cuando regresa a la posición original y una vez más pasa por $\displaystyle x=0$ con rapidez máxima. En consecuencia, el bloque oscila entre los puntos de retorno $\displaystyle x = \pm A$. En ausencia de fricción, este movimiento idealizado continuará por siempre porque la fuerza que ejerce el resorte es conservativa. Por lo general, los sistemas reales están sujetos a fricción, así que no oscilan por siempre.

---

<a id="seccion-2"></a>
### Partícula en movimiento armónico simple [↑](#indice)

El movimiento descrito en la sección precedente se presenta con tanta frecuencia que se considera el modelo de partícula en movimiento armónico simple para representar tales situaciones. Con el fin de elaborar una representación matemática para este modelo, primero se reconoce que el bloque es una partícula bajo una fuerza neta, como se describe en la ecuación $\displaystyle \tag{\color{red}{1}}$. Por lo general se elegirá $\displaystyle x$ como el eje a lo largo del que se presenta la oscilación; por eso, en esta explicación se eliminará la notación de subíndice $\displaystyle x$. Recuerde que, por definición, $\displaystyle a = \frac{d v}{d t} = \frac{d^{2} x}{d t^{2}}$, y así la ecuación se puede expresar como:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\frac{k}{m} x \tag{\color{red}{3}}$$

Si la relación $\displaystyle k/m$ se indica con el símbolo $\displaystyle \omega^{2}$ (se elige $\displaystyle \omega^{2}$ en lugar de $\displaystyle \omega$ para que la solución que se desarrolle a continuación sea más simple en forma), en tal caso:

$$\displaystyle \omega^{2} = \frac{k}{m} \tag{\color{red}{4}}$$

y la ecuación $\displaystyle \tag{\color{red}{3}}$ se puede escribir en la forma:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\omega^{2} x \tag{\color{red}{5}}$$

Lo que necesitamos ahora es una solución para la ecuación $\displaystyle \tag{\color{red}{5}}$, es decir, una función $\displaystyle x(t)$ que satisfaga esta ecuación diferencial de segundo orden.

La solución general de la ecuación diferencial es:

$$\displaystyle x(t) = c_{1} \cos(\omega t) + c_{2} \sin(\omega t) \tag{\color{red}{6}}$$

donde $\displaystyle c_{1}$ y $\displaystyle c_{2}$ son constantes arbitrarias. Se determinan por las condiciones iniciales. Este es, obviamente, un movimiento periódico, por la naturaleza de las funciones seno y coseno. Por comodidad, preferimos expresar esta solución en términos de una sola función trigonométrica como:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \tag{\color{red}{7}}$$

Dado que el coseno de un ángulo no puede ser mayor que 1, el factor $\displaystyle A$ corresponde al desplazamiento máximo llamado amplitud de las oscilaciones. La masa oscilará continuamente entre las posiciones $\displaystyle x = A$ y $\displaystyle x = -A$.

El tiempo durante el cual se completa un ciclo se llama periodo del movimiento:

$$\displaystyle T = \frac{2\pi}{\omega} \tag{\color{red}{8}}$$

Si se conoce el número de oscilaciones o ciclos ($\displaystyle n$) de la partícula en un lapso de tiempo ($\displaystyle t$):

$$\displaystyle T = \frac{t}{n} \tag{\color{red}{9}}$$

La frecuencia de las oscilaciones es el número de oscilaciones por unidad de tiempo, y es igual a la inversa del periodo:

$$\displaystyle f = \frac{1}{T} \tag{\color{red}{10}}$$

$$\displaystyle f = \frac{\omega}{2\pi} \tag{\color{red}{11}}$$

Si se conoce el número de oscilaciones o ciclos ($\displaystyle n$) de la partícula en un lapso de tiempo ($\displaystyle t$):

$$\displaystyle f = \frac{n}{t} \tag{\color{red}{12}}$$

Una unidad para la frecuencia es denominada Hertz ($\text{Hz}$) que equivale al número de ciclos por segundo.

Observe que, en ausencia de cualquier efecto externo, la frecuencia depende sólo de las características de la masa y del resorte, y es independiente de las condiciones iniciales y de la gravedad. La frecuencia $\displaystyle \omega$ es un ejemplo de una frecuencia angular, que tiene unidades de radianes por segundo. El término:

$$\displaystyle \omega = \sqrt{\frac{k}{m}} \tag{\color{red}{13}}$$

se conoce como frecuencia angular natural o simplemente frecuencia natural del sistema.

---

<a id="ejercicios-1"></a>
#### EJERCICIOS [↑](#indice)

1) Una masa que pesa 4 libras se une a un resorte cuya constante es $\displaystyle 16 \text{ lb/pie}$. ¿Cuál es el periodo del movimiento armónico simple?  
*Respuesta:* $\displaystyle T = 0.5539 \text{ s}$

2) a) ¿Qué masa debes unir a un muelle de constante $\displaystyle k = 37 \text{ N/m}$ para que la frecuencia de oscilación del sistema sea de $1\text{ Hz}$? b) ¿Y para que sea de $4\text{ Hz}$?  
*Respuesta:* a) $\displaystyle m = 0.9372 \text{ kg}$; b) $\displaystyle m = 0.0586 \text{ kg}$

3) La punta de un diapasón efectúa 440 vibraciones completas en $0.500\text{ s}$. Calcule a) la frecuencia angular y b) el periodo del movimiento.  
*Respuesta:* a) $\displaystyle \omega = 5529.20 \text{ rad/s}$; b) $\displaystyle T = 0.00114 \text{ s}$

4) Una cuerda de piano produce un "la medio" vibrando primordialmente a $220\text{ Hz}$. a) Calcule su periodo y frecuencia angular. b) Calcule el periodo y la frecuencia angular de una soprano que canta un "la alto", dos octavas más arriba, que es cuatro veces la frecuencia de la cuerda de piano.  
*Respuesta:* a) $\displaystyle T = 0.00455 \text{ s}, \omega = 1382.30 \text{ rad/s}$; b) $\displaystyle T = 0.00114 \text{ s}, \omega = 5529.20 \text{ rad/s}$

5) Un oscilador armónico tiene una masa de $0.500\text{ kg}$ y un resorte ideal con $\displaystyle k = 140 \text{ kg/s}^{2}$. Calcule: a) el periodo; b) la frecuencia; c) la frecuencia angular.  
*Respuesta:* a) $\displaystyle T = 0.3755 \text{ s}$; b) $\displaystyle f = 2.6631 \text{ Hz}$; c) $\displaystyle \omega = 16.73 \text{ rad/s}$

6) Si un objeto en una superficie horizontal sin fricción se une a un resorte, se desplaza y después se suelta, oscilará. Si se desplaza $0.120\text{ m}$ de su posición de equilibrio y se suelta con rapidez inicial cero, después de $0.800\text{ s}$ su desplazamiento es de $0.120\text{ m}$ en el lado opuesto, habiendo pasado por la posición de equilibrio una vez. Calcule: a) la amplitud; b) el periodo; c) la frecuencia.  
*Respuesta:* a) $\displaystyle A = 0.120 \text{ m}$; b) $\displaystyle T = 1.600 \text{ s}$; c) $\displaystyle f = 0.625 \text{ Hz}$

7) Un resorte tiene una longitud de $30\text{ cm}$. Si se cuelga de él un cuerpo de masa $250\text{ g}$ y se le hace oscilar verticalmente, emplea $6\text{ s}$ en realizar 10 oscilaciones completas. Calcular a) la constante elástica del resorte y b) su longitud cuando dicho cuerpo está colgado de él, en reposo.  
*Respuesta:* a) $\displaystyle k = 27.42 \text{ N/m}$; b) $\displaystyle L = 38.94 \text{ cm}$

8) Una pieza de una máquina está en MAS con frecuencia de $5.00\text{ Hz}$ y amplitud de $1.80\text{ cm}$. ¿Cuánto tarda la pieza en ir de $\displaystyle x=0$ a $\displaystyle x=-1.80 \text{ cm}$?  
*Respuesta:* $\displaystyle t = 0.05 \text{ s}$

9) Se crea un oscilador armónico usando un bloque de $0.600\text{ kg}$, que se desliza sobre una superficie sin fricción y un resorte ideal con constante de fuerza desconocida. Se determina que el oscilador tiene un periodo de $0.150\text{ s}$. Calcule la constante de fuerza del resorte.  
*Respuesta:* $\displaystyle k = 1052.76 \text{ N/m}$

10) Una masa de 20 kilogramos se une a un resorte. Si la frecuencia del movimiento armónico simple es $\displaystyle 2/\pi \text{ ciclos/s}$ a) ¿cuál es la constante del resorte $\displaystyle k$? b) ¿Cuál es la frecuencia del movimiento armónico simple si la masa original se reemplaza con una masa de 80 kilogramos?  
*Respuesta:* a) $\displaystyle k = 320 \text{ N/m}$; b) $\displaystyle f = 1/\pi \text{ Hz}$

11) Un cuerpo de masa desconocida se une a un resorte lineal ideal con constante de fuerza de $\displaystyle 120 \text{ kg/s}^{2}$. Se observa que vibra a una frecuencia de $6.00\text{ Hz}$. Calcule: a) el periodo; b) la frecuencia angular; c) la masa del cuerpo.  
*Respuesta:* a) $\displaystyle T = 0.1667 \text{ s}$; b) $\displaystyle \omega = 37.70 \text{ rad/s}$; c) $\displaystyle m = 0.0844 \text{ kg}$

12) Un cuerpo de $300\text{ g}$ se encuentra unido al techo a través de un muelle. El peso del cuerpo hace que el muelle se deforme $6\text{ cm}$. Determinar:  
a) Cuál será la frecuencia angular de oscilación del cuerpo cuando se desplaza de su posición de equilibrio.  
b) Qué ocurriría al variar la masa del cuerpo a $500\text{ g}$.  
c) Determina para este último caso la frecuencia angular y el periodo.  
*Respuesta:* a) $\displaystyle \omega = 12.79 \text{ rad/s}$; b) Si se varía la masa del cuerpo, cambia la frecuencia angular; c) $\displaystyle \omega = 9.90 \text{ rad/s}, T = 0.6346 \text{ s}$

13) ¡Cuidado con los baches! Un automóvil con una masa de $1300\text{ kg}$ se construye de modo que su chasis está sostenido mediante cuatro amortiguadores. Cada amortiguador tiene una constante de fuerza de $\displaystyle 20000 \text{ N/m}$. Dos personas que viajan en el automóvil tienen una masa combinada de $160\text{ kg}$. Encuentre la frecuencia de vibración del automóvil después de que pasa sobre un bache en el camino. Suponga que el automóvil se detiene al lado del camino y las dos personas salen del auto. Una de ellas presiona hacia abajo el automóvil y lo libera de modo que oscile en la vertical. ¿La frecuencia de la oscilación es la misma que el valor recién calculado?  
*Respuesta:* $\displaystyle f = 1.18 \text{ Hz}$. Si las personas se bajan del carro: $\displaystyle f = 1.25 \text{ Hz}$

14) Una silla de $42.5\text{ kg}$ se sujeta a un resorte y se le permite oscilar. Cuando la silla está vacía, tarda $1.30\text{ s}$ en efectuar una vibración completa. Cuando una persona se sienta en ella, sin tocar el piso con los pies, la silla tarda $2.54\text{ s}$ en efectuar un ciclo. Calcule la masa de la persona.  
*Respuesta:* $\displaystyle m_{p} = 119.74 \text{ kg}$

15) Un resorte se mantiene vertical apoyado en el suelo. Se coloca un cuerpo de masa $\displaystyle m$ en reposo sobre el resorte y se observa que éste se acorta $6\text{ cm}$. Si empujamos ligeramente el cuerpo hacia abajo y lo soltamos, a) ¿cuál será la frecuencia de las oscilaciones? b) ¿y si la masa del cuerpo fuese $\displaystyle 2m$?  
*Respuesta:* a) $\displaystyle f_{1} = 2.04 \text{ Hz}$; b) $\displaystyle f_{2} = 1.44 \text{ Hz}$

---

<a id="seccion-3"></a>
### Posición, velocidad y aceleración en función del tiempo [↑](#indice)

<a id="subseccion-3-1"></a>
#### Posición de la partícula en función del tiempo

$$\displaystyle x(t) = A \cos(\omega t + \phi) \tag{\color{red}{7}}$$

<a id="subseccion-3-2"></a>
#### Rapidez de la partícula en función del tiempo

Podemos obtener la rapidez de una partícula que experimenta un movimiento armónico simple diferenciando la ecuación $\displaystyle \tag{\color{red}{7}}$ respecto del tiempo:

$$\displaystyle v(t) = \frac{dx}{dt}$$

$$\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \tag{\color{red}{14}}$$

<a id="subseccion-3-3"></a>
#### Aceleración de la partícula en función del tiempo

La aceleración de la partícula es:

$$\displaystyle a(t) = \frac{dv}{dt}$$

$$\displaystyle a(t) = -\omega^{2} A \cos(\omega t + \phi) \tag{\color{red}{15}}$$

<a id="subseccion-3-4"></a>
#### Convenio de signos para la posición inicial y la velocidad inicial

**Movimiento horizontal.**  
Si el cuerpo se desplaza una posición $\displaystyle x_{0}$ hacia la derecha (estirando el resorte) y se inicia el movimiento, la posición inicial $\displaystyle x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $\displaystyle x_{0}$ hacia la izquierda (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $\displaystyle v_{0}$ hacia la derecha es positiva y hacia la izquierda es negativa.

**Movimiento vertical.**  
Si el cuerpo se desplaza una posición $\displaystyle x_{0}$ hacia abajo (estirando el resorte) y se inicia el movimiento, la posición inicial $\displaystyle x_{0}$ es positiva, mientras que si el cuerpo se desplaza una posición $\displaystyle x_{0}$ hacia arriba (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $\displaystyle v_{0}$ hacia abajo es positiva y hacia arriba es negativa.

<a id="subseccion-3-5"></a>
#### Amplitud y ángulo de fase en función de las condiciones iniciales

Suponga que la posición inicial $\displaystyle x_{0}$ y la velocidad inicial $\displaystyle v_{0}$ de un solo oscilador están dadas, es decir, en $\displaystyle t=0$, $\displaystyle x=x_{0}$ y $\displaystyle v=v_{0}$. Obtenemos $\displaystyle c_{1} = x_{0}$ y $\displaystyle c_{2} = \frac{v_{0}}{\omega}$. La ecuación $\displaystyle \tag{\color{red}{6}}$ se escribe como:

$$\displaystyle x(t) = x_{0} \cos(\omega t) + \frac{v_{0}}{\omega} \sin(\omega t) \tag{\color{red}{16}}$$

Al desarrollar la ecuación $\displaystyle \tag{\color{red}{7}}$:

$$\displaystyle x(t) = A \cos(\omega t) \cos \phi - A \sin(\omega t) \sin \phi \tag{\color{red}{17}}$$

Comparando las ecuaciones $\displaystyle \tag{\color{red}{16}}$ y $\displaystyle \tag{\color{red}{17}}$, tenemos:

$$\displaystyle A \cos \phi = x_{0} \tag{\color{red}{18}}$$

$$\displaystyle -A \sin \phi = \frac{v_{0}}{\omega} \tag{\color{red}{19}}$$

Elevamos al cuadrado, sumamos cada ecuación y usando la identidad $\displaystyle \cos^{2}\phi + \sin^{2}\phi = 1$, tenemos:

$$\displaystyle x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2} = A^{2} \cos^{2}\phi + A^{2} \sin^{2}\phi = A^{2}$$

Eligiendo la raíz cuadrada positiva para $\displaystyle A$ obtenemos:

$$\displaystyle A = \sqrt{x_{0}^{2} + \left(\frac{v_{0}}{\omega}\right)^{2}} \tag{\color{red}{20}}$$

El ángulo $\displaystyle \phi$ se llama ángulo de fase, y puede determinarse dividiendo la ecuación $\displaystyle \tag{\color{red}{19}}$ entre la ecuación $\displaystyle \tag{\color{red}{18}}$, para obtener:

$$\displaystyle \frac{-A \sin \phi}{A \cos \phi} = \frac{\frac{v_{0}}{\omega}}{x_{0}}$$

$$\displaystyle -\tan \phi = \frac{v_{0}}{\omega x_{0}}$$

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \tag{\color{red}{21}}$$

<a id="subseccion-3-6"></a>
#### Casos particulares para el ángulo de fase

* Posición inicial: $\displaystyle x_{0} = A$, Velocidad inicial: $\displaystyle v_{0} = 0 \implies \phi = 0$
* Posición inicial: $\displaystyle x_{0} = -A$, Velocidad inicial: $\displaystyle v_{0} = 0 \implies \phi = -\pi$
* Posición inicial: $\displaystyle x_{0} = 0$, Velocidad inicial: $\displaystyle v_{0} > 0 \implies \phi = -\pi/2$
* Posición inicial: $\displaystyle x_{0} = 0$, Velocidad inicial: $\displaystyle v_{0} < 0 \implies \phi = \pi/2$

<a id="subseccion-3-7"></a>
#### Ajustes en el ángulo de fase (Caso general)

Si utilizamos la ecuación $\displaystyle \tag{\color{red}{7}}$ como la ecuación del movimiento:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \tag{\color{red}{7}}$$

el ángulo de fase se determina según la ecuación $\displaystyle \tag{\color{red}{21}}$:

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \tag{\color{red}{21}}$$

Sin embargo, es necesario elegir el valor apropiado de $\displaystyle \phi$ dependiendo de los valores (signo) de la rapidez inicial ($\displaystyle v_{0}$) y la posición inicial ($\displaystyle x_{0}$) de la partícula.

Entre:

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) \quad \text{y} \quad \phi = \tan^{-1}\left(-\frac{v_{0}}{\omega x_{0}}\right) - \pi$$

elegir como ángulo de fase el que cumpla las condiciones:
* El signo de $\displaystyle \cos\phi$ coincide con el signo de $\displaystyle x_{0}$, y
* El signo de $\displaystyle \sin\phi$ coincide con el signo opuesto de $\displaystyle v_{0}$.

---

<a id="ejercicios-2"></a>
#### EJERCICIOS [↑](#indice)

<a id="caso-1"></a>
##### Inicialmente está en el extremo derecho (inferior) de la trayectoria con velocidad nula ($\phi=0$).

16) Se hace oscilar verticalmente un cuerpo de masa $80\text{ g}$ que está colgado de un muelle en hélice de constante elástica $\displaystyle 2 \text{ N/m}$. Si la amplitud de la oscilación es de $10\text{ cm}$, ¿cuál será la expresión de su elongación en función del tiempo?  
*Respuesta:* $\displaystyle x(t) = 10 \cos(5t + \phi_{0})$ con $\displaystyle t$ en $[\text{s}]$ y $\displaystyle x$ en $[\text{cm}]$.

17) La aceleración (en $\text{m/s}^{2}$) de un M.A.S. en función de la elongación (en $\text{m}$) es $\displaystyle a = -256 x$. Expresar esta aceleración en función del tiempo sabiendo que la amplitud de la vibración es de $2.5\text{ cm}$. Considérese nula la constante de fase.  
*Respuesta:* $\displaystyle a(t) = -6.4 \cos(16t)$

18) Un cuerpo de masa $\displaystyle m = 2 \text{ kg}$ está unido a un muelle horizontal de constante $\displaystyle k = 5 \text{ N/m}$. El muelle se alarga $10\text{ cm}$ y se suelta en el instante inicial $\displaystyle t=0$. Hallar:  
a) La frecuencia, el período y la amplitud del movimiento. Escribir la ecuación del M.A.S.  
b) ¿En qué instante pasa el cuerpo por primera vez por la posición de equilibrio?  
*Respuesta:* a) $\displaystyle f = 0.2515 \text{ Hz}, T = 3.98 \text{ s}, A = 0.1 \text{ m}, x(t) = 0.1 \cos(1.58t)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; b) $\displaystyle t = 0.994 \text{ s}$

19) Una masa que pesa 20 libras alarga a un resorte 6 pulgadas. La masa se libera al inicio desde el reposo de un punto 6 pulgadas abajo de la posición de equilibrio.  
a) Encuentre la posición de la masa en los tiempos $\displaystyle t = \pi/12, \pi/8, \pi/6, \pi/4$ y $\displaystyle 9\pi/32 \text{ s}$.  
b) ¿Cuál es la velocidad de la masa cuando $\displaystyle t = 3\pi/16 \text{ s}$? ¿En qué dirección se dirige la masa en este instante?  
c) ¿En qué tiempos la masa pasa por la posición de equilibrio?

20) Una partícula describe un movimiento armónico simple con una frecuencia de $10\text{ Hz}$ y una amplitud de $5\text{ cm}$. Calcular:  
a) Las funciones de la elongación y de la velocidad de la partícula si para $\displaystyle t=0$ está en la posición $\displaystyle x = +5 \text{ cm}$.  
b) La aceleración para $\displaystyle t = 2 \text{ s}$.  
*Respuesta:* a) $\displaystyle x(t) = 0.05 \cos(20\pi t) \text{ m}, v(t) = -\pi \sin(20\pi t) \text{ m/s}$; b) $\displaystyle a(2\text{ s}) = 197.39 \text{ m/s}^{2}$

21) Una partícula describe un movimiento armónico simple con un periodo de $2\text{ s}$ y una amplitud de $25\text{ cm}$. Calcular:  
a) Las funciones de la elongación y de la velocidad de la partícula si para $\displaystyle t=0$ está en la posición $\displaystyle x = +25 \text{ cm}$.  
b) La aceleración para $\displaystyle t = 3 \text{ s}$.  
*Respuesta:* a) $\displaystyle x(t) = 0.25 \cos(\pi t) \text{ m}, v(t) = -0.25\pi \sin(\pi t) \text{ m/s}$; b) $\displaystyle a(3\text{ s}) = 2.47 \text{ m/s}^{2}$

22) Estiramos un resorte $5\text{ cm}$ y lo dejamos oscilar libremente resultando que completa una oscilación cada $0.2\text{ s}$. Calcular:  
a) La función que nos permite calcular su posición en función del tiempo.  
b) La velocidad y la aceleración a la que estará sometido el extremo libre a los $15\text{ s}$ de iniciado el movimiento.  
*Respuesta:* a) $\displaystyle x(t) = 0.05 \cos(10\pi t)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; b) $\displaystyle v(15\text{ s}) = 0 \text{ m/s}, a(15\text{ s}) = -49.35 \text{ m/s}^{2}$

23) Una partícula que se mueve de acuerdo a un movimiento armónico simple tarda $1\text{ s}$ en llegar de un extremo a otro de su trayectoria. Sabiendo que la distancia que separa ambas posiciones es de $16\text{ cm}$, y que el movimiento se inicia en un extremo de la trayectoria, determinar:  
a) El periodo del movimiento.  
b) La amplitud máxima de las oscilaciones.  
c) La posición de la partícula a los $1.5\text{ segundos}$.  
*Respuesta:* a) $\displaystyle T = 2 \text{ s}$; b) $\displaystyle A = 8 \times 10^{-2} \text{ m}$; c) $\displaystyle x(1.5) = 0$

24) Una masa puntual está sujeta a un resorte elástico y oscila sobre el eje OX con una frecuencia de $0.5\text{ Hz}$ y una amplitud de $30\text{ cm}$. Si en el instante inicial su elongación es de $+30\text{ cm}$, determine:  
a) Las funciones de la elongación, la velocidad y la aceleración.  
b) Su posición y velocidad cuando $\displaystyle t = 2.5 \text{ s}$.  
c) Su aceleración cuando $\displaystyle t = 3 \text{ s}$.  
*Respuesta:* a) $\displaystyle x(t) = 0.30 \cos(\pi t); v(t) = -0.30\pi \sin(\pi t); a(t) = -0.30\pi^{2} \cos(\pi t)$; b) $\displaystyle x(2.5\text{ s}) = 0; v(2.5\text{ s}) = -0.94 \text{ m/s}$; c) $\displaystyle a(3\text{ s}) = +2.96 \text{ m/s}^{2}$

25) Una partícula de $10\text{ kg}$ de masa está sujeta a un muelle de constante elástica de $\displaystyle 10 \text{ N/m}$. En el instante inicial se desplaza $0.5\text{ m}$ de la posición de equilibrio y se suelta con velocidad nula. Representa la elongación y la velocidad frente al tiempo.  
*Respuesta:* $\displaystyle x(t) = 0.5 \cos t, v(t) = -0.5 \sin t$

26) Se cuelga un objeto de $200\text{ g}$ de un muelle sujeto al techo de $35\text{ cm}$ de longitud y su nueva longitud es de $45\text{ cm}$.  
a) Determinar la constante de elasticidad $\displaystyle k$ del muelle.  
b) Si estiramos el muelle hasta que mida $55\text{ cm}$ y lo soltamos, determina las fuerzas que actúan sobre el muelle.  
*Respuesta:* a) $\displaystyle k = 19.6 \text{ N/m}$; b) $\displaystyle P = 1.96 \text{ N}, F_{t} = -1.96 \text{ N}$

<a id="caso-2"></a>
##### Inicialmente está en el extremo izquierdo (superior) de la trayectoria con velocidad nula ($\phi=-\pi$).

27) Tenemos colgado verticalmente un muelle con una constante $\displaystyle k = 400 \text{ N/m}$ y queremos colgarle una masa para que oscile con un periodo de $1\text{ s}$. Calcular:  
a) La masa que debemos colgarle para conseguir ese periodo.  
b) Su posición para $\displaystyle t = 1.5 \text{ s}$ si, para que empiece a vibrar, levantamos la masa $4\text{ cm}$ por encima de su posición de equilibrio y contamos el tiempo desde que la soltamos.  
*Respuesta:* a) $\displaystyle m = 10.13 \text{ kg}$; b) $\displaystyle x(1.5\text{ s}) = -0.04 \text{ m} = -A$

<a id="caso-3"></a>
##### Inicialmente está en el punto de equilibrio y se desplaza hacia la derecha (abajo) ($\phi=-\pi/2$).

28) Un M.A.S. tiene una frecuencia de $5\text{ Hz}$ y una amplitud de $8\text{ mm}$. En el instante $\displaystyle t=0$, el móvil se encuentra en el centro de la vibración y se desplaza en sentido positivo. Expresar su elongación, su velocidad y su aceleración como funciones del tiempo.  
*Respuesta:* $\displaystyle x(t) = 8 \times 10^{-3} \cos(10\pi t - \pi/2)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle v(t) = -8 \times 10^{-2}\pi \sin(10\pi t - \pi/2)$ con $\displaystyle v$ en $[\text{m/s}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle a(t) = -0.8\pi^{2} \cos(10\pi t - \pi/2)$ con $\displaystyle a$ en $[\text{m/s}^{2}]$ y $\displaystyle t$ en $[\text{s}]$.

<a id="caso-4"></a>
##### Inicialmente está en el punto de equilibrio y se desplaza hacia la izquierda (arriba) ($\phi=\pi/2$).

29) Un bloque de $2.00\text{ kg}$, que se desliza sin fricción, se conecta a un resorte ideal con $\displaystyle k = 300 \text{ N/m}$. En $\displaystyle t=0$, el resorte no está estirado ni comprimido y el bloque se mueve en la dirección negativa a $12.00\text{ m/s}$. Calcule: a) la amplitud; b) el ángulo de fase; c) Escriba una ecuación para la posición en función del tiempo; d) Repita los incisos a)-c) pero suponga que, en $\displaystyle t=0$, el bloque tiene una velocidad de $-4.00\text{ m/s}$, y un desplazamiento de $+0.200\text{ m}$.  
*Respuesta:* a) $\displaystyle A = 0.97 \text{ m}$; b) $\displaystyle \pi/2 \text{ rad}$; c) $\displaystyle x(t) = 0.97 \cos(12.32t + \pi/2)$; d) $\displaystyle 0.380 \text{ m}, 1.02 \text{ rad}, x(t) = 0.380 \cos(12.32t + 1.02)$

30) Un cuerpo que se mueve describiendo un movimiento armónico simple a lo largo del eje X presenta, en un instante inicial, una aceleración nula y una velocidad de $-5\vec{i}\text{ m s}^{-1}$, la frecuencia del movimiento es $0.25\text{ Hz}$. Determine la expresión matemática que describe la elongación del muelle en función del tiempo. Justifique su respuesta.  
*Respuesta:* $\displaystyle x(t) = \frac{10}{\pi} \cos(0.5\pi t + \pi/2)$

31) Un objeto está en movimiento armónico simple con periodo de $1.200\text{ s}$ y amplitud de $0.600\text{ m}$. En $\displaystyle t=0$, el objeto está en $\displaystyle x=0$. ¿A qué distancia está de la posición de equilibrio cuando $\displaystyle t = 0.480 \text{ s}$?  
*Respuesta:* $\displaystyle x = -0.360 \text{ m}$

<a id="caso-5"></a>
##### Inicialmente no está en el extremo de la trayectoria ni tiene velocidad inicial nula.

32) Una partícula vibra de tal modo que tarda $0.50\text{ s}$ en ir desde un extremo a la posición de equilibrio, distantes entre sí $8.0\text{ cm}$. Si para $\displaystyle t=0$ la elongación de la partícula es $4.0\text{ cm}$, hallar la ecuación que define este movimiento.  
*Respuesta:* $\displaystyle x(t) = 0.08 \cos(\pi t - \pi/3) \text{ m}$

33) **Ejercicio 6.** Una fuerza de 400 newtons alarga un resorte 2 metros. Una masa de 50 kilogramos se une al extremo del resorte y se libera inicialmente desde la posición de equilibrio con una velocidad hacia arriba de $10\text{ m/s}$. Encuentre la ecuación del movimiento.  
**Ejercicio 7.** Otro resorte cuya constante es $20\text{ N/m}$ se suspende del mismo soporte, pero paralelo al sistema resorte-masa del problema 6. Al segundo resorte se le coloca una masa de 20 kilogramos, y ambas masas se liberan al inicio desde la posición de equilibrio con una velocidad ascendente de $10\text{ m/s}$.  
a) ¿Cuál masa exhibe la mayor amplitud de movimiento?  
b) ¿Cuál masa se mueve más rápido en $\displaystyle t = \pi/4 \text{ s}$?  
c) ¿En qué instantes las dos masas están en la misma posición? ¿Dónde están las masas en estos instantes? ¿En qué direcciones se están moviendo las masas?

34) **Ejercicio 3.** Una masa que pesa 24 libras, unida al extremo de un resorte, alarga a éste 4 pulgadas. Al inicio, la masa se libera desde el reposo en un punto 3 pulgadas arriba de la posición de equilibrio. Encuentre la ecuación del movimiento.  
**Ejercicio 4.** Determine la ecuación del movimiento si la masa del problema 3 al inicio se libera desde la posición de equilibrio con una velocidad descendente de $2\text{ pie/s}$.

35) Una masa que pesa 32 libras alarga un resorte 2 pies. Determine a) la amplitud y b) el periodo del movimiento si la masa se libera inicialmente desde un punto situado 1 pie arriba de la posición de equilibrio con una velocidad ascendente de $2\text{ pies/s}$. c) ¿Cuántos ciclos habrá completado la masa al final de $\displaystyle 4\pi \text{ segundos}$?  
*Respuesta:* a) $\displaystyle A = 1.1175 \text{ ft}$; b) $\displaystyle T = 1.57 \text{ s}$; c) $\displaystyle n = 8 \text{ ciclos}$

36) La punta de la aguja de una máquina de coser se mueve en MAS sobre el eje X con una frecuencia de $2.5\text{ Hz}$. En $\displaystyle t=0$, sus componentes de posición y velocidad son $+1.1\text{ cm}$ y $-15.00\text{ cm/s}$.  
a) Calcule la componente de aceleración de la aguja en $\displaystyle t=0$.  
b) Escriba ecuaciones para las componentes de posición, velocidad y aceleración de la punta en función del tiempo.  
*Respuesta:* a) $\displaystyle a = -2.71 \text{ m/s}^{2}$; b) $\displaystyle x(t) = 0.0146 \cos(15.71t + 0.7149)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle v(t) = -0.23 \sin(15.71t + 0.7149)$ con $\displaystyle v$ en $[\text{m/s}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle a(t) = -3.61 \cos(15.71t + 0.7149)$ con $\displaystyle a$ en $[\text{m/s}^{2}]$ y $\displaystyle t$ en $[\text{s}]$.

37) Una masa que pesa $2\text{ lb}$ alarga un resorte 6 pulgadas. En $\displaystyle t=0$ se libera la masa desde un punto que está 8 pulgadas debajo de la posición de equilibrio con una velocidad ascendente de $4/3\text{ pie/s}$. Determine la ecuación de movimiento.  
*Respuesta:* $\displaystyle x(t) = 0.6871 \cos(8.02t + 0.2444)$ con $\displaystyle x$ en $[\text{ft}]$ y $\displaystyle t$ en $[\text{s}]$.

---

<a id="seccion-4"></a>
### Elongación máxima, velocidad máxima y aceleración máxima [↑](#indice)

A partir de la ecuación $\displaystyle \tag{\color{red}{14}}$ se ve que, puesto que las funciones seno y coseno oscilan entre $\displaystyle \pm 1$, los valores extremos de la velocidad $\displaystyle v$ son $\displaystyle \pm \omega A$. Del mismo modo, la ecuación $\displaystyle \tag{\color{red}{15}}$ muestra que los valores extremos de la aceleración $\displaystyle a$ son $\displaystyle \pm \omega^{2} A$. En consecuencia, los valores máximos de las magnitudes de la velocidad y la aceleración son:

$$\displaystyle v_{\max} = \omega A \tag{\color{red}{22}}$$

$$\displaystyle a_{\max} = \omega^{2} A \tag{\color{red}{23}}$$

Las curvas asociadas de posición, velocidad y aceleración en función del tiempo muestran que la fase de la velocidad difiere de la fase de la posición en $\displaystyle \pi/2\text{ rad}$ ($90^{\circ}$). Es decir: cuando $\displaystyle x$ es un máximo o un mínimo, la velocidad es cero. Del mismo modo, cuando $\displaystyle x$ es cero, la rapidez es un máximo. Además, la fase de la aceleración difiere de la fase de la posición en $\displaystyle \pi\text{ radianes}$ ($180^{\circ}$). Por ejemplo, cuando $\displaystyle x$ es un máximo, $\displaystyle a$ tiene una magnitud máxima en la dirección opuesta.

<a id="subseccion-4-1"></a>
#### Relación entre la aceleración máxima y la velocidad máxima

$$\displaystyle a_{\max} = \omega v_{\max} \tag{\color{red}{24}}$$

---

<a id="ejercicios-3"></a>
#### EJERCICIOS [↑](#indice)

38) Un sistema bloque-resorte. Un bloque de $200\text{ g}$ conectado a un resorte ligero tiene una constante de fuerza de $5.00\text{ N/m}$ y es libre de oscilar sobre una superficie horizontal sin fricción. El bloque se desplaza $5.00\text{ cm}$ desde el equilibrio y se libera del reposo.  
a) Hallar el periodo de su movimiento.  
b) Determine la rapidez máxima del bloque.  
c) ¿Cuál es la aceleración máxima del bloque?  
d) Exprese la posición, velocidad y aceleración como funciones del tiempo.  
e) ¿Y si el bloque se libera desde la misma posición inicial, $\displaystyle x_{0} = 5.00 \text{ cm}$, pero con una velocidad inicial de $\displaystyle v_{0} = -0.100 \text{ m/s}$? ¿Qué partes de la solución cambian y cuáles son las nuevas respuestas para estas?  
*Respuesta:* a) $\displaystyle T = 1.26 \text{ s}$; b) $\displaystyle v_{\max} = 0.25 \text{ m/s}$; c) $\displaystyle a_{\max} = 1.25 \text{ m/s}^{2}$; d) $\displaystyle x(t) = 0.05 \cos(5t), v(t) = -0.25 \sin(5t), a(t) = -1.25 \cos(5t)$; e) $\displaystyle T = 1.26 \text{ s}, x(t) = 0.0539 \cos(5t + 0.3805), v(t) = -0.2695 \sin(5t + 0.3805), a(t) = -1.3475 \cos(5t + 0.3805)$

39) Una cuerda de guitarra vibra con una frecuencia de $440\text{ Hz}$. Un punto en su centro se mueve en M.A.S con amplitud de $3.0\text{ mm}$ y ángulo de fase cero. a) Escriba una ecuación para la posición del centro de la cuerda en función del tiempo. b) ¿Qué magnitud máxima tienen: la velocidad y la aceleración del centro de la cuerda? c) La derivada de la aceleración respecto al tiempo es una cantidad llamada tirón. Escriba una ecuación para el tirón del centro de la cuerda en función del tiempo, y calcule el valor máximo de la magnitud del tirón.  
*Respuesta:* a) $\displaystyle x(t) = 0.003 \cos(2764.60t)$; b) $\displaystyle v_{\max} = 8.29 \text{ m/s}, a_{\max} = 22926.06 \text{ m/s}^{2}$

40) Una masa de $0.50\text{ kg}$ cuelga de un resorte de $\displaystyle k = 50 \text{ N/m}$. Si la desplazamos $5.0\text{ cm}$ y la soltamos, calcular: a) La frecuencia b) La velocidad que tiene cuando pasa por la posición de equilibrio.  
*Respuesta:* a) $\displaystyle f = 1.59 \text{ s}^{-1}$; b) $\displaystyle v_{\max} = 0.50 \text{ m/s}$

41) Una masa $\displaystyle m = 0.5 \text{ kg}$ está suspendida de un resorte que se estiró $0.2\text{ cm}$ bajo la influencia del peso de esta masa. Ahora se tira de la masa hacia abajo y se suelta. En el tiempo $\displaystyle t=0$, se observa que la masa pasa por su posición de equilibrio estático con una velocidad de $10\text{ m/s}$. Despreciando toda fricción, determine la a) frecuencia natural, b) el periodo y c) la amplitud del movimiento resultante.  
*Respuesta:* a) $\displaystyle \omega = 70.04 \text{ rad/s}$; b) $\displaystyle T = 8.97 \times 10^{-2} \text{ s}$; c) $\displaystyle A = 0.1428 \text{ m}$

42) Un muelle se alarga $25\text{ cm}$ al colgar de él una masa de $2.0\text{ kg}$. Calcular la frecuencia y la velocidad máxima de oscilación de la masa sabiendo que la amplitud del movimiento es de $5.0\text{ cm}$. Dato: $\displaystyle g = 9.8 \text{ m/s}^{2}$.  
*Respuesta:* $\displaystyle f = 1 \text{ Hz}, v_{\max} = 0.314 \text{ m/s}$

43) Un cuerpo de masa $20\text{ g}$, que se mueve sobre el eje OX, pasa por el origen de coordenadas con una velocidad de $10\text{ m/s}$. Sobre él actúa una fuerza $\displaystyle F = -4x \text{ N}$, siendo $\displaystyle x$ la abscisa del cuerpo en $\text{m}$. Calcular hasta qué distancia del origen llegará.  
*Respuesta:* $\displaystyle A = 0.707 \text{ m}$

44) Una partícula de $5.0\text{ g}$ se mueve con M.A.S. Si su frecuencia es de $25\text{ Hz}$ y su amplitud $8\text{ cm}$, calcular:  
a) Su periodo.  
b) La frecuencia angular.  
c) Su velocidad máxima.  
d) La constante recuperadora.  
*Respuesta:* a) $\displaystyle T = 1/25 \text{ s}$; b) $\displaystyle \omega = 50\pi \text{ rad/s}$; c) $\displaystyle v_{\max} = 12.566 \text{ m/s}$; d) $\displaystyle k = 123.37 \text{ N/m}$

45) Un objeto está unido a un muelle horizontal sin rozamiento que oscila con una amplitud de $5\text{ cm}$ y una frecuencia de $3.3\text{ Hz}$. Determine:  
a) El periodo del movimiento.  
b) La velocidad máxima y la aceleración máxima.  
*Respuesta:* a) $\displaystyle T = 0.30 \text{ s}$; b) $\displaystyle v_{\max} = \pm 1.03 \text{ m/s}, a_{\max} = \pm 21.48 \text{ m/s}^{2}$

46) Un móvil realiza un movimiento armónico simple en el extremo de un muelle que hace dos oscilaciones por segundo, siendo la amplitud del movimiento $20\text{ cm}$. Calcular:  
a) La velocidad máxima que llega a alcanzar la masa que oscila.  
b) La aceleración de la masa al pasar por el extremo del movimiento vibratorio armónico.  
*Respuesta:* a) $\displaystyle v_{\max} = 2.51 \text{ m/s}$; b) $\displaystyle a_{\max} = -31.58 \text{ m/s}^{2}$

47) Al descargar una carga de un barco mediante una grúa, oscila haciendo un vaivén cada 4 segundos con una amplitud de $2\text{ m}$. Si se mueve con un M.A.S. Calcule:  
a) La aceleración máxima que alcanza.  
b) Si para $\displaystyle t=0$ está en el extremo positivo de la oscilación, su posición para $\displaystyle t = 9 \text{ s}$.  
*Respuesta:* a) $\displaystyle a_{\max} = 4.93 \text{ m/s}^{2}$; b) $\displaystyle x(9\text{ s}) = 0 \text{ m}$

48) Al suspender un cuerpo de masa $300\text{ g}$ del extremo de un muelle que está colgado verticalmente, éste se alarga $20\text{ cm}$. Si se tira del cuerpo $5\text{ cm}$ hacia abajo y se suelta, comienza a oscilar. Calcular el período del movimiento. ¿Cuál será la máxima velocidad que alcanzará?  
*Respuesta:* $\displaystyle v_{\max} = \pm 35.3 \text{ cm/s}$

49) El pistón del cilindro de un coche tiene una carrera (distancia desde abajo hasta arriba del movimiento) de $20\text{ cm}$ y el motor gira a $800\text{ rpm}$. Calcular la velocidad máxima que alcanza.  
*Respuesta:* $\displaystyle v_{\max} = \pm 8.38 \text{ m/s}$

50) Una partícula recorre $8\text{ cm}$ de extremo a extremo en un movimiento armónico simple y su aceleración máxima es de $\displaystyle 48 \text{ m/s}^{2}$. Calcular:  
a) La frecuencia y el periodo del movimiento.  
b) La velocidad máxima de la partícula.  
*Respuesta:* a) $\displaystyle f = 5.51 \text{ Hz}, T = 0.1815 \text{ s}$; b) $\displaystyle v_{\max} = 1.39 \text{ m/s}$

51) ¿Qué amplitud y qué período debe tener un M.A.S. para que la velocidad máxima sea de $\displaystyle 30 \text{ cm/s}$ y la aceleración máxima de $\displaystyle 12 \text{ m/s}^{2}$? Expresar la elongación de ese movimiento en función del tiempo.  
*Respuesta:* $\displaystyle x(t) = 0.0075 \cos(40t)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$.

52) ¿Cuál es la máxima fuerza que actúa sobre un cuerpo de masa $50\text{ g}$ cuando vibra con una frecuencia de $25\text{ Hz}$ y una amplitud de $2\text{ mm}$?  
*Respuesta:* $\displaystyle F_{\max} = 2.47 \text{ N}$

53) En un M.A.S., cuando la elongación es nula, la velocidad es de $1\text{ m/s}$ y, en el instante en que la elongación es de $5\text{ cm}$, la velocidad es nula. ¿Cuál es el período del movimiento?  
*Respuesta:* $\displaystyle T = 0.3142 \text{ s}$

54) La escala de un dinamómetro está graduada en N. Desde la división $0\text{ N}$ hasta la de $20\text{ N}$ hay una distancia de $10\text{ cm}$. Hacemos oscilar, con una amplitud de $1\text{ cm}$, a un cuerpo de masa $800\text{ g}$ suspendido del muelle del dinamómetro. Calcular la frecuencia de las oscilaciones y su aceleración máxima.  
*Respuesta:* $\displaystyle f = 2.52 \text{ Hz}, a_{\max} = 250 \text{ cm/s}^{2}$

---

<a id="seccion-5"></a>
### Relación entre posición, velocidad y aceleración [↑](#indice)

<a id="subseccion-5-1"></a>
#### Relación entre la posición y la aceleración en el movimiento armónico simple

Puesto que $\displaystyle x(t) = A \cos(\omega t + \phi)$, podemos expresar la ecuación $\displaystyle \tag{\color{red}{15}}$ en la forma:

$$\displaystyle a = -\omega^{2} x \tag{\color{red}{25}}$$

<a id="subseccion-5-2"></a>
#### Relación entre la posición y la velocidad en el movimiento armónico simple

Posición en función del tiempo:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \tag{\color{red}{7}}$$

Rapidez en función del tiempo:

$$\displaystyle v(t) = -\omega A \sin(\omega t + \phi) \tag{\color{red}{14}}$$

Al despejar $\displaystyle \cos(\omega t + \phi)$ de la ecuación $\displaystyle \tag{\color{red}{7}}$ y $\displaystyle \sin(\omega t + \phi)$ de la ecuación $\displaystyle \tag{\color{red}{14}}$:

$$\displaystyle \cos(\omega t + \phi) = \frac{x(t)}{A}$$

$$\displaystyle \sin(\omega t + \phi) = -\frac{v(t)}{\omega A}$$

Siendo $\displaystyle \cos^{2}(\omega t + \phi) + \sin^{2}(\omega t + \phi) = 1$, se tiene:

$$\displaystyle \left(\frac{x}{A}\right)^{2} + \left(\frac{v}{\omega A}\right)^{2} = 1$$

$$\displaystyle \frac{x^{2}}{A^{2}} + \frac{v^{2}}{\omega^{2} A^{2}} = 1$$

$$\displaystyle \frac{v^{2}}{\omega^{2} A^{2}} = 1 - \frac{x^{2}}{A^{2}}$$

$$\displaystyle \frac{v^{2}}{\omega^{2} A^{2}} = \frac{A^{2} - x^{2}}{A^{2}}$$

$$\displaystyle \frac{v^{2}}{\omega^{2}} = A^{2} - x^{2}$$

$$\displaystyle v^{2} = \omega^{2}(A^{2} - x^{2})$$

$$\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \tag{\color{red}{26}}$$

<a id="subseccion-5-3"></a>
#### Relación entre la velocidad y la aceleración en el movimiento armónico simple

Rapidez de la partícula:

$$\displaystyle v = \omega \sqrt{A^{2} - x^{2}} \tag{\color{red}{26}}$$

Aceleración de la partícula:

$$\displaystyle a = -\omega^{2} x \tag{\color{red}{25}}$$

De la ecuación $\displaystyle \tag{\color{red}{25}}$:

$$\displaystyle x = -\frac{a}{\omega^{2}}$$

Al sustituir en la ecuación $\displaystyle \tag{\color{red}{20}}$:

$$\displaystyle v = \omega \sqrt{A^{2} - \left(-\frac{a}{\omega^{2}}\right)^{2}}$$

$$\displaystyle v = \omega \sqrt{A^{2} - \frac{a^{2}}{\omega^{4}}}$$

$$\displaystyle v^{2} = \omega^{2}\left(A^{2} - \frac{a^{2}}{\omega^{4}}\right)$$

$$\displaystyle v^{2} = \omega^{2} A^{2} - \frac{a^{2}}{\omega^{2}}$$

$$\displaystyle \frac{a^{2}}{\omega^{2}} = \omega^{2} A^{2} - v^{2}$$

$$\displaystyle a^{2} = \omega^{2}(\omega^{2} A^{2} - v^{2})$$

$$\displaystyle a = \omega \sqrt{\omega^{2} A^{2} - v^{2}} \tag{\color{red}{27}}$$

---

<a id="ejercicios-4"></a>
#### EJERCICIOS [↑](#indice)

55) Un objeto de $0.400\text{ kg}$ en MAS tiene $\displaystyle a_{x} = -2.70 \text{ m/s}^{2}$ cuando $\displaystyle x = 0.300 \text{ m}$. ¿Cuánto tarda una oscilación?  
*Respuesta:* $\displaystyle T = 2.09 \text{ s}$

56) Una partícula se desplaza con M.A.S. de amplitud $1\text{ cm}$ y frecuencia $8\text{ Hz}$. Calcular su velocidad y su aceleración en el instante en que tiene una elongación de $6\text{ mm}$.  
*Respuesta:* $\displaystyle v = \pm 40.21 \text{ cm/s}, a = -15.16 \text{ cm/s}^{2}$

57) En un M.A.S. de amplitud $4\text{ cm}$, en el instante en que la elongación es $\displaystyle \sqrt{7} \text{ cm}$, la velocidad es de $\displaystyle 6\pi \text{ m/s}$. Calcular la frecuencia del movimiento. ¿Cuál será la velocidad del móvil al pasar por la posición de equilibrio?  
*Respuesta:* $\displaystyle f = 100 \text{ Hz}, v_{\max} = 25.1 \text{ m/s}$

58) Un cuerpo está unido a un muelle horizontal. Comienza a oscilar desde uno de los extremos situados a $5\text{ cm}$ de su posición de equilibrio, con un periodo de $0.4\text{ s}$. Determinar:  
a) La velocidad al pasar por la posición de equilibrio.  
b) La velocidad y la aceleración al pasar por $\displaystyle x = 3 \text{ cm}$.  
c) La aceleración en los extremos de la trayectoria.  
d) La aceleración en $\displaystyle x = -1 \text{ cm}$.  
*Respuesta:* a) $\displaystyle v = \pm 25\pi \text{ cm/s}$; b) $\displaystyle a = \pm 20\pi \text{ cm/s}$; c) $\displaystyle a_{\max} = \pm 125\pi^{2} \text{ cm/s}^{2}$; d) $\displaystyle a = \pm 25\pi^{2} \text{ cm/s}^{2}$

59) Sabiendo que un cuerpo de masa $3\text{ kg}$ oscila unido a un muelle a razón de 15 oscilaciones cada segundo, calcular:  
a) La constante elástica del muelle.  
b) El valor de la fuerza cuando la elongación es de $4\text{ cm}$.  
*Respuesta:* a) $\displaystyle k = 26647.9 \text{ N/m}$; b) $\displaystyle F = -1065.91 \text{ N}$

---

<a id="seccion-6"></a>
### Problemas que involucran gráficas [↑](#indice)

60) En la figura se muestra el desplazamiento en función del tiempo ($\displaystyle A = 0.20 \text{ m}$, periodos de $\displaystyle 1.0, 2.0, 3.0, 4.0 \text{ s}$). Calcule: a) la frecuencia; b) la amplitud y c) el periodo.  
*Respuesta:* a) $\displaystyle f = 0.5 \text{ Hz}$; b) $\displaystyle A = 0.20 \text{ m}$; c) $\displaystyle T = 2.00 \text{ s}$

61) Un cuerpo se mueve según un movimiento armónico simple con una gráfica de elongación entre $\displaystyle +3 \text{ m}$ y $\displaystyle -3 \text{ m}$ que completa ciclos en $\displaystyle 10 \text{ s}$. A la vista de ella, di si son verdaderas o falsas las siguientes afirmaciones:  
a) Cada dos segundos el cuerpo está en el mismo estado vibracional.  
b) El periodo del movimiento vale 4 segundos.  
c) El movimiento tiene una amplitud de $6\text{ m}$.  
d) La frecuencia del movimiento es de $0.25\text{ Hz}$.  
e) La ecuación del movimiento es $\displaystyle x(t) = 3 \sin(\pi t / 2) \text{ cm}$.  
*Respuesta:* a) Falso; b) Verdadero; c) Falso; d) Verdadero; e) Falso.

62) La siguiente gráfica representa la elongación en función del tiempo de un cuerpo que se comporta según un movimiento armónico simple ($\displaystyle x$ entre $\displaystyle 5 \text{ m}$ y $\displaystyle -5 \text{ m}$, pasando por tiempos $\displaystyle -11, 1, 13 \text{ s}$). Determinar la amplitud máxima, el periodo, la frecuencia, la frecuencia angular y la fase inicial del movimiento.  
*Respuesta:* $\displaystyle A = 5 \text{ m}, T = 12 \text{ s}, f = 0.0833 \text{ Hz}, \omega = 0.5236 \text{ rad/s}, \phi = -0.5236 \text{ rad}$

63) Determina las ecuaciones de las gráficas de la figura (amplitud $\displaystyle 4 \text{ cm}$, tiempo $\displaystyle 10 \text{ s}$). Determina también el desfase entre ambos movimientos.  
*Respuesta:* $\displaystyle x_{1}(t) = 4 \cos(0.5\pi t + \pi/2), x_{2}(t) = 4 \cos(0.5\pi t + \pi), \Delta\phi = \pi/2 \text{ rad}$

64) La gráfica corresponde a un cuerpo de $150\text{ g}$ de masa que realiza un movimiento armónico simple con amplitud de $9\text{ cm}$ y marcas temporales en $\displaystyle 2\text{ s}$ y $\displaystyle 4\text{ s}$. Se pide calcular:  
a) La velocidad inicial del cuerpo.  
b) La aceleración en los instantes $\displaystyle t = 2 \text{ s}$ y $\displaystyle t = 6 \text{ s}$.  
c) El valor y sentido que tendrá la fuerza que actúa sobre el cuerpo en los instantes $\displaystyle t = 0.5 \text{ s}$ y $\displaystyle t = 1.5 \text{ s}$.  
*Respuesta:* a) $\displaystyle v_{0} = 0.2827 \text{ m/s}$; b) $\displaystyle a(2\text{ s}) = 0, a(6\text{ s}) = 0$; c) $\displaystyle F(0.5\text{ s}) = -0.1332 \text{ N}, F(1.5\text{ s}) = 0.1332 \text{ N}$

<a id="subseccion-6-1"></a>
#### Conocida la ecuación del movimiento

65) La ecuación de un M.A.S. es $\displaystyle x(t) = 2 \cos(30\pi t)$, en la que $\displaystyle x$ es la elongación en $\text{cm}$ y $\displaystyle t$ en $\text{s}$. ¿Cuáles son la amplitud, la frecuencia y el período de este movimiento?  
*Respuesta:* $\displaystyle A = 2 \text{ cm}, f = 15 \text{ Hz}, T = 1/15 \text{ s}$

66) Sabiendo que un movimiento armónico simple tiene por ecuación:  
$$\displaystyle x(t) = 0.5 \sin(0.35\pi t + \pi/4) \text{ [m]}$$  
Determinar la ecuación y la gráfica de la velocidad y de la aceleración.  
*Respuesta:* $\displaystyle v(t) = 0.175\pi \cos(0.35\pi t + \pi/4) \text{ m/s}, a(t) = -0.06125\pi^{2} \sin(0.35\pi t + \pi/4) \text{ m/s}^{2}$

67) Calcular la velocidad y aceleración máximas del M.A.S. cuya ecuación es $\displaystyle x(t) = 5 \cos(4\pi t + \pi/6)$ en la que $\displaystyle x$ es la elongación en $\text{cm}$ y $\displaystyle t$ el tiempo en $\text{s}$.  
*Respuesta:* $\displaystyle v_{\max} = \pm 20\pi = 62.83 \text{ cm/s}, a_{\max} = \pm 789.57 \text{ cm/s}^{2}$

68) Calcular la aceleración y la velocidad en el instante inicial para un muelle cuyo movimiento viene descrito por la función: $\displaystyle x(t) = 0.3 \cos(2t + \pi/6) \text{ [cm]}$.  
*Respuesta:* $\displaystyle a_{0} = -5.92 \text{ m/s}^{2}, v_{0} = -0.3 \sin(\pi/6) \cdot 2 = -0.30 \text{ cm/s}$

69) Una partícula oscila con un movimiento armónico simple de tal forma que su desplazamiento varía de acuerdo con la expresión $\displaystyle x(t) = 5 \cos(2t + \pi/6)$, donde $\displaystyle x$ está en $\text{cm}$ y $\displaystyle t$ en $\text{s}$. En $\displaystyle t=0$ encuentre a) desplazamiento, b) velocidad, c) aceleración. d) Determinar el periodo y la amplitud del movimiento.  
*Respuesta:* a) $\displaystyle x(t) = 5 \cos(2t + \pi/6)$; b) $\displaystyle v(t) = -10 \sin(2t + \pi/6)$; c) $\displaystyle a(t) = -20 \cos(2t + \pi/6)$. En $\displaystyle t=0$: $\displaystyle x = 4.33 \text{ cm}, v = -5 \text{ cm/s}, a = -17.32 \text{ cm/s}^{2}$; d) $\displaystyle T = \pi \text{ s}, A = 5 \text{ cm}$

70) En un M.A.S. la elongación en $\text{cm}$ es $\displaystyle x(t) = 0.4 \cos(10\pi t - \pi/3)$ siendo $\displaystyle t$ el tiempo en $\text{s}$. Calcular la elongación, velocidad y aceleración del móvil en los instantes $\displaystyle t = 0 \text{ s}$ y $\displaystyle t = 1/120 \text{ s}$.  
*Respuesta:* En $\displaystyle t=0 \text{ s}$: $\displaystyle x = 0.2 \text{ cm}, v = 10.88 \text{ cm/s}, a = -197.39 \text{ cm/s}^{2}$

71) La elongación en $\text{cm}$ de un M.A.S. es $\displaystyle x = 4 \cos(10t)$, donde $\displaystyle t$ es el tiempo en $\text{s}$. Calcular la aceleración en el instante en que la elongación es de $3\text{ cm}$.  
*Respuesta:* $\displaystyle a = -3 \text{ m/s}^{2}$

72) La ecuación de un M.A.S. es $\displaystyle x = 6 \cos(5t + \phi_{0})$ en la que $\displaystyle x$ es la elongación en $\text{cm}$ y $\displaystyle t$ el tiempo en $\text{s}$. Determinar la posición y velocidad del móvil en el instante $\displaystyle t = 0 \text{ s}$ si:  
a) $\displaystyle \phi_{0} = 0$; b) $\displaystyle \phi_{0} = \pi/3 \text{ rad}$; c) $\displaystyle \phi_{0} = \pi/2 \text{ rad}$; d) $\displaystyle \phi_{0} = \pi \text{ rad}$. e) Representar gráficamente las funciones del tiempo $\displaystyle x-t$, $\displaystyle v-t$ y $\displaystyle a-t$ en cada uno de los incisos a)-d).  
*Respuesta:* a) $\displaystyle 6 \text{ cm}, 0 \text{ cm/s}$; b) $\displaystyle 3 \text{ cm}, -25.98 \text{ cm/s}$; c) $\displaystyle 0 \text{ cm}, -30 \text{ cm/s}$; d) $\displaystyle -6 \text{ cm}, 0 \text{ cm/s}$

73) Discutir las diferencias entre los M.A.S. que tienen las siguientes ecuaciones de elongación: a) $\displaystyle x(t) = A \sin t$; b) $\displaystyle x(t) = A \cos t$.

74) La abscisa de un móvil en función del tiempo en $\text{s}$ es la función:  
$$\displaystyle x(t) = 4 \sin(10t) + 3 \cos(10t) \text{ [cm]}$$  
Expresar su aceleración en función del tiempo y demostrar que se trata de un M.A.S.  
*Respuesta:* $\displaystyle a(t) = -400 \sin(10t) - 300 \cos(10t)$ con $\displaystyle a$ en $[\text{cm/s}^{2}]$ y $\displaystyle t$ en $[\text{s}]$. Se trata de un M.A.S porque $\displaystyle a = -\omega^{2} x$.

75) La velocidad de una masa de $0.500\text{ kg}$ está dada en función del tiempo por:  
$$\displaystyle v(t) = 3.60 \sin(4.71t - \pi/2) \text{ [m/s]}$$  
Calcule a) el periodo, b) la amplitud y c) la aceleración máxima de la masa.  
*Respuesta:* a) $\displaystyle T = 1.3340 \text{ s}$; b) $\displaystyle A = 0.7643 \text{ m}$; c) $\displaystyle a_{\max} = 16.956 \text{ m/s}^{2}$

76) La velocidad en $\text{m/s}$ de un M.A.S. es $\displaystyle v(t) = -0.36\pi \sin[\pi(24t + 1)]$ donde $\displaystyle t$ es el tiempo en $\text{s}$. ¿Cuáles son la frecuencia y la amplitud de ese movimiento? Escribir la expresión de su elongación en función del tiempo.  
*Respuesta:* $\displaystyle f = 12 \text{ Hz}, A = 0.015 \text{ m}, x(t) = 0.015 \cos[\pi(24t + 1)]$

---

<a id="seccion-7"></a>
### El péndulo [↑](#indice)

El péndulo simple es otro sistema mecánico que muestra movimiento periódico. Consiste en una plomada parecida a una partícula de masa $\displaystyle m$ suspendida de una cuerda ligera de longitud $\displaystyle L$ que está fija en el extremo superior.

El movimiento se presenta en el plano vertical y es impulsado por la fuerza gravitacional. Se demostrará que, siempre que el ángulo $\displaystyle \theta$ sea pequeño (menor que aproximadamente $10^{\circ}$), el movimiento es muy cercano al de un oscilador armónico simple.

Las fuerzas que actúan en la plomada son la fuerza $\displaystyle \vec{T}$ que ejerce la cuerda y la fuerza gravitacional $\displaystyle m\vec{g}$. La componente tangencial $\displaystyle m g \sin \theta$ de la fuerza gravitacional siempre actúa hacia $\displaystyle \theta = 0$, opuesta al desplazamiento de la plomada desde la posición más baja. Por lo tanto, la componente tangencial es una fuerza restauradora y se puede aplicar la segunda ley de Newton del movimiento en la dirección tangencial:

$$\displaystyle F_{t} = -m g \sin \theta = m \frac{d^{2} s}{d t^{2}} \tag{\color{red}{28}}$$

donde $\displaystyle s$ es la posición de la plomada medida a lo largo del arco y el signo negativo indica que la fuerza tangencial actúa hacia la posición de equilibrio (vertical). Ya que $\displaystyle s = L \theta$ y $\displaystyle L$ es constante, esta ecuación se reduce a:

$$\displaystyle \frac{d^{2} \theta}{d t^{2}} = -\frac{g}{L} \sin \theta \tag{\color{red}{29}}$$

Al considerar $\displaystyle \theta$ como la posición, y comparar con la ecuación:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\frac{k}{m} x \tag{\color{red}{30}}$$

no se tiene la misma forma matemática. El lado derecho es proporcional a $\displaystyle \sin \theta$ en vez de $\displaystyle \theta$; por eso, no se esperaría movimiento armónico simple porque la ecuación $\displaystyle \tag{\color{red}{29}}$ no tiene la forma de la ecuación $\displaystyle \tag{\color{red}{30}}$. Sin embargo, si se supone que $\displaystyle \theta$ es pequeño (menor que aproximadamente $10^{\circ}$ o $0.2\text{ rad}$), se puede usar la aproximación de ángulo pequeño, en la que $\displaystyle \sin \theta \approx \theta$, donde $\displaystyle \theta$ se mide en radianes.

Por lo tanto, para ángulos pequeños, la ecuación de movimiento se convierte en:

$$\displaystyle \frac{d^{2} \theta}{d t^{2}} = -\frac{g}{L} \theta \tag{\color{red}{31}}$$

La ecuación $\displaystyle \tag{\color{red}{31}}$ tiene la misma forma que la ecuación $\displaystyle \tag{\color{red}{3}}$, así se concluye que el movimiento para amplitudes de oscilación pequeñas se puede modelar como movimiento armónico simple. En consecuencia, la solución de la ecuación $\displaystyle \tag{\color{red}{31}}$ es:

$$\displaystyle \theta = \theta_{\max} \cos(\omega t + \phi)$$

donde $\displaystyle \theta_{\max}$ es la posición angular máxima y la frecuencia angular $\displaystyle \omega$ es:

$$\displaystyle \omega = \sqrt{\frac{g}{L}} \tag{\color{red}{32}}$$

El periodo del movimiento es:

$$\displaystyle T = \frac{2\pi}{\omega} = 2\pi \sqrt{\frac{L}{g}} \tag{\color{red}{33}}$$

En otras palabras, el periodo y la frecuencia de un péndulo simple sólo dependen de la longitud de la cuerda y de la aceleración debida a la gravedad. Ya que el periodo es independiente de la masa, se concluye que todos los péndulos simples que son de igual longitud y están en la misma ubicación (de modo que $\displaystyle g$ es constante) oscilan con el mismo periodo.

El péndulo simple se puede usar como cronómetro porque su periodo sólo depende de su longitud y del valor local de $\displaystyle g$. También es un dispositivo conveniente para hacer mediciones precisas de la aceleración en caída libre. En tales condiciones son importantes porque las variaciones en los valores locales de $\displaystyle g$ pueden proporcionar información acerca de la ubicación de petróleo y otros recursos subterráneos valiosos.

---

<a id="ejercicios-5"></a>
#### EJERCICIOS [↑](#indice)

77) Determina la longitud que debe tener un péndulo para que oscile con una frecuencia de $2\text{ Hz}$.  
*Respuesta:* $\displaystyle L = 0.06 \text{ m}$

78) El péndulo de un reloj de pie realiza 5 oscilaciones en 10 segundos. Suponiendo que se trata de un péndulo simple, calcule su longitud. Dato: $\displaystyle g = 9.81 \text{ m/s}^{2}$.  
*Respuesta:* $\displaystyle L = 0.99 \text{ m}$

79) Explica razonadamente y con detalle cómo se puede obtener experimentalmente el módulo de la aceleración de la gravedad utilizando un péndulo y un cronómetro.

80) Calcula la longitud de un péndulo de un periodo de $2\text{ s}$ en la Tierra y en la Luna. $\displaystyle g_{\text{Tierra}} = 9.8 \text{ m/s}^{2}$, $\displaystyle g_{\text{Luna}} = 1.6 \text{ m/s}^{2}$.  
*Respuesta:* $\displaystyle L_{\text{Tierra}} = 0.993 \text{ m}, L_{\text{Luna}} = 0.162 \text{ m}$

81) Determina cuál debe ser la amplitud de las oscilaciones de un péndulo de $70\text{ cm}$ sabiendo que el máximo ángulo que separa el hilo de la vertical es de $6^{\circ}$. ¿Qué fuerzas actúan sobre el cuerpo en esa situación suponiendo una masa de $80\text{ g}$?  
*Respuesta:* $\displaystyle A = 0.0728\pi \text{ m}$

82) ¿Cuál será la gravedad en un planeta en el que un péndulo de longitud $10\text{ cm}$ tarda $0.634\text{ segundos}$ en realizar una oscilación completa?  
*Respuesta:* $\displaystyle g = 9.8 \text{ m/s}^{2}$

83) Un niño se columpia con una amplitud de $0.5\text{ m}$. Si en 10 segundos va y vuelve 5 veces. Supuesto un M.A.S., calcular:  
a) La frecuencia del movimiento.  
b) La función de la velocidad y la velocidad máxima que alcanza si la fase inicial es nula.  
*Respuesta:* a) $\displaystyle f = 0.5 \text{ Hz}$; b) $\displaystyle v(t) = -0.5\pi \sin(\pi t), v_{\max} = \pm 1.57 \text{ m/s}$

84) Un niño se columpia con una amplitud de $0.5\text{ m}$ en un columpio de $3.0\text{ m}$ de longitud. Calcula: a) El periodo con el que se columpia. b) Supuesto un M.A.S., la función de la velocidad si la fase inicial es nula.  
*Respuesta:* a) $\displaystyle T = 3.47 \text{ s}$; b) $\displaystyle v(t) = -0.904 \sin(1.808t) \text{ m/s}$

85) Tenemos un péndulo de $224\text{ cm}$ de largo. Calcula: a) Su periodo. b) Si entre los dos extremos del movimiento recorre una distancia de $20\text{ cm}$, y para $\displaystyle t=0$ está en el extremo positivo de la oscilación, calcula su posición para $\displaystyle t = 4.5 \text{ s}$.  
*Respuesta:* a) $\displaystyle T = 3.00 \text{ s}$; b) $\displaystyle x(4.5\text{ s}) = -0.1 \text{ m}$

86) Un péndulo está formado por una partícula de masa $\displaystyle M$ colgada de una cuerda ideal de longitud $\displaystyle L$. Obtén la relación entre los periodos de oscilación del péndulo cuando oscila en la Tierra y en la Luna ($\displaystyle T_{T}/T_{L}$). (Dato: $\displaystyle g_{L} = g_{T}/6$).  
*Respuesta:* $\displaystyle \frac{T_{T}}{T_{L}} = \frac{1}{\sqrt{6}}$

---

<a id="seccion-8"></a>
### Circuitos LC [↑](#indice)

Cuando se conecta un capacitor con un inductor, la combinación es un circuito LC. Si el capacitor está inicialmente con carga y en ese momento se cierra el interruptor, tanto la corriente en el circuito como la carga en el capacitor oscilan entre valores máximos positivos y negativos. Si la resistencia del circuito es igual a cero, no existe transformación de energía en energía interna. En la explicación siguiente la resistencia del circuito es despreciable. También se supone una situación ideal donde no se radia energía hacia afuera del circuito.

Suponga que el capacitor tiene una carga inicial $\displaystyle Q_{\max}$ (carga máxima) y que el interruptor se abre en $\displaystyle t < 0$ y después se cierra en $\displaystyle t = 0$.

Las oscilaciones del circuito LC son electromagnéticamente similares a las oscilaciones mecánicas de un sistema masa-resorte. Mucho de lo que se explicó allí es aplicable a las oscilaciones LC.

Aplicamos la segunda ley de Kirchhoff (ley de voltajes), la cual establece que la suma algebraica de las caídas de tensión en un lazo cerrado es igual a cero.

En el circuito ideal sin resistencia, descrito en párrafos anteriores, el voltaje en el inductor ($\displaystyle V_{L}$) y el voltaje en el capacitor ($\displaystyle V_{C}$) deben sumarse con resultado cero:

$$\displaystyle V_{L} + V_{C} = 0 \tag{\color{red}{34}}$$

Sabemos por las leyes del electromagnetismo que:

$$\displaystyle V_{L} = L \frac{d I}{d t} \tag{\color{red}{35}}$$

Y por definición:

$$\displaystyle V_{C} = \frac{Q}{C} \tag{\color{red}{36}}$$

Al sustituir las ecuaciones $\displaystyle \tag{\color{red}{35}}$ y $\displaystyle \tag{\color{red}{36}}$ en la ecuación $\displaystyle \tag{\color{red}{34}}$:

$$\displaystyle L \frac{d I}{d t} + \frac{Q}{C} = 0 \tag{\color{red}{37}}$$

La corriente eléctrica $\displaystyle I$ se define como la tasa de flujo de carga $\displaystyle Q$ a través del tiempo:

$$\displaystyle I = \frac{d Q}{d t} \tag{\color{red}{38}}$$

Por lo tanto, la derivada de la corriente respecto al tiempo es la segunda derivada de la carga:

$$\displaystyle \frac{d I}{d t} = \frac{d^{2} Q}{d t^{2}} \tag{\color{red}{39}}$$

Al sustituir la ecuación $\displaystyle \tag{\color{red}{39}}$ en la ecuación $\displaystyle \tag{\color{red}{37}}$:

$$\displaystyle L \frac{d^{2} Q}{d t^{2}} + \frac{Q}{C} = 0$$

$$\displaystyle L \frac{d^{2} Q}{d t^{2}} + \frac{1}{C} Q = 0$$

Para llevarla a su forma estándar de un oscilador armónico simple, dividimos toda la ecuación por la inductancia $\displaystyle L$:

$$\displaystyle \frac{d^{2} Q}{d t^{2}} + \frac{1}{L C} Q = 0 \tag{\color{red}{40}}$$

Esta es una ecuación diferencial lineal de segundo orden, homogénea y con coeficientes constantes.

Si definimos la frecuencia angular natural del circuito como:

$$\displaystyle \omega = \frac{1}{\sqrt{L C}}$$

la ecuación se puede escribir de forma compacta:

$$\displaystyle \frac{d^{2} Q}{d t^{2}} + \omega^{2} Q = 0 \tag{\color{red}{41}}$$

La cual corresponde a un oscilador armónico simple.

La solución general de la ecuación $\displaystyle \tag{\color{red}{41}}$ describe un comportamiento oscilatorio senoidal para la carga:

$$\displaystyle Q(t) = Q_{\max} \cos(\omega t + \phi) \tag{\color{red}{42}}$$

#### Corriente en el circuito en función del tiempo

Podemos obtener la intensidad de corriente en el circuito diferenciando la ecuación $\displaystyle \tag{\color{red}{42}}$ respecto del tiempo:

$$\displaystyle I(t) = \frac{d Q}{d t}$$

$$\displaystyle I(t) = -Q_{\max} \omega \sin(\omega t + \phi) \tag{\color{red}{43}}$$

#### Corriente máxima

El valor máximo de las magnitudes de la corriente es:

$$\displaystyle I_{\max} = Q_{\max} \omega \tag{\color{red}{44}}$$

#### Voltaje en el capacitor

De la ecuación $\displaystyle \tag{\color{red}{36}}$:

$$\displaystyle V_{C} = \frac{Q}{C}$$

Al sustituir la ecuación $\displaystyle \tag{\color{red}{42}}$ en la ecuación $\displaystyle \tag{\color{red}{36}}$:

$$\displaystyle V_{C}(t) = \frac{Q_{\max} \cos(\omega t + \phi)}{C} \tag{\color{red}{45}}$$

#### Voltaje en el inductor

De la ecuación $\displaystyle \tag{\color{red}{35}}$:

$$\displaystyle V_{L} = L \frac{d I}{d t}$$

Al derivar la ecuación $\displaystyle \tag{\color{red}{43}}$ y sustituir en la ecuación $\displaystyle \tag{\color{red}{35}}$:

$$\displaystyle V_{L} = L [-Q_{\max} \omega^{2} \cos(\omega t + \phi)]$$

$$\displaystyle V_{L} = -L \omega^{2} Q_{\max} \cos(\omega t + \phi)$$

Pero $\displaystyle L \omega^{2} = \frac{1}{C}$, por lo que:

$$\displaystyle V_{L}(t) = -\frac{Q_{\max} \cos(\omega t + \phi)}{C} \tag{\color{red}{46}}$$

---

<a id="ejercicios-6"></a>
#### EJERCICIOS [↑](#indice)

87) Oscilaciones en un circuito LC. En la figura, la batería tiene una fem de $12.0\text{ V}$, la inductancia es de $2.81\text{ mH}$ y la capacitancia es de $9.00\text{ pF}$. El interruptor se pone en la posición $a$ durante un tiempo considerable, de modo que el capacitor se carga. Luego el interruptor se pone en la posición $b$, retirando la batería del circuito y se conecta el capacitor directamente a través del inductor.  
a) Hallar la frecuencia de oscilación del circuito.  
b) ¿Cuáles son los valores máximos de carga en el capacitor y la corriente en el circuito?  
*Respuesta:* a) $\displaystyle f = 10^{6} \text{ Hz}$; b) $\displaystyle Q_{\max} = 1.08 \times 10^{-10} \text{ C}, I_{\max} = 6.79 \times 10^{-4} \text{ A}$

88) Un capacitor de $1.00\text{ }\mu\text{F}$ es cargado por una fuente de energía de $40.0\text{ V}$. Después se descarga a través de un inductor de $10.0\text{ mH}$. Determine la corriente máxima en las oscilaciones resultantes.  
*Respuesta:* $\displaystyle I_{\max} = 0.400 \text{ A}$

89) Un circuito LC está constituido por un inductor de $20.0\text{ mH}$ y un capacitor de $0.500\text{ }\mu\text{F}$. Si la corriente máxima instantánea es de $0.100\text{ A}$, ¿cuál es la mayor diferencia de potencial en los extremos del capacitor?  
*Respuesta:* $\displaystyle V_{\max} = 20.0 \text{ V}$

90) Para la sintonización de un radioteléfono en un barco se utiliza una inductancia fija $\displaystyle L = 1.05 \text{ }\mu\text{H}$ en serie con un capacitor variable. ¿Qué capacitancia sintoniza el circuito a la señal proveniente de un transmisor que emite señales a $6.30\text{ MHz}$?  
*Respuesta:* $\displaystyle C = 608 \text{ pF}$

91) Un circuito LC está constituido por un inductor de $3.30\text{ H}$ y un capacitor de $840\text{ pF}$, inicialmente con una carga de $105\text{ }\mu\text{C}$. El interruptor se abre en $\displaystyle t < 0$ y después se cierra en $\displaystyle t = 0$. Calcule las siguientes cantidades en $\displaystyle t = 2.00 \text{ ms}$: a) la energía almacenada en el capacitor, b) la energía almacenada en el inductor y c) la energía total del circuito.  
*Respuesta:* a) $\displaystyle 6.03 \text{ J}$; b) $\displaystyle 0.529 \text{ J}$; c) $\displaystyle 6.56 \text{ J}$

---

<a id="seccion-9"></a>
### Energía del oscilador armónico simple [↑](#indice)

Examinemos la energía mecánica del sistema masa-resorte.

Ya que la superficie no tiene fricción, el sistema está aislado y es de esperar que la energía mecánica total del sistema sea constante. Ahora suponga un resorte sin masa, de modo que la energía cinética del sistema sólo corresponde a la del bloque. Se puede usar la ecuación $\displaystyle v(t) = -\omega A \sin(\omega t + \phi)$ para expresar la energía cinética del bloque como:

$$\displaystyle K = \frac{1}{2} m v^{2}$$

$$\displaystyle K = \frac{1}{2} m [-\omega A \sin(\omega t + \phi)]^{2}$$

$$\displaystyle K = \frac{1}{2} m \omega^{2} A^{2} \sin^{2}(\omega t + \phi) \tag{\color{red}{47}}$$

La energía potencial elástica almacenada en el resorte para cualquier elongación $\displaystyle x$ se conoce por $\displaystyle \frac{1}{2} k x^{2}$. Si usa la ecuación $\displaystyle x(t) = A \cos(\omega t + \phi)$ produce:

$$\displaystyle U = \frac{1}{2} k [A \cos(\omega t + \phi)]^{2}$$

$$\displaystyle U = \frac{1}{2} k A^{2} \cos^{2}(\omega t + \phi) \tag{\color{red}{48}}$$

Se ve que $\displaystyle K$ y $\displaystyle U$ siempre son cantidades positivas o cero. La energía mecánica total del oscilador armónico simple se expresa como:

$$\displaystyle E = K + U \tag{\color{red}{49}}$$

Al sustituir las ecuaciones $\displaystyle \tag{\color{red}{47}}$ y $\displaystyle \tag{\color{red}{48}}$ en la ecuación $\displaystyle \tag{\color{red}{49}}$:

$$\displaystyle E = \frac{1}{2} m \omega^{2} A^{2} \sin^{2}(\omega t + \phi) + \frac{1}{2} k A^{2} \cos^{2}(\omega t + \phi)$$

Puesto que $\displaystyle \omega^{2} = \frac{k}{m}$, entonces $\displaystyle m \omega^{2} = k$, por lo tanto:

$$\displaystyle E = \frac{1}{2} k A^{2} \sin^{2}(\omega t + \phi) + \frac{1}{2} k A^{2} \cos^{2}(\omega t + \phi)$$

$$\displaystyle E = \frac{1}{2} k A^{2} [\sin^{2}(\omega t + \phi) + \cos^{2}(\omega t + \phi)]$$

A partir de la identidad $\displaystyle \sin^{2}\theta + \cos^{2}\theta = 1$, se ve que la cantidad entre corchetes es la unidad. En consecuencia, esta ecuación se reduce a:

$$\displaystyle E = \frac{1}{2} k A^{2} \tag{\color{red}{50}}$$

Esto es, la energía mecánica total de un oscilador armónico simple es una constante del movimiento y es proporcional al cuadrado de la amplitud. La energía mecánica total es igual a la energía potencial máxima almacenada en el resorte cuando $\displaystyle x = \pm A$ porque $\displaystyle v = 0$ en estos puntos y no hay energía cinética. En la posición de equilibrio, donde $\displaystyle U = 0$ porque $\displaystyle x = 0$, la energía total, toda en forma de energía cinética, es de nuevo $\displaystyle \frac{1}{2} k A^{2}$.

En todo momento, la suma de las energías cinética y potencial es una constante igual a $\displaystyle \frac{1}{2} k A^{2}$, la energía total del sistema. La energía se transforma continuamente entre energía potencial almacenada en el resorte y energía cinética del bloque.

---

<a id="ejercicios-7"></a>
#### EJERCICIOS [↑](#indice)

92) Una partícula de masa $\displaystyle m = 500 \text{ g}$ está unida a un muelle de constante $\displaystyle k = 200 \text{ N/m}$. Se desplaza la masa $2\text{ cm}$ de la posición de equilibrio, y se le proporciona en el instante inicial $\displaystyle t=0$, una velocidad de $100\text{ cm/s}$ hacia la izquierda.  
a) Calcular el periodo de las oscilaciones.  
b) La ecuación del M.A.S.  
c) Calcular la velocidad, energía cinética, potencial y el (los) instante(s) en el que la partícula pasa por la posición $\displaystyle x = -3 \text{ cm}$ dirigiéndose hacia la derecha.  
*Respuesta:* a) $\displaystyle T = \pi/10 \text{ s}$; b) $\displaystyle x(t) = 5.38 \cos(20t + 1.1903) \text{ cm}, v(t) = -107.7 \sin(20t + 1.1903) \text{ cm/s}$; c) $\displaystyle v = 0.894 \text{ m/s}, E_{c} = 0.2 \text{ J}, E_{p} = 0.09 \text{ J}, E = 0.29 \text{ J}$

93) Un muelle horizontal tiene una constante recuperadora de $\displaystyle k = 48 \text{ N/m}$. En el extremo del muelle se coloca una masa de $\displaystyle m = 0.75 \text{ kg}$ y se estira el muelle $0.2\text{ m}$ a partir de la posición de equilibrio, soltándose a continuación, momento en el que se empieza a contar el tiempo. Hallar:  
a) El periodo de la oscilación.  
b) La ecuación del M.A.S.  
c) El (los) instante(s) en el (los) que el móvil pasa por la posición $\displaystyle x = -0.1 \text{ m}$, después de haber pasado por el origen.  
d) Los valores de la velocidad, aceleración, energía cinética, potencial y total del móvil en dicho(s) instante(s).  
*Respuesta:* a) $\displaystyle T = \pi/4 \text{ s}$; b) $\displaystyle x(t) = 0.2 \cos(8t), v(t) = -1.6 \sin(8t)$; d) $\displaystyle v = -1.39 \text{ m/s}, E_{c} = 0.72 \text{ J}, E_{p} = 0.24 \text{ J}, E = 0.96 \text{ J}$

94) Una partícula de $100\text{ g}$ de masa sujeta a un muelle, se desplaza hacia la derecha de su posición de equilibrio $2\text{ cm}$. A continuación se suelta y comienza a oscilar armónicamente a lo largo del eje OX con una frecuencia de $4\text{ s}^{-1}$. Determine:  
a) Las ecuaciones de la posición y de la velocidad de la partícula, en cualquier instante de tiempo.  
b) El periodo de oscilación de la partícula, su aceleración máxima y la fuerza máxima que actúa sobre la misma.  
c) La constante elástica del muelle así como la energía cinética, la energía potencial y la energía total de la partícula cuando pasa por la posición de equilibrio.  
*Respuesta:* a) $\displaystyle x(t) = 0.02 \cos(8\pi t); v(t) = -0.02\pi \sin(8\pi t)$; b) $\displaystyle T = 0.25 \text{ s}; a_{\max} = \pm 12.63 \text{ m/s}^{2}, F_{\max} = \pm 1.26 \text{ N}$; c) $\displaystyle k = 63.17 \text{ N/m}, E_{c} = E_{T} = 0.0126 \text{ J}, E_{p} = 0$

95) Una masa puntual de $10\text{ g}$ está sujeta a un muelle y oscila sobre el eje OX con una frecuencia de $4\text{ Hz}$ y una amplitud de $6\text{ mm}$. Si en el instante inicial la elongación de la partícula es igual a la máxima elongación, determinar:  
a) Las ecuaciones de la elongación y la velocidad de la masa en cualquier instante de tiempo.  
b) El periodo de oscilación de la masa, su aceleración máxima y la fuerza máxima que actúa sobre la misma.  
c) La constante elástica del muelle, así como la energía cinética, la energía potencial y la energía total de la partícula cuando pasa por el punto de equilibrio.  
*Respuesta:* a) $\displaystyle x(t) = 0.006 \cos(8\pi t), v(t) = -0.048\pi \sin(8\pi t)$; b) $\displaystyle T = 0.25 \text{ s}, a_{\max} = 3.80 \text{ m/s}^{2}$

96) Una masa puntual de $10\text{ g}$ está sujeta a un muelle y oscila sobre el eje OX con una frecuencia de $4\text{ Hz}$ y una amplitud de $6\text{ mm}$. Si en el instante inicial la elongación de la partícula es cero, determinar:  
a) Las ecuaciones de la elongación y la velocidad de la masa en cualquier instante de tiempo.  
b) El periodo de oscilación de la masa, su aceleración máxima y la fuerza máxima que actúa sobre la misma.  
c) La constante elástica del muelle, así como la energía cinética, la energía potencial y la energía total de la partícula cuando pasa por el punto de equilibrio.  
*Respuesta:* a) $\displaystyle x(t) = 0.006 \cos(8\pi t - \pi/2), v(t) = -0.048\pi \sin(8\pi t - \pi/2)$; b) $\displaystyle T = 0.25 \text{ s}, a_{\max} = 3.80 \text{ m/s}^{2}$; c) $\displaystyle k = 6.3 \text{ N/m}, E_{c} = 1.13 \times 10^{-4} \text{ J}$

97) Un muelle elástico de constante $\displaystyle k = 0.4 \text{ N/m}$ está unido a una masa de $\displaystyle m = 25 \text{ g}$. En el instante inicial su posición es $\displaystyle x = 5 \text{ cm}$ y su velocidad $\displaystyle v = -20\sqrt{3} \text{ cm/s}$. Calcular:  
a) El periodo de la oscilación.  
b) Las ecuaciones de la posición, velocidad y aceleración de este M.A.S.  
c) El (los) instante(s) en el que el móvil pasa por el origen, $\displaystyle x=0$, y su velocidad.  
d) La energía cinética, potencial y total cuando el móvil pasa por la posición $\displaystyle x = -5 \text{ cm}$.  
*Respuesta:* a) $\displaystyle T = 1.5708 \text{ s}$; b) $\displaystyle x(t) = 0.1 \cos(4t + \pi/3)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle v(t) = -0.4 \sin(4t + \pi/3)$ con $\displaystyle v$ en $[\text{m/s}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle a(t) = -1.6 \cos(4t + \pi/3)$ con $\displaystyle a$ en $[\text{m/s}^{2}]$ y $\displaystyle t$ en $[\text{s}]$; c) $\displaystyle t = \frac{n\pi}{4} + \frac{\pi}{24}, v_{\max} = \pm 0.4 \text{ m/s}$; d) $\displaystyle E_{p} = 5 \times 10^{-4} \text{ J}, E = 2 \times 10^{-3} \text{ J}, E_{c} = 1.5 \times 10^{-3} \text{ J}$

98) Una partícula de $\displaystyle m = 200 \text{ g}$ de masa unida a un muelle horizontal, realiza un movimiento armónico simple siendo la frecuencia angular $\displaystyle \omega = 100 \text{ rad/s}$. Sabemos que en el instante $\displaystyle t=0$, la posición inicial es $\displaystyle -0.5\sqrt{3} \text{ cm}$ y la velocidad inicial de la partícula es $\displaystyle 50 \text{ cm/s}$.  
a) Escribir la ecuación del M.A.S.  
b) Calcular la constante elástica del muelle y la energía total del movimiento.  
*Respuesta:* a) $\displaystyle x(t) = 0.01 \cos(100t - 5\pi/6)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; b) $\displaystyle k = 2000 \text{ N/m}, E = 0.1 \text{ J}$

99) Un cuerpo de $200\text{ g}$ está unido a un resorte horizontal, sin rozamiento, sobre una mesa y a lo largo del eje OX, con una frecuencia angular $\displaystyle \omega = 8.00 \text{ rad/s}$. En el instante $\displaystyle t=0$ el alargamiento del resorte es de $4.0\text{ cm}$ respecto a la posición de equilibrio y el cuerpo lleva una velocidad de $-20\text{ cm/s}$. Determina:  
a) La amplitud y la fase inicial del M.A.S. realizado por el cuerpo.  
b) La constante elástica del resorte y la energía mecánica del sistema.  
*Respuesta:* a) $\displaystyle A = 0.0472 \text{ m}, \phi = 0.5586 \text{ rad}$; b) $\displaystyle k = 12.8 \text{ N/m}, E = 0.0142 \text{ J}$

100) Una partícula de $300\text{ g}$ de masa está unida a un muelle elástico de constante $\displaystyle k = 43.2 \text{ N/m}$ y describe un movimiento armónico simple de $20\text{ cm}$ de amplitud. Sabiendo que en el instante $\displaystyle t=0$ se encuentra a $10\text{ cm}$ del origen moviéndose hacia la izquierda, determinar:  
a) Las ecuaciones de la posición, velocidad y aceleración en función del tiempo.  
b) Valores de $\displaystyle t$ en los que la partícula pasa por el origen.  
c) Las energías potencial, cinética y total en el instante inicial y en cualquier instante.  
*Respuesta:* a) $\displaystyle x(t) = 0.20 \cos(12t + \pi/3)$ con $\displaystyle x$ en $[\text{m}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle v(t) = -2.4 \sin(12t + \pi/3)$ con $\displaystyle v$ en $[\text{m/s}]$ y $\displaystyle t$ en $[\text{s}]$; $\displaystyle a(t) = -28.8 \cos(12t + \pi/3)$ con $\displaystyle a$ en $[\text{m/s}^{2}]$ y $\displaystyle t$ en $[\text{s}]$; b) $\displaystyle t = \frac{n\frac{\pi}{2} - \frac{\pi}{3}}{12}$ para $\displaystyle n = 1, 2, 3\dots$; c) $\displaystyle E_{p}(t) = 0.864 \cos^{2}(12t + \pi/3) \text{ J}, E_{c}(t) = 0.864 \sin^{2}(12t + \pi/3) \text{ J}, E_{M} = 0.864 \text{ J}$

101) Un objeto de masa $30\text{ g}$ se encuentra apoyado sobre una superficie horizontal y sujeto a un muelle. Se observa que oscila sobre la superficie, en la dirección del eje OX, siguiendo un M.A.S de frecuencia $5\text{ s}^{-1}$ con una amplitud de $10\text{ cm}$. Si en el instante inicial, la elongación de la partícula es igual a la mitad de la máxima elongación o amplitud, determine:  
a) Las ecuaciones de la elongación y la velocidad de la masa en cualquier instante de tiempo.  
b) El período de oscilación de la masa, su aceleración máxima y la fuerza máxima que actúa sobre la misma.  
c) La constante elástica del muelle, así como la energía cinética, la energía potencial y la energía total del objeto cuando pasa por uno de sus puntos de máxima elongación.

102) Un cuerpo de masa $200\text{ g}$ oscila según un movimiento armónico simple de ecuación, en unidades del Sistema Internacional: $\displaystyle x(t) = 0.1 \cos(25t)$.  
Determine:  
a) La frecuencia del oscilador.  
b) La constante recuperadora.  
c) La energía cinética, potencial y mecánica para $\displaystyle t = 0.5 \text{ s}$.  
d) A la vista de los resultados para la energía, ¿puedes concluir algo sobre la posición del cuerpo?  
*Respuesta:* a) $\displaystyle f = 3.98 \text{ Hz}$; b) $\displaystyle k = 125 \text{ N/m}$; c) $\displaystyle E_{c} = 2.75 \times 10^{-3} \text{ J}, E_{p} = 0.6225 \text{ J}$; d) La forma de energía más significativa es la potencial, de tal manera que el objeto se encuentra cerca de uno de los extremos de la trayectoria (en el extremo superior según los cálculos).

103) Considere una partícula de $100\text{ g}$ de masa, cuya posición respecto del origen de coordenadas viene dada por la función $\displaystyle x(t) = A \sin(\omega t + 3\pi/5)$, donde $\displaystyle x$ se mide en metros y $\displaystyle t$ en segundos. La partícula completa 3 oscilaciones o ciclos cada $6\text{ s}$. En el instante inicial ($\displaystyle t=0\text{ s}$), la partícula se encuentra a $+3\text{ cm}$ del origen de coordenadas.  
a) ¿Cuánto valen la frecuencia angular y la amplitud de las oscilaciones? Exprese la función $\displaystyle x(t)$.  
b) Calcule la posición, la velocidad y la aceleración de la partícula en el instante de tiempo $\displaystyle t = 0.4 \text{ s}$.  
c) ¿Cuánto vale la constante elástica asociada al muelle? Calcule la energía total, la energía potencial y la energía cinética de la partícula en $\displaystyle t = 0.4 \text{ s}$.  
*Respuesta:* a) $\displaystyle \omega = \pi \text{ rad/s}, A = 0.031 \text{ m}$; b) $\displaystyle x(0.4\text{ s}) = 0, v(0.4\text{ s}) = -0.097 \text{ m/s}$; c) $\displaystyle k = 0.986 \text{ N/m}, E_{p} = 0, E_{c} = 4.70 \times 10^{-4} \text{ J}, E_{T} = 4.70 \times 10^{-4} \text{ J}$

104) Tenemos un oscilador armónico simple, formado por un muelle de masa despreciable y una masa en el extremo de $40\text{ g}$, que tiene un período de oscilación de $2\text{ s}$. Construimos un segundo oscilador con un muelle idéntico al del primer oscilador y con una masa diferente.  
a) ¿Qué valor debe tener la masa del segundo oscilador para que su frecuencia de oscilación sea el doble que la del primer oscilador?  
b) Si la amplitud de las oscilaciones para ambos osciladores es de $10\text{ cm}$, ¿cuánto vale, en cada caso, la energía potencial máxima que alcanza cada oscilador?  
c) Calcular la velocidad máxima alcanzada por cada masa.  
*Respuesta:* a) $\displaystyle m = 0.010 \text{ kg}$

105) Un oscilador armónico se encuentra en un instante determinado en una posición que es igual a un tercio de su amplitud $\displaystyle A$. Determina para dicho instante la relación existente entre la energía cinética y la energía potencial ($\displaystyle E_{c}/E_{p}$).  
*Respuesta:* $\displaystyle \frac{E_{c}}{E_{p}} = 8$

---

<div style="text-align: center;">

[Volver al inicio](#inicio) | [Volver al índice](#indice)

</div>

</div>