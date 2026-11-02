# Driver Point System

A full-stack web application designed to encourage safe driving through a points-based incentive and rewards program. The platform connects drivers, sponsors, and administrators, allowing drivers to earn and redeem points for rewards while giving sponsors and administrators tools to manage catalogs, users, and program activity.

## Team Members

- Luke Schultz
- Noah Samol
- Scott Schaefer
- Uyen Nguyen

## Tech Stack

### Backend
- Node.js - Backend runtime
- Express.js - REST API and server-side application framework
- MySQL - Relational database management
- JavaScript - Primary backend language
- Express Sessions - User session management and authentication

### Frontend
- JavaScript
- HTML/CSS
- Web-based user interface

### Cloud & Deployment
- AWS Elastic Beanstalk - Application hosting and deployment
- AWS - Cloud infrastructure
- MySQL - Persistent application data storage

## Features

- **User Authentication** - Secure login and session management.
- **Role-Based Access Control** - Separate permissions for administrators, sponsors, and drivers.
- **Driver Management** - Manage driver accounts and information.
- **Sponsor Catalog** - Allow sponsors to manage available rewards.
- **Reward Catalog** - Browse available items and rewards.
- **Points System** - Track driver points and redemption activity.
- **Redemption Cart** - Add rewards to a cart before completing a redemption.
- **Checkout System** - Process reward redemptions.
- **Notifications** - Keep users informed about relevant account and system activity.
- **Administrative Reports** - Provide administrators with reporting and management functionality.

## Deployment

The application is hosted using AWS Elastic Beanstalk.

- **AWS Environment:** `team15-application-env`
- **AWS Region:** `us-east-1`
- **Database:** `Team15_DB`
- **Session Management:** `team15.sid`

## Database

MySQL is used for persistent data storage and application management.

The database supports user roles, driver information, sponsor catalogs, reward redemptions, and other application functionality.

## Project Repository

Developed as part of Clemson University's CPSC 4910 Senior Design course.

**Team 15 – Driver Point System**
