# Clasificador sobre retención de clientes

Se realiza un análisis para la retención de clientes de una empresa de telecomunicaciones, utilizando árboles de decisión y bosque aleatorio para entender las características más relevantes para la retención de clientes de una empresa de telecomunicaciones.

El conjunto de datos se tomó de [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn) Éste cuenta con 7,043 renglones y 21 columnas.

Cada renglón representa un cliente y cada columna un atributo. Entre los atributos se incluyen:

- _Características socidemograficas_: sexo, si tienen pareja y dependientes económicos
- _Información de la cuenta_: antiguedad como cliente en la compañía, contrato, forma de pago, monto del pago mensual, etc
- _Servicios que recibe_: telefono, si tiene multiples líneas, internet, seguridad, respaldos, TV, etc
- _Churn_: Clientes que se abandonaron la compañía en el último mes 
  
En la fase de preprocesamiento, se elimina el customerID, se sustituyen los valors nulos por 0 (solo 11, presentes en la variable TotalCharges), y se realiza una transformación de las variables categóricas en binarias mediante la codificación **One Hot Encoding**.
