# Web scraping con Python

En esta clase del [Diplomado en Ciencia de Datos UC](https://datascience.uc.cl/) aprenderemos a implementar la técnica de extracción de datos conocida como _web scraping_ usando la librería Beautiful Soup. 

## Preparación

Para realizar las actividades planificadas necesitarás las librerías `request`, `beautifulsoup4` y `pandas`. Se pueden instalar desde [PyPI](https://pypi.org/) con `pip`. 

```
pip install beautifulsoup4
pip install requests
pip install pandas
pip install lxml
```

Si prefieres trabajar en Google Colab o en un notebook, no olvides agregar un signo de exclamación al inicio de cada línea para su instalación, es decir:

```
!pip install beautifulsoup4
!pip install requests
!pip install pandas
!pip install lxml
```

Si trabajas en Visual Studio Code, es necesario que crees un entorno virtual. En la clase mostraremos cómo hacerlo.

Si el tiempo nos alcanza (no creo, porque este año tendremos una sola clase sobre web scraping), nos introduciremos en el trabajo con sitios web dinámicos. En ese caso, si quieres reproducir los ejemplos, es necesario trabajar con una instalación local de Python (puede ser un notebook), pero no Google Colab. 


## Atajos de teclado útiles

Los siguientes atajos de teclado serán útiles al explorar las páginas web que _escrapearemos_.

| Acción | Windows / Linux | Mac |
|---|---|---|
| Ver el código fuente de una página | ctrl +  u | command + u|
| Abrir el panel de desarrollo | F12<br/>ctrl + shift + i | F12<br/>option + command +i |
| Abrir el panel de desarrollo con la opción de selección activada | ctrl + shift + c | option/ctrl + command + c |


## Enlaces ejemplos

A lo largo de la sesión revisaremos algunos sitios web a modo de ejemplo o para discutir algunas ideas. Los compartiremos por el chat de Zoom y quedarán acá también como referencia.

:link: [Sitio web estático](https://datascience.uc.cl/que-es-ciencia-de-datos)

:link: [Sitio web dinámico](https://www.camara.cl/transparencia/asesoriasexternasgral.aspx)

:link: [Condiciones de uso](https://www.amazon.com/-/es/gp/help/customer/display.html?nodeId=508088&ref_=footer_cou) 

:link: [Licenciamiento y uso del contenido 1](https://www.biobiochile.cl/)

:link: [Licenciamiento y uso del contenido 2](https://prensa.presidencia.cl/)

:link: [robots.txt 1](https://wikipedia.org/)

:link: [robots.txt 2](https://www.oas.org/)

## Actividades

Durante la clase realizaremos una serie de actividades para poner en práctica lo aprendido. Iremos escribiendo el código "en vivo", por lo que el contenido de los archivos con código se irá actualizando a medida que escribamos en ellos. 

### Ejercicio 1: extraer texto

:link: [Página web](https://www.minciencia.gob.cl/noticias/plan-de-data-centers-se-abre-a-consulta-ciudadana-convocada-por-el-ministerio-de-ciencia/)

:page_facing_up: [Código escrito en clases](https://www.dropbox.com/scl/fi/eje47vygy9n7d54qispb6/ejemplo-1_extraer-texto.py?rlkey=fb525np5qnz11z6irfxa0kb99&st=tkp8ryv2&dl=0)


### Ejercicio 2: extraer tablas

:link: [Página web ejemplo 1](https://www.worldometers.info/world-population/population-by-country/) / [Página web ejemplo 2](https://es.wikipedia.org/wiki/Anexo:%C3%81lbumes_musicales_m%C3%A1s_vendidos)

:page_facing_up: [Código escrito en clases](https://www.dropbox.com/scl/fi/gwfnmyrjyc366xjgrodvq/ejemplo-2_extraer-tablas.py?rlkey=xv8gmr08kl2f2ow3wket8cgsv&st=p3590j6f&dl=0)

### Ejercicio 3: extraer enlaces y descargar archivos

:link: [Página web](https://www.memoriachilena.gob.cl/602/w3-article-644324.html)

:page_facing_up: [Código escrito en clases](https://www.dropbox.com/scl/fi/o00lu4sny8uadsigigq72/ejemplo-3_descargar-archivos.py?rlkey=lge1dom7sqj0h99k6g4jdofzl&st=jor0mkfa&dl=0)


### Ejercicio 4: demo selenium

:link: [Página web](https://www.memoriachilena.gob.cl)

:page_facing_up: [Código escrito en clases](https://www.dropbox.com/scl/fi/zrjxh4le2euo35r0h6znr/ejemplo-4_demo-selenium.py?rlkey=esxk0y39w0ooa7ry34ez385o6&st=0ns2uzop&dl=0)


## Recursos adicionales

### Documentación librerías utilizadas
[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

[Selenium](https://www.selenium.dev/documentation/)

#### En R

El paquete [rvest](https://rvest.tidyverse.org/) nos permite hacer web scraping en sitios web estáticos usando R. [Este tutorial](https://programminghistorian.org/es/lecciones/introduccion-al-web-scraping-usando-r) cubre lo que vimos en el primer ejemplo (extracción de texto). 
Existe también un paquete que se llama [RSelenium](https://docs.ropensci.org/RSelenium/) que permite trabajar con sitios web dinámicos, pero solo funciona con la versión 2.0 de Selenium. 
En la edición 2023 este diplomado consideraba dos sesiones de web scraping con R. El código que escribimos en ese taller está disponible [en este repositorio](https://github.com/rivaquiroga/taller-web-scraping-r-2023).
