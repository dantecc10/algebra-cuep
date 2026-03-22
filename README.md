# 📚 Curso de Inducción: Álgebra para Ingreso a la Universidad

Este repositorio contiene el temario y los materiales didácticos diseñados para nivelar los conocimientos de los aspirantes. El enfoque combina la **lógica conceptual** con la **resolución práctica de problemas**.

---

## 🛠️ Estructura del curso

### Bloque 1: Fundamentos y Lógica del Álgebra
*El objetivo es entender las "reglas del juego" antes de empezar a operar.*

* **1.1 Anatomía de la Matemática:**
    * Diferencia entre **Constante** y **Variable** (el "contenedor" de valor).
    * Partes de un término: Signo, coeficiente, literal y exponente.
* **1.2 Los Axiomas del Número Real:**
    * Propiedad Distributiva (el puente hacia la simplificación).
    * El elemento neutro y el inverso (la lógica detrás de "cancelar" términos).
* **1.3 Jerarquía y Lenguaje:**
    * Orden de operaciones (**PEMDAS/GMDAS**).
    * Traducción de enunciados a expresiones algebraicas (Lenguaje Algebraico).

[Image of an algebraic term labeled with coefficient, variable, and exponent]

---

### Bloque 2: Manipulación de Expresiones (Aritmética Algebraica)
*Aprender a simplificar, organizar y reducir el caos numérico.*

* **2.1 Polinomios:**
    * Suma y resta de términos semejantes ("Manzanas con manzanas").
    * Leyes de los exponentes y radicales.
* **2.2 Productos Notables:**
    * Binomio al cuadrado: $(a \pm b)^2 = a^2 \pm 2ab + b^2$
    * Binomios conjugados: $(a + b)(a - b) = a^2 - b^2$
* **2.3 Factorización (El proceso inverso):**
    * Factor común.
    * Diferencia de cuadrados.
    * Trinomios de la forma $x^2 + bx + c$ y $ax^2 + bx + c$.

[Image of algebraic factorization identities like difference of squares and perfect square trinomials]

---

### Bloque 3: Ecuaciones y Desigualdades
*El arte de encontrar el valor desconocido manteniendo el equilibrio.*

* **3.1 Ecuaciones Lineales (Primer Grado):**
    * La metáfora de la balanza: Mantener la igualdad en ambos lados.
    * Resolución de ecuaciones de una incógnita y despejes fundamentales.
* **3.2 Sistemas de Ecuaciones 2x2:**
    * Métodos de resolución: Sustitución, Igualación y Reducción (Suma y Resta).
    * Interpretación gráfica: El punto de intersección.
* **3.3 Ecuaciones Cuadráticas (Segundo Grado):**
    * Resolución por factorización vs. **Fórmula General**.
    * Uso del discriminante ($b^2 - 4ac$) para determinar el tipo de soluciones.



---

### Bloque 4: Introducción a las Relaciones Visuales
*Conectando el álgebra con su representación en el plano.*

* **4.1 Concepto de Función:**
    * Relación de dependencia: Dominio y Rango (introducción).
* **4.2 La Línea Recta:**
    * Análisis de la pendiente ($m$) y la ordenada al origen ($b$).
    * Ecuación punto-pendiente.
* **4.3 Introducción a la Parábola:**
    * Identificación visual de funciones de segundo grado y su concavidad.

### Sistema de Ecuaciones 3x3 (Cramer / Determinantes)

Un sistema de ecuaciones 3x3 es una relación lineal constituida por 3 ecuaciones con 3 variables.

Las ecuaciones tienen la siguiente forma:

$Ax + By + Cz = D$, donde $A$, $B$, $C$ y $D$ son valores escalares que acompañan a las variables como coeficientes (salvo D, que es una constante).

Para resolver un sistema de ecuaciones 3x3 por el método de determinantes debemos ver el sistema como una matriz, para poder pensar en sus determinantes:

Si llamamos $a$ al coeficiente de $x$ en cada ecuación, tendremos que:

- Para la ecuación 1 ($E_1$) el coeficiente de $x$ es $a_1$.

- Para la ecuación 2 ($E_2$) el coeficiente de $x$ es $a_2$.

