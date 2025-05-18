# 🍽️ Foodify – Recipe Sharing Web Application

**Foodify** is a web-based platform designed for food enthusiasts to explore, share, and manage a variety of recipes. The application offers a user-friendly interface where users can browse through different categories of dishes, view detailed recipes, and contribute their own culinary creations.

🌐 Live Demo
👉 https://foodify-theta.vercel.app

---

## 🔧 Key Features

- **Recipe Categories**: Navigate through categories like Vegetarian, Non-Vegetarian, Vegan, etc.
- **Recipe Details**: View ingredients, steps, and images for each dish.
- **User Contributions**: Add, update, and delete your own recipes.
- **Responsive Design**: Seamless UI across mobile, tablet, and desktop.

---

## 🛠️ Technologies Used

- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL

---

## 📁 Project Structure

- **HTML Files**: Individual recipe pages (`Biriyani.html`, `Carbonara.html`, etc.)
- **PHP Scripts**: Backend logic like `conection.php`, `recipeupload.php`, `update.php`, `delete.php`
- **Stylesheets**: Custom styles in `recipeupload.css`
- **Assets**: Stored in `images/` and `statics/`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Randimal441/Foodify.git

## 🚀 Getting Started

### 2. Set Up the Database

- Create a MySQL database.
- Import the provided SQL schema into your database using tools like **phpMyAdmin** or the **MySQL CLI**.

### 3. Configure Backend

Update the `conection.php` file with your database credentials:

```php
<?php
$host = "localhost";
$user = "your_username";
$password = "your_password";
$dbname = "your_database_name";

// Create connection
$conn = new mysqli($host, $user, $password, $dbname);

// Check connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>




