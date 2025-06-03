# e_mart

e_mart is a web application for selling electronic devices like phones, laptops, headphones, and speakers.  
It supports user creation, seller dashboards, product management, and transaction history

---

## Features
- User login/logout (customers, seller as admin)
- Seller dashboard with product and transaction management
- Product listing with images, descriptions, prices, and stock
- Transaction history and total earnings display

## Demo Presentation
-click the link to see the video
https://drive.google.com/drive/folders/1AqChKqzW2fIbwiNb5SY7G4TRZcCRQ6Dm?usp=sharing

---

### Project Structure
e_mart/
│
├── admin_seller/ # Seller dashboard backend and frontend
├── customer/ # Customer user interface
├── uploads/ # Folder to store product images
│ └── product/ # Product images here
├── db_connect.php # Database connection script
├── e_mart.sql # SQL schema file for database setup
├── index.html # Homepage or login page
├── login.php # Login processing script
├── logout.php # Logout processing script
├── add_product.php # Add new product backend
├── fetch_products.php # Fetch products backend
├── delete_product.php # Delete product backend
└── README.md # This file


---

#### Prerequisites
- MySQL / MariaDB
- Apache or other web server with PHP support
- Composer (optional, if you use PHP dependencies)

---

##### Setup Instructions

Step 1. Clone or extract project files

Download or clone the project into your web server directory (e.g., `htdocs` for XAMPP):

```bash
git clone https://github.com/yourusername/e_mart.git

Or unzip the e_mart.zip and place it in your server directory.


Step 2. Import Database

- Open phpMyAdmin or your MySQL client.
- Create a new database (e.g., `e_mart`).
- Import the `e_mart.sql` file into the new database.

Step 3. Configure Database Connection

- Open `db_connect.php`.
- Update the database credentials (`host`, `username`, `password`, `database`) to match your setup.

---

Step 4. Run the Project

- Use a local server (like XAMPP, WAMP, or MAMP) or deploy on a live server with PHP and MySQL support.  
- Place the `e_mart` folder in your server’s root directory (`htdocs` or `www`).  
- Access the project via browser at `http://localhost/e_mart` (adjust based on your server config).  
- Log in with the default admin credentials to start managing products and view the dashboard.

---

**Note:**  
- The project uses PHP sessions for login management.  
- ONly the admin's password is hashed  
- The database export does NOT include image files, only references to them.  
- You must keep the folder structure intact for images to load properly.  
- For deployment on a live server, ensure proper file permissions and security settings.  
- The default admin/seller login is:  
  - Username: `admin`  
  - Password: `adminpassword`
-Create your own account to shop


Tools & Technologies Used:
- PHP
- MySQL
- phpMyAdmin
- HTML
- CSS
- JavaScript
- XAMPP







