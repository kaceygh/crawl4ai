web: uvicorn app.main:app --host 0.0.0.0 --port $PORT --workers 2
health: curl -fs http://localhost:$PORT/health || exit 1
