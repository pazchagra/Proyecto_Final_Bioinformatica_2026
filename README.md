# Proyecto_Final_Bioinformatica_2026
Reanálisis de datos transcriptómicos mediante herramientas bioinformáticas para el estudio de alteraciones de expresión génica asociadas a tics y síndrome de Tourette.

En este proyecto  se hizo un reanálisis bioinformático independiente a partir de una selección de datos públicos de RNA-seq provenientes de un estudio sobre trastornos por tics y síndrome de Tourette.

Se seleccionaron seis muestras del estudio original, correspondientes a tres pacientes y tres controles sanos. A partir de las lecturas crudas obtenidas del repositorio SRA del NCBI, se desarrolló un flujo de procesamiento bioinformático en Galaxy Europe, que permitió construir una matriz propia de expresión génica.

Posteriormente, se realizó un análisis exploratorio de los perfiles transcriptómicos mediante Python, utilizando herramientas estadísticas y de aprendizaje automático, como PCA y K-means, para investigar similitudes y posibles patrones de agrupamiento entre pacientes y controles.

Finalmente, los resultados se compararon con la matriz original del artículo, compuesta por 48 muestras, para evaluar las similitudes y diferencias entre ambos conjuntos de datos.

Dado que se trabajó con un número reducido de muestras, los resultados tienen un carácter exploratorio y no buscan reproducir la totalidad del estudio original.

**Referencias**

- Artículo científico: Patel et al. (2026). Peripheral blood transcriptomics identifies cohesin–chromatin and immune dysregulation in tics and Tourette syndrome.

- https://doi.org/10.3389/fneur.2026.1730761

- Anotación génica: GENCODE v50.

- https://www.gencodegenes.org/human/release_50.html

