# Tarea: Mi prompt profesional 
## Funcionalidad elegida 
Calculo de notas

## Version 1: prompt basico 
Crea un programa sencillo para calcular el promedio de las notas de un estudiante.

- Qué cambié: Incluí la cantidad de notas y los pasos principales.
- Por qué: Para que el programa tenga requisitos concretos y fáciles de seguir.
- Qué mejoró: La respuesta puede centrarse en una tarea breve y clara.

## Version 2 
Desarrolla un programa para calcular las notas de varios estudiantes. Para cada estudiante, solicita su nombre y sus notas, calcula el promedio y muestra si aprobó o desaprobó según una nota mínima de 11.

- Qué cambié: Añadí varios estudiantes, sus nombres y una condición para aprobar.
- Por qué: Para incorporar repetición y una decisión basada en el promedio.
- Qué mejoró: La respuesta puede resolver un caso más cercano a una situación real.

## Version 3: prompt final 
Actúa como un programador experto en desarrollo de programas educativos. Crea un programa para registrar y calcular las notas de varios estudiantes. Permite ingresar el nombre de cada estudiante y sus calificaciones. Valida que las notas estén entre 0 y 20. Calcula el promedio ponderado usando los pesos indicados por el usuario y determina si cada estudiante aprobó (promedio mínimo de 11) o desaprobó. Al terminar, muestra un reporte ordenado con el nombre, las notas, el promedio y el resultado de cada estudiante. Explica brevemente cómo funciona el programa e incluye un ejemplo de uso. No uses librerías externas.

- Qué cambié: Agregué al inicio el rol: “Actúa como un programador experto en desarrollo de programas educativos”.
- Por qué: Para orientar al modelo a responder desde la perspectiva de alguien con experiencia en programación educativa.
- Qué mejoró: La respuesta puede ser más clara y adecuada para un programa pensado para estudiantes.

## Componentes del prompt final 
| Componente | Texto de mi prompt | 
|------------|--------------------|
| Rol | Actúa como un programador experto en desarrollo de programas educativos.| 
| Tarea |Crear un programa para registrar y calcular las notas de varios estudiantes. | 
| Datos de entrada | Nombre y calificaciones de cada estudiante, además de los pesos para el promedio ponderado.| 
| Reglas y condiciones | Validar que las notas estén entre 0 y 20 y considerar aprobado a quien obtenga un promedio mínimo de 11.| 
| Resultado esperado |Un reporte ordenado con el nombre, las notas, el promedio y el resultado de cada estudiante. |
| Formato de respuesta | Explicar brevemente cómo funciona el programa e incluir un ejemplo de uso.|
| Restricción| No usar librerías externas.|

## Evaluacion del resultado
| Criterio | Prompt 1 | Prompt 2 | Prompt 3 |
|----------|-------------|---------------------|---------------------|
| Menciona el objetivo del sistema | si|si | si|
| Menciona a los usuarios principales | no|no | si|
| Tiene exactamente 3 funcionalidades | no | no|si|
| Esta en 3 parrafos | no|no |no |
| Lo usaria en un informe real |no |no |si|

## Errores que evite

1. Ser demasiado general: El prompt inicial solo pedía calcular un promedio. Lo hice más específico al indicar que el sistema debe registrar estudiantes, validar notas de 0 a 20 y determinar si aprobaron con un promedio mínimo de 11.

2. No indicar el formato: La solicitud no especificaba cómo presentar los resultados. Añadí que el programa debe mostrar un reporte ordenado con el nombre, las notas, el promedio y el resultado de cada estudiante.