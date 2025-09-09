# El Arca Home
**El Arca Home** is a fully functional e-commerce web application developed for a home goods store. 

## Features

- Product listing with stock control
- Dynamic product filtering and carousel gallery
- Shopping cart with localStorage persistence
- Order summary with shipping options (store pickup or home delivery)

## Technologies Used
### Frontend:
- HTML5, CSS3 
- JavaScript
### Backend:
- Java 17+
- Spring Boot (REST APIs, JPA)
- MySQL (database for product and sales records)

## Setup Instructions
1. Navigate to the `backend/` folder.
2. Create a file named `application.properties` (not included in repo) and configure your environment:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.database-platform=org.hibernate.dialect.MySQLDialect
spring.jpa.hibernate.ddl-auto=none
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.properties.hibernate.globally_quoted_identifiers=true
```

## Screenshots
<img width="1919" height="985" alt="Captura de pantalla 2025-09-09 182958" src="https://github.com/user-attachments/assets/5e0fe510-aa02-41ca-82f8-c3f90b24b131" />
<img width="1919" height="985" alt="Captura de pantalla 2025-09-09 183015" src="https://github.com/user-attachments/assets/b7559d3d-3d6a-4e9c-a651-30daeaeb17c4" />
<img width="1919" height="983" alt="Captura de pantalla 2025-09-09 183026" src="https://github.com/user-attachments/assets/f085e984-2e19-4c28-ba5e-8e0f8936e314" />
<img width="1919" height="980" alt="Captura de pantalla 2025-09-09 183102" src="https://github.com/user-attachments/assets/b50d554a-8044-4f5a-93ec-bd28b126d704" />

## Contributing
If you’d like to contribute, feel free to fork the repository and submit a pull request with your improvements.

## License
This project is licensed under the **MIT License**. See the LICENSE file for more details.

## Contact
For any inquiries, feel free to reach out via GitHub or email at **santiborgna5@gmail.com**.

