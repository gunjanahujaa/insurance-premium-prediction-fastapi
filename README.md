# 🏥 Insurance Premium Prediction API

A Machine Learning API built using **FastAPI** that predicts insurance premiums based on user information.

> **Note:** This project was built as part of my FastAPI learning journey by following the CampusX FastAPI playlist. I implemented the API, refactored it into a modular project structure, and used it to understand how ML models can be served through REST APIs.

---

## Features

- Predict insurance premium using a trained ML model
- FastAPI backend
- Input validation using Pydantic
- Modular project structure
- Interactive Swagger UI
- JSON responses

---

## Tech Stack

- Python
- FastAPI
- Pydantic
- Pandas
- Scikit-learn
- Uvicorn

---

## Project Structure

```text
.
├── app.py
├── frontend.py
├── insurance.csv
├── config/
├── model/
├── schema/
└── requirements.txt
```

---

## How to Run

1. Clone the repository
2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Start the server

```bash
uvicorn app:app --reload
```

4. Open your browser and visit:

```
http://127.0.0.1:8000/docs
```

---

## 📌 API Endpoint

**POST** `/predict`

Returns the predicted insurance premium based on the input data.

---

## 👩‍💻 Author

**Gunjan Ahuja**