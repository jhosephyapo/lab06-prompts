# Bitacora de prompts 
Laboratorio 06: Fundamentos de Ingenieria de Prompts. 
Herramienta de IA usada: (escribe aqui cual usaste) 
## Ejercicio 2: Tokens y ventana de contexto 
| Texto | Caracteres | Tokens | 
|-------|------------|--------| 
| Los estudiantes programan en Java. |34 | 7| 
| The students program in Java. | 29| 6| 
| desafortunadamente |18 | 4|

## Ejercicio 3: Temperatura
| Temperatura | % de BiblioTec | Nombres en los 5 intentos | 
|-------------|----------------|---------------------------| 
| 0 | 100|BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec | 
| 0.5 |65.3 | BiblioTec, BiblioTec, BiblioTec, BiblioTec, BiblioTec| 
| 1 | 44.5|BiblioTec, LibroYa, PrestaLibro, BiblioTec, LectoGo| 
| 1.8 | 32.2| PrestaLibro, BiblioTec, LibroYa, BiblioTec, LectoGo|

## Ejercicio 4: Prompt vago vs estructurado 
| Criterio | Prompt vago | Prompt estructurado | 
|----------|-------------|---------------------|
| Menciona el objetivo del sistema | si|si | 
| Menciona a los usuarios principales | no|si | 
| Tiene exactamente 3 funcionalidades | no | si| 
| Esta en 3 parrafos | no|si | 
| Lo usaria en un informe real |no |si |

## Ejercicio 5: Anatomia de un prompt
| Componente | Texto de mi prompt | 
|------------|--------------------|
| Rol |Desarrollador Java | 
| Instruccion | clase Producto con los atributos codigo, nombre, precio y stock.| 
| Contexto | Crea un programa en Java para gestionar los productos de  una tienda.| 
| Ejemplo |Usa este estilo para los metodos: getPrecio(), setPrecio(double precio). | 
| Formato | Explica primero la estructura de la clase y luego presenta el codigo Java.|
