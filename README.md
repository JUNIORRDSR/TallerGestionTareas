# Taller de Menús
**Programación 2**

## Descripción
Este proyecto consiste en una aplicación de escritorio en Java que permite a los usuarios gestionar una lista de tareas pendientes. Cada tarea tendrá un nombre, una descripción y estará asociada a una categoría. Los usuarios pueden realizar varias acciones con las tareas, como agregar, visualizar, filtrar, marcar como completadas o eliminar.

## Funcionalidades
La aplicación tiene las siguientes funcionalidades:

1. **Añadir nuevas tareas**:
   - El usuario podrá ingresar el nombre, la descripción y seleccionar una categoría para la nueva tarea.
   - Cada tarea estará asignada a un usuario específico (se puede seleccionar desde un menú desplegable de usuarios).

2. **Visualizar las tareas**:
   - Las tareas se mostrarán en una lista con al menos el nombre y la categoría de cada una.
   - Además, se podrá ver el progreso de cada tarea.

3. **Filtrar tareas por categoría**:
   - El usuario podrá seleccionar una categoría desde un menú desplegable.
   - La lista de tareas se actualizará para mostrar solo las tareas de la categoría seleccionada.

4. **Marcar tareas como completadas/pendientes**:
   - Cada tarea tendrá una opción para marcarla como completada o pendiente, usando un botón o un checkbox.

5. **Eliminar tareas**:
   - El usuario podrá seleccionar una tarea de la lista y eliminarla.

6. **Gestión de usuarios**:
   - Los usuarios pueden ser añadidos y gestionados en la aplicación. 
   - Se ha implementado una clase para gestionar la lista de usuarios.

## Interfaz Gráfica
La interfaz gráfica de la aplicación está implementada utilizando **Java Swing**, con menús que permiten al usuario interactuar fácilmente con las diferentes funcionalidades:

- Un menú para añadir tareas, gestionar usuarios y eliminar tareas.
- Un área de visualización para mostrar la lista de tareas con sus nombres, categorías y progreso.
- Un menú desplegable para seleccionar y filtrar tareas por categoría.
- Un checkbox o botón para marcar las tareas como completadas o pendientes.

## Tecnologías Utilizadas
- **Lenguaje de programación**: Java
- **Biblioteca para interfaz gráfica**: Java Swing

## Instrucciones de Uso
1. **Clonar el repositorio**:
   - Clona el repositorio en tu máquina local:
   ```bash
   git clone https://github.com/usuario/repositorio.git
