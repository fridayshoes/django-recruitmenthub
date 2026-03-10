## Recruitment Hub - Backend

Features to implement:

- Enroll trainers
- Enroll institutes
- Enroll company

## Installation

Crearte virtual environment

```
pip install -r requirements.txt
```

Adds middleware that, allows your Angular frontend (e.g., ) to call your Django API ().

```
pip install django-cors-headers
```

### Enroll trainers

GET http://127.0.0.1:8000/trainer/get_trainer to see a JSON list of trainers

POST http://127.0.0.1:8000/trainer/add_trainer/ to add a trainer

Eg.

```
{
  "name": "David",
  "contact": "123456789",
  "address": "UK",
  "tech_stack": "Java, Spring Boot, Angular",
  "total_experience": 5.5
}
```
