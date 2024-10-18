# ITRADE
ITRADE

# DESCRIPCION DEL PROYECTO

Aplicación que permita analizar empresas en masa y que nos proporcione entradas de compra. Buscamos empresas que potencialmente vayan a subir y evitamos las empresas "caras". Comenzaremos con una empresa simulada e iremos escalando la funcionalidad.

## FASES

1. Estudiar tecnologias mas adecuadas para este proposito
2. Estudiar todas las variables a tener en cuenta para un analisis, ejemplo P/E
3. Encontrar fuentes de datos de calidad
4. Analizar una empresa a pincho
5. Escalar hasta un proceso automatizado de gran escala


# 1.TECNOLOGIAS

**FRONT:**


**BACKEND: (Pendientes de confirmar)**
-Python para analizar datos en masa y aplicar algoritmos complejos
-NodeJS por agilidad y facilidad de implementar varios procesos paralelos

**SERVIDOR:**
Cloud?

# 2.Variables que necesitamos para un analisis óptimo

# 3.Fuentes de datos

Necesitamos información, estudiar todas las APIS gratuitas o programas avanzados de scraping que nos la puedan proporcionar. Hacer Scraping de forma manual en principio no es nuestro objetivo debido a la gran inversion de tiempo y la posible obsolesencia del codigo, buscar herramientas que puedan automatizar esto (mirar punto 3.2)

# 3.1 APIS PÚBLICAS

**PROBAR CADA UNA DE ELLAS Y ANALIZAR LA CALIDAD DE LOS DATOS PARA LOGRAR NUESTROS OBJETIVOS** , poner valoración de 1 al 10 cuando sean probadas, despues se debatirá su posible implementación

**Yahoo Finance API (a través de terceros)**

Descripción: Yahoo Finance es una de las fuentes de datos financieros más populares. Aunque no ofrece una API oficial gratuita, algunos desarrolladores han creado APIs no oficiales que permiten acceder a sus datos.
Datos disponibles: Precios históricos de acciones, datos fundamentales, cotizaciones en tiempo real, etc.
Límites: Gratis para uso limitado; no es la API oficial, por lo que puede tener limitaciones o cambios sin previo aviso.
Proveedores:
yfinance: Biblioteca Python basada en Yahoo Finance.
Alternativas no oficiales como YahooFinanceAPI.

**Alpha Vantage**

Descripción: Una API muy popular para el análisis técnico y financiero.
Datos disponibles: Datos de mercado en tiempo real y retrasados, indicadores de análisis técnico, tasas de cambio, y datos fundamentales.
Límites: 500 solicitudes diarias en el plan gratuito.
URL: Alpha Vantage

**IEX Cloud**

Descripción: API que ofrece datos de mercado de EE. UU. y otros tipos de datos financieros.
Datos disponibles: Precios de acciones en tiempo real, datos históricos, noticias financieras, entre otros.
Límites: Hasta 10,000 mensajes en el plan gratuito.
URL: IEX Cloud

**Finnhub**

Descripción: API gratuita para datos de mercado, análisis técnico, noticias, y mucho más.
Datos disponibles: Cotizaciones de acciones en tiempo real, análisis técnico, sentimiento de noticias, indicadores económicos y eventos corporativos.
Límites: 60 llamadas por minuto en el plan gratuito.
URL: Finnhub

**Financial Modeling Prep (FMP)**

Descripción: Ofrece una API gratuita que proporciona datos fundamentales de empresas, cotizaciones, balances financieros, y más.
Datos disponibles: Datos históricos, informes financieros, ratios, precios de acciones, entre otros.
Límites: Plan gratuito con limitaciones en la cantidad de llamadas diarias.
URL: Financial Modeling Prep

**News API**

Descripción: API para consultar noticias actuales de múltiples fuentes y medios globales.
Datos disponibles: Noticias de varias fuentes como CNN, Bloomberg, Reuters, y más.
Límites: 500 solicitudes diarias en el plan gratuito.
URL: News API

**Tradier**

Descripción: Plataforma de broker que ofrece una API gratuita para acceder a datos de mercado y realizar operaciones.
Datos disponibles: Precios en tiempo real, opciones, datos históricos, y ejecución de operaciones (para cuentas activas).
Límites: Plan gratuito limitado a datos en tiempo real de acciones y opciones.
URL: Tradier

**Quandl (ahora parte de Nasdaq Data Link)**

Descripción: Base de datos financiera que proporciona acceso a diversos conjuntos de datos económicos y financieros.
Datos disponibles: Datos de acciones, bonos, commodities, tasas de interés, divisas, etc.
Límites: Plan gratuito limitado a 50 llamadas por día.
URL: Quandl

**Polygon.io**

Descripción: Ofrece datos financieros como cotizaciones de acciones, divisas, y criptomonedas.
Datos disponibles: Precios en tiempo real, históricos y noticias sobre acciones y criptomonedas.
Límites: 5 solicitudes por minuto en el plan gratuito.
URL: Polygon.io

**World Trading Data (WTD)**

Descripción: API de datos financieros y de mercado en tiempo real.
Datos disponibles: Precios históricos de acciones, divisas, criptomonedas y noticias financieras.
Límites: 250 solicitudes diarias en el plan gratuito.
URL: World Trading Data

**OpenFIGI**

Descripción: Proporciona identificadores únicos globales (FIGI) para activos financieros.
Datos disponibles: Información sobre títulos financieros, identificación de instrumentos y metadatos.
Límites: Acceso gratuito a la API.
URL: OpenFIGI

**FRED API (Federal Reserve Economic Data)**

Descripción: API que proporciona acceso a miles de series de datos económicos y financieros.
Datos disponibles: Indicadores económicos, tasas de interés, datos de crecimiento económico, y más.
Límites: Acceso gratuito.
URL: FRED API

# 3.2 Fuentes de datos (Scraping)

Scraping
https://github.com/openbullet/openbullet

# 4.COMPLETAR PASOS PREVIOS
# 5.COMPLETAR PASOS PREVIOS
