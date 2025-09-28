# ML_project3 — кросс валидация, Optuna, SHAP

Проект показывает реализацию различных методов распределения данных на выборки, подбор параметров по их важности и оптимизацию гиперпараметров через Optuna.

## Сборка
```bash
python -m venv .venv
source .venv/bin/activate        # macOS/Linux
.venv\Scripts\Activate.ps1     # Windows

pip install -r requirements.txt # установка пакетов
```
---
Данные для обучения и тестирования лежат в /data
Логика в /src