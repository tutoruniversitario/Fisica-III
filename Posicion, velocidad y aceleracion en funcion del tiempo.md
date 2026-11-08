### Posición, velocidad y aceleración en función del tiempo

#### Posición de la partícula en función del tiempo
$$\displaystyle x(t) = A\cos(\omega t + \phi) \quad \color{red}{(7)}$$

#### Rapidez de la partícula en función del tiempo
Podemos obtener la rapidez de una partícula que experimenta un movimiento armónico simple diferenciando la ecuación $\displaystyle \color{red}{(7)}$ respecto del tiempo:

$$\displaystyle v(t) = \frac{dx}{dt}$$
$$\displaystyle v(t) = -\omega A\sin(\omega t + \phi) \quad \color{red}{(14)}$$

#### Aceleración de la partícula en función del tiempo
La aceleración de la partícula es

$$\displaystyle a(t) = \frac{dv}{dt}$$
$$\displaystyle a(t) = -\omega^2 A\cos(\omega t + \phi) \quad \color{red}{(15)}$$

---

### Convenio de signos para la posición inicial y la velocidad inicial

#### Movimiento horizontal
Si el cuerpo se desplaza una posición $\displaystyle x_0$ hacia la derecha (estirando el resorte) y se inicia el movimiento, la posición inicial $\displaystyle x_0$ es positiva, mientras que si el cuerpo se desplaza una posición $\displaystyle x_0$ hacia la izquierda (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $\displaystyle v_0$ hacia la derecha es positiva y hacia la izquierda es negativa.

#### Movimiento vertical
Si el cuerpo se desplaza una posición $\displaystyle x_0$ hacia abajo (estirando el resorte) y se inicia el movimiento, la posición inicial $\displaystyle x_0$ es positiva, mientras que si el cuerpo se desplaza una posición $\displaystyle x_0$ hacia arriba (comprimiendo el resorte) y se inicia el movimiento, la posición inicial es negativa. La velocidad inicial $\displaystyle v_0$ hacia abajo es positiva y hacia arriba es negativa.

---

### Amplitud y ángulo de fase en función de las condiciones iniciales

Suponga que la posición inicial $\displaystyle x_0$ y la velocidad inicial $\displaystyle v_0$ de un solo oscilador están dadas, es decir, en $\displaystyle t = 0$, $\displaystyle x = x_0$ y $\displaystyle v = v_0$. Obtenemos $\displaystyle c_1 = x_0$ y $\displaystyle c_2 = \frac{v_0}{\omega}$. La ecuación $\displaystyle \color{red}{(6)}$ se escribe como:

$$\displaystyle x(t) = x_0\cos(\omega t) + \frac{v_0}{\omega}\sin(\omega t) \quad \color{red}{(16)}$$

Al desarrollar la ecuación $\displaystyle \color{red}{(7)}$:

$$\displaystyle x(t) = A\cos(\omega t)\cos\phi - A\sin(\omega t)\sin\phi \quad \color{red}{(17)}$$

Comparando las ecuaciones $\displaystyle \color{red}{(16)}$ y $\displaystyle \color{red}{(17)}$, tenemos:

$$\displaystyle A\cos\phi = x_0 \quad \color{red}{(18)}$$
$$\displaystyle -A\sin\phi = \frac{v_0}{\omega} \quad \color{red}{(19)}$$

Elevamos al cuadrado, sumamos cada ecuación y usando la identidad $\displaystyle \cos^2\phi + \sin^2\phi = 1$, tenemos:

$$\displaystyle x_0^2 + \left(\frac{v_0}{\omega}\right)^2 = A^2\cos^2\phi + A^2\sin^2\phi = A^2$$

Eligiendo la raíz cuadrada positiva para $\displaystyle A$ obtenemos:

$$\displaystyle A = \sqrt{x_0^2 + \left(\frac{v_0}{\omega}\right)^2} \quad \color{red}{(20)}$$

El ángulo $\displaystyle \phi$ se llama ángulo de fase, y puede determinarse dividiendo la ecuación $\displaystyle \color{red}{(19)}$ entre la ecuación $\displaystyle \color{red}{(18)}$, para obtener:

$$\displaystyle \frac{-A\sin\phi}{A\cos\phi} = \frac{\frac{v_0}{\omega}}{x_0}$$
$$\displaystyle -\tan\phi = \frac{v_0}{\omega x_0}$$
$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_0}{\omega x_0}\right) \quad \color{red}{(21)}$$

---

### Casos particulares para el ángulo de fase

