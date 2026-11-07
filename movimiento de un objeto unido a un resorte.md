# Movimiento Oscilatorio
## Movimiento Armónico Simple (Oscilaciones Libres)

### Movimiento de un Objeto Unido a un Resorte

Como un modelo de movimiento armónico simple, considere un bloque de masa $m$ unido al extremo de un resorte, con el bloque libre de moverse sobre una superficie horizontal sin fricción. Cuando el resorte no está estirado ni comprimido, el bloque queda en reposo, en la posición llamada posición de equilibrio del sistema, que se identifica como $x = 0$. Se sabe por la experiencia que tal sistema oscila de atrás para adelante si se perturba desde su posición de equilibrio.

Se puede entender cualitativamente el movimiento oscilatorio del bloque al recordar primero que, cuando el bloque se desplaza a una posición $x$, el resorte ejerce sobre el bloque una fuerza que es proporcional a la posición y se conoce por la ley de Hooke:

$$\displaystyle F_{s} = -k x \quad {\color{red}(1)}$$

A $F_{s}$ se le llama fuerza restauradora porque siempre se dirige hacia la posición de equilibrio y, en consecuencia, es opuesta al desplazamiento del bloque desde el equilibrio. Es decir, cuando el bloque se desplaza hacia la derecha de $x = 0$, la posición es positiva y la fuerza restauradora se dirige hacia la izquierda. Cuando el bloque está en $x = 0$, la fuerza en el bloque es cero. Cuando el bloque se desplaza a la izquierda de $x = 0$, la posición es negativa y la fuerza restauradora se dirige hacia la derecha.

Al aplicar la segunda ley de Newton al movimiento del bloque, con la ecuación {\color{red}(1)} que proporciona la fuerza neta en la dirección $x$, se obtiene:

$$\displaystyle -k x = m a_{x}$$

$$\displaystyle a_{x} = -\frac{k}{m} x \quad {\color{red}(2)}$$

Es decir, la aceleración del bloque es proporcional a su posición, y la dirección de la aceleración es opuesta a la dirección del desplazamiento del bloque desde el equilibrio. Se dice que los sistemas que se comportan de esta forma exhiben movimiento armónico simple. Un objeto se mueve con movimiento armónico simple siempre que su aceleración es proporcional a su posición y se dirige en sentido opuesto al desplazamiento desde el equilibrio.

Si el bloque se desplaza a una posición $x = A$ y se libera desde el reposo, su aceleración inicial es $-\frac{k A}{m}$. Cuando el bloque pasa a través de la posición de equilibrio $x = 0$, su aceleración es cero. En este instante, su rapidez es un máximo porque la aceleración cambia de signo. Por lo tanto el bloque continúa viajando hacia la izquierda del equilibrio con una aceleración positiva y al final llega a $x = -A$, momento en el que su aceleración es $+\frac{k A}{m}$ y su rapidez de nuevo es cero. El bloque termina un ciclo completo de su movimiento cuando regresa a la posición original y una vez más pasa por $x = 0$ con rapidez máxima. En consecuencia, el bloque oscila entre los puntos de retorno $x = \pm A$. En ausencia de fricción, este movimiento idealizado continuará por siempre porque la fuerza que ejerce el resorte es conservativa. Por lo general, los sistemas reales están sujetos a fricción, así que no oscilan por siempre.

---

### Partícula en Movimiento Armónico Simple

El movimiento descrito en la sección precedente se presenta con tanta frecuencia que se considera el modelo de partícula en movimiento armónico simple para representar tales situaciones. Con el fin de elaborar una representación matemática para este modelo, primero se reconoce que el bloque es una partícula bajo una fuerza neta, como se describe en la ecuación {\color{red}(1)}. Por lo general se elegirá $x$ como el eje a lo largo del que se presenta la oscilación. Recuerde que, por definición, $\displaystyle a = \frac{d v}{d t} = \frac{d^{2} x}{d t^{2}}$, y así la ecuación se puede expresar como:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\frac{k}{m} x \quad {\color{red}(3)}$$

Si la relación $\displaystyle \frac{k}{m}$ se indica con el símbolo $\omega^{2}$ para que la solución sea más simple en forma:

$$\displaystyle \omega^{2} = \frac{k}{m} \quad {\color{red}(4)}$$

entonces la ecuación {\color{red}(3)} se puede escribir en la forma:

$$\displaystyle \frac{d^{2} x}{d t^{2}} = -\omega^{2} x \quad {\color{red}(5)}$$

La solución general de la ecuación diferencial {\color{red}(5)} es:

$$\displaystyle x(t) = c_{1} \cos(\omega t) + c_{2} \sin(\omega t) \quad {\color{red}(6)}$$

donde $c_{1}$ y $c_{2}$ son constantes arbitrarias determinables por las condiciones iniciales. Por comodidad, preferimos expresar esta solución en términos de una sola función trigonométrica como:

$$\displaystyle x(t) = A \cos(\omega t + \phi) \quad {\color{red}(7)}$$

