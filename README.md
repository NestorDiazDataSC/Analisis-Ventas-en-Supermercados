# Analisis de Ventas en Supermercados

Analisis de ventas totales en supermercados a valores corrientes y constantes y evolución por canal de venta, medio de pago y grupos de artículos, dataset proporcionado
por Datos Argentina.

## Heatmap
Luego de la limpieza de los datos, se genero este mapa de calor para ver como se correlacionan los datos entre si. Para interpretarlos es sencillo pues las zonas donde se obtienen colores mas claros es donde se encuentra una mayor correlación entre los datos, como vemos la mayoria de los cuadrados no superar una correlación de 0,6 compararndola con la barra indicadora de la derecha, por supuesto obviando la diagonal del medio que representa la relación entre un mismo campo consigo mismo y al ser un caso asi seria una perfecta correlación igual a 1.
![01](https://user-images.githubusercontent.com/94582879/166084384-f2ad1804-cfb8-4939-97ff-65d6b097692e.jpg)

## Heatmap con información mas relevante
Luego procedi a limpiar un poco mas los datos y de forma arbitraria opte por filtrar los 7 campos con mayor relación con el campo "Ventas Online", como se puede apreciar en el mapa de calor de abajo.
Aqui las "Ventas con debito" son las que mas relacion tiene con el campo "Ventas Online" quizas por razones obvias de que las ventas online se deben pagar con tarjetas de credito o debito, igualmente de la base de datos se desprende que la relación entre estos dos campos no es capas de predecir linea tendencial para poder si generar una predicción con un algoritmo de correlación lineal. 
![02](https://user-images.githubusercontent.com/94582879/166084387-14a3e6de-225f-4008-bdb2-656dc79933a6.jpg)



## Créditos y autor
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nestor_Diaz-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/contadornestordiaz/)
