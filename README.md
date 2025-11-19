# Evaluación de Módulo 3
## Hans Schiess

Este proyecto es una aplicación de línea de comandos simple para gestionar una lista de tareas pendientes. Permite a los usuarios agregar, ver, marcar como completadas y eliminar tareas. Los datos se guardan en un archivo local para que persistan entre sesiones.

## Características

*   **Menú interactivo:** Navegación sencilla a través de opciones numéricas en la consola.
*   **Gestión de Tareas:**
    *   **Agregar:** Añade nuevas tareas a la lista.
    *   **Listar:** Muestra todas las tareas con su estado (Pendiente o Completada).
    *   **Completar:** Marca una tarea existente como completada.
    *   **Eliminar:** Borra una tarea de la lista.
*   **Persistencia de Datos:** Las tareas se guardan automáticamente en un archivo `evaluación_de_modulo_3.txt` al salir del programa y se cargan al iniciarlo.

## Requisitos

* Python 3.x

No se requieren bibliotecas externas, ya que el proyecto utiliza únicamente la biblioteca estándar de Python.

## Uso

Para ejecutar la aplicación, abre una terminal en el directorio del proyecto y ejecuta el siguiente comando:

```bash
python evaluacion_modulo_3.py
```

Aparecerá el siguiente menú en la consola:

```text

--- Gestor de Tareas ---
1. Agregar tarea
2. Ver tareas
3. Marcar tarea como completada
4. Eliminar tarea
5. Salir
Selecciona una opción:
```

Elige una opción numérica para realizar la acción deseada. Las tareas se guardarán al seleccionar la opción `5. Salir`.

## Estructura del Proyecto

* `evaluacion_modulo_3.py`: El script principal de la aplicación que contiene toda la lógica del gestor de tareas.
* `evaluación_de_modulo_3.txt`: Archivo de texto donde se almacenan las tareas. Se crea y actualiza automáticamente.
* `README.md`: Este archivo de documentación.
