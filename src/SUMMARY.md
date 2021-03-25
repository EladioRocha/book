# El Lenguaje de Programación Rust

[El Lenguaje de Programación Rust](title-page.md)
[Prólogo](foreword.md)
[Introducción](ch00-00-introduction.md)

## Primeros Pasos

- [Primeros Pasos](ch01-00-getting-started.md)
    - [Instalación](ch01-01-installation.md)
    - [¡Hola, Mundo!](ch01-02-hello-world.md)
    - [¡Hola, Cargo!](ch01-03-hello-cargo.md)

- [Programando un Juego de Adivinanzas](ch02-00-guessing-game-tutorial.md)

- [Conceptos de Programación Comunes](ch03-00-common-programming-concepts.md)
    - [Variables y Mutabilidad](ch03-01-variables-and-mutability.md)
    - [Tipos de Datos](ch03-02-data-types.md)
    - [Funciones](ch03-03-how-functions-work.md)
    - [Comentarios](ch03-04-comments.md)
    - [Flujo de Control](ch03-05-control-flow.md)

- [Comprendiendo la Propiedad (Ownership)](ch04-00-understanding-ownership.md)
    - [¿Qué es la Propiedad?](ch04-01-what-is-ownership.md)
    - [Referencias y Préstamos](ch04-02-references-and-borrowing.md)
    - [El Tipo Slice](ch04-03-slices.md)

- [Uso de Estructuras para Organizar Datos Relacionados](ch05-00-structs.md)
    - [Definición y Creación de Instancias de Estructuras](ch05-01-defining-structs.md)
    - [Un Programa de Ejemplo Que Usa Estructuras](ch05-02-example-structs.md)
    - [Sintaxis del Método](ch05-03-method-syntax.md)

- [Enumeraciones y Coincidencias de Patrones](ch06-00-enums.md)
    - [Definición de una Enumeración](ch06-01-defining-an-enum.md)
    - [El Operador de Flujo de Control `match`](ch06-02-match.md)
    - [Flujo de Control Conciso usando `if let`](ch06-03-if-let.md)

## Conocimientos Básicos sobre Rust

- [Controla el crecimiento de los proyectos con los Paquetes, Cajones (Crates) y Módulos](ch07-00-managing-growing-projects-with-packages-crates-and-modules.md)
    - [Paquetes y Cajones (Crates)](ch07-01-packages-and-crates.md)
    - [Definición de Módulos para Controlar el Alcance y la Privacidad](ch07-02-defining-modules-to-control-scope-and-privacy.md)
    - [Rutas para Hacer Referencia a un Elemento en el Árbol del Módulo](ch07-03-paths-for-referring-to-an-item-in-the-module-tree.md)
    - [Llevando Rutas al Alcance con la Palabra Clave `use`](ch07-04-bringing-paths-into-scope-with-the-use-keyword.md)
    - [Separación de Módulos en Diferentes Archivos](ch07-05-separating-modules-into-different-files.md)

- [Colecciones Comunes](ch08-00-common-collections.md)
    - [Almacenamiento de Listas de Valores usando Vectores](ch08-01-vectors.md)
    - [Almacenamiento de Textos UTF-8 usando Cadenas de Texto](ch08-02-strings.md)
    - [Almacenamiento de Claves Asociadas a Valores usando Mapas de Hashes](ch08-03-hash-maps.md)

- [Manejo de Errores](ch09-00-error-handling.md)
    - [Errores Irrecuperables con `panic!`](ch09-01-unrecoverable-errors-with-panic.md)
    - [Errores Recuperables con `Result`](ch09-02-recoverable-errors-with-result.md)
    - [Para "Entrar en Pánico" o Para No "Entrar en Pánico"](ch09-03-to-panic-or-not-to-panic.md)

- [Tipos Genéricos, Rasgos y Vidas Útiles](ch10-00-generics.md)
    - [Tipos de Datos Genéricos](ch10-01-syntax.md)
    - [Rasgos: Definición de Comportamiento Definido](ch10-02-traits.md)
    - [Validación de Referencias con Vidas Útiles](ch10-03-lifetime-syntax.md)

- [Escribiendo Pruebas Automatizadas](ch11-00-testing.md)
    - [Cómo Escribir Pruebas](ch11-01-writing-tests.md)
    - [Controlar Cómo Se Ejecutan las Pruebas](ch11-02-running-tests.md)
    - [Organización de las Pruebas](ch11-03-test-organization.md)

- [Un Proyecto de E/S: Creación de un Programa de Línea de Comandos](ch12-00-an-io-project.md)
    - [Aceptar Argumentos en la Línea de Comandos](ch12-01-accepting-command-line-arguments.md)
    - [Leer un Archivo](ch12-02-reading-a-file.md)
    - [Refactorización para Mejorar la Modularidad y el Manejo de Errores](ch12-03-improving-error-handling-and-modularity.md)
    - [Desarrollo de la Funcionalidad de la Librería con Desarrollo Basado en Pruebas](ch12-04-testing-the-librarys-functionality.md)
    - [Trabajando con las Variables de Entorno](ch12-05-working-with-environment-variables.md)
    - [Escribir Mensajes de Error en Error Estándar en lugar de Salida Estándar](ch12-06-writing-to-stderr-instead-of-stdout.md)