* Posición inicial: $\displaystyle x_0 = A$, Velocidad inicial: $\displaystyle v_0 = 0 \implies \phi = 0$.
* Posición inicial: $\displaystyle x_0 = -A$, Velocidad inicial: $\displaystyle v_0 = 0 \implies \phi = -\pi$.
* Posición inicial: $\displaystyle x_0 = 0$, Velocidad inicial: $\displaystyle v_0 > 0 \implies \phi = -\pi/2$.
* Posición inicial: $\displaystyle x_0 = 0$, Velocidad inicial: $\displaystyle v_0 < 0 \implies \phi = \pi/2$.

---

### Ajustes en el ángulo de fase (Caso general)

Si utilizamos la ecuación $\displaystyle \color{red}{(7)}$ como la ecuación del movimiento:

$$\displaystyle x(t) = A\cos(\omega t + \phi) \quad \color{red}{(7)}$$

el ángulo de fase se determina según la ecuación $\displaystyle \color{red}{(21)}$:

$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_0}{\omega x_0}\right) \quad \color{red}{(21)}$$

Sin embargo, es necesario elegir el valor apropiado de $\displaystyle \phi$ dependiendo de los valores (signo) de la rapidez inicial ($\displaystyle v_0$) y la posición inicial ($\displaystyle x_0$) de la partícula.

Entre:
$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_0}{\omega x_0}\right)$$
$$\displaystyle \phi = \tan^{-1}\left(-\frac{v_0}{\omega x_0}\right) - \pi$$

elegir como ángulo de fase el que cumpla las condiciones:
* El signo de $\displaystyle \cos\phi$ coincide con el signo de $\displaystyle x_0$ y
* El signo de $\displaystyle \sin\phi$ coincide con el signo opuesto de $\displaystyle v_0$.

---

### EJERCICIOS

### **EJERCICIO 16.**
Se hace oscilar verticalmente un cuerpo de masa $\displaystyle 80\text{ g}$ que está colgado de un muelle en hélice de constante elástica $\displaystyle 2\text{ N/m}$. Si la amplitud de la oscilación es de $\displaystyle 10\text{ cm}$, ¿cuál será la expresión de su elongación en función del tiempo?

**Respuesta:** $\displaystyle x(t) = 10\cos(5t + \phi_0)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{cm}$)

---

### **EJERCICIO 17.**
La aceleración (en $\displaystyle \text{m/s}^2$) de un M.A.S. en función de la elongación (en $\displaystyle \text{m}$) es $\displaystyle a = -256x$. Expresar esta aceleración en función del tiempo sabiendo que la amplitud de la vibración es de $\displaystyle 2.5\text{ cm}$. Considérese nula la constante de fase.

**Respuesta:** $\displaystyle a(t) = -6.4\cos(16t)\text{ m/s}^2$

---

### **EJERCICIO 18.**
Un cuerpo de masa $\displaystyle m = 2\text{ kg}$ está unido a un muelle horizontal de constante $\displaystyle k = 5\text{ N/m}$. El muelle se alarga $\displaystyle 10\text{ cm}$ y se suelta en el instante inicial $\displaystyle t = 0$. Hallar:
a) La frecuencia, el período y la amplitud del movimiento. Escribir la ecuación del M.A.S.
b) ¿En qué instante pasa el cuerpo por primera vez por la posición de equilibrio?

**Respuesta:** 
a) $\displaystyle f = 0.2515\text{ Hz}$, $\displaystyle T = 3.98\text{ s}$, $\displaystyle A = 0.1\text{ m}$; $\displaystyle x(t) = 0.1\cos(1.58t)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{m}$)
b) $\displaystyle t = 0.994\text{ s}$

---

### **EJERCICIO 19.** Ejercicio 5. Sección 5.1.1 del Zill - Cullen. Sexta Edición. Página 207.
Una masa que pesa $\displaystyle 20\text{ libras}$ alarga a un resorte $\displaystyle 6\text{ pulgadas}$. La masa se libera al inicio desde el reposo de un punto $\displaystyle 6\text{ pulgadas}$ abajo de la posición de equilibrio.
a) Encuentre la posición de la masa en los tiempos $\displaystyle t = \pi/12$, $\displaystyle \pi/8$, $\displaystyle \pi/6$, $\displaystyle \pi/4$ y $\displaystyle 9\pi/32\text{ s}$.
b) ¿Cuál es la velocidad de la masa cuando $\displaystyle t = 3\pi/16\text{ s}$? ¿En qué dirección se dirige la masa en este instante?
c) ¿En qué tiempos la masa pasa por la posición de equilibrio?

**Respuesta:**
a) $\displaystyle x(\pi/12) = -0.25\text{ ft}$, $\displaystyle x(\pi/8) = 0\text{ ft}$, $\displaystyle x(\pi/6) = 0.25\text{ ft}$, $\displaystyle x(\pi/4) = 0.5\text{ ft}$, $\displaystyle x(9\pi/32) = -0.3536\text{ ft}$
b) $\displaystyle v(3\pi/16) = -4\text{ ft/s}$ (se dirige en sentido ascendente)
c) $\displaystyle t = \frac{(2n + 1)\pi}{16}\text{ s}$, para $\displaystyle n = 0, 1, 2, \dots$

