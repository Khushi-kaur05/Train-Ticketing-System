
# Train Ticketing System

Welcome to the Train Ticketing System! This project helps users book and manage train tickets, with separate roles for passengers, travel agents, employees, and admins.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Admin Setup](#admin-setup)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: PostgreSQL
- **PDF Generation**: Python

## Features

### For Passengers
- Register, book tickets, view bookings, and download tickets as PDFs
- Cancel tickets, update profile, change password
- Submit feedback to the admin

### For Employees
- Book tickets with employee discounts, view bookings, update profile
- Perform all passenger actions except self-registration

### For Travel Agents
- Register (approval required from admin), book tickets, view bookings
- Earn commission on ticket bookings, update profile

### For Admins
- Manage passengers, travel agents, employees: approve, block, unblock, view profiles
- Add or update stations, routes, and trains
- Set booking limits, travel agent commission, and employee concessions
- View train schedules and user feedback
- Access earnings data and contact details

## Admin Setup

As the admin, you will need to configure a few settings when you first set up the system:
1. Add stations, routes, and trains.
2. Set booking limits for each user type.
3. Define commission rates for travel agents and concessions for employees.
4. Add employee accounts.
5. Update contact details for the Contact Us page.

