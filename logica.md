# **Lógica proposicional aplicada a la lógica de circuitos**

## Dos perspectivas lógicas

El Curso Inicial Obligatorio de la Facultad de Informática de la UNLP está compuesto por tres materias teórico-prácticas:

* Matemática 0 (MAT0);
* Conceptos de Organización de Computadoras (COC);
* Expresión de Problemas y Algoritmos (EPA).

De estas tres materias, las primeras dos son las que incluyen a la lógica en sus contenidos.

MAT0 lo hace de forma temprana, introduciendo el mundo de la lógica sin la necesidad de conjuntos numéricos. De esta forma, el alumno ya se encuentra sobre una base con la que encarar los posteriores contenidos lógicos de COC.

### 1. Perspectiva matemática *o proposicional*

En la materia **MAT0** se introduce la lógica proposicional. Se explica, entonces, cómo expresiones proposicionales pueden tener valores de verdadero o falso.

Cada proposición se identifica comúnmente con las letras: *p, q, r, s, t*.

Para indicar su valor de verdad, se escribe la letra encerrada en una V(), por ejemplo, V(q).

* #### Proposiciones atómicas

Llámese también "simples" a las proposiciones que, siendo únicas en su expresión, no se pueden descomponer.

> p: 3 + 6 = 9

* #### Proposiciones moleculares

Llámese también "compuestas" a las proposiciones que, no siendo únicas en su expresión, constan de dos o más proposiciones simples.

> p: Bach era organista.

> q: Bach era compositor.

> p y q: Bach era organista y compositor.

* #### Conectivos lógicos

    Las proposiciones simples se unen entre sí mediante **conectivos lógicos**.

  * **Negación (¬)**

    | p |¬p |
    |:-:|:-:|
    | V | F |
    | F | V |

  * **Conjunción (∧)**

    | p | q | p ∧ q |
    |:-:|:-:|:-----:|
    | V | V |   V   |
    | V | F |   F   |
    | F | V |   F   |
    | F | F |   F   |

  * **Disyunción (∨)**

    | p | q | p ∨ q |
    |:-:|:-:|:-----:|
    | V | V |   V   |
    | V | F |   V   |
    | F | V |   V   |
    | F | F |   F   |

  * **Disyunción exclusiva (⊻)**

    | p | q | p ⊻ q |
    |:-:|:-:|:-----:|
    | V | V |   F   |
    | V | F |   V   |
    | F | V |   V   |
    | F | F |   F   |

> Existen más conectivos, pero solo estos nos interesan a la hora de relacionarlos con los de COC.

### 2. Perspectiva computacional *o booleana*

En la materia de **COC**, al aplicarse los conectivos lógicos anteriores a los entornos computacionales, los valores de verdad (V y F) son booleanos y se indican con 0 y 1.

De esta manera, V y F no solo se convierten a esos dos números, sino que también se pueden convertir a fórmulas que hacen más simple su interpretación.

Además, se acostumbra a usar el alfabeto A, B, C,... para denominar las variables (proposiciones en MAT0), y usualmente la letra F para la salida (Por ejemplo, p ∧ q en MAT0 pasa a ser F en COC).

* Estos conectivos son:

  * **Complementación lógica (-)** (NOT)

    | A | Ā |
    |:-:|:-:|
    | 1 | 0 |
    | 0 | 1 |

  * **Producto lógico (*)** (AND)

    | A | B | A * B |
    |:-:|:-:|:-----:|
    | 1 | 1 |   1   |
    | 1 | 0 |   0   |
    | 0 | 1 |   0   |
    | 0 | 0 |   0   |

  * **Suma lógica (+)** (OR)

    | A | B | A + B |
    |:-:|:-:|:-----:|
    | 1 | 1 |   1   |
    | 1 | 0 |   1   |
    | 0 | 1 |   1   |
    | 0 | 0 |   0   |

* #### Puertas lógicas:

  Todo lo anterior cobra sentido si le complementamos el tema de **puertas lógicas**. A través de las puertas lógicas, en función de una combinación o
  combinaciones booleanas, se obtendrá una salida.

1. **Puerta NOT** *(figura c)*

2. **Puerta AND** *(figura c)*

3. **Puerta OR** *(figura c)*

4. **Puerta XOR** *(figura c)*

   1. ![NOT](https://upload.wikimedia.org/wikipedia/commons/5/50/Funcion_logica_SI.PNG)
   2. ![AND](https://upload.wikimedia.org/wikipedia/commons/3/3a/Funcion_logica_Y.PNG)
   3. ![OR](https://upload.wikimedia.org/wikipedia/commons/0/05/Funcion_logica_O.PNG)
   4. ![XOR](https://upload.wikimedia.org/wikipedia/commons/0/01/Funcion_logica_O-EX.PNG)
