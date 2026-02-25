# ML_project3 — кросс валидация, Optuna, SHAP

Проект показывает реализацию различных методов распределения данных на выборки, подбор параметров по их важности и оптимизацию гиперпараметров через Optuna.

## Установка зависимостей
Windows:
```powershell
cd path\to\ML_project3
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

macOS / Linux:
```bash
cd /path/to/ML_project3
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirments.txt
```


---
Данные для обучения и тестирования лежат в /data
Логика кросс валидации в /src
