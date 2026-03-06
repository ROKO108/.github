# 🤝 Guía de Contribución

¡Gracias por querer contribuir! Cualquier aportación es bienvenida. 🙌

## 🚀 Cómo empezar

### 1. Fork y clone

```bash
git clone https://github.com/TU_USUARIO/NOMBRE_REPO.git
cd NOMBRE_REPO
```

### 2. Crea un entorno virtual

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
```

### 3. Instala dependencias de desarrollo

```bash
pip install -e ".[dev]"
# o si usas requirements:
pip install -r requirements-dev.txt
```

### 4. Crea tu rama

```bash
git checkout -b feat/mi-nueva-funcionalidad
# o
git checkout -b fix/nombre-del-bug
```

## 📐 Convenciones

### Commits (Conventional Commits)

```
feat: añadir soporte para X
fix: corregir error en Y
docs: actualizar README
chore: actualizar dependencias
test: añadir tests para Z
refactor: simplificar función W
```

### Código

- Seguimos [PEP 8](https://peps.python.org/pep-0008/)
- Usamos `black` para formateo y `ruff` para linting
- Type hints donde sea posible
- Docstrings en funciones públicas

### Tests

```bash
pytest tests/ -v
pytest tests/ --cov=src --cov-report=term-missing
```

## 📤 Enviar el PR

1. Asegúrate de que los tests pasan
2. Actualiza la documentación si es necesario
3. Abre el PR con la plantilla proporcionada
4. Espera la revisión — suelo responder en 48-72h

## ❓ ¿Dudas?

Abre una [Discussion](https://github.com/ROKO108?tab=discussions) o mencióname en el issue.
