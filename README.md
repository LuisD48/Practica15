# Sistema Administrador de Bitácora - Préstamo de Equipos 

Este repositorio contiene la **Práctica / Ejercicio 15**, desarrollada para la **Facultad de Ingeniería Mochis (UAS)** en la Coordinación de Centros de Cómputo y Red Escolar.

## Descripción del Proyecto

El objetivo de este proyecto es digitalizar y optimizar el formato físico de la "Bitácora de Préstamo de Equipos". Más allá de ser un simple formulario para *gestionar* (recabar datos), este sistema permite **administrar** el ciclo de vida del préstamo de cada equipo en tiempo real.

El sistema rastrea cuándo un equipo está en uso y cuándo es devuelto, estampando automáticamente la fecha y hora de la transacción mediante JavaScript.

## Características Principales

* **Registro de Préstamos:** Captura de datos del solicitante (Nombre, Carrera, Grupo, Tipo de Usuario) y el equipo solicitado.
* **Control de Estado:** Los préstamos ingresan con un estado "Activo" y registran automáticamente la hora exacta de salida.
* **Recepción de Equipos:** Permite marcar un equipo como devuelto, estampando la hora de entrega y cambiando su estado a completado.
* **Interfaz "Vanilla":** Desarrollado utilizando HTML puro y JavaScript nativo sin frameworks CSS, demostrando el dominio de la estructura básica web y la lógica de programación en memoria.

## Tecnologías Utilizadas

* **HTML5:** Estructura de la aplicación y semántica web.
* **JavaScript (ES6):** Lógica del negocio, manipulación del DOM, manejo de arreglos para almacenar los datos en memoria y generación de marcas de tiempo.

## Cómo ejecutar el proyecto

Al ser un proyecto estático que funciona del lado del cliente, no requiere instalación de dependencias ni servidores locales complejos.

1. Clona este repositorio o descarga el archivo principal.
2. Abre el archivo `appPaterno_appMaterno_ejercicio15.html` directamente en cualquier navegador web moderno (Chrome, Firefox, Edge).
3. O bien, visita la versión en vivo alojada en GitHub Pages: [Inserta aquí tu enlace de GitHub Pages]

---
**Autor:** Luis 
**Usuario de GitHub:** [@LuisD48](https://github.com/LuisD48)
