# Zetoro Janaloka Teknologi - Company Website

Official landing page and company profile website for **CV. Zetoro Janaloka Teknologi**, a company providing technology solutions, multimedia services, and business consulting, established in 2021.

---

## 🚀 Key Features

- **Responsive Landing Page**: Built with Bootstrap 5 for a seamless experience across both mobile and desktop devices.
- **Interactive UI**: Includes scroll-based animations using AOS (*Animate On Scroll*) and dynamic navigation with active state highlighting.
- **Integrated Contact Management**: Interactive contact form connected to a local database, with an option to send inquiries directly via WhatsApp.
- **Portfolio & Client Slider**: Dynamically showcases partners, clients, and completed projects.
- **Integrated Location Map**: Uses Google Maps Embed to display the company's office location at Maspion Square, Surabaya.

---

## 🛠️ Tech Stack & Dependencies

### Backend & Database

- **Framework**: Laravel 10 / 11
- **Database**: MySQL
- **Database Table**: `kontak` for storing incoming contact messages

### Frontend

- **CSS Framework**: Bootstrap v5.3.2
- **Icons**: Font Awesome v6.5.0 & Bootstrap Icons v1.11.3
- **Animations**: AOS (Animate On Scroll) v2.3.1
- **Alerts**: SweetAlert2 for successful contact form notifications

---

## 💻 Local Installation & Setup

Make sure you have **PHP**, **Composer**, and a local server environment such as **Laragon** or **XAMPP** installed on your computer.

### 1. Clone the Repository

```bash
git clone https://github.com/syfrzkngl/Zetoro-Janaloka-Technology-personal.git
cd Zetoro-Janaloka-Technology-individual
````

### 2. Install Composer Dependencies

```bash
composer install
```

### 3. Configure the Environment File

Copy `.env.example` to `.env`:

```bash
cp .env.example .env
```

Open the `.env` file and configure your MySQL database settings:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Generate the Application Key

```bash
php artisan key:generate
```

### 5. Run Database Migrations

Create a new MySQL database with the same name specified in your `.env` file, then run:

```bash
php artisan migrate
```

This will create the required database tables, including the `kontak` table for storing contact form submissions.

### 6. Start the Local Development Server

```bash
php artisan serve
```

Then open the following URL in your browser:

```text
http://127.0.0.1:8000
```

---

## 📂 Main Frontend Structure

```text
resources/
└── views/
    └── beranda.blade.php
        └── Main company homepage

public/
├── css/
│   └── beranda.css
│       └── Custom stylesheet
│
└── img/
    ├── Company logo
    ├── Owner photo
    ├── Client logos
    └── Portfolio images
```

---

## 🏢 About Zetoro Janaloka Teknologi

**CV. Zetoro Janaloka Teknologi** is a technology-focused company established in 2021, providing technology solutions, multimedia services, and business consulting.

This website serves as the company's digital profile and provides information about its services, portfolio, clients, and contact information.

---

## 📝 License

© 2025 Zetoro Janaloka Teknologi. All rights reserved.

```
```
