# Proyecto Criptomonedas
<img src= "https://es.investing.com/academy/wp-content/uploads/sites/4/2022/04/Crypto-Mineria-de-criptomonedas.jpg" alt="La imagen no puede cargarse" width="500" height="500">

# Kevin Bonnin

En este proyecto se nos encargó la tarea de tomar el rol de un analista de datos en una empresa que se dedica a la inversión de capitales, últimamente esta empresa se interesó en la inversión en criptomonedas asique nos delegó la responsabilidad de realizar las investigaciones y el análisis pertinente. siguiendo este lineamiento me enfoqué en llevar este proyecto en un lineamiento claro, realizar inversiones que generen ganancias, pero también realizar inversiones que nos permitan mantener nuestro capital con un bajo riesgo, ya entrando en eso, nos vamos al EDA.

# ADE

En esta parte comencé indagando en algunas páginas, ya que mi conocimiento en inversiones no es muy bueno, y encontré dicho que una moneda es confiable cuando tiene una mayor capitalización de mercado, ya que significa que tiene un alto respaldo de los inversionistas. Ya con este conocimiento me decidí a analizar las 12 monedas con mayor capitalización del mercado para elegir en cuales hacer inversiones serias.

Lo primero que se hizo fue realizar la descarga de los datos referentes a precios, capitalización de mercado y demás de las criptomonedas, para ya después quedarse con los primeros 12 en capitalización. Ya sabiendo de que criptomonedas hay que descargar sus datos, se dispuso a extraer los datos de la API y realizarle el análisis para comprobar que los datos estén en condiciones, primero se constato de que no hayan datos duplicados y luego que no haya datos faltantes, siendo en ambos casos el resultado negativo ya que no se encontró ninguna anomalía, después se analizó los outliers, de los cuales si se encontraron algunos, pero antes de tomar acción al respecto se realizó unos gráficos para comprender la naturaleza del movimiento del valor de las monedas con respecto al dólar. Este análisis en los gráficos nos dejo ver que en realidad no se trataban de outliers en sí, sino de movimientos erráticos de la propia moneda, y se creyó que los datos estaban listos para ser pasados a Power Bi, no sin antes limitar el número de comas y pasar a un archivo CSV esos datos.

Lo que siguió fue tomar en cuenta la poca confiabilidad de algunas monedas al ser nuevas en nuestro favor, cuando se descargó los datos de 3 monedas nuevas que han tenido buenos rendimientos en estos días se vio con claridad los datos que tienen al ser pocos, entonces se concluyó que no era necesario un análisis detallado, lo que si se hizo fue realizar gráficos para analizar el comportamiento de los precios en estos últimos días (también primeros) de las monedas y se concluyó que solamente 1 era idónea para el trabajo que se le quiere dar al ser la que más crecimiento tuvo en las últimas horas.

# Dashboard y KPI’s

Primer KPI: Incremento.

Se decidió para este KPI utilizar las monedas con mayor capitalización de mercado, y si bien las conclusiones que se sacan a priori es que por la tendencia negativa del mercado no es el mejor momento para invertir, se decide que las mejores monedas para realizar una inversión con peso son: Bitcoin y Solana, ya que, si bien no están creciendo en este momento, su historial nos dice que siempre tienden a subir su valor.

En base al análisis del historial se puede estimar que invirtiendo en Bitcoin podemos alcanzar una ganancia de un 4,36% en 2 meses, mientras que en el Solana podemos alcanzar una ganancia de 4,46% en 1,6 meses.

Segundo KPI: Mantener capital.

Siguiendo con el lineamiento expresado al principio, no solamente nos vamos a centrar en ganar dinero, sino que también en mantener el que se tiene, y para eso se decide en base al histórico de precios que la mejor moneda para mantener el dinero es el USD Coin, el cual no varia mucho, manteniéndose entre u$d0,99 y u$d1,01 la mayor parte del tiempo, además de estar catalogada como la criptomoneda más segura a la hora de invertir debido a este casi nulo movimiento. Si se invierte en este momento, se espera que para dentro de 3 meses, se obtenga una ganancia de 0,99%.

Tercer KPI: Pequeña inversión.

Es una inversión peligrosa y rápida, por lo que se recomienda hacerla en pequeñas cantidades y constantemente ya que en pocos días o inclusive pocas horas puede cambiar un gran porcentaje, son inversiones en nuevas monedas, las cuales llevan días de vida, el análisis demuestra que llegan a tener es sus primeros días una gran volatilidad en sus precios y estando atentos se puede ganar bastante dinero mientras no le pierdas la pisada. Según los gráficos que se analizaron y en donde se seleccionó una de las tres monedas inspeccionadas y podemos prever que si invertimos en la moneda Sei podríamos obtener una ganancia de 24,06% en 24 HS 
