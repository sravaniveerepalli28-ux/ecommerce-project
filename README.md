## Project Overview

This project is a simple **E-Commerce Website** developed using **PHP, MySQL, HTML, CSS, and JavaScript**. It has two main modules: **Customer** and **Admin**. Customers can register, log in, browse products, and manage their shopping cart, while admins can manage all products through an admin dashboard.

---

## 1. User Module

### User Registration

First, a new user creates an account using the **Register** page by entering their name, email, and password. The password is securely stored in the database after encryption.

### User Login

After registration, the user logs in using their email and password. Once the login is successful, a session is created so the user can access all shopping features.

### Viewing Products

After logging in, users can see all available products on the homepage. Each product displays its image, name, description, and price.

### Adding Products to Cart

If the user wants to buy a product, they simply click the **"Add to Cart"** button. The selected product is then saved in the user's cart.

### Managing the Cart

On the cart page, users can view all selected products, update the quantity, remove unwanted items, and see the total price before checkout.

---

## 2. Admin Module

### Admin Login

The admin logs in using separate admin credentials. Only users with the **admin** role are allowed to access the admin panel.

### Admin Dashboard

After logging in, the admin reaches the dashboard, which acts as the control center for managing the website.

### Adding Products

The admin can add new products by entering the product name, price, description, and uploading a product image. Once submitted, the product becomes visible on the homepage.

### Managing Products

The admin can view all products in a table. From here, they can edit product details or delete products that are no longer available.

---

## 3. Database

The project uses **MySQL** to store all information.

* The **Users** table stores customer and admin details, including encrypted passwords and user roles.
* The **Products** table stores product information such as name, price, description, and image.
* The **Cart** table stores the products added by each user along with their quantities.

---

## 4. Project Flow

The website follows a simple process:

1. The user registers an account.
2. The user logs in.
3. Products are displayed on the homepage.
4. The user adds products to the shopping cart.
5. The cart stores the selected items.
6. The admin logs into the dashboard.
7. The admin adds, updates, or deletes products.
8. Any changes made by the admin are immediately reflected on the website.

---

## 5. Security Features

The project includes basic security measures:

* Passwords are encrypted using **`password_hash()`**, so they are not stored as plain text.
* PHP **sessions** are used to keep users logged in securely.
* Only users with the **admin** role can access the admin dashboard and manage products.

---

## Conclusion

This project demonstrates the basic functionality of an online shopping website. It includes user registration, login, product browsing, cart management, and an admin panel for product management. The project is simple, user-friendly, secure, and provides a good understanding of how a real-world e-commerce system works using PHP and MySQL.
