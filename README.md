# Prácticas TAH

Cuaderno digital de prácticas del módulo profesional 1374, Técnicas de análisis hematológico (CFGS Laboratorio Clínico y Biomédico, curso 2026–2027).

Este repositorio sirve como **plantilla**. En GitHub, pulsa **Use this template → Create a new repository** para obtener una copia personal. Activa **Settings → Pages → GitHub Actions** en tu nuevo repositorio; el workflow incluido compila y publica el sitio después de cada envío a `main`.

## Desarrollo local

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Abre `http://127.0.0.1:8000/`. Para comprobar la compilación antes de guardar cambios:

```bash
python -m mkdocs build --strict
```

Las prácticas están en `docs/practicas-generadas/`. Consulta `docs/assets/README.md` para añadir evidencias visuales. Protege los datos personales y clínicos; publica imágenes solo con autorización.
