# Segmentacion
Proyecto de segmentación de clientes 
# Contexto
La tienda El Mercado está en un ambiente altamente competitivo y está experimentando cambios significativos en las preferencias de los consumidores. La fidelidad del cliente se ha vuelto un desafío, y la tienda en cuestión busca mantener y aumentar sus ingresos mediante una mejor comprensión de su base de clientes y la personalización de sus estrategias de marketing y retención.
La estrategia elegida por la tienda es analizar sus ventas y segmentar su base de clientes mediante la metodología RFM (Cuán reciente, Frecuencia y Valor Monetario). Esta estrategia proporcionará a la empresa una ventaja competitiva clave al brindar un profundo entendimiento del comportamiento de compra de sus clientes y permitirá la toma de decisiones estratégicas basadas en datos.
El objetivo del analisis es preparar la base de datos que pone a disposición la empresa para que se pueda aplicar la segmentación de clientes a través de RFM y sacar conclusiones que posibiliten a la empresa a tomar decisiones, además de buscar información importante que se encuentra oculta en los datos, como por ejemplo: ¿Quiénes son estos clientes? ¿Están casados? ¿Tienen hijos? ¿Cuántos años tienen? ¿Cuál es el volumen de ventas de la empresa (en cantidad)?

# Base de Datos
Se cuenta con una base de datos con las siguientes caracteristicas:
- 3 tablas llamadas Clientes, Transacciones y resumen_compras
- Volumen de 2228 lineas.
- Cuentan con 20 variables en total.

# Proceso de Limpieza y Preparación
Durante el proceso de limpieza se eliminaron las lineas con valores nulos en variables importantes como id_clientes o id_transaccion. 
Los valores nulos en otras variables númericas fueron reemplazadas por el promedio general de los valores no nulos de la misma variable.
Para los datos fuera de alcance estos fueron eliminados, sujetos al limite de no borrar mas de un 1% del total de datos.

# Análisis Exploratorio 
A continuación se muestra el analisis exploratorio realizado para caracterizar a los clientes a segmentar.
![image](https://github.com/FeerOT/Segmentacion/assets/150949526/3f3f6218-1578-46bd-8427-8a4a8d1f1410) 

# Técnicas de Análisis Utilizadas
Durante el proceso de analisis se utilizaron las siguientes tecnicas: 
-Segmentación RFM
-Análisis de Cohortes
-Analisis de datos a largo plazo
-Visualización de datos

# Resultados y Conclusiones
Los principales resultados y conclusiones obtenidos fueron:
- Se caracterizó a los clientes, con la finalidad de conocer quienes son.
- Se segmentaron a los clientes de la base de datos.
- Se realizo análisis por cohorte, basado en la fecha de inscripción de cada cliente
- Se elaboraron recomendaciones para la tienda.
