# ProssDeDatos

Repositorio con una colección de ejercicios básicos de Python para practicar conceptos fundamentales de programación y análisis de datos.

## Contenido

En este repositorio estan los notebooks con ejercicios enfocados en:

- Estructuras de control (condicionales, bucles)  
- Definición y uso de funciones  
- Manejo de variables globales  
- Operaciones con listas y cadenas  
- Diagnóstico y corrección de errores comunes

Todo enfocado al analisis de datos.
Cada notebook incluye comentarios que explican el razonamiento detrás de cada solución.

## Problemas encontrados y cómo se resolvieron

| Libro/Sección | Error detectado | Solución aplicada |
|---------------|------------------|-------------------|
| Libro 8       | La función estaba definida como `sum` en lugar de `add`, lo que generaba conflicto con la función nativa `sum`. | Renombrar la función a `add` para evitar sobrescribir funciones incorporadas. |
| Libro 8 (al final) | Se intentaba usar una variable global que no existía aún, provocando el error `Unresolved reference 'internal_var'`. | Inicializar la variable global antes de usarla: `internal_var = None`. |

## Lo aprendido
 
- Manejo de  listas, conjuntos tuplas, cadenas y diccionarios
- Aplicacion de Bucles, funciones, clases y condiciones

## Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Sergiofbc/ProssDeDatos.git
