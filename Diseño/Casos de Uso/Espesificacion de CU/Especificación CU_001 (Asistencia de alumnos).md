**CU\_001 Asistencia de alumnos**  **Descripción:** 

Este caso de uso explica cómo es el procedimiento de registrar la asistencia de los alumnos que están inscritos en la materia. En donde se usará la tarjeta de movilidad integrada de la ciudad de México a través de la lectura NFC. 

**Actores:** 

- Profesor: Es el responsable de tomar la asistencia a través de su teléfono inteligente a los alumnos que están inscritos en la materia.   
- Alumno: Es todo aquel que está inscrito en la materia que imparte el profesor, además es el portador de su tarjeta de movilidad para la toma de su asistencia.  

  **Precondiciones:** 

1. El profesor debe de tener instalada la aplicación y contar con teléfono con la tecnología NFC. 
1. El profesor debe de tener suficiente espacio en almacenamiento para poder guardar todas las asistencias por clase. 
1. El alumno debe de estar dado de alta en el grupo  por parte del profesor. 
1. El alumno debe de contar con tarjeta de movilidad integral de la CDMX (NFC). 
1. El alumno solo debe de tener asociada una tarjeta con su identidad. 

**Flujo básico de eventos:** 

1. El caso de uso inicia cuando el profesor deberá encender el NFC. 
1. El profesor selecciona en el menú “Toma de asistencia”. 
2. El alumno acerca su tarjeta de movilidad integrada al lector de NFC en el dispositivo del profesor.  
2. El sistema verifica la identidad del alumno mediante la información almacenada en la tarjeta de movilidad integrada NFC. 
2. El sistema del NFC mostrará un mensaje de confirmación de asistencia, en donde aparecerá la fecha y hora en que fue registrada la asistencia del alumno. 

   **Flujos alternativos:** 

1. En caso de que el alumno no esté registrado en la materia dirigirse al CU\_002 Alta de alumno. 
1. En caso de que la tarjeta esté extraviada, esté  dañada o no sea detectada adquirir una nueva y dirigirse al CU\_007 Cambio de tarjeta. 
3. En caso de que el alumno no cuente con tarjeta de movilidad CDMX deberá adquirir una y deberá acercarse con el profesor para que pueda dar de alta la tarjeta (CU\_ 005 Dar de Alta Tarjeta) 

   **Postcondiciones:** 

1\.La asistencia del alumno seleccionado se ha registrado correctamente en la aplicación local del profesor. 

3\.El historial de asistencia del alumno seleccionado y de la clase correspondiente se ha actualizado con la última información registrada. 
