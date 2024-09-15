# Ecommerce Clothing

Ecommerce Clothing is an online platform that allows users to browse, search, and purchase clothing items. It provides a user-friendly experience for customers and an admin dashboard for managing products, orders, and users.

## images
![Screenshot 2024-09-05 181356](https://github.com/user-attachments/assets/6709fce8-4cc5-4f01-b369-28b3e95c72c3)

![Login](https://github.com/user-attachments/assets/bc571fe0-76a6-4b36-a851-b7d89269b2b1)

![Screenshot 2024-09-05 182839](https://github.com/user-attachments/assets/8a9d26ea-a97f-49ea-baf0-c14d5b8e2a1f)

![LandingPage](https://github.com/user-attachments/assets/50754af3-9816-4aa3-87e5-483f801eab06)

![AdminDashboard](https://github.com/user-attachments/assets/ab1ca0da-6e6a-4f23-a5b0-f7de0f4a641a)

![](https://github.com/user-attachments/assets/f03ae0be-5e47-4f3a-b215-39792ce32bff)

![Screenshot 2024-09-05 182449](https://github.com/user-attachments/assets/37523929-62b4-4e03-9805-69fee0d70b50)

![Screenshot 2024-09-05 183717](https://github.com/user-attachments/assets/1025ca0b-dbc4-4a25-94e9-2c7f2851d484)













## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- User authentication and authorization
- Email verification using OTP for secure account activation
- Browse products by category, search, and filter options
- Add products to a shopping cart and manage orders
- Secure payment gateway integration (Razorpay)
- Admin dashboard for managing products, orders, and users
- Responsive design for mobile and desktop users

![Features Screenshot]

## Technologies

- **Frontend:** ReactJS, HTML, CSS, JavaScript
- **Backend:** Spring Boot
- **Database:** MySQL
- **Payment Integration:** Razorpay
- **Authentication:** email OTP verification

## Installation

To set up the project locally, follow these steps:

### Backend

1. Clone the repository:
    ```bash
    git clone https://github.com/waseem-9/Ecommerce-Clothing.git
    ```

2. Navigate to the backend directory:
    ```bash
    cd ecommerce-clothing/backend
    ```

3. Create a MySQL database:
    ```sql
    CREATE DATABASE ecommerce_clothing;
    ```

4. Update the `application.properties` file with the following configuration:

    ```properties
    # Server Configuration
    server.port=8000

    # MySQL Properties
    spring.datasource.url=jdbc:mysql://localhost:3306/Evintagee?createDatabaseIfNotExist=true&useUnicode=true
    spring.datasource.username=root
    # enter your correct mysql password below
    spring.datasource.password=Your_Password
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL57Dialect

    # Create a Folder in your laptop for storing product images
    disk.upload.basepath=........

    # Email SMTP setup
    spring.mail.host=smtp.gmail.com
    spring.mail.port=587
    spring.mail.username=narutoo95424@gmail.com
    spring.mail.password=tsrn uvjy itbv rmjw
    spring.mail.properties.mail.smtp.auth=true
    spring.mail.properties.mail.smtp.starttls.enable=true

    spring.jackson.serialization.fail-on-empty-beans=false
    ```

5. Install the dependencies and build the project:
    ```bash
    ./mvnw clean install
    ```

6. Start the backend server:
    ```bash
    ./mvnw spring-boot:run
    ```

### Frontend

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Start the frontend development server:
    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:5173`.

## Usage

### Customer

1. Sign up or log in to your account.
2. Verify your email using the OTP sent to your registered email address.
3. Browse products by category or search for specific items.
4. Add items to your cart and proceed to checkout.
5. Make a secure payment using Razorpay.
6. Manage your orders from your account dashboard.

### Admin

1. Log in to the admin dashboard.
2. Add, edit, or delete products.
3. View and manage customer orders.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For any inquiries or feedback, you can reach me at shaikwaseem0018@gmail.com.

## Demo Video
click these link to watch the demo
https://github.com/user-attachments/assets/ecc30a63-b8a4-4176-b780-1c8c70fcfc2a


