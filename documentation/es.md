<!-- ELUCENIA technical documentation · escala-lanss · es · no clinical/professional/rights approval -->

# Escala de dolor LANSS

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-lanss)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### ¿El dolor se siente como una sensación extraña y desagradable en la piel (pinchazos, hormigueo o descargas eléctricas)?

`a1`

### ¿El dolor hace que la piel de la zona dolorosa se vea diferente de lo normal (con manchas, enrojecida o rosada)?

`a2`

### ¿El dolor hace que la piel sea anormalmente sensible al tacto (molestia al rozarla suavemente o con ropa ajustada)?

`a3`

### ¿El dolor aparece de repente, en crisis, sin motivo aparente y estando en reposo (descargas eléctricas o punzadas)?

`a4`

### ¿El dolor da la sensación de que ha cambiado la temperatura de la piel (calor o quemazón)?

`a5`

### Exploración: alodinia (dolor o molestia al rozar con algodón la zona dolorosa, comparada con una zona normal)

`b6`

### Exploración: umbral alterado al pinchazo (un pinchazo con aguja 23G se percibe diferente en la zona dolorosa: más o menos intenso)

`b7`

## Edición del método

LANSS/Bennett 2001: 5 síntomas+2 signos, total 0–24, corte ≥12; portugués brasileño Schestatsky 2011

## Fórmula documentada

Parte A (cuestionario): ítems de 5, 5, 3, 2 y 1 punto. Parte B (examen sensitivo): alodinia 5; umbral a la punción alterado 3. Total 0 a 24; corte ≥12.

## Límites y población

La LANSS combina síntomas con signos obtenidos mediante examen sensitivo para investigar el predominio de un mecanismo neuropático en el dolor crónico. Los ítems de examen no deben tratarse como un simple autoinforme. La validación brasileña citada no certifica la implementación ni nuevas traducciones.

## Referencias

- [Bennett M. The LANSS Pain Scale: the Leeds assessment of neuropathic symptoms and signs. Pain, 2001.](https://doi.org/10.1016/S0304-3959(00)00482-6)

- [Schestatsky P et al. Brazilian Portuguese validation of the Leeds Assessment of Neuropathic Symptoms and Signs for patients with chronic pain. Pain Med, 2011.](https://doi.org/10.1111/j.1526-4637.2011.01221.x)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
