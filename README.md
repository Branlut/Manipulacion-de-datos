# Manipulación de datos

## Descripción
Instacart es una plataforma de entregas de comestibles donde la clientela puede registrar un pedido y hacer que se lo entreguen, similar a Uber Eats y Door Dash.

## Objetivo
Poner en practica la manipulacion de datos(eliminar datos duplicado, vacios, verificar tipos de datos) con el data set proporcionado para hacer un analisi exploratorio. 

## Tecnologias
- Python
- Vs code
- pandas
- numpy
- matplotlib

## Análisis
### Para cada hora del día, ¿cuántas personas hacen órdenes?
- En general se realizan una gran cantidad de compras entre las 9 y las 17 horas.
- Tenemos 2 grupos con respecto a la hora que son bajas las compras en la mañana y en la tarde noche. En la mañana entre las 0 y 8 horas hay un menor cantidad de pedidos ya en esta ultima comenzando a aumentar y en la tarde noche a partir de las 18 horas la cantidad de pedidos empieza a diminuir hasta las 23.
- Se puede concluir que el rango de hora en el cual se realizan mas pedidos es en comparacion al horario laboral (periodo de 8 horas) ya que es donde las personas estan mas activas y los rangos de hora en la mañana y en la tarde noche son menos activos ya que estan descansando y van a descansar.

### ¿Qué día de la semana compran víveres las personas?
- Los días Domingos como lunes son lo días en lo que se realizan mas compras dismuyendo mientras avanza la semana y aumenta mientras se acerca el fin de semana.

### ¿Cuánto tiempo esperan las personas hasta hacer otro pedido? Comenta sobre los valores mínimos y máximos
- En promedio se demoran 10 días en comprar nuevamente siendo 0 días el minimo de días que se demora en comprar nuevamente y 30 el maximo.

### Diferencia entre miércoles y sábados para. 

- Como se puede apreciar en la distribución y en los gráficos los 2 días tienen casi la misma distribuición pero el Miécoles tiene una ligera ventaja en las horas 6, 7, 9, 18, 19 y 20.

### ¿Cuál es la distribución para el número de pedidos por cliente?
- En promedio se hacen 14 pedidos.
- La gran mayoria de personas solo hacen 1 pedido, como se puede apreciar entre mas pedidos se hacen menos personas los hacen con esto me refiero a que las personas que hacen 28 pedidos que es el maximo es solo una mientras que las personar que hacen solo 1 pedido son 55357

### ¿Cuáles son los 20 productos más populares (muestra su ID y nombre)?
- El producto mas popular fueron las bananas
- En general los productos mas vendidos son productos organicos.

### ¿Cuántos artículos compran normalmente las personas en un pedido? ¿Cómo es la distribución?
- Como se puede ver la gran mayoria de personas compra en promedio 10 articulos en un pedido
- El minimo de articulos encargados en un pedido es 1 y el maximo de 127

### ¿Cuáles son los 20 principales artículos que vuelven a pedirse con mayor frecuencia
- La mayor cantidad de recompras la tiene las bananas
- En general los productos que se vuelven a comprar son frutas y verduras organicas
- Lo menor pedido es organic half & half

### Para cada producto, ¿cuál es la proporción de las veces que se pide y que se vuelve a pedir?
- El dataframe product_yes_no_reordered muestra los productos que se han comprado y se han vuelto a comprar. De esto en general  en promedio se se se vuelven a comprar 38% de los productos y en promedio se compran solo 1 vez un 61%.

### Para cada cliente, ¿qué proporción de sus productos ya los había pedido?
- Las personas en promedio vuelven a comprar un producto el 49% de las veces 
- Esto quiere decir que por un porcentaje menor de personas solo comprar un producto 1 vez

###  ¿Cuáles son los 20 principales artículos que las personas ponen primero en sus carritos?
- El producto que ponen primero en el carrito es la banana
- En general los productos que ingresan primero al carrito son frutas, verduras o algun producto organico.

# Conclusiones 
- Con relación a los datos evaluados no habian una cantidad significativa de datos nulos o duplicados lo que quiere decir que
la recopilación de la informacíon fue bastante buena
- Con respecto al proyecto se puede apreciar una alta preferencia por los productos orgánicos frutas, verduras, lacteos, etc. 
- Las personas en general tienden a comprar en promedio 10 articulos en un pedido.
- Son 14 en promedio las ordenes de compras que hacen. 
- Las personas tienden a comprar un producto una sola vez.
- Son pocas las personas que realizan compras con muchos artículos en un pedido (considerar que el maximo es 64) y 
de igual forma son pocas las que hacen muchos pedidos (maximo 127)
- En general los días Domingos son los preferedidos para realizar las compras
- En cuanto al horario como se vio en los días Domingo y Miécoles se prefiere las horas de las 9 am a 18 pm para realizar compras.
- Podemos apreciar que las personas estan cuidando su salud ya que la preferencia de compras o por lo que van primero 
son productos órganicos. 
