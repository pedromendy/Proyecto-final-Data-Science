# Proyecto-final-Data-Science
# 📱 Predicción de Ratings en Google Play Store

Este proyecto usa machine learning para predecir el rating de una app en base a datos como cantidad de reseñas, instalaciones, tipo (gratis/paga), precio y público objetivo.

---

## 🔧 ¿Qué se hizo?

- Limpieza de datos y codificación de variables
- Selección de características con SelectKBest
- Entrenamiento con RandomForestRegressor
- Evaluación con métricas como R², MAE y RMSE

---

## 📊 ¿Qué se encontró?

Las variables más influyentes fueron:
- `Reviews`, `Installs`, `Price`, `Type`, `Content Rating`

La popularidad y el modelo de negocio tienen fuerte impacto en cómo los usuarios valoran una app.

---

## 🚀 Ideas para mejorar

- Usar texto de reseñas con NLP
- Probar otros modelos como XGBoost
- Completar valores faltantes

---

## ✍️ Autor

Pedro — Estudiante de Sistemas en UNSAM, curioso y metódico, buscando siempre entender cómo mejorar lo que hace.
