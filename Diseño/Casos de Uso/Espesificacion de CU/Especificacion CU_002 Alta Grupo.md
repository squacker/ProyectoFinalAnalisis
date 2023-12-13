**Caso de Uso:  CU\_002 (Alta Grupo)**  **Descripción:** 

Este caso de uso explica cómo es el procedimiento de cómo el profesor realiza el alta de un nuevo grupo en el sistema para llevar a cabo el registro de asistencia. Implica la creación y configuración de un grupo con información como el nombre del grupo, materia y listado de alumnos.  

**Actores:** 

Profesor: Es el responsable de gestionar la alta de los nuevos grupos para que los alumnos puedan llevar a cabo el registro de asistencia. 

**Precondiciones:** 

1) El profesor tiene instalada la aplicación con tecnología NFC en su teléfono. 
1) El profesor cuenta con la información del grupo que se dará de alta (nombre del grupo, materia, listado de alumnos y carrera) 

**Flujo básico de eventos:**  

1. El profesor abre la aplicación en su teléfono y activa la función NFC.  
1. El profesor selecciona la opción alta de grupos. 
1. La aplicación solicita al profesor ingresar la información del nuevo grupo, (el grupo, materia y carrera) 
1. El sistema verifica que no exista un grupo duplicado con la información que se tiene almacenada. 
1. El sistema genera el grupo y permite al profesor dar de alta alumnos al grupo en cualquier momento. 
1. El profesor selecciona el botón "Guardar". 
1. Sistema manda confirmación de que el grupo fue creado y guardado con éxito. 

**Flujos alternativos:** 

1\.  Si la información ingresada para la creación del grupo es incorrecta, incompleta, o duplicada el sistema muestra un mensaje de error y vuelve al paso número 3 para ingresar la información correctamente. 

**Postcondiciones:** 

El profesor ha realizado con éxito el alta de un nuevo grupo en el sistema. El grupo está creado con el nombre proporcionado, la materia asociada y la lista de alumnos asignados. El grupo está listo para ser utilizado en los registros de asistencia. 
