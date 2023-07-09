## Happy Shopaholic Project Kickoff

Welcome to the Happy Shopaholic Project, where shopping dreams come true! 🛍️

Our client, a shopaholic who's tired of spending hours in stores, has come to us for help in building an online shopping platform that will meet their needs and exceed their expectations. 🎉

As junior developers, it's your mission to create a platform that will allow customers to browse items, add them to their cart, checkout, and receive order notifications via email and SMS. But wait, there's more! We'll also be using Redis and Celery to handle background tasks and improve performance. 💻👨‍💼

## Project Sections

### Section 1: Project Setup, Basic Models, and Authentication (80 points)

We gotta get this project up and running! Here are some tasks for you:

1. **Project Setup (20 points)**
   - Create a new Django project and app.
   - Configure the app to use PostgreSQL as the database.
   - Initialize a Git repository and commit your initial project files.
   

2. **Basic Models (30 points)** 
   - Create the following models: `Product`, `Category`, `Customer`, `Order`, `OrderItem`, and `Address`.
   - Define appropriate fields and relationships between models.
   - Add Django admin configurations for each model.

3. **User Authentication (30 points)** 🔑📱
   - Implement a custom user model that inherits from `AbstractBaseUser`, using phone numbers for login.
   - Create OTP verification for phone number authentication using the "Kavenegar" structure, but print the OTP instead of sending it via SMS.
   - Write unit tests for your authentication views and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 1 by the end of the first week and earn 5 extra points.🐦👀
- Presentation bonus: Present your completed Section 1 during the nightly meeting with your mentor and earn an additional 5 points.🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 1 and earn a bonus 10 points.🥳🏆

### Deliverables:

- A Git repository containing your Django project
- A `README.md` file with instructions on how to set up and run the project using Docker.

### Section 2: Product Listing and Shopping Cart (100 points)

It's time to let our users in on the fun! Here's what you need to do:

1. **Docker Configuration (15 points)**
   - Set up a Docker and docker-compose configuration for running the project locally.

2. **Product Listing (35 points)** 🛍️👀
   - Implement views and templates for displaying products by category.
   - Add pagination for product listing pages.
   - Implement search functionality for products.
   - Write unit tests for your views and ensure at least 90% coverage.

3. **Shopping Cart (50 points)** 🛒💸
   - Implement a shopping cart using Django sessions.
   - Allow customers to add and remove products from their cart.
   - Display the cart contents and total price.
   - Write unit tests for the shopping cart functionality and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 2 by the end of the second week and earn 10 extra points. 🐥👀
- Presentation bonus: Present your completed Section 2 during the nightly meeting with your mentor and earn an additional 10 points. 🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 2 and earn a bonus 20 points. 🎉🏆

### Deliverables:

- Updated Git repository with code for product listing and shopping cart features.

### Section 3: Checkout Process and Email Notifications (100 points)

It's time to get those items in the cart and on their way to the shopaholic! Here's what you need to do:

1. **Checkout Process (70 points)** 🚚💳
   - Implement the checkout process, including shipping address and order review.
   - Create an `Order` object upon successful checkout.
   - Integrate ZarinPal for payment processing during the checkout process.
   - Write unit tests for the checkout views and payment processing functionality and ensure at least 90% coverage.

2. **Email Notifications (30 points)** 📧📦
   - Integrate Celery and Redis for handling background tasks.
   - Send order confirmation and shipping update emails asynchronously using Celery tasks.
   - Write unit tests for your email tasks and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus:Complete Section 3 by the end of the third week and earn 15 extra points.
- Presentation bonus: Present your completed Section 3 during the nightly meeting with your mentor and earn an additional 15 points.
- Completion bonus: Complete all tasks for Section 3 and earn a bonus 30 points.

### Deliverables:

- Updated Git repository with code for checkout process and email notifications features.

### Section 4: API and Performance Optimization (80 points)

It's time to optimize and add some extra shopping features! Here's what you need to do:

1. **API Implementation (40 points)** 📚🤖
   - Implement a RESTful API for your online shopping platform using Django Rest Framework (DRF).
   - Add endpoints for products, categories, customers, orders, and authentication.
   - Write unit tests for your API and ensure at least 90% coverage.

2. **Performance Optimization (40 points)** 🚀🔥
   - Implement Redis caching for your API endpoints and views.
   - Optimize database queries using Django's `select_related` and `prefetch_related` methods.
   - Write unit tests for your optimized views and ensure at least 90% coverage.

### Achievements and Incentives:
- Early bird bonus: Complete Section 4 by the end of the fourth week and earn 20 extra points. 🐥👀
- Presentation bonus: Present your completed Section 4 during the nightly meeting with your mentor and earn an additional 20 points. 🎤👨‍🏫
- Completion bonus: Complete all tasks for Section 4 and earn a bonus 40 points. 🎉🏆

### Deliverables:

- Updated Git repository with code for API and performance optimization features.
- A `README.md` file with instructions on how to run and test the project, including any additional features you added.

### Final Incentives and Achievements:
- Perfect Attendance: Attend all nightly meetings with your mentor and earn a bonus 10 points. 🌟👨‍🏫
- Code Quality: Maintain code quality throughout the project and earn a bonus 20 points. 💻🔍
- Innovation: Implement an innovative feature that impresses your mentor and earn a bonus 30 points. 🤖💡
- Early Submission: Submit your project before the deadline and earn a bonus 50 points. 🚀📅

### Conclusion

Congratulations, you've completed the Happy Shopaholic Project! 🎉🎉🎉

You've built an online shopping platform that will make our client's dreams come true. Now, go ahead and celebrate with some online shopping of your own! 🛍️💸
