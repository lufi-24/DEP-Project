# RideWithUs - Carpooling Application

## Deployed Software 
http://ridewithus.ct.ws/

## Group Members

|NAME                   |ROLL NO. |
|-----------------------|---------|
|AJAY            |2022MCB1254   |

## Project Overview
RideWithUs is a web-based carpooling application that connects drivers and riders for shared trips. The application allows users to create trips, search for available rides, and manage ride requests.

## Technologies Used
- Frontend: HTML5, CSS3, JavaScript, AJAX
- Backend: PHP, MySQL

## Setup Instructions

### Prerequisites
- MySQL Server
- PHP Server
- Web Browser

### Database Setup
1. Start MySQL server
2. Execute the following commands:
```sql
CREATE USER 'ridewithus'@'localhost' IDENTIFIED BY 'rideLikeABoss';
GRANT CREATE ON *.* TO 'ridewithus'@'localhost';
FLUSH PRIVILEGES;
CREATE DATABASE IF NOT EXISTS ridewithus;
```
> **NOTE:**  Use a secure `username` and `password`, and update it in the `functions/functions.php` file.

### Application Setup
1. Run `functions/setup.php` to create necessary tables
2. Start PHP server
3. Access the application through your web browser


