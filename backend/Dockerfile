FROM python:3.11-slim

WORKDIR /backend

COPY . .
RUN useradd -m appuser
USER appuser

CMD ["python3", "server.py"]