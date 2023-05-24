# services APIs

## Bank
### endpoint
    - {{uri}}/api/service/bank/
    - body
        {
            "location": "mansoura"
        }
    
### output
    [
        {
            "id": 1,
            "name": "CIB",
            "location": "Egypt, Mansoura",
            "image": "https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/Cib_Logo.svg/2560px-Cib_Logo.svg.png",
            "description": "It is commercial bank",
            "link": "https://www.cibeg.com/",
            "telephone": "+202 19666"
        },
        {
            "id": 2,
            "name": "Blom Bank Egypt",
            "location": "35, Saad Zaghloul St., Torail - El Mansoura",
            "image": "https://media.licdn.com/dms/image/C4E0BAQHZlPWSr6HVeg/company-logo_200_200/0/1615731922466?e=2147483647&v=beta&t=nrlNShBcT4hk3P7bUu73kq1Nr-_Peo7JEv9XNUQBNGc",
            "description": "Mansoura Branch",
            "link": "https://www.blombankegypt.com/BlomEgypt/Mansoura",
            "telephone": null
        }
    ]

-------------------

### endpoint
    - {{uri}}/api/service/bank/1/
    - 1 -> bank id

### output
    {
        "id": 1,
        "name": "CIB",
        "location": "Egypt, Mansoura",
        "image": "https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/Cib_Logo.svg/2560px-Cib_Logo.svg.png",
        "description": "It is commercial bank",
        "link": "https://www.cibeg.com/",
        "telephone": "+202 19666"
    }


============================
## Restraunt

### endpoint
    - {{uri}}/api/service/restaurant/
    - body
        {
            "location": "mansoura"
        }

### output

    [
        {
            "id": 1,
            "name": "Elsabah",
            "location": "Egypt, Mansoura",
            "image": "https://lh5.googleusercontent.com/p/AF1QipN3-9gpbNbbt18puW9rsNm_veB45CLMUABdQlxj=w114-h114-n-k-no",
            "description": "",
            "telephone": null,
            "website": null,
            "open_from": null,
            "open_to": null,
            "rating": 4,
            "cuisines": "",
            "features": "",
            "meals": "",
            "type_r": null,
            "menu": null
        }
    ]

------------------

### endpoint
    - {{uri}}/api/service/restaurant/1/
    - 1 -> is the restraunt id

### output
    {
        "id": 1,
        "name": "Elsabah",
        "location": "Egypt, Mansoura",
        "image": "https://lh5.googleusercontent.com/p/AF1QipN3-9gpbNbbt18puW9rsNm_veB45CLMUABdQlxj=w114-h114-n-k-no",
        "description": "",
        "telephone": null,
        "website": null,
        "open_from": null,
        "open_to": null,
        "rating": 4,
        "cuisines": "",
        "features": "",
        "meals": "",
        "type_r": null,
        "menu": null
    }

=======================

## Hotel

### endpoint
    - {{uri}}/api/service/hotel/
    - body  
        {
            "location": "mansoura"
        }

### body
    [
        {
            "id": 1,
            "name": "El mansour hotel apartmen 84",
            "location": "حى الجامعة, 35111 Mansoura, Egypt",
            "image": "https://cf.bstatic.com/xdata/images/hotel/max1280x900/407744992.jpg?k=8c9208ab49a459a393581a64f4bf21828dff5e85e17350deeeadd33fb12aa4d5&o=&hp=1",
            "description": "Featuring accommodation with a balcony, El mansour hotel apartmen 84 is located in Mansoura. The property provides a 24-hour front desk and free WiFi is available throughout the property.\r\n\r\nThe air-conditioned aparthotel consists of 2 bedrooms, a living room, a fully equipped kitchenette with a microwave and a kettle, and 1 bathroom with a bidet and a shower. A flat-screen TV is provided.\r\n\r\nThe nearest airport is Cairo International Airport, 120 km from the aparthotel.",
            "review": 4,
            "cleanlinsess_review": 3,
            "service_review": null,
            "value_review": null,
            "language_spoken": "English, Arabic"
        }
    ]


----------------------
### endpoint
    - {{uri}}/api/service/hotel/1/
    - 1 -> hotel id

### output
    {
        "id": 1,
        "name": "El mansour hotel apartmen 84",
        "location": "حى الجامعة, 35111 Mansoura, Egypt",
        "image": "https://cf.bstatic.com/xdata/images/hotel/max1280x900/407744992.jpg?k=8c9208ab49a459a393581a64f4bf21828dff5e85e17350deeeadd33fb12aa4d5&o=&hp=1",
        "description": "Featuring accommodation with a balcony, El mansour hotel apartmen 84 is located in Mansoura. The property provides a 24-hour front desk and free WiFi is available throughout the property.\r\n\r\nThe air-conditioned aparthotel consists of 2 bedrooms, a living room, a fully equipped kitchenette with a microwave and a kettle, and 1 bathroom with a bidet and a shower. A flat-screen TV is provided.\r\n\r\nThe nearest airport is Cairo International Airport, 120 km from the aparthotel.",
        "review": 4,
        "cleanlinsess_review": 3,
        "service_review": null,
        "value_review": null,
        "language_spoken": "English, Arabic"
    }
 

 =======================================

 q = mansoura

 {
    "services": {
        "Bank": [
            {
                "id": 1,
                "name": "CIB",
                "location": "mansoura",
                "image": "https://www.cibeg.com/en",
                "description": "it is a bank CIB ( Commercial International Bank) Mansoura",
                "link": "https://www.cibeg.com/",
                "telephone": "+202148923"
            }
        ],
        "Restraunt": [
            {
                "id": 1,
                "name": "Africa  Egypt  Ad-Daqahliyah Governorate  Mansoura  Mansoura Restaurants  Al Sabbahi Restaurants",
                "location": "3 Suez Canal St. Beside Security Directorate, Mansoura Egypt",
                "image": "https://media-cdn.tripadvisor.com/media/photo-s/07/04/42/8f/al-sabbahi-restaurants.jpg",
                "description": "Africa  Egypt  Ad-Daqahliyah Governorate  Mansoura  Mansoura Restaurants  Al Sabbahi Restaurants",
                "telephone": "+20 2 33336819",
                "website": "http://www.alsabbahi.com/",
                "open_from": "11:00:00",
                "open_to": "02:00:00",
                "rating": 4,
                "cuisines": "",
                "features": "",
                "meals": "",
                "type_r": null,
                "menu": null
            },
            {
                "id": 2,
                "name": "Mohamady Restauran",
                "location": "Sekket Sandoub St. El Sheikh Hassanein Sq., Mansoura Egypt",
                "image": "https://media-cdn.tripadvisor.com/media/photo-s/07/04/42/8d/al-sabbahi-restaurants.jpg",
                "description": "Mohamady Restauran Sekket Sandoub St. El Sheikh Hassanein Sq., Mansoura Egypt",
                "telephone": "+20 2 33336819",
                "website": "http://www.alsabbahi.com/",
                "open_from": "11:00:00",
                "open_to": "02:00:00",
                "rating": 4,
                "cuisines": "",
                "features": "",
                "meals": "",
                "type_r": null,
                "menu": "http://l.ead.me/baw9B6"
            }
        ]
    }
}