---

### **EJERCICIO 20.**
Una partícula describe un movimiento armónico simple con una frecuencia de $\displaystyle 10\text{ Hz}$ y una amplitud de $\displaystyle 5\text{ cm}$. Calcular:
a) Las funciones de la elongación y de la velocidad de la partícula si para $\displaystyle t = 0$ está en la posición $\displaystyle x = +5\text{ cm}$.
b) La aceleración para $\displaystyle t = 2\text{ s}$.

**Respuesta:**
a) $\displaystyle x(t) = 0.05\cos(20\pi t)\text{ m}$, $\displaystyle v(t) = -\pi\sin(20\pi t)\text{ m/s}$
b) $\displaystyle a(2\text{ s}) = 197.39\text{ m/s}^2$

---

### **EJERCICIO 21.**
Una partícula describe un movimiento armónico simple con un periodo de $\displaystyle 2\text{ s}$ y una amplitud de $\displaystyle 25\text{ cm}$. Calcular:
a) Las funciones de la elongación y de la velocidad de la partícula si para $\displaystyle t = 0$ está en la posición $\displaystyle x = +25\text{ cm}$.
b) La aceleración para $\displaystyle t = 3\text{ s}$.

**Respuesta:**
a) $\displaystyle x(t) = 0.25\cos(\pi t)\text{ m}$, $\displaystyle v(t) = -0.25\pi\sin(\pi t)\text{ m/s}$
b) $\displaystyle a(3\text{ s}) = 2.47\text{ m/s}^2$

---

### **EJERCICIO 22.** Primer Examen Parcial. Profesor Willians Medina. Universidad de Oriente. Núcleo de Anzoátegui. 08/05/2026.
Estiramos un resorte $\displaystyle 5\text{ cm}$ y lo dejamos oscilar libremente resultando que completa una oscilación cada $\displaystyle 0.2\text{ s}$. Calcular:
a) La función que nos permite calcular su posición en función del tiempo.
b) La velocidad y la aceleración a la que estará sometido el extremo libre a los $\displaystyle 15\text{ s}$ de iniciado el movimiento.

**Respuesta:**
a) $\displaystyle x(t) = 0.05\cos(10\pi t)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{m}$)
b) $\displaystyle v(15\text{ s}) = 0\text{ m/s}$, $\displaystyle a(15\text{ s}) = -49.35\text{ m/s}^2$

---

### **EJERCICIO 23.**
Una partícula que se mueve de acuerdo a un movimiento armónico simple tarda $\displaystyle 1\text{ s}$ en llegar de un extremo a otro de su trayectoria. Sabiendo que la distancia que separa ambas posiciones es de $\displaystyle 16\text{ cm}$, y que el movimiento se inicia en un extremo de la trayectoria, determinar:
a) El periodo del movimiento.
b) La amplitud de las oscilaciones.
c) La posición de la partícula a los $\displaystyle 1.5\text{ segundos}$.

**Respuesta:**
a) $\displaystyle T = 2\text{ s}$
b) $\displaystyle A = 8 \times 10^{-2}\text{ m}$
c) $\displaystyle x(1.5) = 0\text{ m}$

---

### **EJERCICIO 24.**
Una masa puntual está sujeta a un resorte elástico y oscila sobre el eje OX con una frecuencia de $\displaystyle 0.5\text{ Hz}$ y una amplitud de $\displaystyle 30\text{ cm}$. Si en el instante inicial su elongación es de $\displaystyle +30\text{ cm}$, determine:
a) Las funciones de la elongación, la velocidad y la aceleración.
b) Su posición y velocidad cuando $\displaystyle t = 2.5\text{ s}$.
c) Su aceleración cuando $\displaystyle t = 3\text{ s}$.

**Respuesta:**
a) $\displaystyle x(t) = 0.30\cos(\pi t)\text{ m}$; $\displaystyle v(t) = -0.30\pi\sin(\pi t)\text{ m/s}$; $\displaystyle a(t) = -0.30\pi^2\cos(\pi t)\text{ m/s}^2$
b) $\displaystyle x(2.5\text{ s}) = 0\text{ m}$; $\displaystyle v(2.5\text{ s}) = -0.94\text{ m/s}$
c) $\displaystyle a(3\text{ s}) = +2.96\text{ m/s}^2$

---