## Pensando en Rust

- [Características del Lenguaje Funcional: Iteradores y Clausuras](ch13-00-functional-features.md)
    - [Clausuras: Funciones Anónimas que Pueden Capturar Su Entorno](ch13-01-closures.md)
    - [Procesando una Serie de Elementos usando Iteradores](ch13-02-iterators.md)
    - [Mejorando Nuestro Proyecto de E/S](ch13-03-improving-our-io-project.md)
    - [Comparación del Rendimiento: Bucles frente a Iteradores](ch13-04-performance.md)

- [Más acerca de Cargo y Crates.io](ch14-00-more-about-cargo.md)
    - [Personalización de Compilaciones con Perfiles de Versión](ch14-01-release-profiles.md)
    - [Publicar una Caja en Crates.io](ch14-02-publishing-to-crates-io.md)
    - [Espacios de Trabajo de Cargo](ch14-03-cargo-workspaces.md)
    - [Instalación de Binarios desde Crates.io usando `cargo install`](ch14-04-installing-binaries.md)
    - [Ampliación de Cargo con Comandos Personalizados](ch14-05-extending-cargo.md)

- [Punteros Inteligentes](ch15-00-smart-pointers.md)
    - [Uso de `Box<T>` para Apuntar a Datos en el Montón](ch15-01-box.md)
    - [Tratar los Punteros Inteligentes Como Referencias Regulares con el Rasgo `Defer`](ch15-02-deref.md)
    - [Ejecutar Código en la Limpieza con el Rasgo `Drop`](ch15-03-drop.md)
    - [`Rc<T>`, el Puntero Inteligente Contado de Referencia](ch15-04-rc.md)
    - [`RefCell<T>` y el Patrón de Mutabilidad Interior](ch15-05-interior-mutability.md)
    - [Los Ciclos de Referencia Pueden Perder Memoria](ch15-06-reference-cycles.md)

- [Concurrencia](ch16-00-concurrency.md)
    - [Uso de Subprocesos para Ejecutar Código Simultáneamente](ch16-01-threads.md)
    - [Uso de la Transferencia de Mensajes para Transferir Datos entre Subprocesos](ch16-02-message-passing.md)
    - [Concurrencia de Estado Compartido](ch16-03-shared-state.md)
    - [Concurrencia Extensible con los Rasgos `Sync` y `Send`](ch16-04-extensible-concurrency-sync-and-send.md)

- [Características de la Programación Orientada a Objetos de Rust](ch17-00-oop.md)
    - [Características de los Lenguajes Orientados a Objetos](ch17-01-what-is-oo.md)
    - [Uso de Rasgos que Permiten Valores de Diferentes Tipos](ch17-02-trait-objects.md)
    - [Implementación de un Patrón de Diseño Orientado a Objetos](ch17-03-oo-design-patterns.md)

## Temas Avanzados

- [Patrones y Coincidencias](ch18-00-patterns.md)
    - [Se Pueden Utilizar Todos los Patrones de Lugares](ch18-01-all-the-places-for-patterns.md)
    - [Refutabilidad: Si un Patrón Puede No Coincidir](ch18-02-refutability.md)
    - [Sintaxis del Patrón](ch18-03-pattern-syntax.md)

- [Características Avanzadas](ch19-00-advanced-features.md)
    - [Rust Inseguro](ch19-01-unsafe-rust.md)
    - [Rasgos Avanzados](ch19-03-advanced-traits.md)
    - [Tipos Avanzados](ch19-04-advanced-types.md)
    - [Funciones Avanzadas y Clausuras](ch19-05-advanced-functions-and-closures.md)
    - [Macros](ch19-06-macros.md)

- [Proyecto Final: Construcción de un Servidor Web Multiproceso](ch20-00-final-project-a-web-server.md)
    - [Creación de un Servidor Web de un Solo Subproceso](ch20-01-single-threaded.md)
    - [Convirtiendo Nuestro Servidor de un Solo Subproceso en un Servidor de Múltiples Subprocesos](ch20-02-multithreaded.md)
    - [Cierre y Limpieza Amigables](ch20-03-graceful-shutdown-and-cleanup.md)

- [Apéndice](appendix-00.md)
    - [A - Palabras clave](appendix-01-keywords.md)
    - [B - Operadores y Símbolos](appendix-02-operators.md)
    - [C - Rasgos Derivables](appendix-03-derivable-traits.md)
    - [D - Herramientas de Desarrollo](appendix-04-useful-development-tools.md)
    - [E - Ediciones](appendix-05-editions.md)
    - [F - Traducciones del libro](appendix-06-translation.md)
    - [G - Cómo se desarrolla Rust y "Rust Nocturno"](appendix-07-nightly-rust.md)
