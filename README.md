
# Medical Records Management System

The Medical Records Management System is a web-based application designed to assist medical facilities
in managing patient records and keeping track of their medicine inventor.This system provides a user-friendly interface to efficiently handle essential tasks for medical staff, administrators, and pharmacists.

## Features

### Patient Records Management

- Create, update, and delete patient records.
- Store comprehensive patient information, including personal details, medical history, and appointment schedules.
- Easily search and retrieve patient records.
- Assign unique identifiers to patients for easy tracking.

### Medicine Inventory

- Maintain an up-to-date inventory of available medicines.
- Record medicine details such as name, quantity, expiration date, and supplier information.
- Receive notifications when medicines are running low or about to expire.
- Track medicine usage and replenish stock as needed.

### User Roles and Authentication

- Implement role-based access control, allowing different user roles, including administrators, doctors, nurses, and pharmacists.
- Secure user authentication and authorization mechanisms to protect sensitive patient data.
- Admins can manage user roles and permissions.

### User-Friendly Interface

- Intuitive and responsive web interface for easy navigation.
- User-friendly forms for adding and updating patient records and medicines.
- Dashboard for quick access to important statistics and notifications.

## Getting Started

To run the Medical Records Management System on your local machine, follow these steps:

1. Clone this repository to your local environment:

   ```bash
   https://github.com/Clifford537/Pharmacy-Inventory-System.git
   ```

2. Set up a web server environment with PHP support. You can use tools like XAMPP, WAMP, or MAMP for local development.

3. Create a database and import the provided database schema (if any) into your database server. Make sure to configure the database connection in your PHP scripts accordingly.

4. Open the project directory in your web server's document root.

5. Access the system through your web browser.

## Usage

1. Access the system by opening it in your web browser.
2. Login using your credentials. By default, you can use the following test accounts:
   - Admin Account:
     - Username: admin
     - Password: adminpassword
   - Doctor Account:
     - Username: doctor
     - Password: doctorpassword
   - Nurse Account:
     - Username: nurse
     - Password: nursepassword
   - Pharmacist Account:
     - Username: pharmacist
     - Password: pharmacistpassword
3. Explore and use the system according to your role:
   - Admins can manage users, patient records, and medicine inventory.
   - Doctors and nurses can view and update patient records.
   - Pharmacists can manage the medicine inventory.

**Important:** In a production environment, ensure that you implement proper security measures to protect patient data, such as user authentication, secure database connections, and secure server configurations.

## Technology Stack

- PHP
- HTML
- CSS
- MySQL 

## Contributing

We welcome contributions to improve this project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test thoroughly.
5. Create a pull request describing your changes.

Please follow our [Code of Conduct](CODE_OF_CONDUCT.md) and [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

