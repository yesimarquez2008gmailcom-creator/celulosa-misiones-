# Exportación de celulosa de Misiones (2020-2025)

Proyecto de **Comercio Exterior**. Análisis de las exportaciones de celulosa (pasta para papel) de la provincia de Misiones, Argentina, entre 2020 y 2025, y de los cambios en derechos de exportación, reintegros y Draw Back que las rodearon.

- **Autora:** Yesica Adriana Marquez
- **Carrera:** Comercio Exterior
- **Sitio web publicado (Netlify):** [https://celulosamisiones.netlify.app/](https://celulosamisiones.netlify.app/)
- **Archivos en Google Drive (2 Excel y 1 Word):** [Carpeta de Drive](https://drive.google.com/drive/folders/1kf6JNJjZs-Tl4Chumv-0yEhEmlAd5DhO)
- **Repositorio en GitHub:** [https://github.com/yesimarquez2008gmailcom-creator/celulosa-misiones-](https://github.com/yesimarquez2008gmailcom-creator/celulosa-misiones-)

---

## 1. Qué se hizo, en resumen

La consigna pedía crear un sitio web a partir del análisis de dos archivos Excel y un archivo Word, con datos de al menos cinco años, usando solo herramientas permitidas. Este proyecto hizo lo siguiente:

1. Reunió datos cuantitativos de exportaciones, destinos, derechos de exportación y reintegros en **dos Excel**.
2. Reunió los cambios en decretos y resoluciones sobre Draw Back y Reintegros en **un Word**.
3. Contrastó esos datos con los informes originales del IPEC Misiones y con los textos oficiales de las normas, y corrigió lo que no tenía respaldo.
4. Cargó los tres archivos en Cuaderno Gemini para consultarlos y hizo un **análisis conjunto** de los tres archivos con Claude.
5. Generó el **sitio web** (`index.html`) a partir de ese análisis y lo publicó en Netlify.
6. Documentó todo en este repositorio.

## 2. Herramientas utilizadas

Solo se usaron las herramientas permitidas por la consigna. No se usó ChatGPT, DeepSeek, Grok ni ninguna otra inteligencia artificial.

| Herramienta | Para qué se usó |
|---|---|
| Perplexity | Buscar y reunir los datos y las normas de cada Excel y del Word |
| Cuaderno Gemini | Organizar los tres archivos como fuentes, consultarlos y contrastar las cifras del análisis |
| Claude | Contrastar y corregir los datos, hacer el análisis conjunto, generar los Excel y el Word, y armar el HTML |
| Google Drive | Guardar los dos Excel y el Word |
| Netlify | Publicar el sitio web |
| GitHub | Este repositorio, con el código y la documentación |

## 3. Paso 1: recopilación de datos con Perplexity

Se hicieron tres consultas a Perplexity, una por archivo. Sus respuestas se guardaron como PDF y con ellas se armaron los Excel y el Word.

**Consulta 1, exportaciones (Excel 1):**

> Necesito datos estadísticos anuales de exportaciones de celulosa (pasta química de madera, posiciones NCM 4702 y 4703) de la provincia de Misiones, Argentina, del período 2020 a 2025. Armá una tabla año por año con: valor FOB en USD, toneladas exportadas y precio promedio por tonelada. Citá la fuente de cada dato (INDEC, Ministerio de Economía u otra oficial) e indicá claramente qué datos son estimaciones o no están disponibles a nivel provincial.

**Consulta 2, destinos, derechos de exportación y reintegros (Excel 2):**

> Necesito una tabla anual 2020-2025 de los principales países de destino de las exportaciones de celulosa de Misiones, Argentina, con participación porcentual y valor FOB por destino. Agregá también, año por año, el porcentaje de reintegros y de derechos de exportación aplicables a la celulosa. Citá fuentes oficiales y marcá lo que sea estimado.

**Consulta 3, marco normativo (Word):**

> Listá cronológicamente, entre 2020 y 2025, los decretos y resoluciones de Argentina que modificaron el régimen de Draw Back y de Reintegros a la exportación, con foco en su aplicación a la celulosa y al papel. Para cada norma indicá: número, fecha, organismo emisor, qué cambió y cómo impacta al exportador. Incluí el enlace a la fuente oficial (Boletín Oficial).

## 4. Los tres archivos de datos

Están en este mismo repositorio, con los nombres que se indican a continuación.

### Excel 1: exportaciones de celulosa de Misiones

`Excel1_Exportaciones_Celulosa_Misiones_2020-2025.xlsx`

- **Hoja `Exportaciones`:** valor FOB, toneladas, precio por tonelada (fórmula), variaciones anuales (fórmulas), fuente y estado de verificación de cada año.
- **Hoja `Resumen`:** indicadores calculados con fórmulas (total acumulado, promedio anual, variación 2020-2025, precio ponderado) y un gráfico de barras.
- **Hojas `Fuentes` y `Notas`:** enlaces a los informes y aclaraciones metodológicas.

### Excel 2: destinos, derechos de exportación y reintegros

`Excel2_Destinos_y_Reintegros_Celulosa_Misiones.xlsx`

- **Hoja `Destinos`:** rangos de participación de Brasil, China y Estados Unidos por año (estimados, salvo Brasil y China de 2022) y el FOB total de cada año.
- **Hoja `DE y Reintegros`:** lo que respondió Perplexity sobre derechos de exportación y reintegros, comparado con lo que se pudo verificar, con un estado por año.
- **Hoja `Normas verificadas`:** 11 normas leídas contra el texto oficial, con su relación con la celulosa y el enlace.
- **Hojas `Fuentes` y `Notas`:** fuentes y advertencias.

### Word: marco normativo del Draw Back y los Reintegros

`Word_Marco_Normativo_DrawBack_Reintegros_Celulosa.docx`

- Contexto de ambos regímenes y de los derechos de exportación.
- Cronología de **12 normas** (2020-2025). Cada una indica fecha, organismo, qué cambió, su relación con la celulosa y el enlace.
- Cuadro resumen del impacto de cada norma.
- Tabla de qué está confirmado año por año sobre el derecho de exportación.
- Observaciones, limitaciones y fuentes.

## 5. Verificación y correcciones

Las respuestas de Perplexity se contrastaron con los informes originales del IPEC Misiones y con los textos oficiales de los decretos. Se corrigió lo siguiente:

| Tema | Lo que decía Perplexity | Corrección |
|---|---|---|
| FOB 2020 | USD 96,5 M | USD 97,66 M, según el IPEC |
| FOB total de los destinos | Rangos estimados que no coincidían con la serie de exportaciones | Se usan los valores del IPEC y las estimaciones quedan como nota |
| D.E. de 4,5% en 2020 | Aplicable desde 2020 | Rige desde el 01/01/2021 (Decreto 1060/2020) |
| D.E. de 0% en 2024 | Aplicable en 2024 | Sin respaldo; la baja verificada es de enero de 2025 (Decreto 38/2025, posición 4703.11.00) |
| Reintegro de 4,5% en todo el período | Aplicable todos los años | No se pudo confirmar en ninguna norma |
| Decretos 506/2023, 9/2024 y 557/2024 | Con efecto sobre pasta de celulosa | Se refieren a lácteos; sin vínculo verificado con la celulosa |
| Decreto 557/2023 | Redujo a 0% el D.E. y los reintegros de la celulosa | Aprueba la NCM (VII Enmienda) con sus reintegros; no fija 0% para la celulosa |
| Enlaces al Boletín Oficial | Algunos incorrectos | Se reemplazaron por enlaces confirmados |

**Pendiente:** no se pudieron consultar los anexos de los decretos 1060/2020 y 305/2025 ni el Anexo I del 557/2023. Falta confirmar en ellos las posiciones 4703.21.00 y 4703.29.00 (pastas blanqueadas), que son las que más exporta Misiones.

## 6. Paso 2: organización de fuentes y análisis

### Cuaderno Gemini

Los tres archivos del proyecto se cargaron como fuentes en un cuaderno de Cuaderno Gemini:

- `Excel1_Exportaciones_Celulosa_Misiones_2020-2025.pdf`
- `Excel2_Destinos_y_Reintegros_Celulosa_Misiones.pdf`
- `Word_Marco_Normativo_DrawBack_Reintegros_Celulosa.docx`

Los dos Excel se cargaron como copias en PDF, con el mismo contenido de todas sus hojas, porque el cuaderno no aceptó los archivos `.xlsx` ni las hojas de cálculo de Google. Los Excel originales (`.xlsx`) son los entregables y están en este repositorio y en Drive. Las copias en PDF también están en este repositorio.

Con las tres fuentes seleccionadas se le hizo esta consulta al cuaderno: *"¿En qué años cayó el valor exportado de celulosa y cuánto? ¿Qué pasó con las toneladas y el precio por tonelada en esos años?"*. El cuaderno respondió que el valor cayó en 2022 y en 2023. Para 2022 dio estas cifras, que coinciden con el Excel 1 y con el análisis hecho con Claude:

| Dato de 2022 | Respuesta del cuaderno |
|---|---|
| Valor FOB | Cayó 9,5%, de USD 140.986.513 a USD 127.547.352 |
| Toneladas | Bajaron 23,3%, de 196.226 a 150.459 |
| Precio por tonelada | Subió de 718,5 a 847,7 USD/t |

### Análisis conjunto con Claude

El análisis completo está en [`Analisis_Conjunto_Celulosa_Misiones.md`](Analisis_Conjunto_Celulosa_Misiones.md). Sus resultados principales:

| Año | FOB (USD M) | Var. anual | Toneladas | USD/t |
|---|---|---|---|---|
| 2020 | 97,7 | - | s/d | s/d |
| 2021 | 141,0 | +44,4% | 196.226 | 718 |
| 2022 | 127,5 | -9,5% | 150.459 | 848 |
| 2023 | 103,3 | -19,0% | s/d | s/d |
| 2024 | 120,6 | +16,7% | 159.301 | 757 |
| 2025* | 148,3 | +23,0% | 196.006 | 756 |

*Dato provisorio. s/d = sin dato provincial publicado.

1. **El valor exportado creció 51,8% entre 2020 y 2025** (8,7% anual), con dos caídas seguidas en 2022 y 2023. El acumulado fue de USD 738 M.
2. **La caída de 2022 fue de volumen:** el precio por tonelada subió 18% y las toneladas bajaron 23,3%.
3. **El crecimiento de 2025 vino todo del volumen:** el precio no cambió y las toneladas subieron 23,0%.
4. **La celulosa es entre el 27% y el 30% de las exportaciones de Misiones** en los años con dato (IPEC).
5. **Los destinos habrían cambiado:** Brasil pierde peso y Estados Unidos lo gana. Son estimaciones y deben leerse como tendencia.
6. **Marco normativo:** el derecho de exportación fue de 4,5% desde 2021 (probable para la celulosa) y bajó a 0% en enero de 2025 para la posición 4703.11.00. La coincidencia con el crecimiento de 2025 no prueba una relación de causa.

## 7. Paso 3: sitio web

El sitio es un único archivo, [`index.html`](index.html), generado con Claude a partir del análisis. No depende de librerías externas: los gráficos son SVG dibujados con JavaScript propio, y solo se cargan tipografías desde Google Fonts.

**Secciones:**

1. **Portada:** gráfico de anillos, como los de un tronco. Cada anillo es un año y su grosor indica el valor exportado. Incluye cuatro datos clave.
2. **Evolución:** barras del valor FOB anual, con la variación de cada año.
3. **Precio y volumen:** toneladas y precio por tonelada, con los años sin dato marcados y la tabla que explica cada variación.
4. **Peso provincial:** la celulosa como parte de las exportaciones totales de Misiones.
5. **Destinos:** rangos estimados, con un aviso de que no son datos oficiales.
6. **Normas:** línea de tiempo de las 12 normas, con filtro para ver solo las que pueden afectar a la celulosa, y tabla de qué está confirmado año por año.
7. **Método y límites** y **fuentes.**

**Decisiones de diseño:**

- Los títulos de cada sección enuncian el hallazgo, en lugar de nombrar un tema.
- Lo estimado y lo provisorio se distinguen siempre con trama, y los años sin dato se marcan con "s/d".
- Los gráficos se pueden recorrer con teclado, muestran el detalle al pasar el cursor o tocar, y tienen tablas de datos como alternativa.
- El diseño se adapta al celular y respeta la preferencia de reducir movimiento.

**Para verlo en tu computadora:** abrir `index.html` con un navegador. No hace falta instalar nada.

## 8. Paso 4: publicación en Netlify

El sitio se publicó en Netlify subiendo la carpeta con el archivo `index.html`.

**Enlace:** [https://celulosamisiones.netlify.app/](https://celulosamisiones.netlify.app/)

## 9. Paso 5: estructura del repositorio

```
.
├── README.md                                              Este archivo
├── index.html                                             Código del sitio web
├── Excel1_Exportaciones_Celulosa_Misiones_2020-2025.xlsx  Datos de exportaciones
├── Excel2_Destinos_y_Reintegros_Celulosa_Misiones.xlsx    Destinos, derechos de exportación y reintegros
├── Word_Marco_Normativo_DrawBack_Reintegros_Celulosa.docx Marco normativo
├── Analisis_Conjunto_Celulosa_Misiones.md                 Análisis conjunto
├── Excel1_Exportaciones_Celulosa_Misiones_2020-2025.pdf   Copia en PDF, cargada en el cuaderno
└── Excel2_Destinos_y_Reintegros_Celulosa_Misiones.pdf     Copia en PDF, cargada en el cuaderno
```

**Enlaces:**

- Sitio publicado en Netlify: [https://celulosamisiones.netlify.app/](https://celulosamisiones.netlify.app/)
- Archivos guardados en Google Drive: [Carpeta de Drive](https://drive.google.com/drive/folders/1kf6JNJjZs-Tl4Chumv-0yEhEmlAd5DhO)
- Repositorio en GitHub: [https://github.com/yesimarquez2008gmailcom-creator/celulosa-misiones-](https://github.com/yesimarquez2008gmailcom-creator/celulosa-misiones-)

## 10. Limitaciones

- Faltan las toneladas de 2020 y 2023: no están publicadas a nivel provincial.
- El dato de 2025 es provisorio.
- Los destinos son estimaciones de Perplexity. Los datos por provincia, producto y país no se publican completos, porque el INDEC protege la información cuando hay pocos exportadores.
- El derecho de exportación de 2021 a 2024 es probable, pero no está confirmado por posición arancelaria. El reintegro no está confirmado.
- La Resolución 212/2022 no se contrastó con su texto oficial.
- Los datos no permiten afirmar que la baja del derecho de exportación de 2025 haya causado el crecimiento de ese año.

## 11. Cumplimiento de la consigna

- [x] Dos archivos Excel con datos de al menos cinco años (2020-2025).
- [x] Un archivo Word con los cambios en decretos y resoluciones sobre Draw Back y Reintegros.
- [x] Archivos guardados en Google Drive personal
- [x] Fuentes organizadas en Cuaderno Gemini
- [x] Análisis realizado con Claude.
- [x] Código HTML generado con Claude.
- [x] Sitio publicado en Netlify
- [x] Repositorio de GitHub con README que explica cada tema.
- [x] Solo se usaron herramientas permitidas.

## 12. Fuentes principales

- IPEC Misiones: [Exportaciones 2021-2022](https://www.ipec.misiones.gov.ar/wp-content/uploads/2023/05/IPEC-Misiones-Exportaciones-A%C3%B1os-2021-2022.pdf) y [Exportaciones 2025](https://www.ipec.misiones.gov.ar/wp-content/uploads/2026/05/IPEC_Misiones_Exportaciones-2025.pdf).
- Ministerio de Economía: [Exportaciones provinciales 2023](https://www.argentina.gob.ar/sites/default/files/exportaciones_provinciales-2023.pptx.pdf) e [Informe productivo de Misiones](https://www.argentina.gob.ar/sites/default/files/misiones_06_2023.pdf).
- Normas: [Decreto 1060/2020](https://www.argentina.gob.ar/normativa/nacional/decreto-1060-2020-345886/texto), [Decreto 38/2025](https://www.cira.org.ar/es/servicios/normativas-servicios/decreto/decreto-38-2025/) y su [Anexo I](https://www.cira.org.ar/wp-content/uploads/anexo_7291708_1.pdf), [Decreto 305/2025](https://www.argentina.gob.ar/normativa/nacional/decreto-305-2025-412414/texto) y [Resolución General 5792/2025](https://www.boletinoficial.gob.ar/detalleAviso/primera/334907/20251125).
- La lista completa de normas y enlaces está en el Word y en la hoja `Normas verificadas` del Excel 2.
