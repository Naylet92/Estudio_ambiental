# Estudio ambiental
En este repositorio aparece el paso a paso del procesamiento de imágenes para realizar una evaluación comparativa de la perdida del hábitat de ANP y no ANP de Jalisco

### Códigos de áreas (nomenclatura de préfijos):
* **NCL** - Nevado de Colima
* **SGB** - San Gabriel
* **CML** - Chamela
* **PRL** - Punta Perula
* **QLA** - Sierra de Quila
* **SVD** - Sierra Verde

### Tipos de archivos:
* **.ipynb** - Jupiter notebook con codigo de Python ejecutable, comentarios y resultados, formato de Google Colab
* **.md** - Markdown, archivos de comentarios
* **.tif** - formato raster GeoTIFF

**Nota:** en los archivos .ipynb se recomienda no incluir los resultados de visualización interactiva de mapas (widgets), debido a errores de visualización en GitHub que suelen ocurrir en caso de incluir los widgets

**Nota:** Al reubicar el archivo en otra carpeta en GitHub o renombrar, para posibilidad de abrirlo en Colab sin necesidad de una descarga manual a Google Drive se requiere actualizar la ruta en Colba Bage en la parte superior del archivo .ipynb

### Nomenclatura de archivos (AAA - código de área):
* **AAA_plantilla.ipynb** - plantilla con definiciones de area de estudio y rectangulo envolvente BBOX en cada caso
* **AAA_L_20XX.ipynb** - seleccion y preprocesamienot de datos Landsat por fecha
* **AAA_L_indices_20XX.ipynb** - generación de los indices de vegetación y transformaciones lineales estándares (Tasseled Cap)
* **AAA_NDVI_Graficas.ipynb** - generación de graficas de dinamica mensual de NDVI en 4 periodos 2000-2005, 2005-2010, 2010-2015, 2015-2020 en las zonas de muestreo. Proposito es presentr el comportamiento del índice a lo largo de tiempo en el contexto distintos tipos de cobertura de suelo y demostrar compatibilidad de valores calculados con los fuentes heterogeneos (L5, L7, L8, L9)

### Archivos auxiliares (sin relación con áreas de estudio elegidos):
* **Delimitación_del_Área_de_Tapalpa.ipynb** - ensayo preliminar sobre la dinamica temporal del índice NDVI

