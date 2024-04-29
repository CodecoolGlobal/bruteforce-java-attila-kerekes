# Brute Force Password Breaker

Brute forcing is a method of trying to break a password by systematically checking all possible combinations until the correct one is found. This project aims to experiment with brute force attacks on passwords stored in an SQL database using Java and SQLite.

## Overview

The project contains embedded database files in the resources folder, called Users.db and CrackedUsers.db to store user credentials on each rerun of the program. After setting up a predefined number of users with a predefined maximum password length, the program implements a brute-force password breaker algorithm to crack passwords stored in the database. The application consists of components such as password and user generators, an authentication service, and a password breaker. 

To set the initial values, in the Application.java file modify these values:
```java
int userCount = <num>;
int maxPwLength = <num>;
```

After the program successfully runs, a list of cracked users, their passwords, and the required time in milliseconds is saved in the CrackedUsers.db.

## Prerequisites

- Java 21
- SQLite: Serverless database for storing user credentials (Or any similar technology for visualizing .db files)
- Maven: Dependency management and build tool.
- JUnit: Unit testing framework for Java.
- DB Browser for SQLite: GUI application for inspecting and managing SQLite databases.

## Installation and Usage

1. Clone the repository:
git clone <repository-url>
