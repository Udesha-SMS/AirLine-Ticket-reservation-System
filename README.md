# ✈️ Airline Ticket Reservation System

## 📋 Overview

Airline Ticket Reservation System is a web-based application developed as part of the IWT module at SLIIT, designed to simplify flight booking and reservation management. It enables users to easily browse flights, make reservations, and handle their bookings online.

---

## 🚀 Key Features

* User sign-up and login functionality
* Flight lookup based on date and destination
* Online ticket reservation system
* (Optional) Integration with a payment gateway
* Manage bookings – view, edit, or cancel reservations
* Admin dashboard to oversee flight schedules and bookings

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS
* **Backend:** PHP
* **Database:** MySQL

---

## ⚙️ Setup Instructions

1. **Download or clone** the project repository
2. **Install** a local server environment like **XAMPP** or **WAMP**
3. **Create** a new MySQL database and **import** the `database.sql` file included
4. **Update the database connection** in `config.php` as follows:

```php
<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "airline_reservation";

$conn = new mysqli($servername, $username, $password, $dbname);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
```

5. **Run the project** by opening your browser and navigating to:
   `http://localhost/airline-reservation/`

---

## 🧑‍💼 How to Use

* Sign up as a new user or log in with your account
* Search for flights using filters like destination and travel date
* Pick a flight and complete your booking
* View or manage your reservations from your account
* Admin users can log in separately to manage flight data and bookings

---

## 🌟 Planned Improvements

* Integration of real-time flight tracking features
* Secure online payments through a payment gateway
* Option for seat selection and in-flight service requests

---

## 📄 License

This project is distributed under the **MIT License** – feel free to use, modify, and distribute as needed.
