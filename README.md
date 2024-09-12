# Explicación del Cronograma de Actividades

Este código crea una aplicación web simple para gestionar un cronograma de actividades. Permite a los usuarios agregar, editar y eliminar actividades asociadas a días específicos. A continuación, se explica cada parte del código:

## HTML

La estructura HTML define la página web con los siguientes elementos principales:

1. Un formulario para ingresar nuevas actividades.
2. Una tabla para mostrar las actividades existentes.

## CSS

El estilo CSS proporciona un diseño básico y responsive:

- Centra el contenido y limita el ancho máximo.
- Estiliza la tabla para una mejor legibilidad.
- Aplica márgenes y rellenos para mejorar el espaciado.

## JavaScript

El código JavaScript maneja la funcionalidad de la aplicación:

### Variables globales

- `actividades`: Un array que almacena los objetos de actividades.

### Funciones principales

1. `agregarActividad()`:
   - Captura los valores de día y actividad del formulario.
   - Agrega un nuevo objeto de actividad al array `actividades`.
   - Actualiza la tabla y limpia el formulario.

2. `actualizarTabla()`:
   - Limpia y reconstruye la tabla con las actividades actuales.
   - Agrega botones de edición y eliminación para cada actividad.

3. `limpiarFormulario()`:
   - Resetea los campos del formulario después de agregar una actividad.

4. `editarActividad(index)`:
   - Permite al usuario editar una actividad existente mediante un prompt.
   - Actualiza el array de actividades y la tabla.

5. `eliminarActividad(index)`:
   - Elimina una actividad del array después de la confirmación del usuario.
   - Actualiza la tabla para reflejar los cambios.

## Flujo de la aplicación

1. El usuario ingresa un día y una actividad en el formulario.
2. Al hacer clic en "Agregar", se crea una nueva entrada en la tabla.
3. Las actividades existentes se pueden editar o eliminar usando los botones correspondientes.
4. La tabla se actualiza automáticamente después de cada acción.

Este código proporciona una base sólida para un cronograma de actividades simple y funcional, que se puede expandir o modificar según sea necesario.
