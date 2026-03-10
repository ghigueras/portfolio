# Algorithmic Trading System
**Personal Project | Python, R, REST APIs, Machine Learning | 2020-Present**

## Context
Motivated by a deep interest in financial markets and a desire to apply software
engineering skills beyond professional work, I conceived and built from scratch
a fully automated trading system capable of operating in live forex and index
markets. The project evolved in two major phases: a rule-based strategy engine
and a later machine learning extension developed after completing a Master's in
Big Data and Machine Learning.

## My Role
Solo developer and product owner. Responsible for concept, architecture, 
development, testing and deployment of the entire system.

## Approach
The system was built around Oanda's REST API, which provided real-time market
data and allowed programmatic execution of trades on a live account. Strategies
were defined using classical technical analysis indicators and validated through
a backtesting engine built before deploying to production. After completing the
Master's, the system was extended with a machine learning layer that predicted
market direction as an additional input signal.

## Key Deliverables

### Phase 1 – Rule-Based Trading Engine
- Integrated with Oanda REST API for real-time data retrieval and order execution
- Implemented technical indicator library including Bollinger Bands, RSI, MACD
  and weighted moving averages
- Built custom backtesting engine to validate strategies against historical data
  before live deployment
- Developed position management logic including entry, exit, stop-loss and
  take-profit rules
- Backtesting code publicly available on GitHub

### Phase 2 – Machine Learning Extension
- Engineered feature set from technical indicators as model inputs
- Trained classification models to predict market direction (bull/bear)
- Integrated model output as an additional trading signal within the existing
  strategy engine
- Applied knowledge from Master's in Big Data and Machine Learning to a
  real-world financial domain

## Technical Notes
The production system is not publicly available as it contains API credentials
linked to a live Oanda trading account. The backtesting repository on GitHub
demonstrates the core strategy logic, indicator implementation and system
architecture.

## Tools & Technologies
Python, REST APIs, Oanda API, Bollinger Bands, RSI, MACD, Weighted Moving
Averages, Scikit-learn, Machine Learning, Backtesting, Financial Markets,
Forex, Index Trading

---

# Sistema de Trading Algorítmico
**Proyecto Personal | Python, REST APIs, Machine Learning | 2015-Presente**

## Contexto
Motivado por un profundo interés en los mercados financieros y el deseo de
aplicar conocimientos de ingeniería de software más allá del trabajo
profesional, concebí y desarrollé en solitario un sistema automatizado de
trading capaz de operar en mercados reales de divisas e índices. El proyecto
evolucionó en dos fases principales: un motor de estrategias basado en reglas
y una extensión de machine learning desarrollada tras completar el Máster en
Big Data y Machine Learning.

## Mi Rol
Desarrollador en solitario y product owner. Responsable de la concepción,
arquitectura, desarrollo, pruebas y despliegue del sistema completo.

## Enfoque
El sistema se construyó sobre la API REST de Oanda, que proporcionaba datos de
mercado en tiempo real y permitía la ejecución programática de operaciones sobre
una cuenta real. Las estrategias se definieron usando indicadores de análisis
técnico clásico y se validaron mediante un motor de backtesting construido antes
del despliegue en producción. Tras completar el Máster, el sistema se amplió con
una capa de machine learning que predecía la dirección del mercado como señal
adicional de entrada.

## Entregables Clave

### Fase 1 – Motor de Trading Basado en Reglas
- Integración con la API REST de Oanda para obtención de datos en tiempo real
  y ejecución de órdenes
- Implementación de librería de indicadores técnicos incluyendo Bandas de
  Bollinger, RSI, MACD y medias móviles ponderadas
- Construcción de motor de backtesting propio para validar estrategias contra
  datos históricos antes del despliegue en producción
- Desarrollo de lógica de gestión de posiciones incluyendo entrada, salida,
  stop-loss y take-profit
- Código del backtesting disponible públicamente en GitHub

### Fase 2 – Extensión de Machine Learning
- Ingeniería de características a partir de indicadores técnicos como inputs
  del modelo
- Entrenamiento de modelos de clasificación para predecir la dirección del
  mercado (bull/bear)
- Integración del output del modelo como señal adicional de trading dentro del
  motor de estrategias existente
- Aplicación práctica de los conocimientos del Máster en Big Data y Machine
  Learning a un dominio financiero real

## Notas Técnicas
El sistema de producción no está disponible públicamente ya que contiene
credenciales de API vinculadas a una cuenta real de Oanda. El repositorio de
backtesting en GitHub muestra la lógica central de las estrategias, la
implementación de indicadores y la arquitectura del sistema.

## Herramientas y Tecnologías
Python, APIs REST, API de Oanda, Bandas de Bollinger, RSI, MACD, Medias Móviles
Ponderadas, Scikit-learn, Machine Learning, Backtesting, Mercados Financieros,
Forex, Trading de Índices
