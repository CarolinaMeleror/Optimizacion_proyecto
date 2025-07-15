🎮 Predicción de Ventas de Videojuegos - VentaGamer

  📋 Descripción

  Análisis de Machine Learning para predecir ventas globales de videojuegos usando datos históricos de 16,600 juegos (1980-2020).

  🎯 Objetivo

  Predecir las ventas globales de videojuegos basándose en características como plataforma, género, año y ventas regionales.

  📊 Dataset

  - Fuente: Dataset VentaGamer
  - Registros: 16,598 videojuegos
  - Período: 1980-2020
  - Variables: 11 (plataforma, género, año, ventas por región)

  🤖 Modelos Implementados

  Versión Básica:

  - Regresión Lineal
  - Random Forest

  Versión Avanzada:

  - Linear Regression, Ridge, Lasso
  - KNN, Decision Tree, Random Forest
  - XGBoost, LightGBM (si disponibles)

  🔧 Técnicas Aplicadas

  - Limpieza: Imputación, manejo de outliers
  - Preprocesamiento: ColumnTransformer, StandardScaler, OneHotEncoder
  - Pipelines: Automatización completa
  - Optimización: GridSearchCV, RandomizedSearchCV, Optuna
  - Transformaciones: Logarítmicas para normalizar ventas

  📈 Resultados

  - Mejor modelo: [Se determina automáticamente]
  - Métricas: RMSE, R², MAE
  - Validación: Validación cruzada de 5 folds

  🏆 Características Más Importantes

  1. Ventas en Norteamérica (NA_Sales)
  2. Ventas en Europa (EU_Sales)
  3. Ventas en Japón (JP_Sales)
  4. Plataforma del juego
  5. Género del videojuego

  📁 Estructura

  EDA_VentaGamer.ipynb    # Análisis completo
  ├── Secciones 1-15      # EDA básico
  ├── Secciones 16-22     # ML básico
  └── Secciones 23-30     # ML avanzado

  🚀 Uso

  # Ejecutar notebook paso a paso
  # Versión básica: Secciones 16-22
  # Versión avanzada: Secciones 23-30

  💡 Aplicaciones

  - Predicción de ventas para nuevos lanzamientos
  - Decisiones de plataforma y género
  - Planificación de marketing regional
  - Análisis de mercado de videojuegos

  👩‍💻 Autora

  Carolina Melero - Proyecto de Machine Learning

  ---Predicción inteligente de ventas de videojuegos con ML 🎮
