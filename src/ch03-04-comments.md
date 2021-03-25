## Comentarios

Todos los programadores se esfuerzan por hacer que su código sea fácil de entender,
pero a veces añadir una explicación extra es esencial. En estos casos, los programadores
dejan notas o *comentarios* en el código fuente que el compilador ignorará, pero los lectores
encontrarán muy útil.

Aquí hay un comentario simple:

```rust
// hola, mundo
```

En Rust, los comentarios comienzan con dos barras diagonales y continúan hasta
el final de la línea. Para realizar comentarios que se extienden por más de una
sola línea, necesitas incluir `//` en cada línea, algo así:

```rust
// Entonces aquí estamos haciendo algo complicado, lo suficiente como para
// que necesitemos varias líneas de comentarios para hacerlo. ¡Uf!
// Esperemos que este comentario explique lo que está pasando.
```

Los comentarios también pueden colocarse al final de una línea que contiene código:

<span class="filename">Archivo: src/main.rs</span>

```rust
{{#rustdoc_include ../listings/ch03-common-programming-concepts/no-listing-24-comments-end-of-line/src/main.rs}}
```

Pero los verá más a menudo usados en este formato, con un comentario
en una línea separada del código:

<span class="filename">Archivo: src/main.rs</span>

```rust
{{#rustdoc_include ../listings/ch03-common-programming-concepts/no-listing-25-comments-above-line/src/main.rs}}
```

Rust contiene otro tipo de comentarios, los de documentación, estos serán explicados
a detalle en la Sección "Publicar una Caja en Crates.io" del Capítulo 14.
