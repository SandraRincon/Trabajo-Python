# Limpieza y análisis de datos  sobre la venta de vehículos usados de una página Web.

# Motivación y Descripción : 

La venta de carros  a nivel mundial  ha sido recurrente através de los años. Los carros son un  medio de transporte personal muy útil para las personas.Sin embargo, en ciertos casos la persona no cuentan con los recursos necesarios para comprar un carro cero kilómetros dadas circunstancias externas. Es por esto que la motivación a realizar este trabajo  fue explorar mediante una base de datos  las características de los carros comprados  de segunda  en una página Web. Mediante técnicas de Python. 
Algunas preguntas y afirmaciones que motivaron  para la realización del trabajo son :

* Preferencia de carros usados que compran los individuos. 

* La vida útil de los carros es de 5 años. ¿ Qué pasa con los carros que fueron fabricados en  los años 1985? Qué política pública se podría implementar en Colombia para favorecer la compra de vehiculos amigables con el medio ambiente?

* ¿ Cuál es el color más vendido  de carros en la página Web  ?

* ¿Cuáles son las marcas que mas se vendieron en la página Web ?

* ¿Que tanto influyen las variables cualitativas o cuantitavias a la hora de comprar un vehículo usado ?

* ¿Existe alguna relación entre precio del auto y kilómetros recorridos ?



Lo primero que se realizo  fue bajar la base de datos de kaggle entrando con un usuario y contraseña. Dicha base esta pública y es de Data Market(base de España). Cabe aclarar que se utilizó esta base como una muestra representativa hipotética para la venta de carros en miras de que comprar carros usados es una actividad común  en los distintos  países. Para este trabajo se utilizó  la versión número 1 de ventas de coches de segunda mano en las principales plataformas. Dicha base consta de la página  Web de donde se ha realizado la extracción del anuncio  de carros (encriptado).Es decir,no  tiene el nombre como tal de la página web.Y de ahí en adelante se cuenta  con las demás variables de interés.Como lo son: precios de ventas, marca del auto, kilómetros recoridos, año de fabricación,etc.

#  Método utilizado:

PYTHON -> Numpy, Pandas , Matplotlib y Seaborn 

Pasos del método : 

1. Hacer registro de usuario en Kaggle
2. Descargar base de datos de Kaggle en formato csv.La página es: 'https://www.kaggle.com/datamarket/venta-de-coches/version/1' 
3. Importar librerias  de Python: Pandas, Numpy ,Seaborn y Matplotlib
4. Cargar base : 5000 filas y 20 variables.Posteriormente eliminar variables que no aportan a la investigación.
5. Limpieza de base de datos.Remover Nas y outliers negativos. Queda la base con 4045 filas y 15 variables.
6. Visualización de datos. Los años de la base comienzan apartir de 1982 hasta 2021.
7. Análisis de datos para las variables cualitativas y cuantitativas,que hacen referencia a caracteristicas de los autos.Siendo estas las encontradas en la base de datos.Cabe aclarar que las variables cuantitativas son aquellas que tienen valores númericos y en ellas se pueden realizar operaciones.Como por ejemplo: El precio de venta del automóvil,los kilómetros recorridos,potencia del auto, entre otros. Mientras que  en el tratamiento de  las variables cualitativas se observará unicamente la distribución que tienen según sus categorías, y  se procede a realizar conteos sobre estas en la medida que estos datos puedan ser interpretables.Un ejemplo de ellas son : Marca, color, modelo de referencia, entre otros.
8. Para las variables cuantitativas observar la correlación existente entre ellas y para las cualitativas encontrar las características mas importantes entre ellas.

Recomendaciones :

    1) A mayor potencia el carro tendrá un mayor precio.    
    2) A mayor kilómetros recorridos  del carro el precio disminuye, esto debido al uso del automóvil.    
    3) A mayor kilómetros recorridos menor es el año del auto.    
    4) La mayor cantidad de marcas vendidas son:  VOLKSWAGEN, BMW y MERCEDES-BENZ.    
    5) La mayoría de carros cuentan con combustión interna de  diesel, seguidos de gasolina.    
    6) La mayoría de los carros son mecánicos en vez de automáticos.    
    7) Los colores mas vendidos fueron el blanco,gris/plata y negro.


# La aplicación a política Pública

Gracias a los resultados obtenidos en el estudio, se podría asociar dicho tema a la creación de una política pública.
Política pública:  Incentivar a los cuidadanos a realizar la transición de vehículos usados a vehículos nuevos atrevés de créditos blandos. Para disminuir los mayores  gastos en mantenimiento y operación de vehículos usados y así mismo aumentar  el ingreso  destinado para  la canasta familiar y la recreación  de la persona. De igual forma  con el uso de carros nuevos  se esperaría que la contaminación del aire no sea tan pronunciada y disminuya ya que los carros nuevos traen tecnologías limpias, innovadoras y eficientes  que sirven para mitigar  las emisiones de gases de efecto invernadero. Es  fundamental apostar por nuevos modelos, más sostenibles basados en energías renovables (Fundación aquae,2021).


Bibliografía

Fundación Aquae.(2021).¿Cuánta contaminación produce el coche?. Obtenido de:
'https://www.fundacionaquae.org/cuanto-contaminan-los-coches/amp/?gclid=EAIaIQobChMIwuLqt7Wu9AIVPYpaBR3cdQ4bEAAYASAAEgKTkvD_BwE'
