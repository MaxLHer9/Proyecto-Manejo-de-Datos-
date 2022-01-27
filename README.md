# Proyecto-Manejo-de-Datos-
Equipo 4 
Equipo 4.
Integrantes:
-Alanis Martínez Fernanda Yoselin
-Camacho Guzman Luis Angel
-Hernández Pérez Maximiliano
-Luna Barroso Lucía.
Este proyecto fue elaborado en Jupyter Notebook,se desarrolló un web scraper con ayuda de chromedriver el cual extrae datos de tres diferentes 
sitios web, el tema elegido fue ropa (jeans, playeras, vestidos, botas),por lo que los sitios web de los cuales se está extrayendo la información son: 
Liverpool, C&A y Sears. 
Para poder ejecutar este proyecto es necesario que cuentes con Jupyter o un editor de código fuente,una vez se haya abierto el proyecto, sólo se necesita
dar 'Run' el cual se encuentra en la barra de tareas, por lo que procederá a ejecutarse y abrirá los sitios web y los productos,es decir abrirá el producto 
jeans de los sitios Liverpool, Sears, C&A, posteriormente el producto playeras, vestidos y por último botas,para poder hacer que nos monstrará cada uno de los
sitios web fue utilizando un bucle for para que de esta forma recorra los elementos de la lista, y que las diferentes funciones creadas para las diferentes
tiendas busquen los respectivos datos solicitados (los productos, los precios promocionales, los precios normales de cada sitio).
Sin embargo al momento de correr el código justamente al aplicar la función precios_float_casears al dataframe aparece una advertencia, no obstante
el código se ejecuta con éxito, hubo un pequeño detalle al conseguir los precios en floats de la tienda Liverpool ya que se tenía que eliminar los últimos dos dígitos que correspondían a los centavos, así como en algunos casos el precio y el descuento estaban intercambian¿dos por la etiqueta; por lo que se recurrió a un método adicional llamado precio_chido el cual evalúa las columnas de precio situando el precio menor en la columna de descuento y el mayor en la de precios normales.
Por otro lado toda la información de dichos productos se guardan en un archivo con extensión csv , estos datos son ocupados para hacer consultas.
