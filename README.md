# Futebol IA Global — MVP
Aplicativo web para análise de partidas e jogadores.
Inclui API FastAPI, motor inicial de probabilidades e painel web.
Os dados incluídos são demonstrativos; para produção, conecte um provedor de dados esportivos no `data_provider.py`.

## Executar
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload

Depois abra `frontend/index.html`.
