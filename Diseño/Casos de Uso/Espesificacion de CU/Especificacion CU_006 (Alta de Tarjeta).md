` `**Caso de Uso CU\_006 (Alta de Tarjeta)**  **Descripción:** 

El caso de uso describe el proceso mediante el cual un profesor realiza el alta de una tarjeta de movilidad de la CDMX en el sistema de asistencias. Esta tarjeta se asocia a un alumno específico y se utiliza para facilitar el registro de asistencia del alumno en el contexto de un grupo, nombre del alumno, número de cuenta(ID) y materia. 

**Actores:** 

Profesor: es el responsable de dar de alta las tarjetas de movilidad de los alumnos para tomar asistencia. **Precondiciones:** 

1. El profesor debe de tener instalada la aplicación y contar con teléfono con la  tecnología NFC. 
1. El alumno ya contará con tarjeta de movilidad integrada de la CDMX 
1. El grupo al que se asociará la tarjeta de movilidad de la CDMX ya ha sido creado en el sistema. 
1. El alumno al que se asociará la tarjeta NFC se dará de alta en el sistema y pertenece a un grupo especificado. 
1. La materia o asignatura a la que se asociará la tarjeta NFC ya ha sido creada y configurada en el sistema. **Flujo básico de eventos:** 
1) El profesor abre su aplicación. 
1) El profesor selecciona la opción de dar de alta la tarjeta  
1) El sistema solicita al profesor ingresar la siguiente información asociada al alumno, grupo al que pertenece el alumno, nombre completo del alumno, número de cuenta del alumno, materia o asignatura asociada. 

4)El sistema verifica que la información ingresada del alumno (grupo, materia y alumno) no esté duplicada. 

4) El sistema registra la información y solicita al usuario una tarjeta para asociar. 
4) El profesor acerca la tarjeta al lector NFC. 
4) El sistema confirma que la tarjeta ha sido dada de alta y está lista para usarse en el sistema de asistencias. **Flujos alternativos:** 
1) Si la información ingresada para la tarjeta NFC (grupo, materia y alumno), es duplicada, el sistema muestra un mensaje de error y vuelve al paso número 3 para ingresar la información correctamente. 
1) En caso de que el alumno no esté registrado en la materia, debe de ir a CU\_002 Altas de alumnos.      **Postcondiciones:** 

   El profesor ha dado de alta una nueva tarjeta NFC, la ha asociado a un alumno, grupo y materia, y puede utilizarla para el registro eficiente de asistencia durante las sesiones de clase. 

. 
