<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<h1 align="center">Commission Tracker System</h1>

## Overview

Commission Tracker System is a web application built with Laravel that helps businesses manage and track sales commissions efficiently. This system streamlines the process of calculating, tracking, and reporting commissions for sales teams, making commission management transparent and error-free.

## Features

- **Dashboard Analytics:** Visual representation of commission data with key metrics
- **Commission Calculation:** Flexible rules engine for different commission structures
- **Sales Tracking:** Monitor sales performance and associated commissions
- **User Management:** Role-based access with separate views for sales representatives and managers
- **Reports Generation:** Export detailed commission reports in various formats
- **Commission Approvals:** Multi-step approval workflow for commission payments
- **Notification System:** Alerts for new commissions, approvals, and payments

## Technology Stack

- **Backend:** Laravel 12.0
- **Frontend:** Blade templates with Bootstrap and Vue.js components
- **Database:** MySQL
- **Authentication:** Laravel Sanctum/Fortify
- **Reporting:** Laravel Excel for export functionality

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TheRealAngelo/commission_tracker_system.git
   cd commission_tracker_system
   ```

2. **Install dependencies:**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Configure environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Set up database:**
   ```bash
   # Configure your database in .env first
   php artisan migrate --seed
   ```

5. **Launch the application:**
   ```bash
   php artisan serve
   ```

## Usage

After installation, access the system at http://localhost:8000 (default). 

**Default Login Credentials:**
- Admin: `admin1` / `123`
- Owner: `owner1` / `123`
- Unitmanager: `unitmanager1` / `123`


## Running Tests

```bash
php artisan test
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgements

- [Laravel](https://laravel.com) - The web framework used
- [Bootstrap](https://getbootstrap.com) - Frontend framework
- [Chart.js](https://www.chartjs.org) - For dashboard analytics

---

<p align="center">Developed by Angelo Morales</p>