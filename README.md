 Prueba Técnica

## Duración: 24 Horas

## Secciones:
1. Front-end (React o Vue.js)
2. Gestión del Estado (Redux o Vuex)
3. backend laravel

## Instrucciones:
- Completa cada sección de la prueba.
- Puedes usar documentación en línea, pero no se permite la colaboración con otras personas.
---

## Sección 1: Front-end (React o Vue.js)

### Tarea 1: Crear una Aplicación Avanzada

Crea una aplicación que muestre una lista de tareas (To-Do List). La aplicación debe permitir:
- Agregar nuevas tareas.
- Marcar tareas como completadas.
- Editar tareas existentes.
- Filtrar tareas por estado (todas, completadas, pendientes).

**Requisitos:**
- Utiliza React o Vue.js.
- La lista de tareas debe ser un componente separado.
- Debe haber un componente para agregar y editar tareas.
- Debe haber un componente para cada tarea individual.
- Implementa un sistema de rutas para navegar entre las vistas principales de la aplicación (por ejemplo, usando React Router o Vue Router).
- Añadir animaciones al agregar, editar y eliminar tareas.
- Implementar un tema oscuro/modo claro.

---

## Sección 2: Gestión del Estado (Redux o Vuex)

### Tarea 2: Integrar Gestión del Estado

Integra una solución de gestión del estado (Redux para React, Vuex para Vue.js) en la aplicación de tareas creada en la sección anterior.

**Requisitos:**
- Almacena las tareas en el estado global.
- Las acciones para agregar, completar, editar y eliminar tareas deben actualizar el estado global.
- Conecta los componentes a la tienda de estado para mostrar y modificar las tareas.
- Manejar el estado de la autenticación de usuarios (login/logout).
**obcional**
- Implementar persistencia del estado en el almacenamiento local del navegador (localStorage).


---


### Tarea 3: Crear un Backend

Crea una aplicación en Laravel que sirva como backend para la aplicación de tareas. Debe proporcionar una API RESTful para gestionar las tareas y autenticación de usuarios.

**Requisitos:**
- Configura un proyecto nuevo de Laravel.
- Crea una migración para la bd`.
- Implementa la autenticación de usuarios.
- Crea un controlador de tareas con las siguientes rutas:
  - `GET /tasks` - Obtener todas las tareas.
  - `POST /tasks` - Crear una nueva tarea.
  - `PUT /tasks/{id}` - Actualizar una tarea existente.
  - `DELETE /tasks/{id}` - Eliminar una tarea.
- Protege las rutas de tareas para que solo los usuarios autenticados puedan acceder.

**Puntos extra:**
- Implementar validación de datos en los endpoints de creación y actualización de tareas.
- Implementar paginación y búsqueda en el listado de tareas.

---

## Entrega

- Sube tu código a un repositorio de GitHub y proporciona el enlace.
- Incluye un archivo README.md con instrucciones sobre cómo ejecutar la aplicación front-end y el backend.

---

## Criterios de Evaluación

1. **Funcionalidad**: La aplicación debe cumplir con los requisitos especificados.
2. **Código Limpio**: El código debe ser claro y seguir buenas prácticas de programación.
3. **Uso de Gestión del Estado**: Implementación correcta y eficiente de Redux o Vuex.
4. **Implementación de Laravel**: Correcta configuración y funcionamiento de la API RESTful y autenticación.
5. **Documentación**: Instrucciones claras sobre cómo ejecutar las aplicaciones.

---
