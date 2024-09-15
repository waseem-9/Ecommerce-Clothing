# Ecommerce Clothing

Ecommerce Clothing is an online platform that allows users to browse, search, and purchase clothing items. It provides a user-friendly experience for customers and an admin dashboard for managing products, orders, and users.

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
    # Enter your email ID
    # Login with this email ID in your Google Account
    # Generate the App Password and enter that password here
    # Note: Don't enter your actual email password here
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

4. Open your browser and navigate to `http://localhost:3000`.

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

## Images

(Add screenshots or demo images here)

# Hotel Booking System

The Hotel Booking System is a web application that allows users to search, book, and manage hotel reservations. It provides an easy-to-use interface for both customers and hotel administrators to streamline the booking process.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Features

- User authentication and authorization
- Search hotels by location, date, and room type
- View hotel details and room availability
- Make and manage bookings
- Admin dashboard for managing hotels, rooms, and bookings
- Responsive design for mobile and desktop users

![Features Screenshot]
## Technologies

- **Frontend:** ReactJS, HTML, CSS, JavaScript
- **Backend:** Spring Boot
- **Database:** MySQL
- **Authentication:** JWT (JSON Web Tokens)

## Installation

To set up the project locally, follow these steps:

### Backend

1. Clone the repository:
    ```bash
    git clone https://github.com/waseem-9/Hotel-Booking-Platform.git
    ```

2. Navigate to the backend directory:
    ```bash
    cd hotel-booking-system/backend
    ```

3. Create a MySQL database:
    ```sql
    CREATE DATABASE hotel_booking_system;
    ```

4. Update the `application.properties` file with your MySQL database configuration:
    ```# MySQL Properties
    spring.datasource.url=jdbc:mysql://localhost:3306/DatabaseName?createDatabaseIfNotExist=true&useUnicode=true
    spring.datasource.username=root

    #Enter the correct MySQL Password below
    spring.datasource.password=YourDbPassword
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL57Dialect

    spring.servlet.multipart.max-file-size=10MB
    spring.servlet.multipart.max-request-size=10MB

    #give image path
    disk.upload.basepath=D:/img/urlpath

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

4. Open your browser and navigate to `http://localhost:3000`.

## Usage

### Customer

1. Sign up or log in to your account.
2. Search for hotels by entering the location, check-in, and check-out dates.
3. Browse through the list of available hotels and view their details.
4. Select a room and proceed with the booking process.
5. Manage your bookings from your account dashboard.

### Admin

1. Log in to the admin dashboard.
2. Add, edit, or delete hotels and rooms.
3. View and manage customer bookings.

## Contributing

Contributions are welcome! Feel Free to open issues or submit pull requests.


## Contact

For any inquiries or feedback, you can reach me at shaikwaseem0018@gmail.com

##Images

