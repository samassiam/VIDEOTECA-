Videoteca Digital

Este proyecto es una aplicación sencilla en Python que permite analizar una videoteca (lista de películas) y contar cuántos títulos cumplen con ciertos criterios definidos por el usuario.

Descripción

El programa trabaja con una matriz de datos que contiene información de películas, incluyendo:

Título
Año de estreno
Calificación
Género

A partir de estos datos, el usuario puede ingresar:

Una calificación mínima
Un año mínimo

El sistema filtrará las películas que cumplan ambas condiciones y mostrará:

✔ Las películas que cumplen
📊 El total de resultados

⚙️ Funcionamiento

El programa utiliza una función llamada:

contar_titulos(matriz, umbral_calificacion, anio_limite)
🔍 Lógica:
Recorre la matriz de películas
Evalúa cada registro
Verifica si:
calificación >= umbral
año >= año límite
Cuenta y muestra los resultados
🧪 Ejemplo de uso
Entrada:
Ingrese la calificación mínima (ej: 8): 8
Ingrese el año mínimo (ej: 2018): 2018
Salida:
✔ Cumple: Avengers: Endgame | Año: 2019 | Calificación: 9.0
✔ Cumple: Parasite | Año: 2019 | Calificación: 8.6
✔ Cumple: Joker | Año: 2019 | Calificación: 8.5
✔ Cumple: The Batman | Año: 2022 | Calificación: 8.2

===================================
Total de títulos que cumplen: 4
===================================
