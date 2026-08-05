# ConnectaTel
sprint7-final-project

# Análisis y Segmentación de Clientes - ConnectaTel

## 🎯 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel a partir de variables relacionadas con su edad y el uso de los servicios de comunicación.

El análisis busca identificar patrones de uso, detectar valores extremos y segmentar a los clientes según su nivel de utilización y edad, con el fin de generar conclusiones y recomendaciones comerciales que ayuden a ConnectaTel en la toma de decisiones.

## 📊 Datasets utilizados

Para el desarrollo del proyecto se utilizaron los datos proporcionados para el análisis de clientes de ConnectaTel.

Las principales variables utilizadas incluyen:

- `age`: edad del usuario.
- `plan`: plan contratado.
- `calls`: cantidad de llamadas.
- `texts`: cantidad de mensajes.
- `minutes`: total de minutos de llamadas.

A partir de estas variables se construyó y analizó el dataframe `user_profile`.

## 🔎 Etapas del análisis

El proyecto se desarrolló en las siguientes etapas:

### 1. Preparación y revisión de los datos

Se revisó la estructura y calidad de los datos y se realizaron las transformaciones necesarias para preparar las variables para el análisis.

### 2. Análisis exploratorio

Se analizaron las principales variables relacionadas con los clientes y su comportamiento de uso.

Se estudiaron:

- Edad.
- Cantidad de llamadas.
- Cantidad de mensajes.
- Total de minutos de llamadas.
- Plan contratado.

### 3. Visualización de distribuciones

Se utilizaron histogramas para analizar la distribución de:

- `age`
- `texts`
- `calls`
- `minutes`

Los histogramas permitieron comparar el comportamiento de los usuarios según el plan.

### 4. Identificación de outliers

Se utilizaron boxplots para detectar valores extremos en las variables de edad y uso.

Los outliers identificados principalmente en llamadas, mensajes y minutos de llamadas fueron revisados y se decidió conservarlos porque pueden representar comportamientos reales de usuarios con alto consumo.

### 5. Segmentación por nivel de uso

Los usuarios fueron clasificados en tres grupos:

- **Bajo uso:** llamadas < 5 y mensajes < 5.
- **Uso medio:** llamadas < 10 y mensajes < 10.
- **Alto uso:** resto de los casos.

### 6. Segmentación por edad

Los usuarios fueron clasificados en:

- **Joven:** edad < 30 años.
- **Adulto:** edad < 60 años.
- **Adulto Mayor:** resto de los casos.

### 7. Visualización de segmentos

Se utilizaron gráficos de barras para visualizar la cantidad de usuarios pertenecientes a cada grupo de uso y grupo de edad.

### 8. Insight ejecutivo

Finalmente, los resultados fueron traducidos en conclusiones y recomendaciones orientadas a la segmentación comercial, los patrones de uso y las oportunidades de mejora de los planes de ConnectaTel.

## 💡 Principales conclusiones

El análisis permitió identificar diferentes perfiles de clientes según su edad y nivel de utilización de los servicios.

Los usuarios de alto uso representan un segmento de especial interés comercial debido a su mayor intensidad de utilización de llamadas y mensajes.

También se identificaron usuarios con consumos elevados de minutos de llamadas. Estos valores extremos no fueron eliminados automáticamente porque pueden representar clientes reales con un comportamiento de consumo intensivo.

La combinación de edad y nivel de uso permite desarrollar estrategias comerciales más personalizadas.

## 🚀 Recomendaciones

Se recomienda desarrollar ofertas diferenciadas según el nivel de uso:

- Planes económicos para usuarios de bajo uso.
- Estrategias de fidelización y migración para usuarios de uso medio.
- Planes Premium o de mayor capacidad para usuarios de alto uso.

También se recomienda combinar la segmentación por edad con el nivel de uso para crear campañas comerciales más personalizadas.

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Google Colab
- GitHub

## ▶️ Cómo ejecutar el proyecto

1. Ingresar al repositorio público de GitHub.
2. Entrar a la carpeta `notebooks`.
3. Abrir el archivo `ConnectaTel_Analisis_Final.ipynb`.
4. Descargar el notebook mediante la opción de descarga de GitHub.
5. Abrir el archivo en Google Colab.
6. Cargar o verificar la disponibilidad de los datasets requeridos.
7. Ejecutar las celdas en orden desde el inicio hasta el final.
8. Revisar los resultados, gráficos, insights y conclusiones del análisis ejecutivo.

## 🔄 Guía de reproducción

1. Descargar el archivo `.ipynb` desde este repositorio.
2. Abrir el notebook en Google Colab.
3. Cargar o verificar la disponibilidad de los datasets requeridos.
4. Ejecutar las celdas en orden.
5. Reproducir las etapas de limpieza y preparación de datos.
6. Ejecutar el análisis exploratorio y las visualizaciones.
7. Analizar los outliers identificados.
8. Crear y analizar los segmentos `grupo_uso` y `grupo_edad`.
9. Revisar el análisis ejecutivo y las recomendaciones finales.
    
## 🔗 Repositorio público

https://github.com/elianacarolinaecheverrit-maker/ConnectaTel-analysis
