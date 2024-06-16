# RocketHackathon 2024

## Autores
- José Abraham Martínez Licona, México
- Sofía Álvarez Sandoval, México
- Kevin Antonio González Díaz, México
- Yuu Ricardo Akachi Tanaka, México 

**Fecha:** Junio 16, 2024

## Desafío 3: "Hackea el churn: anticipando e identificando la posible baja de clientes" - Rocket Hackathon 2024

Este repositorio de GitHub contiene los códigos desarrollados para el Desafío 3 del Rocket Hackathon 2024, titulado "Hackea el churn: anticipando e identificando la posible baja de clientes". El objetivo de este desafío es predecir la deserción de clientes de los servicios de Arca Continental, la segunda embotelladora más grande de Latinoamérica, que abastece a más de 200,000 tienditas en la región. Para ello, se implementaron múltiples modelos de aprendizaje automático, optimizados para identificar con precisión a los clientes propensos a darse de baja.

## Preprocesamiento de los Datos

El preprocesamiento de los datos se realizó utilizando el archivo CSV `sales.csv`. Se eliminaron los registros de clientes del mes de noviembre de 2023 debido a que estos datos contenían valores nulos en `churn_next_month`, ya que son los datos de predicción. Posteriormente, la variable `month` se transformó a formato de fecha para permitir la ordenación y agrupación de los datos por `customer_id`. Esto facilitó la generación de columnas para la variable `amount` correspondientes a cada mes y registro. Además, se aplicó un padding al inicio de los registros para igualar la longitud de los arrays con menores datos de `amount`. Finalmente, se agregó el valor correspondiente de `churn_next_month` a cada registro.

## Modelo de predicción XGBoost con Ventana de Tiempo



## Modelo de predicción Random Forest con TDA

## Algoritmo Mapper

