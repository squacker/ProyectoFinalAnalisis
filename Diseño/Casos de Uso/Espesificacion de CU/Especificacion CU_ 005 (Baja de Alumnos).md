**Caso de Uso: CU\_ 005 (Baja de Alumnos)** **Descripción:** 

Este caso de uso describe el procedimiento mediante el cual el profesor realiza la baja de un alumno existente de un grupo en el sistema. Implica la eliminación de información individual de los alumnos que ya no formarán parte del grupo, lo que puede ser necesario debido a cambios en la inscripción o situaciones similares. 

**Actores:** 

Profesor: Responsable de gestionar las bajas de alumnos en un grupo específico. 

` `**Precondiciones:** 

\1) El profesor tiene acceso a los datos de  los alumnos en el grupo y conoce la información necesaria para identificar al alumno que se dará de baja\.  (nombre, apellidos, número de cuenta, grupo, materia, carrera\.) 

**Flujo básico de eventos:**  

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Baja de Alumnos". 
1) La aplicación muestra la lista de alumnos actualmente registrados en el sistema. 
1) El profesor selecciona al alumno que se dará de baja. 
1) El sistema solicita confirmación para la baja del alumno. 
1) El profesor confirma la baja. 
1) El sistema muestra una notificación de que el alumno ha sido dado de baja correctamente.  **Flujos alternativos:** 

1\.  Si el profesor selecciona al alumno incorrecto a dar de baja el sistema vuelve al paso número 3. 

**Postcondiciones:** 

1\.  El profesor ha realizado con éxito la baja de un alumno en el grupo. 

Se perderán todos los datos del alumno dado de alta.  
