**Caso de Uso: CU\_003 (Baja de Grupo)** **Descripción:** 

Este caso de uso describe el procedimiento mediante el cual el profesor realiza la baja de un grupo existente en el sistema, desvinculándose del registro de asistencia. La acción implica la eliminación de la información asociada al grupo, incluyendo nombre del grupo, número de cuenta del alumno (id) materia, listado de alumnos motivo de baja y carrera. 

**Actores:** 

Profesor: Es el responsable de gestionar la baja de los grupos para mantener actualizado el sistema de registro de asistencia. 

**Precondiciones:** 

1. El profesor tiene instalada la aplicación con tecnología NFC en su teléfono. 
1. Existe al menos un grupo previamente creado en el sistema que se desea dar de baja. 
1. El profesor  deberá de conocer la clave de grupo que se desea eliminar 

**Flujo básico de eventos:** 

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Baja de Grupos". 
1) El sistema muestra la lista de los grupos existentes y permite al profesor seleccionar el grupo que se dará de baja. 
1) El profesor confirma la selección del grupo a dar de baja. 
1) El sistema muestra una confirmación de la acción y solicita la confirmación final del profesor. 
8) El sistema elimina la información del grupo seleccionado, incluyendo nombre del grupo, materia, listado de alumnos y carrera. 
8) El sistema muestra un mensaje de éxito indicando que la baja del grupo ha sido realizada con éxito. **Flujos alternativos:** 

**Flujos alternativos:**
   1)  El profesor selecciona erróneamente el grupo incorrecto para dar de baja\. El sistema vuelve al paso 3 para que seleccione el grupo correcto a dar de baja\. 

**Postcondiciones:** 

\1)  El profesor ha dado de baja con éxito un grupo en el sistema\. La información asociada al grupo, incluyendo nombre del grupo, materia, listado de alumnos y carrera, ha sido eliminada y el grupo ya no está disponible para el registro de asistencia\. 
