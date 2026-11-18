# Entrega de Proyecto Final
### Hito 1
#### Fundamentos de Programación para Análisis Económico · UdeC-EAN

# ============================================================
#  H1 — Propuesta
# Autor: [Tomás Troncoso]      Fecha: [2026-11-17]
# ============================================================

## Pregunta de Investigación
¿Cuál es la elasticidad del valor FOB y el volumen exportado de las distintas 
categorías de vino chileno ante fluctuaciones en el Tipo de Cambio Real (TCR) 
durante los últimos 10 años?

## 📊 Fuentes de Datos
Las bases de datos originales se encuentran en la carpeta `data/raw/`.
**Oficina de Estudios y Políticas Agrarias (ODEPA):** Matriz detallada de comercio exterior. 
 *Fecha de descarga:* 17 de noviembre de 2026. 
 *Enlace:* [https://reportes.odepa.gob.cl/matriz-comex/matriz.do](https://reportes.odepa.gob.cl/matriz-comex/matriz.do)
 
**Banco Central de Chile:** Base de Datos Estadísticos (Tipo de Cambio Real y Dólar Observado).
 *Fecha de descarga:* 17 de noviembre de 2026. 
 *Enlace:* [https://si3.bcentral.cl/Siete/](https://si3.bcentral.cl/Siete/)

### Justificación de Herramientas (Reparto R/Stata)
**Stata:** Se utiliza de forma exclusiva para las fases de limpieza (`01_limpiar.do`) 
y estimación (`02_modelar.do`) debido a su eficiencia y estabilidad en la gestión 
de bases de datos, además de su robustez base para pruebas de diagnóstico en series de tiempo.

**R:** Se emplea en la fase de reporte (`03_reporte.R`) para aprovechar librerías 
gráficas como `ggplot2` y de tabulación como `modelsummary`.



```markdown
## Declaración de autoría humana y uso de tecnologías digitales emergentes
- Integrantes y responsabilidades: Tomás Troncoso (tranajo individual)
- Herramienta(s) de IA utilizada(s): Gemini (3.1 Pro) (o «ninguna»)
- Para qué se usaron: En el Hito 1 se uso para explorar alternativas 
de temas y en la redacción del pdf subido (sea específico por tarea)
- Qué hizo el equipo: Búsqueda, filtrado y descarga de datos, definición de la 
pregunta de investigación, diseño de la especificación del modelo y de la
estructura del informe y sus fases.
- Verificación: confirmamos que entendemos y podemos explicar todo lo que
entregamos, incluido cada línea de código.


```