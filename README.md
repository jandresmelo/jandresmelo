# Bienvenido a mi GitHub

## Acerca de mí
¡Hola! Soy Jorge, un especialista en estadística aplicada apasionado por el análisis de datos y la ciencia de datos en general. Actualmente, me desempeño en la extracción, transformación y mejora de la calidad de los datos contenidos en bases de datos PostgreSQL. Mi formación abarca diversas áreas del conocimiento, incluyendo la geografía, cartografía, ambiente y ordenamiento territorial, con un énfasis particular en el análisis de datos.

Como profesional especializado en estadística, tengo un fuerte interés en integrarme a equipos de desarrollo y contribuir en actividades como la limpieza, integración, procesamiento y modelado de datos. Además, me especializo en el análisis descriptivo y la construcción de dashboards, utilizando tanto bases de datos SQL como NoSQL. Mi experiencia incluye el manejo de lenguajes de programación como R, Python y JavaScript, así como el uso de herramientas y software como Google Data Studio, Tableau, QGIS, ArcGIS, Excel y Power BI para proporcionar información precisa y representativa.

Estoy comprometido con aprovechar mis habilidades y conocimientos para ayudar a generar insights significativos y soluciones eficaces en el campo del manejo de datos.


### Proyecto 1. Buscador

- **Descripción**:  
  El **Buscador Litoteca Nacional** es una herramienta desarrollada para facilitar la **consulta, validación y trazabilidad** de información técnica y documental relacionada con **pozos, proyectos y productos** almacenados en la Litoteca Nacional.  
  Se apoya en una base de datos **PostgreSQL**, alimentada automáticamente mediante procesos de extracción de metadatos, para ofrecer:

  - Búsquedas rápidas por identificadores únicos (UWI, UPI)
  - Filtros por tipo de producto (PDF, imágenes, registros)
  - Estadísticas detalladas del repositorio
  - Detección de inconsistencias estructurales en los archivos

  El sistema cuenta con **autenticación de usuarios** y se ejecuta desde la **intranet institucional**.

- **Tecnologías Utilizadas**:
  - `Python 3.12`
  - `Flask` (Web Framework)
  - `PostgreSQL` (Base de datos relacional)
  - `psycopg2` (Conexión SQL con Python)
  - `HTML5 + CSS3` (Interfaz de usuario)
  - `Jinja2` (Motor de plantillas)
  - `Visual Studio Code` + `Conda` (entorno de desarrollo)

- **Enlace al Proyecto**:  
  [Buscador](https://github.com/jandresmelo/BUSCADOR.git)

- **Tema**:  
  Exploración y localización de archivos mediante metadatos generados automáticamente, con enfoque en la eficiencia, trazabilidad y calidad de datos técnicos.


### Proyecto 2. Extraccion de datos - Metadata Harvesting
- **Descripción**: Este proyecto tiene como objetivo automatizar la extracción de metadatos de archivos y directorios, verificando su existencia en una base de datos PostgreSQL. El proceso incluye la validación de identificadores únicos de pozos (UWI), la exclusión de archivos innecesarios o temporales, y la inserción eficiente de los datos en la base de datos en lotes, utilizando técnicas de paralelismo para maximizar el rendimiento.
- **Tecnologías Utilizadas**: PostgreSQL para la gestión de la base de datos, SQL para consultas eficientes y Python para la automatización del procesamiento de archivos, incluyendo bibliotecas como psycopg2 para la conexión a bases de datos y concurrent.futures para el procesamiento en paralelo.
- **Enlace al Proyecto**: [Extraccion de datos en carpeta](https://github.com/jandresmelo/FILEPROPEXTRACTOR.git)
- **Tema**: Automatización y optimización de procesos de extracción de datos en archivos y directorios, con validación y registro de errores.

### Proyecto 2. Extracción de Metadatos de Archivos
- **Descripción**: HEste proyecto automatiza la extracción de metadatos de archivos y directorios en un repositorio, almacenando la información en una base de datos PostgreSQL. Se excluyen archivos temporales y se procesan los datos en lotes mediante paralelismo con múltiples hilos, optimizando el rendimiento y el tiempo de procesamiento.
- **Tecnologías Utilizadas**: PostgreSQL para la gestión de datos, SQL para consultas y Python con librerías como psycopg2 y concurrent.futures para el procesamiento paralelo de archivos.
- **Enlace al Proyecto**: [Extracción de metadatos en carpetas](https://github.com/jandresmelo/METADATAHARVESTER.git)
- **Tema**: Extraccion de datos en archivos.

### Proyecto 3. Validador Inventario
- **Descripción**: Herramienta de gestión de inventarios diseñada para facilitar el control y administración de bienes devolutivos en una litoteca. La aplicación permite realizar búsquedas, inserciones y actualizaciones de registros utilizando una base de datos PostgreSQL y una interfaz gráfica amigable desarrollada en Tkinter.
- **Tecnologías Utilizadas**: Python, Tkinter, PostgreSQL, psycopg2, openpyxl.
- **Enlace al Proyecto**: [Verificación Inventario Bienes Devolutivos](https://github.com/jandresmelo/INVENTARIO_VALIDATOR.git)
- **Tema**: Gestión de Inventarios / Control de Bienes

### Proyecto 4. union pdf por listado xlsx
- **Descripción**: Este proyecto tiene como objetivo combinar varios archivos PDF basándose en un listado proporcionado en un archivo XLSX. La funcionalidad permite automatizar el proceso de combinación de PDFs en función de criterios establecidos en el documento Excel, optimizando así el manejo de grandes volúmenes de información en formato PDF.
- **Tecnologías Utilizadas**: El proyecto utiliza tecnologías para la manipulación de archivos PDF y el procesamiento de datos en Excel. Se emplean bibliotecas como PyPDF2 para la manipulación de PDFs y pandas para la lectura y manejo de archivos XLSX.
- **Enlace al Proyecto**: [join pdfs listado xlsx](https://github.com/jandresmelo/UNION_PDF.git)
- **Tema**: Automatización en la combinación de PDFs basada en listados de Excel.



## Contáctame
¡Si estás interesado en colaborar en alguno de mis proyectos o simplemente quieres ponerte en contacto, no dudes en hacerlo!

- **Email**: [jandresmelo@gmail.com](mailto:jandresmelo@gmail.com )
- **LinkedIn**: [jandresmelo](https://www.linkedin.com/in/jandresmelo/)


¡Gracias por visitar mi GitHub!

