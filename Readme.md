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

### Institute

GET http://127.0.0.1:8000/institute/get_institute/

```
[]
```

POST http://127.0.0.1:8000/institute/add_institute/

```
{

  "institute_name": "Prime Talent Academy",

  "contact_number": "9876543210",

  "email": "contact@primetalent.com",

  "course_offered": "Java Full Stack",

  "tech_stack": "Java, Spring Boot, Angular",

  "city": "Mumbai",

  "address": "Andheri East, Mumbai"

}
```

GET http://127.0.0.1:8000/institute/get_institute/

```
output here
```
