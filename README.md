# Análisis evolutivo del _locus_ de apareamiento en híbridos de _Saccharomyces_

Este repositorio contiene los scripts y materiales computacionales desarrollados para la tesis de licenciatura **«Estrategias bioinformáticas para el analisis de genes multicopia responsables del tipo de apareamiento en genomas híbridos de _Saccharomyces_»**, cuyo objetivo es estudiar la variación y la contribución parental en regiones asociadas con el apareamiento de híbridos interespecíficos de *Saccharomyces cerevisiae* y *S. paradoxus*.

El análisis se centra en la caracterización de las regiones del _locus_ de apareamiento y en el uso de la cobertura de secuenciación para estudiar la representación de secuencias de ambas especies en genomas híbridos.

## Objetivos

- Caracterizar las regiones del _locus_ de apareamiento en híbridos de *S. cerevisiae* y *S. paradoxus*.
- Analizar las secuencias asociadas con los tipos de apareamiento *a* y α, así como su origen parental.
- Evaluar la utilidad de las regiones del _locus_ para distinguir secuencias de ambas especies.
- Estimar y comparar la contribución parental mediante el análisis de cobertura de secuenciación.
- Examinar las diferencias entre híbridos diploides y triploides.

## Organización del repositorio

El repositorio se organiza en dos directorios principales, correspondientes a los ejes de análisis de la investigación.

```text
YeastMat/
├── identidad/
│   └── Análisis de identidad y caracterización de secuencias
├── profundidad/
│   └── Análisis de cobertura y estimación de contribución parental
├── LICENSE
└── README.md
```

**`identidad/`**

Contiene los materiales relacionados con la caracterización de secuencias del _locus_ de apareamiento y el análisis de su utilidad para distinguir el origen de las secuencias en las especies parentales.

**`profundidad/`**

Contiene los materiales relacionados con el análisis de cobertura de secuenciación, la normalización de las estimaciones y la comparación de métodos para inferir la contribución parental.

> La descripción detallada de los archivos y scripts de cada directorio se actualizará de acuerdo con su contenido.

## Fundamento del análisis

El _locus_ de apareamiento de *Saccharomyces* comprende las regiones HML, MAT y HMR. Estas regiones participan en la determinación del tipo de apareamiento y presentan secuencias relacionadas con los alelos *a* y α.

En híbridos interespecíficos, la similitud entre las secuencias de las especies parentales dificulta la asignación inequívoca del origen de algunas regiones genómicas. Por ello, esta investigación combina la caracterización de secuencias con el análisis de cobertura para explorar la contribución de *S. cerevisiae* y *S. paradoxus* en los _loci_ de apareamiento.

## Metodología general

El flujo de trabajo comprende los siguientes componentes:

1. **Obtención y preparación de secuencias de referencia.** Selección de las regiones de interés de los genomas de referencia de ambas especies.
2. **Caracterización de la identidad de las secuencias.** Comparación de las regiones del _locus_ de apareamiento para evaluar su capacidad de distinguir el origen de las secuencias.
3. **Análisis de cobertura.** Cálculo de la cobertura de secuenciación en las regiones de interés y en el genoma.
4. **Normalización y estimación de la contribución parental.** Evaluación de distintos procedimientos para estimar la representación de las secuencias parentales.
5. **Comparación y visualización de resultados.** Evaluación de las estimaciones obtenidas y análisis de las diferencias entre híbridos diploides y triploides.

## Resultados y alcance

La investigación evalúa la utilidad de las regiones del _locus_ de apareamiento para estudiar el origen parental de las secuencias y compara estrategias de estimación basadas en la cobertura.

El análisis también considera las limitaciones de la asignación de origen parental: la capacidad de distinguir secuencias entre especies no implica necesariamente que sea posible identificar un clado o una cepa parental específica.

Las figuras, tablas y resultados cuantitativos se incorporarán a esta sección con referencias a los análisis correspondientes.

## Reproducibilidad

Los requisitos computacionales, las dependencias, los archivos de entrada y las instrucciones de ejecución se documentarán junto con los scripts correspondientes.

Los resultados dependen de los genomas de referencia, los datos de secuenciación y los parámetros utilizados en cada análisis. Por ello, las instrucciones específicas deberán consultarse en los directorios respectivos.

## Información académica

**Título de la tesis:** Estrategias bioinformáticas para el analisis de genes multicopia responsables del tipo de apareamiento en genomas híbridos de _Saccharomyces_

**Institución:** Universidad Nacional Autónoma de México (UNAM), Escuela Nacional de Estudios Superiores, Unidad Morelia.

**Programa:** Licenciatura en Tecnologías para la Información en Ciencias.

**Año:** 2026.

## Licencia

Este proyecto se distribuye bajo los términos de la licencia GNU General Public License v3.0 (GPL-3.0). Consulta el archivo [`LICENSE`](LICENSE) para conocer las condiciones de uso, modificación y distribución del código.
