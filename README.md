Introduction

The Company Complaint Management System is designed to streamline the process of handling customer complaints. Customers can log their issues, and company representatives can manage and respond to these complaints through the system.

!!!!!!! Features

- Customer registration and login
- Complaint submission by customers
- Admin dashboard to manage complaints
- Status tracking for each complaint
- Notifications for updates on complaints

!!!!!! Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL (using XAMPP)
- **Server**: Apache (using XAMPP)

!!!!! Installation

To set up the project locally, follow these steps:

1. **Install XAMPP**: Download and install [XAMPP](https://www.apachefriends.org/index.html).

2. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/complaint-management-system.git
    cd complaint-management-system
    ```

3. **Set Up Database**:
    - Open XAMPP Control Panel and start Apache and MySQL.
    - Open `phpMyAdmin` by navigating to `http://localhost/phpmyadmin/`.
    - Create a new database named `complaint_system`.
    - Import the database schema from the `db/complaint_system.sql` file included in the project.

4. **Configure Database Connection**:
    - Open the `config.php` file located in the project directory.
    - Update the database configuration with your `username`, `password`, and `database name`.

    ```php
    <?php
    $servername = "localhost";
    $username = "root";
    $password = "";
    $dbname = "complaint_system";
    ?>
    ```

5. **Run the Project**:
    - Place the project folder in the `htdocs` directory of your XAMPP installation.
    - Open your web browser and navigate to `http://localhost/complaint-management-system/`.
