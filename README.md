# Goals API

## Overview

The Goals API is a feature-rich application designed to streamline goal management for users. Developed using Microsoft technologies, including C# and ASP.NET Core 6.0, this API empowers users to create, update, and manage their goals efficiently. Whether you're planning short-term achievements or long-term financial goals, the Goals API provides the tools you need for effective goal tracking.

## Table of Contents

- [Technologies](#technologies)
- [Functionality](#functionality)
- [Testing](#testing)
- [Deployment](#deployment)
- [Security](#security)
- [Frontend Integration](#frontend-integration)
- [Getting Started](#getting-started)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Technologies

The Goals API is built on the following technologies:

- **Programming Language:** C#
- **Framework:** ASP.NET Core 6.0
- **IDE:** Visual Studio
- **Database:** Amazon RDS with PostgreSQL

## Functionality

### CRUD Operations for Goals

The API supports standard CRUD operations for managing goals, allowing users to:

- Create new goals
- Read details of existing goals
- Update goals based on changing requirements
- Delete goals that are no longer relevant

### User-Specific Operations

The API includes operations tailored to individual users, such as:

- Retrieving a personalized list of goals
- Removing all goals associated with a specific user
- Obtaining a summary of goal-related information

### Financial Tracking

Beyond basic goal management, the API facilitates financial tracking, enabling users to:

- Add money to save amounts
- Merge goals strategically
- Gain insights into total monthly paid goals

## Testing

The Goals API undergoes thorough testing using the xUnit testing framework. Test cases cover various scenarios, ensuring the reliability and correctness of the API. Developers are encouraged to run tests regularly to maintain the integrity of the application.

## Deployment

The backend of the Goals API is hosted on Amazon RDS, utilizing PostgreSQL as the database. Automatic updates are in place to ensure the API stays current with the latest features and security patches. Developers can choose between containerization or traditional server hosting for deployment.

## Security

Security is a top priority in the Goals API:

- User authentication is enforced for operations accessing sensitive data.
- Secure transactions are facilitated through HTTPS, encrypting communication between clients and the API.

## Frontend Integration

A React-based frontend application is under development to complement the Goals API. This frontend will provide users with an intuitive interface for interacting with their goal data.

## Getting Started

To get started with the Goals API, follow these steps:

1. Clone the repository.
2. Open the solution in Visual Studio.
3. Set up the database connection in the `ServiceExtensions.cs` file.
4. Run the application.


## API Endpoints

For a complete list of API endpoints and their documentation.
![image](https://github.com/saurabhchaudhary882/Goals/assets/56185985/3e600d48-0890-40f6-9a5e-f72399dcd49f)


## Contributing

Contributions to the Goals API are welcome!

---
