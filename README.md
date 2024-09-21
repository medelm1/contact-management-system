# Contact Management System
A web application for managing contacts, built with Laravel and Vue.js.

## Table of Contents

- Introduction
- Features
- Technologies Used
- Installation
- Usage
- API Endpoints
- Contributing
- License

## Introduction

The Contact Management System is a web application designed to help users manage their contacts efficiently. Users can add, edit, delete, and organize contacts, as well as search and filter through their contact list. The application is built using Laravel for the backend and Vue.js for the frontend, providing a modern and responsive user experience.

## Features

- User authentication (registration, login, password reset)
- Add, edit, delete, and view contacts
- Search and filter contacts
- Group contacts into categories
- Import contacts from CSV
- Export contacts to CSV
- Responsive design for mobile and desktop

## Technologies Used

- Laravel
- Vue.js
- Vue Router
- Pinia
- Axios
- Tailwind CSS

## Installation

### Prerequisites

- PHP 8.x
- Composer
- Node.js & npm
- MySQL or any other supported database

### Steps

1. Clone the repository:
```bash
git clone https://github.com/medelm1/contact-management-system.git
cd contact-management-system
```

2. Install PHP dependencies:
```bash
composer install
```

3. Install JavaScript dependencies:
```bash
npm install
```

4. Copy the `.env.example` file to `.env` and configure your environment variables:
```bash
cp .env.example .env
```

5. Generate the application key:
```bash
php artisan key:generate
```

6. Run migrations to set up the database:
```bash
php artisan migrate
```

7. Build the frontend assets:
```bash
npm run dev
```

8. Start the development server:
```bash
php artisan serve
```

## Usage
### Authentication
- Register a new user or log in with an existing account.
- Use the navigation menu to access different parts of the application.

### Managing Contacts

- __Add Contact__: Click the "Add Contact" button and fill in the form.
- __Edit Contact__: Click the "Edit" button next to a contact and update the information.
- __Delete Contact__: Click the "Delete" button next to a contact to remove it.
- __Search Contacts__: Use the search bar to filter contacts by name, email, or phone number.
- __Group Contacts__: Assign contacts to categories for better organization.

### Import/Export Contacts

- __Import__: Click the "Import" button and upload a CSV file containing contacts.
- __Export__: Click the "Export" button to download contacts as a CSV file.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/contacts | Retrieve all contacts |
| POST | /api/contacts | Create a new contact |
| GET | /api/contacts/{id} | Retrieve a specific contact |
| PUT | /api/contacts/{id} | Update a specific contact |
| DELETE | /api/contacts/{id} | Delete a specific contact |


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
```bash
git checkout -b feature-name
```
3. Make your changes and commit them:
```bash
git commit -m "Description of changes"
```
4. Push to your branch:
```bash
git push origin feature-name
```
5. Open a pull request on GitHub.

## License

This project is licensed under the MIT License. See the LICENSE file for details.



