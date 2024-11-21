# Seguimiento 3 Corte 3: Principios SOLID - Interfaces Funcionales - Streams

Este repositorio contiene la implementación de un proyecto enfocado en la aplicación de los principios SOLID, interfaces funcionales y Streams en Java. Utilizamos patrones de diseño como Observer y Factory, además de servicios para gestionar tareas.

---

## 🚀 Objetivos del Proyecto

- **Aplicar principios SOLID** en el diseño de clases y servicios.
- **Implementar patrones de diseño** como Factory y Observer.
- **Usar interfaces funcionales y Streams** para procesar datos de manera funcional y eficiente.

---

## 📂 Estructura del Proyecto

```plaintext
Seguimiento3/
├── src/
│   ├── principal/
│   │   ├── java/
│   │   │   ├── config/               # Configuración general del proyecto
│   │   │   │   └── Configuracion.java
│   │   │   ├── factory/              # Implementación del patrón Factory
│   │   │   │   └── TareaFactory.java
│   │   │   ├── model/                # Clases modelo
│   │   │   │   └── Tarea.java
│   │   │   ├── observer/             # Implementación del patrón Observer
│   │   │   │   ├── GestorNotificaciones.java
│   │   │   │   ├── Observador.java
│   │   │   │   └── Usuario.java
│   │   │   ├── service/              # Servicios principales
│   │   │   │   ├── GestorDeTareas.java
│   │   │   │   └── App.java
│   ├── probar/                       # Clases de pruebas
│   │   ├── java/
│   │   │   └── AppTest.java
└── pom.xml                           # Archivo de configuración para Maven
