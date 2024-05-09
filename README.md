# Manipulando_Api_Peliculas_java_SpringBoot
# Resumen del Proyecto

Este repositorio contiene un proyecto desarrollado en Java utilizando el framework Spring. 

Este sistema es una aplicación de línea de comandos que permite al usuario buscar información sobre una serie de televisión utilizando una API externa y realizar diversas operaciones con los datos obtenidos. Aquí está una explicación detallada de lo que hace:



## Consumo de API

Se aprendió a consumir APIs a través del método `obtenerDatos`, que devuelve los datos deseados en formato JSON.



## Serialización y Deserialización

Se exploró cómo transformar JSON en clases y cómo esto es útil para el proyecto.


## Creación de Interfaces e Implementación de Métodos

Se demostró la creación de una interfaz con un método genérico que utiliza Generics, así como la implementación de este método en una clase separada.


## Inclusión de Nuevas Dependencias en el Proyecto

Se detalló cómo agregar una nueva dependencia al archivo `.pom.xml` y cómo este proceso es gestionado por Maven.

## APIs y Consultas Detalladas

Se explicó cómo trabajar con APIs para obtener información detallada y realizar consultas más específicas.

## Uso de Anotaciones `@JsonAlias` y `@JsonIgnoreProperties`

Se exploró la importancia de utilizar estas anotaciones para mapear la API a la aplicación.

## Creación de Métodos para Interacción con el Usuario

Se creó un método para mostrar el menú e interactuar con el usuario, permitiéndoles ingresar el nombre de la serie que desean buscar.

## Manipulación de Datos de una API

Se mostró cómo importar y manipular datos de una API, en este caso, datos de series de televisión.

## Manipulación de Cadenas para Acceder a una API

Se observó cómo manipular cadenas para crear direcciones que la API entenderá y devolverá los datos deseados.

## Introducción a los Lambdas

Se conoció las Expresiones Lambda en Java, también conocidas como funciones anónimas que podemos usar para escribir código más eficiente.

## Funciones Lambda

Se aprendió la sintaxis de las funciones lambda en Java y cómo permiten una escritura más concisa.

## Uso de Streams en Java

Se obtuvo una comprensión esencial de los streams, que son flujos de datos en Java, y cómo realizar operaciones encadenadas en ellos.

## Filtrado de Datos

Se aprendió cómo usar la funcionalidad de filtrado en streams para seleccionar solo datos específicos, en este caso, episodios de series de televisión con una calificación específica.

## Manipulación de Fechas

Se exploró cómo convertir cadenas en `LocalDate`s y cómo manejar posibles excepciones que pueden ocurrir en este proceso.


## Manejo de Excepciones

Se realizó el manejo de excepciones específicas, como `NumberFormatException` y `DateTimeParseException`, que pueden ocurrir debido a la conversión de datos.


## Uso de la función `peek`

Se introdujo la función `peek` en Java, que permite visualizar lo que está sucediendo en cada etapa del Stream, facilitando el proceso de depuración.

## Operaciones Intermedias y Finales
Se aprendió sobre la utilización de operaciones
▲ `find`
▲ `filter`
▲ `map`

## Uso de Contenedores para Datos

Se examinó cómo usar el contenedor `Optional` para almacenar un episodio dentro de un Stream y evitar referencias nulas.

## Uso de `DoubleSummaryStatistics`

Se aprendió cómo la clase `DoubleSummaryStatistics` de Java puede ayudar a analizar información, como la calificación más alta, la más baja y la cantidad de evaluaciones en nuestras series.

## Nota

Este proyecto proporciona una sólida base de conocimientos sobre desarrollo en Java con Spring, el consumo de APIs, manipulación de datos y el uso de características avanzadas del lenguaje Java como lambdas y streams.
