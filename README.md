# Desafío Práctico #2 - Control de Combustible (C#)

**Universidad Don Bosco (UDB) - Ciclo 02-2026**  
**Asignatura:** Programación Estructurada (PRE104)  
**Docente:** Mg. Dennis Pérez  
**Integrantes:**
- Geovany Mejía [MM250639]
- Josué Tábora [TF263310]

---

## 📌 Descripción del Proyecto
Aplicación de consola en C# (.NET 8.0) para la gestión y análisis de rendimiento de combustible en una flota de transporte interurbano (5 microbuses).

El sistema implementa:
1. **Captura y validación robusta** con bucles while y Double.TryParse seguro contra entradas no numéricas o menores o iguales a cero.
2. **Estructuras de almacenamiento contiguo** mediante arreglos unidimensionales paralelos (unidades, kilometros, galones).
3. **Modularización estructurada**:
   - `MostrarBienvenida()`: Pantalla de inicio con carátula institucional.
   - `CalcularRendimiento(km, gal)`: Función matemática (km / gal).
   - `ClasificarRendimiento(rend)`: Clasificación diagnóstica (Óptimo / Alto Consumo).
   - `MostrarReporte(unidades, kilometros, galones)`: Procedimiento que procesa e imprime la tabla alineada, el acumulador total de galones y la búsqueda del peor rendimiento.

---

## 📖 Guía Interactiva de Estudio y Defensa
Este repositorio incluye el archivo `guia_defensa_desafio2.html`:
- **Mega Glosario y Diccionario Técnico:** Explicación exhaustiva de cada palabra clave, tipo de dato, modificador y método del código en paleta de colores académica.
- **Desglose Sección por Sección (1 a 13):** Con analogías de la vida real, ejemplos aislados y respuestas clave ante preguntas del docente.
- **Evidencias Formales:** Referencias cruzadas directas a las guías oficiales del laboratorio (Guías 6, 7, 8 y 9).
- **Diagramas Interactivos:** Permite alternar entre mapa de memoria/traza y **Diagramas de Flujo Estándar** de inicio a fin.

---

## 🚀 Compilación y Ejecución
```bash
dotnet build
dotnet run
```
