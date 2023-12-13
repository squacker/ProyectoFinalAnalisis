**Caso de Uso: CU\_ 004 (Altas de Alumnos)** **Descripción:** 

Este caso de uso detalla el proceso mediante el cual el profesor realiza el alta de nuevos alumnos en un grupo recién creado. Implica la incorporación de información individual de los alumnos al grupo para facilitar el registro de asistencia. 

**Actores:** 

Profesor: Responsable de gestionar las altas de alumnos en un grupo específico. 

**Precondiciones:** 

1) El profesor ha realizado con éxito el alta de un nuevo grupo en el sistema (referido al CU\_008 - Alta Grupo). 
1) El profesor tiene instalada la aplicación con tecnología NFC en su teléfono 
1) El profesor cuenta con la información de los alumnos que se darán de alta   

**Flujo básico de eventos:** 

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Altas de Alumnos". 
1) La aplicación solicita al profesor ingresar la información del nuevo alumno (nombre, apellidos, número de cuenta, grupo, materia, carrera.) 
1) El sistema verifica que no exista un alumno duplicado con la información proporcionada. 
1) El sistema agrega al nuevo alumno al grupo previamente creado por el profesor. 
1) El profesor selecciona el botón "Guardar". 
1) El sistema muestra un mensaje de confirmación de que los alumnos ya están registrados en el grupo previamente creado. 

**Flujos alternativos:** 

1) Si la información ingresada para la creación del alumno es incorrecta, incompleta o duplicada, el sistema muestra un mensaje de error y vuelve al paso número 3 para ingresar la información correctamente. 
1) En caso de problemas de conexión durante el alta de un alumno, el sistema muestra un mensaje de error y el sistema guarda la información de los alumnos de manera local para que en cuanto se restablezca la conexión a internet se actualice la información.  

   **Postcondiciones:** 

1) El profesor ha realizado con éxito el alta de uno o varios alumnos en el grupo previamente creado. 
1) Los alumnos están asociados al grupo con la información proporcionada durante el proceso. 
1) El grupo, con la materia asociada y la lista completa de alumnos, está listo para ser utilizado en los registros de asistencia. 