Dado que el coseno de un ángulo no puede ser mayor que 1, el factor $A$ corresponde al desplazamiento máximo llamado **amplitud** de las oscilaciones. La masa oscilará continuamente entre las posiciones $x = A$ y $x = -A$.

El tiempo durante el cual se completa un ciclo se llama **periodo** del movimiento:

$$\displaystyle T = \frac{2 \pi}{\omega} \quad {\color{red}(8)}$$

Si se conoce el número de oscilaciones o ciclos ($n$) de la partícula en un lapso de tiempo ($t$):

$$\displaystyle T = \frac{t}{n} \quad {\color{red}(9)}$$

La **frecuencia** de las oscilaciones es el número de oscilaciones por unidad de tiempo, e igual a la inversa del periodo:

$$\displaystyle f = \frac{1}{T} \quad {\color{red}(10)}$$

$$\displaystyle f = \frac{\omega}{2 \pi} \quad {\color{red}(11)}$$

Si se conoce el número de oscilaciones o ciclos ($n$) en un lapso de tiempo ($t$):

$$\displaystyle f = \frac{n}{t} \quad {\color{red}(12)}$$

Una unidad para la frecuencia es denominada Hertz (Hz), equivalente al número de ciclos por segundo.

Observe que, en ausencia de cualquier efecto externo, la frecuencia depende sólo de las características de la masa y del resorte, y es independiente de las condiciones iniciales y de la gravedad. La frecuencia $\omega$ es un ejemplo de frecuencia angular, con unidades de radianes por segundo:

$$\displaystyle \omega = \sqrt{\frac{k}{m}} \quad {\color{red}(13)}$$

se conoce como **frecuencia angular natural** o simplemente **frecuencia natural** del sistema.

---

## Ejercicios del 1 al 15

### EJERCICIO 1. (Ejercicio 1. Sección 5.1.1 del Zill - Cullen. Sexta Edición)
Una masa que pesa 4 libras se une a un resorte cuya constante es $16\text{ lb/pie}$. ¿Cuál es el periodo del movimiento armónico simple?

**Respuesta:** $\displaystyle T = 0.5539\text{ s}$

---

### EJERCICIO 2.
a) ¿Qué masa debes unir a un muelle de constante $k = 37\text{ N/m}$ para que la frecuencia de oscilación del sistema sea de 1 Hz?  
b) ¿Y para que sea de 4 Hz?

**Respuesta:** a) $\displaystyle m = 0.9372\text{ kg}$; b) $\displaystyle m = 0.0586\text{ kg}$

---

### EJERCICIO 3.
La punta de un diapasón efectúa 440 vibraciones completas en $0.500\text{ s}$. Calcule:  
a) la frecuencia angular y  
b) el periodo del movimiento.

**Respuesta:** a) $\displaystyle \omega = 5529.20\text{ rad/s}$; b) $\displaystyle T = 0.00114\text{ s}$

---

### EJERCICIO 4.
Una cuerda de piano produce un "la medio" vibrando primordialmente a 220 Hz.  
a) Calcule su periodo y frecuencia angular.  
b) Calcule el periodo y la frecuencia angular de una soprano que canta un "la alto", dos octavas más arriba, que es cuatro veces la frecuencia de la cuerda de piano.

**Respuesta:** a) $\displaystyle T = 0.00455\text{ s}$, $\displaystyle \omega = 1382.30\text{ rad/s}$; b) $\displaystyle T = 0.00114\text{ s}$, $\displaystyle \omega = 5529.20\text{ rad/s}$

---

### EJERCICIO 5.
Un oscilador armónico tiene una masa de $0.500\text{ kg}$ y un resorte ideal con $k = 140\text{ kg/s}^{2}$. Calcule:  
a) el periodo;  
b) la frecuencia;  
c) la frecuencia angular.

**Respuesta:** a) $\displaystyle T = 0.3755\text{ s}$; b) $\displaystyle f = 2.6631\text{ Hz}$; c) $\displaystyle \omega = 16.73\text{ rad/s}$

---

### EJERCICIO 6.
Si un objeto en una superficie horizontal sin fricción se une a un resorte, se desplaza y después se suelta, oscilará. Si se desplaza $0.120\text{ m}$ de su posición de equilibrio y se suelta con rapidez inicial cero, después de $0.800\text{ s}$ su desplazamiento es de $0.120\text{ m}$ en el lado opuesto, habiendo pasado por la posición de equilibrio una vez. Calcule:  
a) la amplitud;  
b) el periodo;  
c) la frecuencia.

**Respuesta:** a) $\displaystyle A = 0.120\text{ m}$; b) $\displaystyle T = 1.600\text{ s}$; c) $\displaystyle f = 0.625\text{ Hz}$

---

### EJERCICIO 7. (Primer Examen Parcial. Profesor Willians Medina. UDO Anzoátegui)
Un resorte tiene una longitud de 30 cm. Si se cuelga de él un cuerpo de masa 250 g y se le hace oscilar verticalmente, emplea 6 s en realizar 10 oscilaciones completas. Calcular:  
a) la constante elástica del resorte y  
b) su longitud cuando dicho cuerpo está colgado de él, en reposo.