### **EJERCICIO 25.**
Una partícula de $\displaystyle 10\text{ kg}$ de masa está sujeta a un muelle de constante elástica de $\displaystyle 10\text{ N/m}$. En el instante inicial se desplaza $\displaystyle 0.5\text{ m}$ de la posición de equilibrio y se suelta con velocidad nula. Representa la elongación y la velocidad frente al tiempo.

**Respuesta:** $\displaystyle x(t) = 0.5\cos(t)\text{ m}$, $\displaystyle v(t) = -0.5\sin(t)\text{ m/s}$

---

### **EJERCICIO 26.**
Se cuelga un objeto de $\displaystyle 200\text{ g}$ de un muelle sujeto al techo de $\displaystyle 35\text{ cm}$ de longitud y su nueva longitud es de $\displaystyle 45\text{ cm}$.
a) Determinar la constante de elasticidad $\displaystyle k$ del muelle.
b) Si estiramos el muelle hasta que mida $\displaystyle 55\text{ cm}$ y lo soltamos, determina las fuerzas que actúan sobre el muelle.

**Respuesta:**
a) $\displaystyle k = 19.6\text{ N/m}$
b) $\displaystyle P = 1.96\text{ N}$, $\displaystyle F_t = -1.96\text{ N}$

---

### **EJERCICIO 27.**
Tenemos colgado verticalmente un muelle con una constante $\displaystyle k = 400\text{ N/m}$ y queremos colgarle una masa para que oscile con un periodo de $\displaystyle 1\text{ s}$. Calcular:
a) La masa que debemos colgarle para conseguir ese periodo.
b) Su posición para $\displaystyle t = 1.5\text{ s}$ si, para que empiece a vibrar, levantamos la masa $\displaystyle 4\text{ cm}$ por encima de su posición de equilibrio y contamos el tiempo desde que la soltamos.

**Respuesta:**
a) $\displaystyle m = 10.13\text{ kg}$
b) $\displaystyle x(1.5\text{ s}) = -0.04\text{ m} = -A$

---

### **EJERCICIO 28.** Primer Examen Parcial. Profesor Willians Medina. Universidad de Oriente. Núcleo de Anzoátegui. 08/05/2026.
Un M.A.S. tiene una frecuencia de $\displaystyle 5\text{ Hz}$ y una amplitud de $\displaystyle 8\text{ mm}$. En el instante $\displaystyle t = 0$, el móvil se encuentra en el centro de la vibración y se desplaza en sentido positivo. Expresar su elongación, su velocidad y su aceleración como funciones del tiempo.

**Respuesta:**
$\displaystyle x(t) = 8 \times 10^{-3}\cos(10\pi t - \pi/2)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{m}$)
$\displaystyle v(t) = -8 \times 10^{-2}\pi\sin(10\pi t - \pi/2)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle v$ en $\displaystyle \text{m/s}$)
$\displaystyle a(t) = -0.8\pi^2\cos(10\pi t - \pi/2)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle a$ en $\displaystyle \text{m/s}^2$)

---

### **EJERCICIO 29.**
Un bloque de $\displaystyle 2.00\text{ kg}$, que se desliza sin fricción, se conecta a un resorte ideal con $\displaystyle k = 300\text{ N/m}$. En $\displaystyle t = 0$, el resorte no está estirado ni comprimido y el bloque se mueve en la dirección negativa a $\displaystyle 12.00\text{ m/s}$. Calcule:
a) La amplitud.
b) El ángulo de fase.
c) Escriba una ecuación para la posición en función del tiempo.
d) Repita los incisos a)-c) pero suponga que, en $\displaystyle t = 0$, el bloque tiene una velocidad de $\displaystyle -4.00\text{ m/s}$, y un desplazamiento de $\displaystyle +0.200\text{ m}$.

**Respuesta:**
a) $\displaystyle A = 0.97\text{ m}$
b) $\displaystyle \phi = \pi/2\text{ rad}$
c) $\displaystyle x(t) = 0.97\cos(12.32t - 3\pi/2)\text{ m}$
d) $\displaystyle A = 0.380\text{ m}$, $\displaystyle \phi = 1.02\text{ rad}$, $\displaystyle x(t) = 0.380\cos(12.32t + 1.02)\text{ m}$

---

### **EJERCICIO 30.**
Un cuerpo que se mueve describiendo un movimiento armónico simple a lo largo del eje X presenta, en un instante inicial, una aceleración nula y una velocidad de $\displaystyle -5\mathbf{\hat{i}}\text{ m/s}$, la frecuencia del movimiento es $\displaystyle 0.25\text{ Hz}$. Determine la expresión matemática que describe la elongación del muelle en función del tiempo. Justifique su respuesta.

**Respuesta:** $\displaystyle x(t) = \frac{10}{\pi}\cos(0.5\pi t - 3\pi/2)\text{ m}$

