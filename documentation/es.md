<!-- ELUCENIA technical documentation · cts-6 · es · no clinical/professional/rights approval -->

# CTS-6 (síndrome del túnel carpiano)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/cts-6)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Entumecimiento predominante o exclusivo en el territorio del nervio mediano

`dorm`

### Entumecimiento nocturno

`noturna`

### Atrofia y/o debilidad de la musculatura tenar

`atrofia`

### Prueba de Phalen positiva

`phalen`

### Pérdida de discriminación de dos puntos (\> 6 mm)

`dpp`

### Signo de Tinel positivo sobre el túnel carpiano

`tinel`

## Edición del método

CTS-6/Graham 2006: 6 criterios ponderados de túnel carpiano; exploración clínica

## Fórmula documentada

Sume: adormecimiento mediano 3,5; nocturno 4; atrofia/debilidad tenar 5; Phalen positivo 5; pérdida de discriminación de dos puntos 4,5; Tinel positivo 4. Total 0–26.

## Límites y población

El desarrollo Graham 2006 utilizó consenso de expertos e historias de casos que combinaban criterios clínicos; la validación descrita en el resumen comparó las probabilidades del modelo con los juicios de otro panel. Este diseño no establece por sí solo el rendimiento frente a pruebas electrofisiológicas en cada población clínica. La puntuación de seis ítems, su punto de corte y el intervalo de edad deben comprobarse en el método completo.

## Referencias

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

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

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

Baja probabilidad de síndrome del túnel carpiano (por debajo de aproximadamente el 25%)

Considere diagnósticos alternativos (radiculopatía cervical, polineuropatía).


### 2

Probabilidad intermedia (entre aproximadamente el 25% y el 80%)

La electroneuromiografía tiene más valor en este rango.


### 3

Probabilidad intermedia (entre aproximadamente el 25% y el 80%)

La electroneuromiografía tiene más valor en este rango.


### 4

Alta probabilidad de síndrome del túnel carpiano (aproximadamente el 80% o más)

En este rango, la electroneuromiografía rara vez cambia el diagnóstico clínico.

