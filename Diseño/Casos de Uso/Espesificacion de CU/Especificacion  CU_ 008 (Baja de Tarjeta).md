**Caso de Uso: Baja de Tarjeta (CU\_ 008)** **Descripción:** 

Este caso de uso detalla el proceso mediante el cual un profesor realiza la baja de una tarjeta de movilidad de la CDMX en el sistema de asistencias. Esta acción implica desvincular la tarjeta de movilidad de un alumno específico, permitiendo así un manejo eficiente y preciso de las tarjetas asociadas a la toma de asistencia en el contexto de un grupo, nombre del alumno, número de cuenta (ID) y materia. 

**Actores:** 

Profesor: Es el encargado de gestionar las bajas de tarjetas de movilidad de los alumnos para llevar a cabo correctamente el registro de asistencia. 

**Precondiciones:** 

1) El profesor tiene instalada la aplicación y cuenta con tecnología NFC en su teléfono. 
1) El alumno ya posee una tarjeta de movilidad integrada de la CDMX. 
1) El grupo al que se asociará la tarjeta de movilidad de la CDMX ya está creado en el sistema. 
1) El alumno al que se asociará la tarjeta ya está registrado en el sistema y pertenece a un grupo especificado. 
1) El profesor cuenta con la información necesaria para la tarjeta NFC ( grupo, materia y alumno). 

**Flujo básico de eventos:** 

1) El profesor abre la aplicación en su teléfono y activa la función NFC. 
1) El profesor selecciona la opción "Baja de Tarjeta"  
1) El sistema muestra la lista de tarjetas de movilidad dadas de alta y permite al profesor seleccionar la tarjeta que desea dar de baja. 
1) El profesor confirma la baja de la tarjeta seleccionada. 
1) El sistema verifica que la tarjeta no tenga asociada ninguna asistencia pendiente o activa en sesiones de clase. 
1) El sistema registra la baja de la tarjeta y actualiza la información correspondiente. 
1) En caso de ser necesario, el profesor puede asignar la tarjeta a otro alumno o dejarla disponible para futuras altas. 

**Flujos alternativos:** 

\1)    Si la tarjeta tiene asistencias pendientes o activas, el sistema informa al profesor y sugiere esperar a que se completen antes de realizar la baja\. 

**Postcondiciones:** 

\1)  El profesor ha realizado con éxito la baja de una tarjeta de movilidad de la CDMX en el sistema\. La tarjeta ya no está asociada a ningún alumno y puede ser utilizada para futuros registros o asignada a otro estudiante si es necesario 
