# Maison

Catálogo de perfumes (venta directa + gestión de ventas por Vinted).
Aplicación Flask que sirve una única página autocontenida
(`templates/index.html` — HTML/CSS/JS, todos los datos se guardan en
el `localStorage` del navegador del dispositivo).

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
