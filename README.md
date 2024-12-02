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

:link: [Página web]()

:page_facing_up: [Código escrito en clases]()


### Ejercicio 2: extraer tablas

:link: [Página web ejemplo 1](https://www.worldometers.info/world-population/population-by-country/) / [Página web ejemplo 2](https://es.wikipedia.org/wiki/Anexo:%C3%81lbumes_musicales_m%C3%A1s_vendidos)

:page_facing_up: [Código escrito en clases]()

### Ejercicio 3: extraer enlaces y descargar archivos

:link: [Página web](https://www.memoriachilena.gob.cl/602/w3-article-644324.html)

:page_facing_up: [Código escrito en clases]()


### Ejercicio 4: demo selenium

:link: [Página web](https://www.memoriachilena.gob.cl)

:page_facing_up: [Código escrito en clases]()


## Recursos adicionales

### Documentación librerías utilizadas
[Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

[Selenium](https://www.selenium.dev/documentation/)
# diplomado-ds-2024-web-scraping