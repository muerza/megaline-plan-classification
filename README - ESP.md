# Clasificación de planes Megaline 📱🤖

Proyecto de *Machine Learning* para **recomendar el plan móvil correcto** para clientes de Megaline: **Smart** o **Ultra**.  
El modelo aprende del comportamiento de los usuarios para apoyar **cambios de plan** y reducir el uso de planes antiguos.

---

## Objetivo 🎯
Construir un modelo de clasificación para predecir:
- `is_ultra` (1 = Ultra, 0 = Smart)

Meta mínima:
- ✅ **Accuracy ≥ 0.75**

Dataset:
- `users_behavior.csv`

---

## Enfoque 🧠
- Cargar y explorar los datos
- Dividir en conjuntos de entrenamiento/validación
- Entrenar modelos base (baseline)
- Ajustar hiperparámetros
- Evaluar usando **accuracy** (y revisar la matriz de confusión)

---

## Modelos probados 🔍
- Árbol de decisión
- Random Forest ✅ (final)
- Regresión logística

---

## Resultado ✅
Modelo final: **RandomForestClassifier**

- **Accuracy en validación: 0.8085** 🎯

Esto supera el umbral requerido y ofrece un buen balance entre desempeño y estabilidad.

---

## Estructura sugerida del repositorio 🗂️

```text
.
├── data/
│   └── users_behavior.csv
├── notebooks/
│   └── megaline-plan-classification.ipynb
├── src/                  # (opcional) funciones reutilizables
│   ├── train.py
│   └── utils.py
├── README.md
└── requirements.txt
