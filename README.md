📌 Description

This notebook implements a trading bot in Python that connects to the Binance API and applies different technical indicators, with a special focus on Bollinger Bands.

📊 Bollinger Bands Strategy

Bollinger Bands are a volatility indicator composed of:

Simple Moving Average (SMA) in the middle.

Upper Band: SMA + (standard deviation × factor).

Lower Band: SMA – (standard deviation × factor).

In this project, the bot:

Retrieves historical price data from Binance (OHLCV candles).

Automatically calculates the SMA and standard deviation.

Plots the upper and lower bands around the price.

Helps identify key moments:

Price touching the upper band → possible overbought signal.

Price touching the lower band → possible oversold signal.

⚙️ Technologies used

Python 🐍

python-binance

pandas 📊

🔒 Security

⚠️ Note: Do not include your Binance API keys (API_KEY and API_SECRET) directly in the public notebook. Use environment variables or a .env file instead.

👉 In summary: this notebook connects to Binance, retrieves cryptocurrency data, and applies the Bollinger Bands strategy to analyze volatility and detect potential entry or exit points in the market.
_________________________________________________________________________________________________________________________________________________________________________________________________________
📌 Descripción

Este notebook implementa un bot de trading en Python que se conecta a la API de Binance y aplica diferentes indicadores técnicos, con un enfoque especial en las Bandas de Bollinger.

📊 Estrategia de Bandas de Bollinger

Las Bandas de Bollinger son un indicador de volatilidad compuesto por:

Media móvil simple (SMA) en el centro.

Banda superior: SMA + (desviación estándar × factor).

Banda inferior: SMA – (desviación estándar × factor).

En este proyecto, el bot:

Obtiene datos históricos de precios de Binance (velas OHLCV).

Calcula automáticamente la SMA y la desviación estándar.

Traza las bandas superior e inferior alrededor de los precios.

Permite identificar momentos clave:

Precio tocando la banda superior → posible sobrecompra.

Precio tocando la banda inferior → posible sobreventa.

⚙️ Tecnologías utilizadas

Python 🐍

python-binance

pandas 📊

🔒 Seguridad

⚠️ Nota: No incluyas tus claves de Binance (API_KEY y API_SECRET) directamente en el notebook público. Usa variables de entorno o un archivo .env.

👉 En resumen: este notebook conecta con Binance, obtiene datos de criptomonedas y aplica la estrategia de Bandas de Bollinger para analizar la volatilidad y detectar posibles puntos de entrada o salida en el mercado.
