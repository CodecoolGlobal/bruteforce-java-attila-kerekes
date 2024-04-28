# Brute Force Password Breaker

Brute forcing is a method of trying to break a password by systematically checking all possible combinations until the correct one is found. This project aims to experiment with brute force attacks on passwords stored in an SQL database using Java and SQLite.

## Overview

The project uses SQLite, a lightweight and self-contained database solution, to store user credentials. It implements a brute force password breaker algorithm to crack passwords stored in the database. The application consists of components such as password and user generators, an authentication service, and a password breaker. 

In the Application.java file
```bash
int userCount = <num>;
int maxPwLength = <num>;
```
should be set, to state the number of users to be generated in a Users.db file with the maximum length of passwords.

After the program is run, a CrackedUsers.db file is generated with the list of cracked users, their passwords and the time required for that.

## Prerequisites

- Java 21
- SQLite: Serverless database for storing user credentials (Or any similar technology for visualizing .db files)
- Maven: Dependency management and build tool.
- JUnit: Unit testing framework for Java.
- DB Browser for SQLite: GUI application for inspecting and managing SQLite databases.

## Installation and Usage

1. Clone the repository:
git clone <repository-url>
