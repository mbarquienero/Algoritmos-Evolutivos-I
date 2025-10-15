# Algoritmos Evolutivos I — Trabajo Final
**Tema:** Mochila 0/1 para equipamiento de alpinismo resuelta con Algoritmo Genético (GA).

## Descripción breve
Este trabajo modela el armado de una mochila de alpinismo como un problema de **mochila 0/1**. Cada ítem del catálogo tiene **peso (kg)** y **utilidad**. El objetivo es seleccionar el subconjunto que **maximiza utilidad** respetando una **capacidad**.  
Se implementó un **Algoritmo Genético** con representación binaria, selección por ruleta, cruce de 1 punto, mutación por bit y elitismo.  
Para reflejar criterios del dominio (seguridad y coherencia técnica) se usaron **restricciones suaves** en la función de aptitud: bonificaciones por ítems críticos (agua, comida, cuerda, botiquín, navegación), penalizaciones por faltantes, dependencias mínimas (p. ej., ATC→cuerda, cuerda→arnés/casco) y penal por **sobrepeso**.
