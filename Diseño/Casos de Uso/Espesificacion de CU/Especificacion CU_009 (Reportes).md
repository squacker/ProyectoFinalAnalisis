**Caso de Uso: CU\_009 (Reportes)** **Descripción:** 

Este caso de uso describe el procedimiento mediante el cual el sistema genera un reporte mensual de todas las asistencias de los alumnos que están cursando con el profesor. 

**Actores:** 

Sistema: Es el responsable de generar un reporte cuando llega el primero de cada mes. 

Profesor: Es el encargado de visualizar la asistencia de los alumnos. 

**Precondiciones:**.  

1. El grupo ya debe de estar creado para la generación del reporte.  
1. El sistema cuenta con la información necesaria para generar el reporte de la asistencia de cada mes. 

**Flujo básico de eventos:** 

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Reporte".
2) El profesor selecciona el grupo del que desea obtener el reporte
1) El sistema solicita el mes, del grupo del que se desea obtener la lista de asitencia.  
1) El profesor selecciona el mes de la lista de asistencia . 
1) El sistema verifica el grupo y el mes seleccionado y genera el reporte de los alumnos que están registrados. 


**Flujos alternativos:** 

1) En caso de que el alumno no se encuentre dado de alta en el grupo, irse al CU\_ 002 
1) En caso de que el profesor seleccione un mes de asistencia incorrecta o que no exista, el sistema envía un mensaje de error y regresa al paso 4      

**Postcondiciones:** 

\1) El profesor ha realizado con éxito el reporte de asistencias de sus alumnos inscritos en la materia en el sistema 