---

### **EJERCICIO 31.**
Un objeto está en movimiento armónico simple con periodo de $\displaystyle 1.200\text{ s}$ y amplitud de $\displaystyle 0.600\text{ m}$. En $\displaystyle t = 0$, el objeto está en $\displaystyle x = 0$. ¿A qué distancia está de la posición de equilibrio cuando $\displaystyle t = 0.480\text{ s}$?

**Respuesta:** $\displaystyle x = -0.360\text{ m}$

---

### **EJERCICIO 32.**
Una partícula vibra de tal modo que tarda $\displaystyle 0.50\text{ s}$ en ir desde un extremo a la posición de equilibrio, distantes entre sí $\displaystyle 8.0\text{ cm}$. Si para $\displaystyle t = 0$ la elongación de la partícula es $\displaystyle 4.0\text{ cm}$, hallar la ecuación que define este movimiento.

**Respuesta:** $\displaystyle x(t) = 0.08\cos(\pi t - \pi/3)\text{ m}$

---

### **EJERCICIO 33.** Ejercicios 6 y 7. Sección 5.1.1 del Zill - Cullen. Sexta Edición. Página 207.

**Ejercicio 6.**
Una fuerza de $\displaystyle 400\text{ newtons}$ alarga un resorte $\displaystyle 2\text{ metros}$. Una masa de $\displaystyle 50\text{ kilogramos}$ se une al extremo del resorte y se libera inicialmente desde la posición de equilibrio con una velocidad hacia arriba de $\displaystyle 10\text{ m/s}$. Encuentre la ecuación del movimiento.

**Ejercicio 7.**
Otro resorte cuya constante es $\displaystyle 20\text{ N/m}$ se suspende del mismo soporte, pero paralelo al sistema resorte-masa del problema 6. Al segundo resorte se le coloca una masa de $\displaystyle 20\text{ kilogramos}$, y ambas masas se liberan al inicio desde la posición de equilibrio con una velocidad ascendente de $\displaystyle 10\text{ m/s}$.
a) ¿Cuál masa exhibe la mayor amplitud de movimiento?
b) ¿Cuál masa se mueve más rápido en $\displaystyle t = \pi/4\text{ s}$?
c) ¿En qué instantes las dos masas están en la misma posición? ¿Dónde están las masas en estos instantes? ¿En qué direcciones se están moviendo las masas?

**Respuesta:**
* **Ejercicio 6:** $\displaystyle x(t) = -5\sin(2t)\text{ m}$
* **Ejercicio 7:**
  a) La masa del segundo resorte ($\displaystyle 20\text{ kg}$) exhibe mayor amplitud ($\displaystyle A_2 = 10\text{ m}$ vs $\displaystyle A_1 = 5\text{ m}$).
  b) La masa del problema 6 ($\displaystyle 50\text{ kg}$) se mueve más rápido en $\displaystyle t = \pi/4\text{ s}$.
  c) Están en la misma posición en $\displaystyle t = n\pi/3\text{ s}$ para $\displaystyle n = 0, 1, 2, \dots$

---

### **EJERCICIO 34.** Ejercicios 3 y 4. Sección 5.1.1 del Zill - Cullen. Sexta Edición. Página 207.

**Ejercicio 3.**
Una masa que pesa $\displaystyle 24\text{ libras}$, unida al extremo de un resorte, alarga a éste $\displaystyle 4\text{ pulgadas}$. Al inicio, la masa se libera desde el reposo en un punto $\displaystyle 3\text{ pulgadas}$ arriba de la posición de equilibrio. Encuentre la ecuación del movimiento.

**Ejercicio 4.**
Determine la ecuación del movimiento si la masa del problema 3 al inicio se libera desde la posición de equilibrio con una velocidad descendente de $\displaystyle 2\text{ pie/s}$.

**Respuesta:**
* **Ejercicio 3:** $\displaystyle x(t) = -0.25\cos(9.82t)\text{ ft}$
* **Ejercicio 4:** $\displaystyle x(t) = 0.2036\sin(9.82t)\text{ ft}$

---

### **EJERCICIO 35.** Ejercicio 8. Sección 5.1.1 del Zill - Cullen. Sexta Edición. Página 207.
Una masa que pesa $\displaystyle 32\text{ libras}$ alarga un resorte $\displaystyle 2\text{ pies}$. Determine la a) amplitud y b) el periodo del movimiento si la masa se libera inicialmente desde un punto situado $\displaystyle 1\text{ pie}$ arriba de la posición de equilibrio con una velocidad ascendente de $\displaystyle 2\text{ pies/s}$. c) ¿Cuántos ciclos habrá completado la masa al final de $\displaystyle 4\pi\text{ segundos}$?

