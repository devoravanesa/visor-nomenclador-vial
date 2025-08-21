# Visor Institucional - Red Provincial de Caminos de Santa Cruz
## Descripción
Esta herramienta permite visualizar, consultar y exportar información sobre la red vial de la provincia de Santa Cruz. Está orientado a profesionales, organismos públicos y ciudadanía interesada en la gestión y transparencia de datos viales. Utiliza datos oficiales de SITU Santa Cruz e IGN y está referenciado en IDERA.
## Procedencia de los datos geográficos
- **Rutas Provinciales, Zonas de Conservación, Bases Viales**: descargadas desde el [SITU Santa Cruz](https://situ.santacruz.gob.ar/geoportal/visor/emergencias)
- **Rutas Nacionales, Areas Protegidas, Centros Urbanos y Pasos Internacionales**: desargados desde [Portal del IGN](https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG)
- El visor institucional también se encuentra publicado en la [Sección Otras IDE y Visualizadores de IDERA](https://www.idera.gob.ar/index.php/servicios/otras-ide-y-visualizadores)
> **Advertencia:** El visor no permite la descarga ni redistribución de los objetos geográficos originales. Solo es posible exportar la información tabular (DT) visualizada en la herramienta.
## Usabilidad
- Interfaz intuitiva con controles de capa y leyendas.
- Tabla interactiva y exportable (DT) para filtrar, ordenar, imprimir y desargar datos tabulares.
- Popups y etiquetas informativas en el mapa.
- Instrucciones breves y ayuda para usuarios nuevos.
## Tecnología
- Desarrollado en R Markdown con flexdashboard y leaflet.
- Librerías utilizadas: `flexdashboard`, `shiny`, `sf`, `dplyr`, `tidyverse`, `leaflet`, `leaflet.extras`, `DT`, `knitr`, `png`, `htmltools`, `htmlwidgets`.
- Compatible con R (>= 4.0) y RStudio.
## Documentación y advertencia legal
> **Advertencia sobre datos y licencias:**
> Este visor utiliza datos geográficos provistos por organismos oficiales (AGVP, SITU Santa Cruz, IGN, IDERA). Cada capa vectorial está identificada por su fuente en el visor.
> El código fuente se publica bajo la Licencia Pública General de GNU, versión 3 (GPL v3), lo que garantiza el acceso abierto y el carácter colaborativo de los proyectos derivados.
> Los datos geográficos deben descargarse exclusivamente desde  los sitios institucionales y su uso está sujeto a las condiciones de cada organismo.
## Accesibilidad
- Contraste adecuado y textos legibles.
- Navegacion por teclado y compatibilidad con lectores de pantalla.
- Descripciones alternativas en imágenes e íconos.
- Canal de contacto para reportar problemas de accesibilildad.
## Instalación
1. Instala R (>= 4.0) y RStudio.
2. Instala los paquetes necesarios:
   ```r
   install.packages(c("flexdashboard", "shiny", "sf", "dplyr", "tidyverse", "leaflet", "leaflet.extras", "DT", "knitr", "png", "htmltools", "htmlwidgets"))
3. Descarga los datos geográficos desde: [SITU Santa Cruz](https://situ.santacruz.gob.ar/geoportal/visor/emergencias) (Red Provincial, Base Vial, Zonas de Conservación), [Portal del IGN](https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG) (Red Nacional, Areas Protegidas, Centros Urbanos y Paso Internacional), [IDERA](https://www.idera.gob.ar/index.php/servicios/otras-ide-y-visualizadores) (Referencia nacional y acceso a otros visores)
4. Abre el archivo .Rmd en RStudio y ejecuta el visor.
## Sobre la autora
- Desarrollado por Dévora Vanesa Antiñirre, Maestra Mayor de Obras. Profesional técnica especializada en gestión, organización y presentación de información geografica aplicada a Obras Públicas en la provincia de Santa Cruz.
## Licencia
- Este proyecto se publica bajo la Licencia Pública General de GNU, version 3 (GPL v3).
- Copyright (c) 2025 Dévora Vanesa Antiñirre
- Esta herramienta es software libre: usted puede redistribuirlo y/o modificarlo bajo los términos de la Licencia Pública General de GNU publicada por la Free versión 3 de la LIcencia, o (a su elección) cualquier versión posterior.
- Esta herramienta se distribuye con el proposito de que resulte útil, pero SIN NINGUNA GARANTIA; sin siquiera la garantía implícita de COMERCIALIZACIÓN o IDONEIDAD PARA UN PROPÓSITO PARRTICULAR. Consulte la Licencia Pública General de GNU para más detalles <https://gnu.org/licenses/>.

