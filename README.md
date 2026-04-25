# Database Management Course Project

This repository contains a project developed for the Database Management course at the Technion - Israel Institute of Technology.

The project focuses on a rental apartment database system and combines relational data, SQL queries and views, and a Django-based application layer for presenting and analyzing the data.

## Authors

- Nir Chauser
- Sagi Dvir

## Semester

Spring 2025

## Project Overview

The system manages information about:

- apartment owners
- apartments
- rental records

The project includes:

- Django models mapped to the database tables
- SQL queries and views for analysis tasks
- pages for displaying query results
- forms for adding rental records
- search and analysis tools for owners and apartments
- HTML templates and static files for the web interface

## Database Structure

The project is based on the following main relations:

- Owners(ownerID, oName, residenceCity, bDate)
- Apartments(aID, city, roomsNum, ownerID)
- Rentals(renterID, rYear, aID, cost)

## Website Pages

### Home Page

A landing page with navigation links to the other pages in the website.

### Query Results

A page that displays the results of predefined SQL queries and database views.

### Add Rental

A page that allows the user to add a new rental record to the Rentals table, including input validation.

### Search and Analysis

A page that allows the user to search for apartment owners and analyze owner-related statistics.

## Repository Contents

- Rentals_App/ - main Django application code
- templates/ - HTML templates
- static/ - static assets
- data/ - CSV data files and SQL setup scripts
- manage.py - Django management entry point
- queries_views.sql - SQL queries and database views used in the project
- 2025S_Project_B.pdf - original project instructions

## Running the Project

This repository contains the main application files and data used in the project.

To run it locally, you need:

1. Python and Django installed
2. SQL Server or a compatible database environment
3. a configured database with the project tables and views
4. local Django settings configured for the project

Typical steps:

1. Clone the repository:

git clone https://github.com/Nir-Chauser/database-management-course-project.git

2. Enter the project folder:

cd database-management-course-project

3. Load the database data and setup scripts from data/

4. Apply the SQL definitions from queries_views.sql

5. Configure the Django settings and database connection locally

6. Run the Django server with:

python manage.py runserver

7. Open the application in the browser:

http://127.0.0.1:8000/

## Important Note

The project depends on a configured database connection.

Database credentials and personal configuration files should not be uploaded to GitHub.
Each user should configure the database connection locally.

## Institution

Technion - Israel Institute of Technology
