Despliegue en Render:
1) Subir a GitHub los archivos de este ZIP.
2) Render -> New Web Service -> Conectar repo.
3) Build Command: pip install -r requirements.txt
4) Start Command: gunicorn app:app
5) Abrir la URL pública que Render provea.
