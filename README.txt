# Evaluación Final Spring Módulo 5: Desarrollo de Aplicaciones Web Dinámicas con Java

## Sistema de Información para Empresa de Asesorías en Prevención de Riesgos

### Integrantes:
- Diego Rivera
- Beatriz Maldonado
- Jorge Lira
- Jorge Montoya

## Índice

- [1. CONTEXTO](#1-contexto)
- [2. PROBLEMA](#2-problema)
- [3. SOLUCIÓN](#3-solución)
- [4. OBJETIVOS DEL PROYECTO](#4-objetivos-del-proyecto)
- [5. REQUISITOS DEL SISTEMA](#5-requisitos-del-sistema)
- [6. ESTRUCTURA DEL PROYECTO](#6-estructura-del-proyecto)
- [7. MODELO DE DATOS](#7-modelo-de-datos)
- [8. REPOSITORIOS](#8-repositorios)

---

## 1. CONTEXTO

En la última década, los índices de accidentabilidad han aumentado, especialmente en empresas de los sectores industrial, minero y de la construcción. A pesar de la existencia de leyes y normativas que obligan a las empresas a implementar medidas necesarias para proteger la vida y salud de los trabajadores, los incidentes han incrementado considerablemente.

Las empresas del rubro de la prevención de riesgos tienen la responsabilidad de ofrecer soluciones efectivas y un sistema que permita gestionar toda la información necesaria para llevar un control adecuado. En este contexto, surge la necesidad de desarrollar un sistema de información que ayude a gestionar las operaciones diarias de una empresa de asesorías en prevención de riesgos.

---

## 2. PROBLEMA

La empresa no posee un sistema de información adecuado que le permita:
1. Administrar de forma eficiente la cantidad de información que se genera a diario.
2. Controlar las actividades de prevención y la gestión de recursos humanos.
3. Mantener un registro y control de los incidentes laborales.
4. Gestionar la información de manera centralizada para la toma de decisiones.

Actualmente, estos procesos se realizan de manera manual o con sistemas poco eficientes, lo que incrementa la posibilidad de errores y retrasa las operaciones.

---

## 3. SOLUCIÓN

Para resolver estos problemas, se propone el desarrollo de un **Sistema de Información Dinámico** que permita:
1. Centralizar la información de clientes, capacitaciones y accidentes laborales.
2. Gestionar el recurso humano de forma eficiente, permitiendo a los encargados tener acceso rápido a los datos relevantes.
3. Facilitar la creación de reportes y análisis sobre las capacitaciones, accidentes y visitas en terreno.
4. Mejorar la experiencia del usuario con una interfaz intuitiva y fácil de usar.
5. Automatizar procesos clave para reducir el riesgo de errores y mejorar la eficiencia operativa.

Este sistema se desarrollará utilizando tecnologías modernas como **Java** y **bases de datos Oracle**, siguiendo el patrón de diseño **MVC**.

---

## 4. OBJETIVOS DEL PROYECTO

- Desarrollar un sistema web dinámico que permita la gestión de la información de clientes, capacitaciones y accidentes laborales.
- Implementar una solución escalable y adaptable a las necesidades de la empresa.
- Proveer una interfaz de usuario amigable que permita a los empleados acceder y gestionar información de manera eficiente.
- Automatizar procesos que actualmente se realizan de forma manual para reducir los tiempos de operación y el margen de error.
- Conectar el sistema a una base de datos relacional para asegurar la integridad y disponibilidad de la información.

---

## 5. REQUISITOS DEL SISTEMA

El sistema debe cumplir con los siguientes requisitos funcionales y no funcionales:

### Requisitos Funcionales:
1. Gestionar la información de los **clientes**.
2. Registrar y gestionar las **capacitaciones** realizadas a los empleados.
3. Registrar **accidentes laborales** y permitir la generación de reportes.
4. Gestionar las **visitas en terreno** realizadas por los profesionales a las empresas clientes.
5. Permitir la generación de **informes** de capacitación, accidentes y visitas.

### Requisitos No Funcionales:
1. El sistema debe ser accesible desde cualquier navegador moderno.
2. El rendimiento del sistema debe permitir un acceso rápido a la información.
3. Debe tener un diseño responsive que permita el acceso desde dispositivos móviles.
4. La seguridad de los datos debe ser una prioridad, implementando autenticación y control de acceso.

---

## 6. ESTRUCTURA DEL PROYECTO

El proyecto seguirá una arquitectura basada en el patrón de diseño **MVC (Modelo-Vista-Controlador)**, distribuyendo las responsabilidades en capas separadas para mejorar la mantenibilidad del sistema:

1. **Modelo:** Encargado de la representación y manipulación de los datos (conexión a la base de datos Oracle).
2. **Vista:** Proveerá la interfaz gráfica a través de una aplicación web dinámica y responsive.
3. **Controlador:** Gestionará la lógica del sistema, conectando la vista con el modelo y gestionando las solicitudes de los usuarios.

---

## 7. MODELO DE DATOS

El sistema gestionará los siguientes datos principales:

1. **Clientes:** Información de las empresas que contratan los servicios de prevención de riesgos.
2. **Capacitaciones:** Información detallada sobre las capacitaciones realizadas.
3. **Accidentes Laborales:** Registro de accidentes ocurridos en las empresas clientes.
4. **Visitas en Terreno:** Información de las visitas que los profesionales realizan a los clientes.

El modelo de datos estará implementado en **Oracle**, garantizando la integridad referencial y permitiendo consultas eficientes mediante **SQL**.

---

## 8. REPOSITORIOS

- **Frontend:** El desarrollo del frontend se realizará utilizando tecnologías como **HTML**, **CSS**, **JavaScript** y frameworks como **Bootstrap** para un diseño responsivo y dinámico.
- **Backend:** El backend será desarrollado en **Java**, utilizando el framework **Spring** para la gestión de controladores y acceso a la base de datos.
- **Base de Datos:** La base de datos estará alojada en **Oracle**, utilizando **SQL** para el diseño e interacción con los datos.

El código fuente del proyecto estará organizado en diferentes repositorios para facilitar su gestión y colaboración entre los integrantes del equipo:

1. [Repositorio del Frontend](#enlace-frontend)
2. [Repositorio del Backend](#enlace-backend)
3. [Repositorio de la Base de Datos](#enlace-base-de-datos)

---

Fin del documento.
