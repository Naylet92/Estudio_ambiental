# Estudio ambiental
En este repositorio aparece el paso a paso del procesamiento de imágenes para realizar una evaluación comparativa de la perdida del hábitat de ANP y no ANP de Jalisco

Códigos de áreas (nomenclatura de préfijos):
* **NCL** - Nevado de Colima
* **SGB** - San Gabriel
* **CHM** - Chamela
* **PPR** - Púnta Perula
* **QUI** - Sierra de Quila
* **SVE** - Sierra Verde

Tipos de archivos:
* **.ipynb** - Jupiter notebook con codigo de Python ejecutable, comentarios y resultados, formato de Google Colab
* **.md** - Markdown, archivos de comentarios
* **.tif** - formato raster GeoTIFF
Nota: en los archivos .ipynb se recomienda no incluir los resultados de visualización interactiva de mapas (widgets), debido a errores de visualización en GitHub que suelen ocurrir en caso de incluir los widgets

Nomenclatura de archivos (AAA - código de área):
* **AAA_plantilla.ipynb** - plantilla con definiciones de areas y poligonos
* **AAA_L_20XX.ipynb** - seleccion y preprocesamienot de datos Landsat según fecha
* **AAA_L_indices_20XX.ipynb** - generación de los indices de vegetación y transformaciones lineales estándares (Tasseled Cap)
