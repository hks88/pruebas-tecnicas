# 🧠 Prueba Técnica – Verificador de Heterogramas

## Enunciado

Desarrolla una función en JavaScript que reciba una palabra y determine si es un **heterograma**.

Un **heterograma** es una palabra o frase en la que **ninguna letra del alfabeto se repite**.  
Ignora espacios, signos de puntuación y distingue solo letras (a-z, sin acentos).  

## Requisitos

- Imprimir en consola si el texto es un heterograma o no.
- En caso de **no ser heterograma**, debe mostrar:
- Qué letras se repiten.
- Cuántas veces aparece cada letra repetida.

> ⚠️ Todos los resultados deben ser mostrados en consola.  

---

### Ejemplo 1
```esHeterograma("murciélago");``` → murciélago es un heterograma.

### Ejemplo 2
```esHeterograma("camaleón");``` → camaleón NO es un heterograma; Letras repetidas: a (2)

### Ejemplo 3
```esHeterograma("cristalina");``` → cristalina NO es un heterograma; Letras repetidas: a (2), i (2)

