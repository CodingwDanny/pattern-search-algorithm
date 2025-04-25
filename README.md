Búsqueda de Patrón en Texto con Diagrama de Flujo

Introducción

Este proyecto implementa un algoritmo simple de búsqueda de patrones dentro de un texto. A través de pasos bien definidos, un diagrama de flujo y pseudocódigo, se logra detectar si una palabra o fragmento específico existe en un texto más grande.

---

Pasos del algoritmo

1. Ingresar texto y patrón
2. Iniciar `i` en 0 y `encontrado` en FALSO
3. Mientras aún haya texto por recorrer:
   - Extraer subcadena
   - Comparar con el patrón
   - Si coinciden, marcar como encontrado y salir
   - Si no, incrementar `i` y repetir
4. Mostrar si el patrón fue encontrado o no

---

 Diagrama de flujo


---

Pseudocódigo

Definir texto
Definir patron
Definir i ← 0
Definir encontrado ← FALSO

Mientras i <= longitud(texto) - longitud(patron) Hacer
    subcadena ← texto[i : i + longitud(patron)]

    Si subcadena == patron Entonces
        encontrado ← VERDADERO
        Salir del bucle
    FinSi

    i ← i + 1
FinMientras

Si encontrado Entonces
    Escribir "Patrón encontrado"
Sino
    Escribir "Patrón NO encontrado"
FinSi

---

 Conclusión

Este proyecto fue una gran oportunidad para aplicar y entender el proceso completo de desarrollo de un algoritmo: desde la idea, el análisis lógico y visual con un diagrama de flujo, hasta su implementación con pseudocódigo. Aprendí a pensar como un programador y cómo estructurar una solución clara y replicable.

