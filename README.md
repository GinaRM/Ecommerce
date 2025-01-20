# Ecommerce Project

This repository contains the source code for an Ecommerce platform, built using modern backend and frontend technologies. The project is designed to provide a robust, scalable, and user-friendly online shopping experience.

## Features
- **User Management:** Register, login, and manage user accounts.
- **Product Catalog:** Browse, search, and view detailed product information.
- **Shopping Cart:** Add, remove, and manage products in the cart.
- **Order Processing:** Place orders and view order history.
- **Admin Dashboard:** Manage products, orders, and users (admin only).

## Technologies Used
### Backend
- **Language:** Java
- **Framework:** Spring Boot
- **Database:** MySQL
- **Other Tools:** Hibernate, JPA, Spring Security

### Frontend
- **Framework:** React.js
- **Styling:** CSS Modules, Bootstrap
- **State Management:** Redux

## Prerequisites
To run this project, ensure you have the following installed:
- Java 15 or later
- Node.js 16 or later
- MySQL Server

## Installation and Setup

### Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/GinaRM/Ecommerce.git
   cd Ecommerce/backend
   ```
2. Configure the database:
   - Create a MySQL database named `ecommerce`.
   - Update the database connection properties in `application.properties`.

3. Build and run the backend:
   ```bash
   ./mvnw spring-boot:run
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

The application should now be accessible at `http://localhost:3000`.

## Usage
1. Access the application in your web browser.
2. Register as a new user or log in with existing credentials.
3. Explore the product catalog, add items to your cart, and proceed to checkout.
4. Admin users can log in to access the dashboard for managing products and orders.

## Testing
- Run backend tests:
  ```bash
  ./mvnw test
  ```
- Run frontend tests:
  ```bash
  npm test
  ```

## Contributing
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch:
   ```bash
   git commit -m "Description of changes"
   git push origin feature-name
   ```
4. Open a pull request.


## Contact
For questions or suggestions, please contact [Gina Rodríguez](https://github.com/GinaRM).
