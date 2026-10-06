# Retroalimentación — Taller evaluativo 01

**Estudiante:** Angie Carolina Ibarra · **Taller:** Taller evaluativo 01 — Python y estructuras de datos
**Fecha límite:** 2026-10-06 23:59 · **Versión revisada:** commit `397dcbb`

## Nota

| Criterio | Puntos |
|---|---|
| Variables, tipos y operadores (Ej. 1 a 4) | 20 / 20 |
| Condicionales y clasificación (Ej. 5) | 15 / 15 |
| Bucles, acumuladores y control de flujo (Ej. 6 a 8) | 28 / 30 |
| Estructuras de datos nativas (Ej. 9) | 3 / 15 |
| Ejecución sin errores | 5 / 10 |
| Documentación en celdas de texto | 4 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **76 / 100** |
| **Nota (0–5)** | **3.80** |

Este taller aporta **11.4 %** de los 15 % del momento evaluativo.

## 1. Variables, tipos y operadores (20 / 20)
**Lo que hizo bien:**
- Las siete variables del Ejercicio 1 tienen el tipo correcto y lo verificó con `type()`.
- La conversión y los tres errores del Ejercicio 2 salen de operaciones, no de valores escritos a mano.
- El Ejercicio 3 usa solo `//` y `%`; el Ejercicio 4 usa `and` y `not` sin ningún `if`.

## 2. Condicionales y clasificación (15 / 15)
**Lo que hizo bien:**
- La cadena `if` / `elif` / `else` está ordenada de menor a mayor y clasifica la lectura de 41.8 como "Dañina para grupos sensibles".

## 3. Bucles, acumuladores y control de flujo (28 / 30)
**Lo que hizo bien:**
- Ejercicio 6: descarta los dos -999.0 con `continue`, queda con 10 lecturas válidas y promedio 22.55.
- Ejercicio 7: máximo 58.3, mínimo 7.5 y desviación con dos recorridos, sin `max()`, `min()` ni `sum()`.
- Ejercicio 8: el `while` actualiza la concentración y termina (10 horas).

**Lo que puede mejorar:**
- En el Ejercicio 8 no declaró `factor_decaimiento` ni `umbral_buena`; escribió 0.85 y 12.0 directamente en el código.

## 4. Estructuras de datos nativas (3 / 15)
**Lo que puede mejorar:**
- No se hizo lo que pedía el Ejercicio 9: faltan la lista `registros_estaciones` con las tres estaciones (EST-01, EST-02 y EST-03).
- Armó un solo diccionario con datos de la estación del Ejercicio 1, con otras claves y otros datos.
- No desempaquetó las coordenadas en `latitud` y `longitud`, ni calculó el promedio de cada estación con un `for` interno.
- No usó `get` con el valor por defecto "no disponible" para la humedad, ni clasificó cada estación ni imprimió una línea por estación.

## 5. Ejecución sin errores (5 / 10)
**Lo que hizo bien:** todas las celdas corren, en orden, sin errores ni bucles infinitos.
**Lo que puede mejorar:** falta la celda de verificación final, así que no aparece el mensaje "Verificación completada sin errores."

## 6. Documentación en celdas de texto (4 / 5)
**Lo que hizo bien:** cada ejercicio tiene su celda de texto previa y los nombres de variables son claros y en `snake_case`.
**Lo que puede mejorar:** falta la celda inicial con el título del taller, su nombre completo y la fecha; la primera celda solo tiene el enlace de Colab.

## 7. Entrega correcta (1 / 5)
**No siguió la estructura acordada:** el notebook debe estar en la carpeta `ejercicios/` con el nombre exacto `taller-evaluativo-01-calidad-del-aire.ipynb`. Usted lo subió a la raíz del repositorio como `taller_evaluativo_01_calidad_del_aire.ipynb` (con guiones bajos). Sí llegó a tiempo y se ve en GitHub.

## ¿El notebook funciona?
Corre completo sin errores y los resultados de los Ejercicios 1 al 8 coinciden con los esperados. Falta la celda de verificación y el Ejercicio 9 no corresponde a lo pedido.

## Para el próximo taller
- Lea el enunciado completo y compare cada ejercicio con lo que pide antes de entregar; el Ejercicio 9 pedía datos distintos a los que usó.
- Copie la celda de verificación al final del notebook y ejecútela.
- Declare como variables los valores que da el enunciado (por ejemplo, el factor de decaimiento).
- Agregue al inicio una celda con título, nombre completo y fecha.
- Guarde el notebook en `ejercicios/` con el nombre exacto, usando guiones medios.
