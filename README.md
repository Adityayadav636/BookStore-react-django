# BookStore-react-django
[Visit Live Demo]( http://16.171.160.34:8000/#/  )



[Visit video Demo](https://www.youtube.com/watch?v=NJnmgEatAjE)

This is a Bookstore Application built using Django, Django REST Framework, Simple JWT, React, Redux Toolkit, Material UI, and Bootstrap. The application provides a comprehensive catalog of books with various features such as ecommerce facilities, search functionality, advanced filtering options, and PayPal integration.

Features
Book Catalog: The application offers a wide range of books with details such as title, author, description, cover image, price, and customer ratings.

Search Functionality: Customers can easily search for books by title, author, or category. The search feature helps users find specific books quickly.

Advanced Filtering: The application provides advanced filtering options to refine search results based on genre, price range, publication date, and other criteria. This allows users to narrow down their search and find books that match their preferences.

Ecommerce Facilities: The bookstore application includes ecommerce facilities to enable customers to purchase books online. Users can add books to their cart, proceed to checkout, and make payments securely.

PayPal Integration: PayPal buttons are integrated into the application to facilitate secure and convenient online payments. Customers can choose PayPal as their preferred payment method during checkout.

Technologies Used
Django: Python-based web framework used for the backend development of the application.
Django REST Framework: Powerful toolkit for building RESTful APIs with Django.
Simple JWT: Library for adding JWT authentication to Django REST Framework.
React: JavaScript library for building user interfaces.
Redux Toolkit: Redux library that simplifies state management in React applications.
Material UI: React component library that provides pre-designed UI components following the Material Design principles.
Bootstrap: CSS framework for creating responsive and visually appealing web pages.
Deployment
The application is deployed on AWS EC2, which provides scalable and reliable cloud computing resources. The deployment process involves configuring the EC2 instance, setting up security groups, and deploying the Django backend and React frontend on the instance. Additionally, Nginx or another web server can be used to serve the static files and handle HTTPS requests.

Please note that deploying the application on AWS EC2 requires appropriate configuration and security measures to ensure a safe and reliable deployment.

InstSure! Here's an example of how you can format the installation and usage instructions with clear step-by-step instructions:

## Installation and Usage

To run the application locally, follow these steps:

1. Clone the repository:
   ```shell
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```shell
   cd <project-directory>
   ```

3. Set up and activate a virtual environment (recommended).

4. Install backend dependencies:
   ```shell
   pip install -r requirements.txt
   ```

5. Set up the database and run migrations:
   ```shell
   python manage.py migrate
   ```

6. Start the Django development server:
   ```shell
   python manage.py runserver
   ```

7. Navigate to the frontend directory:
   ```shell
   cd frontend
   ```

8. Install frontend dependencies:
   ```shell
   npm install
   ```

9. Start the frontend development server:
   ```shell
   npm start
   ```

10. Access the application in your web browser at [http://localhost:3000](http://localhost:3000)

Please ensure that you have Python, pip, and Node.js installed on your local machine before running the application.

These instructions provide a clear and structured guide for users to follow when installing and running the application locally. Feel free to modify the formatting or add additional explanations as needed.

Conclusion
The Bookstore Application  use of Django, Django REST Framework, React, Redux Toolkit, Material UI, and Bootstrap ensures a robust and user-friendly application  .

Feel free to explore and customize the application to suit your specific requirements. If you encounter any issues or have questions, please refer to the documentation or seek assistance from the project contributors.

Enjoy the Bookstore Application!




