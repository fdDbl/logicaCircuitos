# **Lógica proposicional aplicada a la lógica digital**

## Dos perspectivas lógicas

El Curso Inicial Obligatorio de la Facultad de Informática de la UNLP está compuesto por tres materias teórico-prácticas:

* Matemática 0 (MAT0);
* Conceptos de Organización de Computadoras (COC);
* Expresión de Problemas y Algoritmos (EPA).

De estas tres materias, las primeras dos son las que incluyen a la lógica en sus contenidos.

MAT0 lo hace de forma temprana, introduciendo el mundo de la lógica sin la necesidad de conjuntos numéricos. De esta forma, el alumno ya se encuentra sobre una base con la que encarar los posteriores contenidos lógicos de COC.

1. ### Perspectiva matemática *o proposicional*

En la materia **Matemática 0** se introduce la lógica proposicional. Se explica, entonces, cómo expresiones proposicionales pueden tener valores de verdadero o falso.

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

Las proposiciones moleculares se unen entre sí mediante **conectivos lógicos**.

Estos son:

  * Conjunción (∧)   

| p | q | p ∧ q |
|:-:|:-:|:-----:|
| V | V |   V   |
| V | F |   F   |
| F | V |   F   |
| F | F |   F   |