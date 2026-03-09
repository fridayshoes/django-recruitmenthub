## Recruitment Hub

Features to implement:

- Enroll trainers
- Enroll institutes
- Enroll company

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