**Respuesta:**
a) $\displaystyle A = 1.1175\text{ ft}$
b) $\displaystyle T = 1.57\text{ s}$
c) $\displaystyle n = 8\text{ ciclos}$

---

### **EJERCICIO 36.**
La punta de la aguja de una máquina de coser se mueve en MAS sobre el eje x con una frecuencia de $\displaystyle 2.5\text{ Hz}$. En $\displaystyle t = 0$, sus componentes de posición y velocidad son $\displaystyle +1.1\text{ cm}$ y $\displaystyle -15.00\text{ cm/s}$.
a) Calcule la componente de aceleración de la aguja en $\displaystyle t = 0$.
b) Escriba ecuaciones para las componentes de posición, velocidad y aceleración de la punta en función del tiempo.

**Respuesta:**
a) $\displaystyle a(0) = -2.71\text{ m/s}^2$
b) $\displaystyle x(t) = 0.0146\cos(15.71t + 0.7149)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{m}$)
$\displaystyle v(t) = -0.23\sin(15.71t + 0.7149)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle v$ en $\displaystyle \text{m/s}$)
$\displaystyle a(t) = -3.61\cos(15.71t + 0.7149)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle a$ en $\displaystyle \text{m/s}^2$)

---

### **EJERCICIO 37.** Ejemplo 1. Sección 5.1 del Zill - Cullen. Sexta Edición. Página 196.
Una masa que pesa $\displaystyle 2\text{ lb}$ alarga un resorte $\displaystyle 6\text{ pulgadas}$. En $\displaystyle t = 0$ se libera la masa desde un punto que está $\displaystyle 8\text{ pulgadas}$ debajo de la posición de equilibrio con una velocidad ascendente de $\displaystyle 4/3\text{ pie/s}$. Determine la ecuación de movimiento.

**Respuesta:** $\displaystyle x(t) = 0.6871\cos(8.02t + 0.2444)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{ft}$)

---

### **EJERCICIO 38.**
Una masa de $\displaystyle 0.50\text{ kg}$ cuelga de un resorte de $\displaystyle k = 50\text{ N/m}$. Si la desplazamos $\displaystyle 5.0\text{ cm}$ y la soltamos, calcular:
a) La frecuencia
b) La velocidad que tiene cuando pasa por la posición de equilibrio.

**Respuesta:**
a) $\displaystyle f = 1.59\text{ s}^{-1}$
b) $\displaystyle v_{\max} = 0.50\text{ m/s}$

---

### **EJERCICIO 39.** Problema 3-193 del Cengel - Palm. Página 172.
Una masa $\displaystyle m = 0.5\text{ kg}$ está suspendida de un resorte que se estiró $\displaystyle 0.2\text{ cm}$ bajo la influencia del peso de esta masa. Ahora se tira de la masa hacia abajo y se suelta. En el tiempo $\displaystyle t = 0$, se observa que la masa pasa por su posición de equilibrio estático con una velocidad de $\displaystyle 10\text{ m/s}$. Despreciando toda fricción, determine la a) frecuencia natural, b) el periodo y c) la amplitud del movimiento resultante.

**Respuesta:**
a) $\displaystyle \omega = 70.04\text{ rad/s}$
b) $\displaystyle T = 8.97 \times 10^{-2}\text{ s}$
c) $\displaystyle A = 0.1428\text{ m}$

---

### **EJERCICIO 40.**
Un muelle se alarga $\displaystyle 25\text{ cm}$ al colgar de él una masa de $\displaystyle 2.0\text{ kg}$. Calcular la frecuencia y la velocidad máxima de oscilación de la masa sabiendo que la amplitud del movimiento es de $\displaystyle 5.0\text{ cm}$. Dato: $\displaystyle g = 9.8\text{ m/s}^2$.

**Respuesta:** $\displaystyle f = 1\text{ Hz}$, $\displaystyle v_{\max} = 0.314\text{ m/s}$

---

### **EJERCICIO 41.**
Un cuerpo de masa $\displaystyle 20\text{ g}$, que se mueve sobre el eje OX, pasa por el origen de coordenadas con una velocidad de $\displaystyle 10\text{ m/s}$. Sobre él actúa una fuerza $\displaystyle F = -4x\text{ N}$, siendo $\displaystyle x$ la abscisa del cuerpo en $\displaystyle \text{m}$. Calcular hasta qué distancia del origen llegará.

**Respuesta:** $\displaystyle A = 0.707\text{ m}$

---

### **EJERCICIO 42.**
Una partícula de $\displaystyle 5.0\text{ g}$ se mueve con M.A.S. Si su frecuencia es de $\displaystyle 25\text{ Hz}$ y su amplitud $\displaystyle 8\text{ cm}$, calcular:
a) Su periodo.
b) La frecuencia angular.
c) Su velocidad máxima.
d) La constante recuperadora.

