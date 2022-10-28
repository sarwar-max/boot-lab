docker run --env RDS_URL=jdbc:h2:mem:mydata --env RDS_DRIVER_CLASS=org.h2.Driver --env RDS_USERNAME=sa --env RDS_PASSWORD=password --env RDS_DIALECT=org.hibernate.dialect.H2Dialect --publish 8080:8080 waghrameshwar123/docker-ebookstore:0.0.1-SNAPSHOT



    {
        "id": 2,
        "name": "Chicken Biryani",
        "category": "Indian",
        "actualPrice": 365,
        "discount": 0,
        "price": 0,
        "avail": "yes",
        "imagepath": "./assets/images/biryani.jpg",
        "desc": "Rice Steamed with Chicken and spices"
    }
