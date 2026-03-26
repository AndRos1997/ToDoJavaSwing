# ToDoJavaSwing
Aplicación para Test practico de Java Swing
# 📝 ToDo List - Java Swing

Aplicación de escritorio desarrollada en Java utilizando Swing, que permite gestionar tareas con diferentes estados.

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git clone https://github.com/AndRos1997/ToDoList-Java-Swing.git
```

2. Abrir el proyecto en NetBeans

3. Ejecutar el proyecto:

* Clic derecho sobre el proyecto
* Seleccionar **Run**

📌 Requisitos:

* Java JDK 8 o superior
* NetBeans IDE

---

## 🧠 Decisiones tomadas

* Se utilizó **Java Swing** para la interfaz gráfica por su integración con NetBeans.
* Se implementó una estructura basada en:

  * Lista en memoria (`ArrayList`) como fuente de datos
  * `JTable` como representación visual
* Se separó la lógica de datos de la vista (tabla), permitiendo mayor escalabilidad.
* Se utilizó `DefaultTableModel` para manejar dinámicamente los datos en la tabla.
* Se implementaron validaciones para mejorar la experiencia del usuario.

---

## ✅ Funcionalidades implementadas

### 📌 Gestión de tareas

* Crear tareas con:

  * Título (obligatorio)
  * Descripción
  * Estado:

    * Pendiente
    * En progreso
    * Completada

### 📋 Visualización

* Listado de tareas en tabla
* Visualización de:

  * Título
  * Estado

### 🔎 Filtros

* Filtrar tareas por estado:

  * Todos
  * Pendiente
  * En progreso
  * Completada

### ⚙️ Acciones sobre tareas

* Agregar tarea
* Eliminar tarea (con confirmación)
* Cambiar estado dinámicamente

### 🛡️ Validaciones

* No permite crear tareas sin título
* Mensajes de advertencia si:

  * No hay tareas
  * No hay selección

---

## 🎨 Mejoras de interfaz

* Ajuste automático de texto en la descripción
* Scroll dinámico según contenido
* Interfaz organizada con componentes Swing

---
---

## 👨‍💻 Autor

Desarrollado por Andrés Rosero

