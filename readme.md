# FastAPI Application

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Locally

```bash
python main.py
```

The application will be available at:

```text
http://localhost:8000
```

## Run with Docker

Build and start the containers:

```bash
docker compose up --build
```

The application will be available at:

```text
http://localhost:8000
```

## Services

- `app` — FastAPI application
- `postgres` — PostgreSQL database
