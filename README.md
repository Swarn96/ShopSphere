# ShopSphere

ShopSphere is a robust e-commerce application built using Java and Spring Boot, designed with a focus on security, scalability, and ease of maintenance. This application leverages Spring Data JPA for seamless interaction with a MySQL database, managing entities such as users, products, categories, orders, and more.

## Features

**Admin:**
- **Login:** Secure access for admin users.
- **Users Management:** Manage user information and roles.
- **Address Management:** Handle addresses associated with users.
- **Categories:** Create and manage product categories.
- **Products:** Add, update, and delete products.
- **Price & Discount Management:** Configure product pricing and discounts.
- **Orders Management:** View and manage customer orders.

**User:**
- **Registration & Login:** User authentication and registration.
- **Fetch Categories and Products:** Browse products by category.
- **Cart Management:** Add and delete products in the cart.
- **Address and Quantity Management:** Manage shipping addresses and product quantities.
- **Order Products:** Place orders and track order status.

## Security

ShopSphere utilizes JSON Web Tokens (JWT) for securing API endpoints, managed by Auth0. To access the API, users must authenticate via the `/login` endpoint to obtain a JWT, which should be passed in the Authorize option available in Swagger UI.

## API Documentation

The APIs are well-documented and easily accessible through Swagger UI, providing developers with an intuitive interface for testing and understanding the various endpoints.

## Technology Stack

- **Languages:** Java 8, Core Java
- **Frameworks:** Spring Boot, Spring Data JPA, Hibernate, JPA
- **Database:** MySQL
- **Security:** Auth0 for authentication, JWT for API security
- **Tools:** Swagger UI for API documentation

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/shopsphere.git
    ```
2. Navigate to the project directory:
    ```bash
    cd shopsphere
    ```
3. Configure the MySQL database settings in `application.properties`.
4. Run the application:
    ```bash
    mvn spring-boot:run
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
