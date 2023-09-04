# Holi
[x] Encabezados Marckdown permirte realizar encabezados, dependiendo el tamaÃ±o de la letra, para lo cual dependera de repetir el signo hashtag "#" algunas veces o escribir el codico "H y el numero de veces que se repite el hashtag del 1 al 6, por ejemplo:
VISUALIZACION DE DATOS MASIVOS ## Actividad de contextualizacion
Por: Jose Leonardo Roman
27 de Agosto 2023
[x] Citas en bloque La creacion de Blockquotes o citas en bloque sirve para incluir referencias de autores, tambien para resaltar algun elemento, de la siguiente manera: >
Especializacion BIG DATA >
Segundo Semestre
Contextualizacion
En Lenguaje HTML/Formateo de texto dice:
Ejemplo de cita larga. Recomendamos que las implementaciones de hojas de estilo porporcionen un mecanismo para insertar signos de puntuaciÃ³n de citas antes y despuÃ©s de una cita delimitada por un BLOCKQUOTE de un modo apropiado segÃºn el contexto del idioma actual y el grado de anidamiento de las citas.

[x] Seccion de codigo Es posible incluir codigo de python en una seccion de marckdown abriendo con tres tildes inversas y la palabra Python y luego cerrando con ttildes inversas de nuevo, ejemplo: ```Python import time def temporizador(segundos ): for s in range(segundos, 0, -1): print(f"Faltan {s} segundos") time.sleep(1) print("!Tiempo AgotadoÂ¡") temporizador(5) ```
[x] Signo matematico Marcdown da la posibilidad de escribir formulas matematicas con el fin de visualizar correctamente la estructura, por ejemplo: Ejemplos: $$\sqrt{2x+5} + (10X)^2$$ $$\int_0^1 {x^2} \,{\rm d}x$$ $$\lim_{n \to +\infty} \frac{1}{n(n+1)}$$ # **FORMULA DE VARIANZA** $\sigma = \sum_{1}^N \frac{(X_i -\overline{X})^2}{N }$ **$X$** $\rightarrow$ Variable **$\overline{X}$** $\rightarrow$ Es la media variable **$X_i$** $\rightarrow$ Observacion numero i de la viariable X **$N$** $\rightarrow$ Numero de obervaciones [Markdown fÃ³rmulas y sÃ­mbolos matemÃ¡ticos](https://programmerclick.com/article/9139292621/#google_vignette)
Aqui se encuentran codigos para usar los signos matematicos
[x] Salto de linea Los saltos de linea, crean un espacio entre los textos que se estan escribiendo, separande en varias lineas el parrafo o codigo que se desea, por ejemplo: Tambien se pueden usar los operadores trigonometricos tales como:
- $\sin$
- $\cos$
- $\tan$
- Entre otros
[x] Texto en negrita y cursiva se utiliza para darle formato al texto, se debe iniciar con los signos antes y despues del texto que se desea modificar por ejemplo: **Bold (negrilla)**
_Italics (Cursiva)_

~~Tachado (strikethrough)~~

**_Cursiva y negrilla_**

Subscriptsubindice

Superscriptsuperindicesubindice
[x] Linea horizontal Se utiliza diferentes simbolos para crea lineas de separacion horizontal, puede ser usado para diferencias los temas como se ha visto en los ejemplos anteriores, se puede utilizar de la siguiete manera:
Opcion 1: ---
Opcion 2: ***
Opcion 3: - - - -
Opcion 4:
[x] Lista ordenada con marckdown se puede crear listas ordenadas,extisten varias formas de crear listas ordenadas, por ejemplo:
Avengers
Doctor Strange
Ironman
La numeracion se puede hacer automatica de la siguente manera: 1. Captain America 1. The Winter soldier. 1. Civil War 1. Ant-man 1. Scarlet witch 1. Black widow 1. Hulk 1. Black panther [x] # Lista desordenada Para las listas desordenadas, se puede utlilizar, "+", "-", "*" y para crear subtemas solo se realiza una tabulacion * Series de HBO - Game of thrones + The Last of us + Series de Netflix + Stranger things * Merlina De igualmanera se puede realiar con el siguietne codigo:
Cine colombia
Cinemarck
Procinal
[x] Enlace Interno Se puede usar para ir rapitamente a una seccion del codigo, pueser usarse buscando encabezados con "#" o asignar un codigo en una ubicacion, por ejemplo: [Inicio](#actividad-de-contextualizacion) [Codigo_Python](#Codigo_Python)
[x] Enlace Externo Los enlaces externos pueden pegarse directametne en el codigo para ir al sitio web requerido, de igualmanera puede escribirse de manera que se pueda cambiar el nombre del enlace: https://www.datacamp.com/tutorial/markdown-in-jupyter-notebook [Data camp, Marckdown in Jupyter Notebool Tutorial](https://www.datacamp.com/tutorial/markdown-in-jupyter-notebook)
[x] Tablas Existen varias formas de crear tablar en marckdown, en las cuales pueden hacer tablas simples y tabla complejas, por ejemplo:
|Nombre|Nacionalidad|Ocupacion| |-----|-------|------| |Jose Roman |Colombiano|Ing. Industrial| |Pepito|Aleman|Especialista Big data|

de igual manera uede usarse un codigo para crear tablas mas complejas
Column 1	Column 2	Column 3
R1 Text	R2 Text A	R3 Text A
R3 Text B
R2 Text B	R3 Text C
R3 Text D[Generador de tablas](https://www.tablesgenerator.com/markdown_tables)
Aqui se encuentran una herramienta para la creacion rapita de tablas
[x] Tablas de imagenes Para insertar imagenes se puede hacer con fuentes internas y externas, para el siguente ejemplo se tomara enlaces externos dentro de una tabla: usanto la estructura ![DescripciÃ³n de la imagen](direccion de la imagen) para insertar la imagen | IMAGEN1 | IMAGEN2 | IMAGEN3 | | | |------|-------|--------|---|---| | ![DescripciÃ³n de la imagen](https://interlat.co/wp-content/uploads/2020/05/59915-2048x1363.jpg) | ![DescripciÃ³n de la imagen](https://supirole.com/wp-content/uploads/2017/11/Bases_de_datos_de_particulares.jpg) |![DescripciÃ³n de la imagen](https://www.tecnologias-informacion.com/analisisd.jpg) | | | | Visualizacion de datos | Base de datos | Estadistica | | |
