# Sistemas Posicionales y Conversión entre Bases

Los sistemas posicionales son la base de toda representación numérica utilizada en computación. Permiten expresar números mediante símbolos y posiciones asociadas a potencias de una base. Comprender su funcionamiento es esencial para entender cómo se representan, almacenan y procesan los datos dentro de un sistema digital.

---

## Conceptos clave

- **Sistema posicional:** representación en la que el valor de un dígito depende de su posición y la base.
- **Base:** número de símbolos distintos utilizados en un sistema numérico (por ejemplo, base 2 → {0,1}).
- **Parte entera:** componente a la izquierda del punto (representa múltiplos de potencias positivas de la base).
- **Parte fraccionaria:** componente a la derecha del punto (representa potencias negativas de la base).
- **Conversión de bases:** proceso de transformar un número de una base a otra manteniendo su valor.
- **Notación científica:** forma de expresar números grandes o pequeños mediante una mantisa y una potencia.

---

## Representación Numérica en Sistemas Posicionales

### Dígitos

Un sistema numérico posicional se construye a partir de dos componentes fundamentales: los dígitos (símbolos permitidos) y la base (o _radix_, que determina cuántos símbolos existen y cómo se interpretan las posiciones).

Los dígitos son los símbolos elementales usados para representar valores dentro de una base determinada.
En una base $b$, los dígitos válidos son los números enteros desde 0 hasta $b-1$.

Por ejemplo:

|         Base $b$ | Conjunto de dígitos válidos                      |
| ---------------: | :----------------------------------------------- |
|      2 (binario) | {0, 1}                                           |
|        8 (octal) | {0, 1, 2, 3, 4, 5, 6, 7}                         |
|     10 (decimal) | {0, 1, 2, 3, 4, 5, 6, 7, 8, 9}                   |
| 16 (hexadecimal) | {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F} |

En bases mayores que 10, las letras del alfabeto latino se usan como extensión simbólica:

$$
A = 10, B = 11, C = 12, D = 13, E = 14, F = 15
$$

### Bases

La **base** $b$ de un sistema numérico indica cuántos dígitos distintos existen y qué peso tiene cada posición. Cada posición representa una potencia distinta de la base.
El valor total del número se calcula sumando cada dígito multiplicado por la potencia correspondiente:

$$
N = \sum_{i=0}^{n-1} d_i \cdot b^i
$$

donde:

- $d_i$ es el dígito en la posición $i$,
- $b$ es la base,
- $i = 0$ corresponde a la posición menos significativa (la derecha).

**Ejemplo en base 10:**

$$
(4725)_{10} = 4\times10^3 + 7\times10^2 + 2\times10^1 + 5\times10^0 = 4000 + 700 + 20 + 5
$$

**Ejemplo en base 2:**

$$
(1011)_2 = 1\times2^3 + 0\times2^2 + 1\times2^1 + 1\times2^0 = 8 + 0 + 2 + 1 = 11
$$

### Potencias Posicionales

Cada posición en un número tiene un peso posicional que depende de su distancia al punto (decimal o binario).
A la izquierda del punto, las potencias de la base son positivas; a la derecha, negativas:

$$
(d_{n-1} \dots d_1 d_0 . d_{-1} d_{-2} \dots d_{-m})_b = \sum_{i=-(m)}^{n-1} d_i \cdot b^i
$$

**Ejemplo:**

$$
(110.101)_2 = 1\cdot2^2 + 1\cdot2^1 + 0\cdot2^0 + 1\cdot2^{-1} + 0\cdot2^{-2} + 1\cdot2^{-3} = 6.625
$$

### Significado práctico

En hardware digital, cada _bit_ representa un dígito en base 2. Agrupaciones de bits permiten representar bases mayores:

- 3 bits → base 8 (octal)
- 4 bits → base 16 (hexadecimal)
  
Esta estructura jerárquica facilita la conversión rápida entre sistemas y la interpretación binaria de los datos en memoria.

### Comportamiento de las Bases

Puedes pensar en la base como la “regla de conteo” del sistema:

- En base 10, después del 9, se reinicia con 0 y se agrega un 1 a la izquierda → 10.
- En base 2, después del 1, se reinicia con 0 y se agrega un 1 → $10_{2}$ ($=2_{10}$).
- En base 16, después de la F, se reinicia con 0 y se agrega un 1 → $10_{16}$ ($=16_{10}$).

## Sistemas Numéricos Comunes

### Binario (Base 2)

Usa los símbolos {0, 1}. Es el sistema nativo de las computadoras porque representa fácilmente los dos estados eléctricos: encendido y apagado.

**Ejemplo:**  
$$
(1101)_2 = 1\cdot2^3 + 1\cdot2^2 + 0\cdot2^1 + 1\cdot2^0 = 13_{10}
$$

### Octal (Base 8)

Usa los símbolos {0–7}. Cada dígito octal representa 3 bits binarios.

**Ejemplo:**  
$$
(57)_8 = 5\cdot8^1 + 7\cdot8^0 = 47_{10}
$$

### Decimal (Base 10)

Sistema habitual en el uso cotidiano. Las computadoras lo emulan mediante aritmética binaria.

### Hexadecimal (Base 16)

Usa los símbolos {0–9, A–F}. Cada dígito hexadecimal representa 4 bits binarios (_nibble_).

**Ejemplo:**  
$$
(2F)_{16} = 2\cdot16^1 + 15\cdot16^0 = 47_{10}
$$

## Conversión entre Bases

### De Binario a Decimal

Se multiplica cada bit por su potencia de 2 correspondiente y se suman los resultados.

$$
(10101)_2 = 1\cdot2^4 + 0\cdot2^3 + 1\cdot2^2 + 0\cdot2^1 + 1\cdot2^0 = 21_{10}
$$

### De Decimal a Binario

Se divide sucesivamente entre 2, registrando los restos hasta obtener un cociente 0.  
El número binario se forma leyendo los restos de abajo hacia arriba.

$$
\begin{array}{rcl}
21 / 2 &=& 10 \quad \text{resto } 1 \\
10 / 2 &=& 5 \quad \text{resto } 0 \\
5 / 2 &=& 2 \quad \text{resto } 1 \\
2 / 2 &=& 1 \quad \text{resto } 0 \\
1 / 2 &=& 0 \quad \text{resto } 1 \\
\hline
 & & \Rightarrow (10101)_2
\end{array}
$$

### De Binario a Hexadecimal

Agrupar en grupos de 4 bits desde la derecha y convertir cada grupo a su equivalente hexadecimal.

$$
1101111010111101_2
\rightarrow
1101\;1110\;1011\;1101
\rightarrow
(\text{DEBD})_{16}
$$
