# Tech Nova

An online shop for selling second-hand technology at affordable prices. Built as a university group project by a team of 10.

## Features
- Browse phones, tablets, laptops, smartwatches and audio devices
- Customer and admin accounts (hashed passwords, prepared PDO statements)
- Basket and checkout with stock checks, order history and product reviews
- Admin tools: manage stock, prices, users and order status
- Sales reports (top-selling products, revenue) exported to PDF (TCPDF) and Excel
- Contact form, password reset and product update emails (PHPMailer)
- Dark mode preference saved in the browser

## Built with
PHP, MySQL, JavaScript, HTML, CSS. PDF export uses [TCPDF](https://github.com/tecnickcom/TCPDF) and emails use [PHPMailer](https://github.com/PHPMailer/PHPMailer); both are third-party libraries.

## Running it locally
1. Install XAMPP (or any PHP and MySQL stack) and copy this folder into `htdocs`.
2. Create a database and import `database.sql`.
3. Check the database settings in `connectdb.php`.
4. Run `composer install` to restore PHPMailer, then open the site in your browser.


