**Caso de Uso: Cambio de Tarjeta (CU\_007)** **Descripción:** 

Este caso de uso describe el procedimiento mediante el cual el profesor realiza el cambio de tarjeta de movilidad de la CDMX en el sistema de asistencias. La acción implica desvincular la tarjeta actual de un alumno específico y asociar una nueva tarjeta al mismo alumno, manteniendo la continuidad en el registro de asistencia en el contexto de un grupo, nombre del alumno, número de cuenta (ID) y materia. 

**Actores:** 

Profesor: Es el responsable de gestionar los cambios de tarjetas de movilidad de  los alumnos para llevar a cabo el registro de asistencia. 

Alumno: Es todo aquel que posee la tarjeta de movilidad de la CDMX que cambiara de tarjeta. 

**Precondiciones:** 

1) El profesor tiene instalada la aplicación con tecnología NFC en su teléfono. 
1) El alumno ya posee una nueva tarjeta de movilidad integrada de la CDMX. 
1) El grupo al que se asociará la nueva tarjeta de movilidad ya está creado en el sistema. 
1) El alumno al que se asociará la nueva tarjeta ya está registrado en el sistema y pertenece a un grupo especificado. 
1) La materia o asignatura a la que se asociará la nueva tarjeta ya ha sido creada y configurada en el sistema. 
1) El profesor cuenta con la información necesaria para la nueva tarjeta NFC ( grupo, materia y alumno). 

**Flujo básico de eventos:** 

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Cambio de Tarjeta" en la sección de gestión de tarjetas de movilidad. 
1) El sistema muestra la lista de tarjetas de movilidad dadas de alta y permite al profesor seleccionar la tarjeta actual que se desea cambiar. 
1) El profesor confirma la selección de la tarjeta actual que será cambiada. 
1) El sistema solicita al profesor ingresar la información asociada a la nueva tarjeta NFC: Grupo al que pertenece el alumno, nombre completo del alumno, número de cuenta del alumno, materia o asignatura asociada. 
1) El sistema verifica que la información ingresada para la nueva tarjeta (grupo, materia y alumno) no esté duplicada 
1) El sistema registra la información y solicita al usuario acercar la nueva tarjeta al lector NFC. 
1) El profesor acerca la nueva tarjeta al lector NFC. 
1) El sistema confirma que la nueva tarjeta ha sido asociada al alumno, grupo y materia, y actualiza la información correspondiente. 

**Flujos alternativos:** 

1) Si la información ingresada para la nueva tarjeta NFC es incorrecta o incompleta, el sistema muestra un mensaje de error y vuelve al paso número 5 para ingresar la información correctamente. 
1) En caso de problemas de conexión durante el cambio de la tarjeta, el sistema muestra un mensaje de error y permite al profesor intentar nuevamente. 

   **Postcondiciones:** 

\1)    El profesor ha realizado con éxito el cambio de tarjeta de movilidad de la CDMX en el sistema\. La nueva tarjeta está asociada al mismo alumno, grupo y materia, y puede utilizarse para futuros registros de asistencia\. La antigua tarjeta ya no está vinculada a dicho alumno en el sistema\. 