**Respuesta:**
a) $\displaystyle T = 1/25\text{ s}$
b) $\displaystyle \omega = 50\pi\text{ rad/s}$
c) $\displaystyle v_{\max} = 12.566\text{ m/s}$
d) $\displaystyle k = 123.37\text{ N/m}$

---

### **EJERCICIO 43.**
Un objeto está unido a un muelle horizontal sin rozamiento que oscila con una amplitud de $\displaystyle 5\text{ cm}$ y una frecuencia de $\displaystyle 3.3\text{ Hz}$. Determine:
a) El periodo del movimiento.
b) La velocidad máxima y la aceleración máxima.

**Respuesta:**
a) $\displaystyle T = 0.30\text{ s}$
b) $\displaystyle v_{\max} = \pm 1.03\text{ m/s}$; $\displaystyle a_{\max} = \pm 21.48\text{ m/s}^2$

---

### **EJERCICIO 44.**
Un móvil realiza un movimiento armónico simple en el extremo de un muelle que hace dos oscilaciones por segundo, siendo la amplitud del movimiento $\displaystyle 20\text{ cm}$. Calcular:
a) La velocidad máxima que llega a alcanzar la masa que oscila.
b) La aceleración de la masa al pasar por el extremo del movimiento vibratorio armónico.

**Respuesta:**
a) $\displaystyle v_{\max} = 2.51\text{ m/s}$
b) $\displaystyle a_{\max} = -31.58\text{ m/s}^2$

---

### **EJERCICIO 45.**
Al suspender un cuerpo de masa $\displaystyle 300\text{ g}$ del extremo de un muelle que está colgado verticalmente, éste se alarga $\displaystyle 20\text{ cm}$. Si se tira del cuerpo $\displaystyle 5\text{ cm}$ hacia abajo y se suelta, comienza a oscilar. Calcular el período del movimiento. ¿Cuál será la máxima velocidad que alcanzará?

**Respuesta:** $\displaystyle T = 0.898\text{ s}$, $\displaystyle v_{\max} = \pm 35.3\text{ cm/s}$

---

### **EJERCICIO 46.**
El pistón del cilindro de un coche tiene una carrera (distancia desde abajo hasta arriba del movimiento) de $\displaystyle 20\text{ cm}$ y el motor gira a $\displaystyle 800\text{ rpm}$. Calcular la velocidad máxima que alcanza.

**Respuesta:** $\displaystyle v_{\max} = \pm 8.38\text{ m/s}$

---

### **EJERCICIO 47.**
Una partícula recorre $\displaystyle 8\text{ cm}$ de extremo a extremo en un movimiento armónico simple y su aceleración máxima es de $\displaystyle 48\text{ m/s}^2$. Calcular:
a) La frecuencia y el periodo del movimiento.
b) La velocidad máxima de la partícula.

**Respuesta:**
a) $\displaystyle f = 5.51\text{ Hz}$; $\displaystyle T = 0.1815\text{ s}$
b) $\displaystyle v_{\max} = 1.39\text{ m/s}$

---

### **EJERCICIO 48.**
¿Cuál es la máxima fuerza que actúa sobre un cuerpo de masa $\displaystyle 50\text{ g}$ cuando vibra con una frecuencia de $\displaystyle 25\text{ Hz}$ y una amplitud de $\displaystyle 2\text{ mm}$?

**Respuesta:** $\displaystyle F_{\max} = 2.47\text{ N}$

---

### **EJERCICIO 49.** Primer Examen Parcial. Profesor Willians Medina. Universidad de Oriente. Núcleo de Anzoátegui. 08/05/2026.
En un M.A.S., cuando la elongación es nula, la velocidad es de $\displaystyle 1\text{ m/s}$ y, en el instante en que la elongación es de $\displaystyle 5\text{ cm}$, la velocidad es nula. ¿Cuál es el período del movimiento?

**Respuesta:** $\displaystyle T = 0.3142\text{ s}$

---

### **EJERCICIO 50.**
La escala de un dinamómetro está graduada en N. Desde la división $\displaystyle 0\text{ N}$ hasta la de $\displaystyle 20\text{ N}$ hay una distancia de $\displaystyle 10\text{ cm}$. Hacemos oscilar, con una amplitud de $\displaystyle 1\text{ cm}$, a un cuerpo de masa $\displaystyle 800\text{ g}$ suspendido del muelle del dinamómetro. Calcular la frecuencia de las oscilaciones y su aceleración máxima.

**Respuesta:** $\displaystyle f = 2.52\text{ Hz}$, $\displaystyle a_{\max} = 250\text{ cm/s}^2$

---