**Respuesta:** a) $\displaystyle k = 27.42\text{ N/m}$; b) $\displaystyle L = 38.94\text{ cm}$

---

### EJERCICIO 8. (Primer Examen Parcial. Profesor Willians Medina. UDO Anzoátegui)
Una pieza de una máquina está en MAS con frecuencia de 5.00 Hz y amplitud de 1.80 cm. ¿Cuánto tarda la pieza en ir de $x = 0$ a $x = -1.80\text{ cm}$?

**Respuesta:** $\displaystyle t = 0.05\text{ s}$

---

### EJERCICIO 9.
Se crea un oscilador armónico usando un bloque de $0.600\text{ kg}$, que se desliza sobre una superficie sin fricción y un resorte ideal con constante de fuerza desconocida. Se determina que el oscilador tiene un periodo de $0.150\text{ s}$. Calcule la constante de fuerza del resorte.

**Respuesta:** $\displaystyle k = 1052.76\text{ N/m}$

---

### EJERCICIO 10. (Ejercicio 2. Sección 5.1.1 del Zill - Cullen. Sexta Edición)
Una masa de 20 kilogramos se une a un resorte. Si la frecuencia del movimiento armónico simple es $\displaystyle \frac{2}{\pi}\text{ ciclos/s}$:  
a) ¿cuál es la constante del resorte $k$?  
b) ¿Cuál es la frecuencia del movimiento armónico simple si la masa original se reemplaza con una masa de 80 kilogramos?

**Respuesta:** a) $\displaystyle k = 320\text{ N/m}$; b) $\displaystyle f = \frac{1}{\pi}\text{ Hz}$

---

### EJERCICIO 11.
Un cuerpo de masa desconocida se une a un resorte lineal ideal con constante de fuerza de $120\text{ kg/s}^{2}$. Se observa que vibra a una frecuencia de 6.00 Hz. Calcule:  
a) el periodo;  
b) la frecuencia angular;  
c) la masa del cuerpo.

**Respuesta:** a) $\displaystyle T = 0.1667\text{ s}$; b) $\displaystyle \omega = 37.70\text{ rad/s}$; c) $\displaystyle m = 0.0844\text{ kg}$

---

### EJERCICIO 12.
Un cuerpo de 300 g se encuentra unido al techo a través de un muelle. El peso del cuerpo hace que el muelle se deforme 6 cm. Determinar:  
a) Cuál será la frecuencia angular de oscilación del cuerpo cuando se desplaza de su posición de equilibrio.  
b) Qué ocurriría al variar la masa del cuerpo a 500 g.  
c) Determina para este último caso la frecuencia angular y el periodo.

**Respuesta:** a) $\displaystyle \omega = 12.79\text{ rad/s}$; b) Si se varía la masa del cuerpo, cambia la frecuencia angular; c) $\displaystyle \omega = 9.90\text{ rad/s}$, $\displaystyle T = 0.6346\text{ s}$

---

### EJERCICIO 13. (Ejemplo 15.2 del Serway - Jewett. Séptima Edición)
¡Cuidado con los baches! Un automóvil con una masa de 1300 kg se construye de modo que su chasis está sostenido mediante cuatro amortiguadores. Cada amortiguador tiene una constante de fuerza de $20000\text{ N/m}$. Dos personas que viajan en el automóvil tienen una masa combinada de 160 kg. Encuentre la frecuencia de vibración del automóvil después de que pasa sobre un bache en el camino. Suponga que el automóvil se detiene al lado del camino y las dos personas salen del auto. Una de ellas presiona hacia abajo el automóvil y lo libera de modo que oscile en la vertical. ¿La frecuencia de la oscilación es la misma que el valor recién calculado?

**Respuesta:** $\displaystyle f = 1.18\text{ Hz}$ (con pasajeros), $\displaystyle f = 1.25\text{ Hz}$ (sin pasajeros)

---

### EJERCICIO 14.
Una silla de $42.5\text{ kg}$ se sujeta a un resorte y se le permite oscilar. Cuando la silla está vacía, tarda $1.30\text{ s}$ en efectuar una vibración completa. Cuando una persona se sienta en ella, sin tocar el piso con los pies, la silla tarda $2.54\text{ s}$ en efectuar un ciclo. Calcule la masa de la persona.

**Respuesta:** $\displaystyle m_{p} = 119.74\text{ kg}$

---

### EJERCICIO 15.
Un resorte se mantiene vertical apoyado en el suelo. Se coloca un cuerpo de masa $m$ en reposo sobre el resorte y se observa que éste se acorta 6 cm. Si empujamos ligeramente el cuerpo hacia abajo y lo soltamos:  
a) ¿cuál será la frecuencia de las oscilaciones?  
b) ¿y si la masa del cuerpo fuese $2 m$?

**Respuesta:** a) $\displaystyle f_{1} = 2.04\text{ Hz}$; b) $\displaystyle f_{2} = 1.44\text{ Hz}$