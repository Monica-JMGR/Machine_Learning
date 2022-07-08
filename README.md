# Precio de Venta en coches de segunda mano

## Objetivo

El objetivo de este proyecto es crear un modelo predictivo de Machine Learning que prediga el precio de venta de un coche de segunda mano a partir de los datos recogidos en un dataset.

### Datos

Para este proyecto se ha utilizado un dataset que procede de https://datamarket.es.
Esta base de datos es la que tienen disponible en su web como prueba.
Está formada por Anuncios de venta de coches de segunda mano en las principales plataformas. 
Contiene un total de 50.000 observaciones y 21 características.

### Proyecto

Nos encontramos con un problema de regresión, pues lo que queremos predecir es un número (precio de venta) y de tipo Supervisado.
Es supervisado porque el dataset con el que entrenamos nuestro modelo conoce el precio del vehículo y aprende a partir de éste.
Los atributos con los que vamos a trabajar son:

+ Marca y modelo (‘marca_modelo’)
+ Combustible (‘fuel’)
+ Antigüedad del vehículo (‘years’)
+ Potencia (‘power’)
+ Provincia (‘province’)

<br>
<br>

Proyecto ML | Bootcamp Data Science | Monica Garrido Ramirez
