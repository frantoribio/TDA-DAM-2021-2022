# Programación - Tipo de Datos Abstractos, Colecciones y Genéricos

Tema 06 Tipo de Datos Abstracto. 1DAM. Curso 2021/2022.

![imagen](https://thesoftclix.com/wp-content/uploads/2019/09/unnamed-1.png)

- [Programación - Tipo de Datos Abstractos, Colecciones y Genéricos](#programación---tipo-de-datos-abstractos-colecciones-y-genéricos)
  - [Tipo de Datos Abstracto](#tipo-de-datos-abstracto)
  - [Genéricos](#genéricos)
  - [Colecciones](#colecciones)
    - [Listas](#listas)
      - [ArrayList](#arraylist)
      - [LinkedList](#linkedlist)
      - [Cola](#cola)
      - [Pila](#pila)
  - [Colecciones en JAVA](#colecciones-en-java)
  - [Recursos](#recursos)
  - [Autor](#autor)
    - [Contacto](#contacto)
      - [Agradecimientos:](#agradecimientos)

## Tipo de Datos Abstracto
Un tipo de dato abstracto (TDA) es un conjunto de datos u objetos creado de manera personalizada por un programador para un fin específico. Un TDA es una abstracción que permite modelar las características de un elemento en particular. Es por ello que es crucial definir cómo se comportará un TDA y poder reutilizarlo lo máximo posible independientemente del tipo de información que contiene.

## Genéricos
En su esencia, el término genéricos significa tipos parametrizados. Los tipos parametrizados son importantes porque le permiten crear clases, interfaces y métodos en los que el tipo de datos sobre los que operan se especifica como parámetro. Una clase, interfaz o método que funciona con un tipo de parámetro se denomina genérico, como una clase genérica o método genérico.

Una ventaja principal del código genérico es que trabajará automáticamente con el tipo de datos pasados a su parámetro de tipo. Muchos algoritmos son lógicamente los mismos, independientemente del tipo de datos a los que se apliquen. Por ejemplo, un Quicksort (algoritmo de ordenación) es el mismo si está ordenando elementos de tipo Integer, String, Object, o Hilo. Con los genéricos, puede definir un algoritmo una vez, independientemente de cualquier tipo específico de datos, y luego aplicar ese algoritmo a una amplia variedad de tipos de datos sin ningún esfuerzo adicional.

Es importante entender que Java siempre le ha dado la habilidad de crear clases, interfaces y métodos generalizados operando a través de referencias del tipo Object. El problema era que no podían hacerlo con la seguridad del tipo porque se necesitaban conversiones para convertir explícitamente de Object al tipo real de datos sobre los que se operaba. Por lo tanto, fue posible crear accidentalmente desajustes de tipo. Los genéricos agregan el tipo de seguridad que faltaba porque hacen que estas conversiones sean automáticas e implícitas. En resumen, los genéricos amplían su capacidad de reutilizar el código y le permiten hacerlo de forma segura y confiable.


## Colecciones
Las colecciones son una forma de organizar datos en una estructura de datos. Estas estructuras de datos permiten almacenar datos de diferentes tipos y tamaños y tiene un comportamiento específico según la naturaleza que se le asignan.
### Listas
Las listas almacenan información en un orden determinado. Pueden ser enlazadas o no. Y se puede acceder a ellas mediante un índice, si este está disponible.
#### ArrayList
Es una lista cuyo acceso y modificación se hace a través de un índice. Es una lista de acceso aleatorio.
#### LinkedList
Es una lista cuyo acceso y modificación se hace a través de una referencia. Es una lista de acceso secuencial.
#### Cola
Es una lista que implementa el comportamiento FIFO (First In First Out). Es decir, el primer elemento que se añade es el primero en salir. Y por lo tanto, lo que nos interesa es hacer referencia a dichos elementos y comportamiento específico.
#### Pila
Es una lista que implementa el comportamiento LIFO (Last In First Out). Es decir, el último elemento que se añade es el primero en salir. Nos interesa conocer la cima, y por lo tanto aprovechar este comportamiento específico.

## Colecciones en JAVA
![colecciones](./images/collection.jpg)

## Recursos
- Twitter: https://twitter.com/joseluisgonsan
- GitHub: https://github.com/joseluisgs
- Web: https://joseluisgs.github.io
- Discord: https://discord.gg/uv7GcytM
- Aula Virtual: https://aulavirtual33.educa.madrid.org/ies.luisvives.leganes/course/view.php?id=245



## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/joseluisgonsan)

[![Twitter](https://img.shields.io/twitter/follow/joseluisgonsan?style=social)](https://twitter.com/joseluisgonsan)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto
<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
    <a href="https://twitter.com/joseluisgonsan" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://joseluisgs.github.io/" target="_blank">
        <img src="https://joseluisgs.github.io/favicon.png" 
    height="30">
    </a>
</p>

#### Agradecimientos:
Mi más sincero agradecimiento a Fernando G. Aranzabe (CIFP Virgen de Gracia), porque estos contenidos no serían posible sin él, pues son la mayoría suyos y con el cual compartía y me unía (y me sigue uniendo) la misma visión en cómo enseñar la programación y qué elementos/contenidos usar en este proceso. Muchas gracias.