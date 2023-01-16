# Myrh
# Enpoint for the Myrh API
### Request Search
`GET /api/v1/public/offers/search?title=java&domain=IT&education_level=MASTER&salary=1000`
### Response
```json
{
    "id": 1,
    "title": "Java Developer",
    "description": "We are looking for a Java Developer",
    "domain": "IT",
    "education_level": "MASTER",
    "salary": 1000,
    "company": {
        "id": 1,
        "name": "Myrh",
        "description": "Myrh is a company",
        "address": "Myrh address",
        "city": "Myrh city",
        "country": "Myrh country",
        "email": "test@test.io",
        "phone": "123456789",
     }
}
```
### Request Get All Offers for User
`GET /api/v1/public/offers?pageNumber=0&size=2`
### Response
```json
{
    "content": [
        {
            "id": 1,
            "title": "Java Developer",
            "description": "We are looking for a Java Developer",
            "domain": "IT",
            "education_level": "MASTER",
            "salary": 1000,
            "company": {
                "id": 1,
                "name": "Myrh",
                "description": "Myrh is a company",
                "address": "Myrh address",
                "city": "Myrh city",
                "country": "Myrh country",
                "email": "test@test.io"
                "phone": "123456789"
            }
        },
        {
            "id": 2,
            "title": "Java Developer",
            "description": "We are looking for a Java Developer",
            "domain": "IT",
            "education_level": "MASTER",
            "salary": 1000,
            "company": {
                "id": 1,
                "name": "Myrh",
                "description": "Myrh is a company",
                "address": "Myrh address",
                "city": "Myrh city",
                "country": "Myrh country",
                "email": "testi@testt.io"
                "phone": "123456789"
            }
    ]
}
```


