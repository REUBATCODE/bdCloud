
# Alumno: RUBEN BERNARDO RUIZ VEGA - CLOUD DATABASES

## Portada
Bases de Datos para Cloud Apps
Nombre del Alumno: Rubén Bernardo Ruíz Vega
28 de enero de 2024

## Introducción
Esta primera tarea es para explicar la importancia de los conceptos básicos de Bases de Datos y específicamente en la Nube. En clase se explicaron demás temas relacionados que funcionan como parte integral del plan de estudios y los conocimientos esperados al finalizar esta unidad. 

## Mapas Conceptuales por Cada Fuente Sugerida
![Alt text](mapa1.png)
---
![Alt text](mapa2.png)
---
![Alt text](mapa3.png)
---
![Alt text](mapa4.png)
---
![Alt text](mapa5.png)
---
![Alt text](mapa6.png)
---
![Alt text](mapa7.png)
---
## Quizes de SQL
![Alt text](quizes.png)
---

## Tablas del ejercicio de la biblioteca
![Alt text](tablas.png)
Autores (Authors): Contiene información sobre los autores de los libros, con campos para el ID del autor (que es la clave primaria), nombre y apellido.

Libros (Books): Representa los libros, con un ISBN único como clave primaria, y contiene detalles como el título, año de publicación, editorial y el ID del autor (que hace referencia a la tabla Autores).

Volúmenes (Volumes): Se refiere a copias físicas específicas de los libros. Incluye un ID de volumen como clave primaria, el ISBN del libro (que vincula a la tabla Libros), y un campo que indica si el volumen está dañado.

Miembros (Members): Detalla los miembros de la biblioteca, con un ID de miembro como clave primaria y contiene información personal como nombre, apellido, fecha de nacimiento, número de membresía y dirección.

Préstamos (Loans): Registra los detalles de los préstamos de los libros, con un ID de préstamo como clave primaria, el ID de volumen (vinculado a Volúmenes), el ID de miembro (vinculado a Miembros) y la fecha del préstamo.
---


## Bibliografía
1. "Data Modeling - What is Data Modeling?" - AWS. Disponible en: [https://aws.amazon.com/es/what-is/data-modeling/](https://aws.amazon.com/es/what-is/data-modeling/)
2. "NoSQL - Introducción a las bases de datos no estructuradas" - SlideShare. Disponible en: [https://es.slideshare.net/dipina/nosql-introduccin-a-las-bases-de-datos-no-estructuradas](https://es.slideshare.net/dipina/nosql-introduccin-a-las-bases-de-datos-no-estructuradas)
3. "The Difference Between ACID and BASE Database" - AWS. Disponible en: [https://aws.amazon.com/compare/the-difference-between-acid-and-base-database/](https://aws.amazon.com/compare/the-difference-between-acid-and-base-database/)
