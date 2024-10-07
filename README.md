## Project Structure

The backend project is organized as follows:

```
backend/
│
├── app/
│   ├── api/
│   │   ├── controllers/
│   │   │   └── config/
│   │   └── ...
│   ├── client/
│   │   └── ...
│   ├── datagenerator/
│   │   └── ...
│   ├── harness/
│   │   └── ...
│   ├── middlewares/
│   │   └── ...
│   └── schemas/
│       └── ...
├── database/
│   └── ...
├── dependencies/
│   └── ...
├── logs/
│   └── ...
├── models/
│   └── ...
├── repository/
│   └── ...
├── routes/
│   └── ...
├── services/
│   └── ...
├── utils/
│   └── ...
├── .env
├── main.py
├── settings.py
├── .gitignore
├── README.md
└── requirements.txt
```

## Technologies Used

- **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.7+ based on standard Python type hints.
- **Pydantic**: Used for data validation and settings management through Python type annotations.
- **Uvicorn**: A lightning-fast ASGI server implementation, using `uvloop` and `httptools`.
- **SQLAlchemy**: The SQL toolkit and Object-Relational Mapping (ORM) system for Python.
- **Alembic**: A lightweight database migration tool for use with SQLAlchemy.
- **Python Dotenv**: For loading environment variables from a `.env` file.
- **Pydantic-Settings**: For enhanced settings management with Pydantic.
- **Logging**: Python’s built-in logging module for tracking application behavior and errors.
