# __Inicio de sesión__

__El login se hace en el portal de chartio:__

[chartio.com](https://chartio.com)

![reportes_001.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/reportes_001.png)

__En la página principal, hacer clic en Login para iniciar el proceso de inicio de sesión.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_002.png)

__En la ventana de login, hay que ingresar las credenciales de inicio de sesión. Si la cuenta de Chartio está ligada a una cuenta de debug Experts, hay que iniciar sesión previamente con la cuenta de Debug Experts en cuestión, si hay un inicio de sesión actual en el navegador web, el inicio de sesión en Chartio es inmediato dando clic en el botón de Login with Google.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_003.png)

__En el panel de inicio de Chartio, hallarán distintos dashboards disponibles. Cada cliente tiene un dashboard. En este ejemplo, se accederá al Dashboard del TEPJF haciendo clic en el dashboard llamado "Reporte Firewall TEPJF".__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_004.png)

__Esta es la vista del Dashboard del "Reporte Firewall TEPJF". Del lado izquierdo se observan los elementos que estarán disponible en el reporte generado, mientras que del lado derecho se observan los elementos de edición del Dashboard. No todos estos elementos estarán disponibles porque dependen de los permisos de escritura/lectura del usuario que accede.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_005.png)

__Antes de generar un reporte, se deben aplicar filtros en el reporte, para ello, se hará uso de los filtros que se encuentran en el inicio del Dashboard. Tales filtros determinan el Sitio, en caso de que el cliente cuente con más de un sitio, además del mes del reporte que se desee generar.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_006.png)

__Para seleccionar el sitio, solo basta con hacer clic en el filtro "Sitio"; un menú desplegable aparecerá indicando los sitios disponibles. En este caso, se seleccionará el sitio llamado "Sala Superior".__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_007.png)

__Se repite el mismo procedimiento para el filtro "Mes". En este caso se seleccionará el mes de Abril.__

__Tras haber usado ambos filtros, la información correspondiente será poblada en el dashboard.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_008.png)

__Antes de continuar, se recomienda ampliamente que se revisen que en todas las páginas aparezca información referente al Firewall y que en especial no se presenten errores. Habrá situaciones en la que algun chart no contengan ningún tipo de dato, eso puede ser normal en casos en el que no exista información. Independiente de que sea un comportamiento esperado, se recomienda reportar este tipo de situaciones.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_009.png)

__Tras haber finalizado la revisión del dashboard, se puede descargar e imprimir el reporte. Para ello, se debe hacer clic en el botón "Download", ubicado en la parte inferior derecha del Dahsboard y elegir la opción "Download as PDF". El reporte será entonces generado con la información desplegada en el Dashboard y posteriormente descargado al navegador que se esté utilizando. Este proceso puede llevar de unos segundos a un par de minutos.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_010.png)

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_011.png)

__EDICIÓN DEL REPORTE.__

__El reporte en pdf contiene la información filtrada del Dashboard, además de una serie de estampas de tiempo, número de página y marcas de agua que Chartio imprime en el documento. El siguiente paso es borrar tales elementos.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_012.png)

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_013.png)

__Con un editor de pdfs (en este documento se usará el editor de pdf de preview de MacOS), se cubrirán los elementos que se encuentran en la parte superior e inferior de todas las páginas del documento.__


__Se utilizarán autoformas rectangulares sin borde, que empaten con el color del fondo del reporte y se colocarán a modo que bloqueen los elementos que deseamos cubrir.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_014.png)

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_015.png)

__Tras haber cubierto la primer página, se seleccionan las dos autoformas usadas y se copian y pegan en las siguientes páginas.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_016.png)

__Al final obtendremos un documento pdf sin las marcas que Chartio pone. Para hacer los cambios permanentes, solo basta con guardar el documento o sobreescribir el que se había descargado.__

![reportes_002.png](https://raw.githubusercontent.com/EgaleanaDexperts/services-manual/master/manual/Images/reportes_017.png)

__Esto finaliza el proceso de generación de un reporte de Chartio.__















