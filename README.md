# 🏥 Insurance Premium Prediction API

A Machine Learning API built using **FastAPI** that predicts insurance premiums based on user information.

> **Note:** This project was built as part of my FastAPI learning journey by following the CampusX FastAPI playlist. I implemented the API, refactored it into a modular project structure, and later containerized the application using Docker to understand how ML models can be packaged and deployed.

---

## 🚀 Features

- Predict insurance premium using a trained Machine Learning model
- FastAPI backend
- Input validation using Pydantic
- Modular project structure
- Interactive Swagger UI
- JSON responses
- Docker support for containerized deployment

---

## 🛠️ Tech Stack

- Python
- FastAPI
- Pydantic
- Pandas
- Scikit-learn
- Uvicorn
- Docker

---

## 📂 Project Structure

```text
.
├── app.py
├── frontend.py
├── insurance.csv
├── config/
├── model/
├── schema/
├── Dockerfile
└── requirements.txt
```

---

# ▶️ Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/gunjanahujaa/insurance-premium-prediction-fastapi.git
cd insurance-premium-prediction-fastapi
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Start the FastAPI server

```bash
uvicorn app:app --reload
```

### 4. Open the API documentation

```
http://127.0.0.1:8000/docs
```

---

# 🐳 Run with Docker

### Build the Docker image

```bash
docker build -t gunjanahujaa/insurance-premium-api .
```

### Run the Docker container

```bash
docker run -p 8000:8000 gunjanahujaa/insurance-premium-api
```

### Pull directly from Docker Hub

```bash
docker pull gunjanahujaa/insurance-premium-api
docker run -p 8000:8000 gunjanahujaa/insurance-premium-api
```

After running the container, open:

```
http://localhost:8000/docs
```

---

## 📌 API Endpoint

### POST `/predict`

Returns the predicted insurance premium based on the input features provided by the user.

---

## 📚 Concepts Practiced

- FastAPI
- REST API Development
- Request Validation with Pydantic
- Machine Learning Model Serving
- Docker Images
- Docker Containers
- Docker Hub
- API Documentation using Swagger UI

---

## 👩‍💻 Author

**Gunjan Ahuja**

- GitHub: https://github.com/gunjanahujaa
- Docker Hub: https://hub.docker.com/u/gunjanahujaa
