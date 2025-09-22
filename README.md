Se realiza un estudio acerca de que factores influyen para que un cliente esté más predispuesto para la contratación de un producto ofrecido por el banco. Los resultados se muestran en la columna ‘y’.
Desde un Jupiter notebook “PROYECTO_EDA” se importa el archivo csv y las tres hojas de excel corespondientes a los años 2012, 2013, 2014. Realizamos un contacto visual y obtenemos información de los dataframes, cantidad filas y columnas, tipos de datos, nulos, duplicados.
Unimos los dataframes en uno solo “bank_concat”, lo hacemos a través de la colunma ‘ID’ que la establecemos como índice.
Realizamos la transformación y limpieza de los datos.
Buscar correlaciones en las columnas numéricas mediante matriz de correlación y heatmap.
Relaciones cruzadas mediante scatterplot de las columnas numéricas y countplot de las categóricas. Conclusiones de la exploración en celdas de markdown.
Exportamos el dataframe “bank_concat” a csv, para posteriormente importarlo en una nueva hoja de Jupiter notebook “bank_eda” y realizar un análisis descritivo de los datos sobre el resultado de la columna ‘y’. El análisis se comenta en celdas de markdown.
En ocasiones he realizado diferente código para obtener un mismo resultado, esto lo he hecho para mejorar mi aprendizaje y ver diferentes formas de programación con un mismo resultado, por ejemplo: comprobar duplicados u obtener solamente clientes ‘yes’ de la columna ‘y’.
