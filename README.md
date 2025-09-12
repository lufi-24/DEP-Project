# RideWithUs - Carpooling Application

## Deployed Software (Only for BETA testing by other teams)
http://172.27.16.252/
Accessible from iitk network

## Group Members

|NAME                   |ROLL NO. |
|-----------------------|---------|
|AYUSH YADAV            |210251   |
|HARSHIT PATEL          |210424   |
|JATOTH SHASHI VARDAN   |230501   |
|KANDULA AMARNADHU      |230522   |
|PAL AJAY RAMSAGAR      |230725   |
|ROHIT VINOD ATKURKAR   |230872   |
|SANGA BADRI            |230911   |
|SUGALI YASHWANTH NAIK  |231046   |
|SUNANDINI BANSAL       |EXY24032 |
|V HARIVANSH            |231109   |

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

## Project Details

- [Software Requirements Specification](docs/RequirementDoc_CS253.pdf)
- [Software Design Document](docs/DesignDoc_CS253.pdf)
- [Software Implementation Document](docs/ImplementationDoc_CS253.pdf)
- [Software Test Document](docs/TestDoc_CS253.pdf)
- [Software User Manual](docs/UserManual_CS253.pdf)

