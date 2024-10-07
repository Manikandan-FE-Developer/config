## Backend Project Structure

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



## Frontend Project Structure

The frontend project is organized as follows:

```
frontend/
│
├── public/
│   └── images/
│
├── src/
│   ├── assets/
│   │   └── ...
│   ├── components/
│   │   ├── Common.tsx
│   │   ├── GenerateConfig.tsx
│   │   ├── Harness.tsx
│   │   ├── Header.tsx
│   │   ├── KeyValue.tsx
│   │   ├── Sidebar.tsx
│   │   └── UploadConfig.js
│   ├── constants.ts
│   └── main.tsx
│
├── index.html
├── package.json
└── README.md
```

## Technologies Used

- **React**: A JavaScript library for building user interfaces, enabling the creation of reusable UI components.
- **React Router**: For managing routing and navigation within the application.
- **Axios**: A promise-based HTTP client for making API requests.
- **React Toastify**: For displaying toast notifications.
- **CSS Modules or Styled Components**: For styling components with scoped CSS.
- **JavaScript (ES6+)**: Utilizing modern JavaScript features for development.
- **npm**: Node package manager used for managing dependencies.
