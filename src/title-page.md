# El Lenguaje de Programación Rust

*por Steve Klabnik y Carol Nichols, con la ayuda de la Comunidad de Rust*

Esta versión del texto asume que estás utilizando Rust 1.50 o superior con
la Edición 2018 (`edition="2018"`) dentro del *Cargo.toml* de tus proyectos.
Consulte la [Sección "Instalación" del Capítulo 1][install] para instalar o
actualizar Rust, y mira el [Apéndice de Ediciones][editions] para más información.

La Edición 2018 del lenguaje Rust incluye un número de importantes cambios que
hacen a Rust más cómodo para el desarrollador y más fácil de aprender. Esta Edición
del libro contiene una serie de capítulos para describir estas mejoras:

- El Capítulo 7, "Controla el crecimiento de los proyectos con los Paquetes, Cajones (Crates) y Módulos",
  ha sido reescrito en su mayoría. El sistema de módulos y la forma en que trabajan las rutas
  en la Edición 2018 se hicieron más consistentes.
- El Capítulo 10 tiene nuevas secciones tituladas "Rasgos como Parámetros" y "Retornando Tipos
  que Implementan un Rasgo" que explican la nueva sintaxis de `impl Trait`.
- El Capítulo 11 tiene una nueva sección titulada "Uso de `Result<T, E>` en las Pruebas" que muestra
  cómo escribir pruebas que usan el operador `?`.
- La Sección "Vidas Útiles Avanzadas" en el Capítulo 19 fue retirada porque las mejoras
  del compilador han hecho que las construcciones en esa sección sean aún más raras.
- El Apéndice D anterior, "Macros", se ha ampliado para incluir las macros de procedimiento
  y fue movida a la sección "Macros" en el Capítulo 19.
- El Apéndice A, "Palabras Claves", también explica la nueva función de identificadores sin
  procesar que permite que el código escrito en la Edición 2015 y la Edición 2018 interoperen.
- El Apéndice D ahora se titula "Herramientas de Desarrollo" y cubre las herramientas lanzadas
  recientemente para ayudarte a escribir código Rust.
- Hemos corregido una serie de pequeños errores y una redacción imprecisa a lo largo del libro.
  ¡Gracias a los lectores que los informaron!

Tenga en cuenta que cualquier código de Ediciones anteriores de *El Lenguaje de Programación Rust*
que se compiló continuará compilándose sin `edition="2018"` en el *Cargo.toml* del proyecto, incluso
cuando actualice la versión del compilador de Rust que está utilizando. ¡Esas son las garantías de
compatibilidad con versiones anteriores de Rust en funcionamiento!

La versión en inglés en formato HTML está disponible en línea en
[https://doc.rust-lang.org/stable/book/](https://doc.rust-lang.org/stable/book/)
y una versión fuera de línea para instalaciones de Rust hechas con `rustup`
ejecutando `rustup docs --book` para abrirlo en el navegador.

Este texto está disponible en inglés en [paperback and ebook format from No Starch
Press][nsprust].

[install]: ch01-01-installation.html
[editions]: appendix-05-editions.html
[nsprust]: https://nostarch.com/rust