### **EJERCICIO 51.**
Una cuerda de guitarra vibra con una frecuencia de $\displaystyle 440\text{ Hz}$. Un punto en su centro se mueve en M.A.S con amplitud de $\displaystyle 3.0\text{ mm}$ y ángulo de fase cero.
a) Escriba una ecuación para la posición del centro de la cuerda en función del tiempo.
b) ¿Qué magnitud máxima tienen: la velocidad y la aceleración del centro de la cuerda?
c) La derivada de la aceleración respecto al tiempo es una cantidad llamada tirón. Escriba una ecuación para el tirón del centro de la cuerda en función del tiempo, y calcule el valor máximo de la magnitud del tirón.

**Respuesta:**
a) $\displaystyle x(t) = 0.003\cos(2764.60t)\text{ m}$
b) $\displaystyle v_{\max} = 8.29\text{ m/s}$, $\displaystyle a_{\max} = 22926.06\text{ m/s}^2$
c) $\displaystyle j(t) = 6.34 \times 10^7\sin(2764.60t)\text{ m/s}^3$; $\displaystyle j_{\max} = 6.34 \times 10^7\text{ m/s}^3$

---

### **EJERCICIO 52.** Primer Examen Parcial. Profesor Willians Medina. Universidad de Oriente. Núcleo de Anzoátegui. Período III - 2026.
Al descargar una carga de un barco mediante una grúa, oscila haciendo un vaivén cada $\displaystyle 4\text{ segundos}$ con una amplitud de $\displaystyle 2\text{ m}$. Si se mueve con un M.A.S. Calcule:
a) La aceleración máxima que alcanza.
b) Si para $\displaystyle t = 0$ está en el extremo positivo de la oscilación, su posición para $\displaystyle t = 9\text{ s}$.

**Respuesta:**
a) $\displaystyle a_{\max} = 4.93\text{ m/s}^2$
b) $\displaystyle x(9\text{ s}) = 0\text{ m}$

---

### **EJERCICIO 53.**
¿Qué amplitud y qué período debe tener un M.A.S. para que la velocidad máxima sea de $\displaystyle 30\text{ cm/s}$ y la aceleración máxima de $\displaystyle 12\text{ m/s}^2$? Expresar la elongación de ese movimiento en función del tiempo.

**Respuesta:** $\displaystyle A = 0.0075\text{ m}$, $\displaystyle T = 0.1571\text{ s}$; $\displaystyle x(t) = 0.0075\cos(40t)$ (con $\displaystyle t$ en $\displaystyle \text{s}$ y $\displaystyle x$ en $\displaystyle \text{m}$)

---

### **EJERCICIO 54.** Ejemplo 15.1 del Serway - Jewett. Séptima Edición. Página 424.
Un sistema bloque-resorte. Un bloque de $\displaystyle 200\text{ g}$ conectado a un resorte ligero tiene una constante de fuerza de $\displaystyle 5.00\text{ N/m}$ y es libre de oscilar sobre una superficie horizontal sin fricción. El bloque se desplaza $\displaystyle 5.00\text{ cm}$ desde el equilibrio y se libera del reposo.
a) Hallar el periodo de su movimiento.
b) Determine la rapidez máxima del bloque.
c) ¿Cuál es la aceleración máxima del bloque?
d) Exprese la posición, velocidad y aceleración como funciones del tiempo.
e) ¿Y si el bloque se libera desde la misma posición inicial, $\displaystyle x_0 = 5.00\text{ cm}$, pero con una velocidad inicial de $\displaystyle v_0 = -0.100\text{ m/s}$? ¿Qué partes de la solución cambian y cuáles son las nuevas respuestas para estas?

**Respuesta:**
a) $\displaystyle T = 1.26\text{ s}$
b) $\displaystyle v_{\max} = 0.25\text{ m/s}$
c) $\displaystyle a_{\max} = 1.25\text{ m/s}^2$
d) $\displaystyle x(t) = 0.05\cos(5t)\text{ m}$; $\displaystyle v(t) = -0.25\sin(5t)\text{ m/s}$; $\displaystyle a(t) = -1.25\cos(5t)\text{ m/s}^2$
e) El periodo no cambia, porque es independiente de cómo se pone en movimiento el oscilador y depende sólo de parámetros del sistema tal como la masa y la constante del resorte. $\displaystyle v_{\max} = 0.2695\text{ m/s}$, $\displaystyle a_{\max} = 1.3475\text{ m/s}^2$; $\displaystyle x(t) = 0.0539\cos(5t + 0.3805)\text{ m}$, $\displaystyle v(t) = -0.2695\sin(5t + 0.3805)\text{ m/s}$, $\displaystyle a(t) = -1.3475\cos(5t + 0.3805)\text{ m/s}^2$
