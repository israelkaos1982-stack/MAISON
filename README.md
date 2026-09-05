# Maison

Aplicación Flask que sirve una página única (`templates/index.html`).

## Desarrollo local

```bash
pip install -r requirements.txt
python app.py
```

## Despliegue en Render

- `Procfile` ya define `web: gunicorn app:app`.
- Solo hace falta crear un Web Service en Render apuntando a este
  repositorio; Render detecta `requirements.txt` y `Procfile`
  automáticamente.