- Para la ecuación 3 ($E_3$) el coeficiente de $x$ es $a_3$.

Lo mismo para $y$ y $z$:

- Para la ecuación 1 ($E_1$) el coeficiente de $y$ es $b_1$.

- Para la ecuación 2 ($E_2$) el coeficiente de $y$ es $b_2$.

- Para la ecuación 3 ($E_3$) el coeficiente de $y$ es $b_3$.

- Para la ecuación 1 ($E_1$) el coeficiente de $z$ es $c_1$.

- Para la ecuación 2 ($E_2$) el coeficiente de $z$ es $c_2$.

- Para la ecuación 3 ($E_3$) el coeficiente de $z$ es $c_3$.

Mientras que los resultados de las sumas [o restas] de los coeficientes, es $d_i$ (d independiente). Aquí tomaremos directamente el valor:

- Para la ecuación 1 ($E_1$) el valor de $d_i$ es $d_{i_1}$.

- Para la ecuación 2 ($E_2$) el valor de $d_i$ es $d_{i_1}$.

- Para la ecuación 3 ($E_3$) el valor de $d_i$ es $d_{i_3}$.

Entonces, podemos ver el sistema como:

$$ D =
\left[
\begin{array}{ccc|c}
  a_1 & b_1 & c_1 & | & d_{i_1} \\
  a_2 & b_2 & c_2 & | & d_{i_2} \\
  a_3 & b_3 & c_3 & | & d_{i_3}
\end{array}
\right]$$

Para obtener el valor de $x$, $y$ y $z$, debemos obtener los determinantes correspondientes a una matriz 3 x 3, pero sustituyendo la columna del coeficiente de la variable, por la de $d_i$.

Así, la matriz a la que le sacaremos el determinante para el caso de $x$ sería:

$$ D_x =
\left[
\begin{array}{ccc|c}
  d_{i_1} & b_1 & c_1 \\
  d_{i_2} & b_2 & c_2 \\
  d_{i_3} & b_3 & c_3
\end{array}
\right]$$

Para el caso de $y$ sería:

$$ D_y =
\left[
\begin{array}{ccc|c}
  a_1 & d_{i_1} & c_1 \\
  a_2 & d_{i_2} & c_2 \\
  a_3 & d_{i_3} & c_3
\end{array}
\right]$$


Y para el caso de $z$ queda como:

$$ D_z =
\left[
\begin{array}{ccc|c}
  a_1 & b_1 & d_{i_1} \\
  a_2 & b_2 & d_{i_2} \\
  a_3 & b_3 & d_{i_3}
\end{array}
\right]$$

Ahora, podemos resolver los determinantes considerando que, para la forma general de una matriz de 3 columnas por 3 columnas ($M_{33}$):

$$
M_{33} = 
\left[
\begin{array}{ccc|c}
  a_1 & b_1 & c_1 \\
  a_2 & b_2 & c_2 \\
  a_3 & b_3 & c_3
\end{array}
\right]$$

$det(M_33) = [(a_1 \cdot b_2 \cdot c_3) + (b_1 \cdot c_2 \cdot a_3) + (c_1 \cdot a_2 \cdot b_3)] - [(c_1 \cdot b_2 \cdot a_3) + (a_1 \cdot c_2 \cdot b_3) + (b_1 \cdot a_2 \cdot c_3)]$

Por lo tanto, usando esa forma, resolvemos el determinante de $x$:

Sea $D_x$:

$$ D_x =
\left[
\begin{array}{ccc|c}
  d_{i_1} & b_1 & c_1 \\
  d_{i_2} & b_2 & c_2 \\
  d_{i_3} & b_3 & c_3
\end{array}
\right]$$

$det(D_x) = [(d_{i_1} \cdot b_2 \cdot c_3) + (b_1 \cdot c_2 \cdot d_{i_3}) + (c_1 \cdot d_{i_2} \cdot b_3)] - [(c_1 \cdot b_2 \cdot d_{i_3}) + (d_{i_1} \cdot c_2 \cdot b_3) + (b_1 \cdot d_{i_2} \cdot c_3)]$

